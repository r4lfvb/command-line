# Get information about the system

**get basic system info**

```cmd
wmic baseboard get manufacturer, product, serialnumber
```

**get RAM info**

```cmd
wmic memorychip get devicelocator, manufacturer
```

```cmd
systeminfo | findstr /C:"Total Physical Memory"
```

**get disk status**

```cmd
wmic diskdrive get status
```
