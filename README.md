# Build
```
platformio run
```

# Upload

```
platformio run -t upload
```

# Attach Serial

Note that the baud rate to use comes from what ever was setup in the setup() function.

```
platformio device monitor -b 115200
```