# Register-DNS Extension

Custom nodes DNS.


You can validate that the extension was run by running (make sure you have tunneled into the master):

```
ls -l /var/log/
```



# Example
``` javascript

    "extensionProfiles": [
      {
        "name": "register-dns",
        "version": "v1",
        "extensionParameters": "example.com",
        "rootURL": "https://raw.githubusercontent.com/Azure/aks-engine/master/",
        "script": "register-dns.sh"
      }
    ],


```
