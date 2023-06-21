# cron

```* * * * * /usr/bin/curl -X POST -H "Content-Type: application/json" -d '{"jsonrpc": "2.0","id": 1,"method": "requestAirdrop","params": ["9z8eyT5meZsQK79Pm2rmqBQcQKfj6tWJfRVbjQczyKcK",1000000000]}' https://api.devnet.solana.com```
```grep CRON /var/log/syslog | grep solana```
