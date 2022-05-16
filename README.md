# faucet

```shell
npx create-react-app faucet
```

```shell
npm install truffle -g
```

```shell
truffle init
```

```shell
truffle compile
```

```shell
truffle migrate
```

```shell
truffle console
```

```shell
const instance = await Faucet.deployed()
```

```shell
const instance = new web3.eth.Contract(Faucet.abi,"0x37133B36Ba72a38A4C2E9fA2b70aa8b24217Ba2c")
```

```shell
const _a = await instance.methods.a().call()
```

```shell
truffle migrate --reset
```

```
web3.eth.sendTransaction({from: accounts[0], to: "0x3f83F1A9b4D5726fc4C8315D539FfBe0A3095Bd7", value: "1000000000000000"})
```