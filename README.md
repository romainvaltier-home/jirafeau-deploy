# jirafeau-deploy

```bash
git clone https://repo.valtier.fr/home/jirafeau-deploy.git jirafeau \
&& cd jirafeau/ \
&& touch config.local.php \
&& sudo chown 82:82 config.local.php \
&& docker-compose build --force-rm \
&& docker-compose up -d
```