## Contoh cara implementasi Redis di Windows dengan Nodejs
- Dokumentasi API **nodejs-redis**: https://documenter.getpostman.com/view/16401113/2s8ZDbWg1J#f6cb6cea-2dfe-4f0d-9882-2b2f7b24c1a8

## Konfigurasi Redis WSL Debian
- ```apt-get update && apt-get install -y lsb-release && apt-get clean all```
- ```apt-get install curl```
- ```apt-get install gnupg gnupg2```
- ```curl -fsSL https://packages.redis.io/gpg | sudo gpg --dearmor -o /usr/share/keyrings/redis-archive-keyring.gpg```
- ```echo "deb [signed-by=/usr/share/keyrings/redis-archive-keyring.gpg] https://packages.redis.io/deb $(lsb_release -cs) main" | sudo tee /etc/apt/sources.list.d/redis.list```
- ```sudo apt-get update```
- ```sudo apt-get install redis```

## Memulai Redis
- ```service redis-server start```
- ```redis-cli```

##### Redis: https://redis.io/docs/
##### WSL: https://learn.microsoft.com/en-us/windows/wsl/
##### Debian: https://www.debian.org/doc/
