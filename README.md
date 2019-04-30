# Scordite-Blockchain-Explorer
Block explorer for Scordite CryptoNote based cryptocurrency.

#### Installation

1) It takes data from daemon scordited. It should be accessible from the Internet. Run scordited with open port as follows:
```bash
./scordited --restricted-rpc --enable-cors=* --enable-blockchain-indexes --rpc-bind-ip=95.179.160.20 --rpc-bind-port=26111
```
2) Just upload to your website and change 'api' variable in config.js to point to your daemon.
 