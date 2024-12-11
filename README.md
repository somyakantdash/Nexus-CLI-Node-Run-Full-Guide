# Nexus-CLI-Node-Run-Full-Guide

## Web Miner

🍀Go: https://beta.nexus.xyz/

👉Click Connect & That's It > Must Connect ur Gmail & Must Save ur PROVER ID (Do Not Clear ur Browser Cache & History)

👉Must open ur browser in background -- More Uptime means More Reward

### 🔶For Next Day Run This Command
Just Click Connect & That's it

## CLI Miner

### Need Some Requirements for PC Users

1. For Windows Install WSL - https://learn.microsoft.com/en-us/windows/wsl/install#install-wsl-command

2. For macOS If you have Installed Homebrew (https://brew.sh/) to manage packages on OS X,
run this command to install Git.
```
brew install git
```

1️⃣ Dependencies for WINDOWS & LINUX
```
sudo apt update
sudo apt upgrade
```

2️⃣ Download Some Files
```
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```
```
rustup target add riscv32i-unknown-none-elf
```
```
cargo install --git https://github.com/nexus-xyz/nexus-zkvm cargo-nexus --tag 'v0.2.4'
```
```
cargo nexus new nexus-project
```
```
cd nexus-project
```
```
sudo apt install -y protobuf-compiler
```

3️⃣ Start Node
```
curl https://cli.nexus.xyz/ | sh
```

### Change Your Prover ID
```
cd
```
```
cd .nexus
```
```
ls
```
```
vi prover-id
```

Press the - "i" button

Press the - "ESC" button

Then Save ur Prover ID -  ``` :wq ``` Then Press Enter
```
cd
```
```
cd nexus-project
```
```
curl https://cli.nexus.xyz/ | sh
```

