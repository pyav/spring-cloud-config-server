```
curl http://localhost:8888/limits-service/default | python3 -m json.tool
```
```json
{
    "name": "limits-service",
    "profiles": [
        "default"
    ],
    "label": null,
    "version": "eacb720258fa3739d3bd231849d20fd6b3e29c14",
    "state": null,
    "propertySources": [
        {
            "name": "file:///home/anand/Desktop/github/git-localconfig-repo/limits-service.properties",
            "source": {
                "limits-service.min": "4",
                "limits-service.max": "996"
            }
        }
    ]
}
```
