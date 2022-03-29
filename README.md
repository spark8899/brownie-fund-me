# brownie-fund-me
test brownie contract

# request
get infura token

go to https://infura.io/

get Rinkeby eth

go to https://faucets.chain.link/

# start ganache-cli test
```shell
ganache-cli
```

# install python3 venv
```shell
python3 -m venv venv
source venv/bin/activate
pip3 install -r requirements.txt
```

# compile
```shell
brownie compile
```

# deploy on local
```shell
brownie run ./scripts/deploy.py
```

# deploy on rinkeby
```shell
brownie run .\scripts\deploy.py --network rinkeby 
```

# test
```shell
brownie test
```