# OKTA Testing


### Read sensitive file untrusted
```
sudo cat /etc/shadow > /dev/null
```

### Search Private Keys or Passwords
```
sudo find /root -name "id_rsa"
```

# ~/falcosidekick-ui-compose$ 

### Shutdown Docker
```
docker compose -f docker-compose.yaml stop
```

### Startup Docker Silently
```
docker compose -f docker-compose.yaml up -d 
```

### Check Docker Processes
```
docker ps
```

### Check for Errors in Configuration
```
docker compose logs -f
```

Check that the API key is correctly set
```
cat falco.yaml | grep api
```

```api_token:``` 008cYuP#####9VA_v-qdrXqJg-evYJK######Hc8a



