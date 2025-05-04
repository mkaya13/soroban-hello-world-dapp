# Soroban Project

## Build

```stellar contract build```

```stellar contract optimize --wasm target/wasm32-unknown-unknown/release/hello_world.wasm```

```
stellar contract deploy --wasm target/wasm32-unknown-unknown/release/hello_world.optimized.wasm --source alice --network testnet --alias hello_world
```

## Deploy

ℹ️  Signing transaction: 4c4e4718b1e438d63a6575eb1cf542e0056be1225728568e3ffdf2985c761f24
🌎 Submitting deploy transaction…
🔗 https://stellar.expert/explorer/testnet/contract/CAX4MN5K3KERBOLMDGFBDHFQJ7QR7PF35A37BEEMKFVQH25J6FFTZ3RB
✅ Deployed!
CAX4MN5K3KERBOLMDGFBDHFQJ7QR7PF35A37BEEMKFVQH25J6FFTZ3RB


## Invoke

stellar contract invoke --id CAX4MN5K3KERBOLMDGFBDHFQJ7QR7PF35A37BEEMKFVQH25J6FFTZ3RB --source alice --network testnet --set_username --value Mertcik