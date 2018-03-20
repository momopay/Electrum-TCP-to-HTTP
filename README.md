## Run this project

```bash
git clone https://github.com/Chinafreak/Electrum-TCP-to-HTTP.git
cd Electrum-TCP-to-HTTP
npm install
node app
```

## Parameter

All parameter are optimal. But if you want to change some settings:

```--e_port```

Electrum's port

**default: 50002**

```--e_ip```

Electrum's ip address

**default: your public ip address**

```--e_protocol```

Electrum's protocol [tcp, ssl or tls]

**default: tls**

```--port```

Port for http request

**default: 50003**

### Example:

```bash
node app --e_port=50001 --e_ip=35.123.23.195 --e_protocol=tcp --port=8080
```

## License
MIT