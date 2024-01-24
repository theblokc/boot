# Arbitrum Developers Bootcamp Starter Kit
<a href="https://theblokc.com"/>
<img alt="Visit The BLOKC" src="https://avatars.githubusercontent.com/u/116444255?" style="height: 100px; width:100px;" />
</a>

# 
This starter kit contains the pre-requsite account and software necessary for the BLK104SP program.

## Machine Profile
It is recommended to use a machine that is running either Linux or MacOS
- OS: Linux, MacOS, Windows
- Browser: Chrome

## Accounts and tooling
- [GitHub](https://github.com/)
- [Metamask for Browser](https://metamask.io/download/)
- [Infura Account](https://app.infura.io/register)
- [Alchemy Account](https://alchemy.com/?r=TQ0MjA3MDI1MTM3M)
- [Etherscan](https://etherscan.io/register)
- [Rust & Cargo](https://doc.rust-lang.org/cargo/getting-started/installation.html)

## Pre-requisite knowledge
The bootcamp requires fundamental understanding of the following software development concepts and tooling.
Here are some crash course videos to get you started with these:
- [TypeScript Programming language](https://www.youtube.com/watch?v=BCg4U1FzODs)
- [Command line](https://www.youtube.com/watch?v=uwAqEzhyjtw)
- [Git and GitHub](https://www.youtube.com/watch?v=mJ-qvsxPHpY)
- [Rust programming language](https://www.youtube.com/playlist?list=PLzMcBGfZo4-nyLTlSRBvo0zjSnCnqjHYQ)
- [GitHub Codespace](https://www.youtube.com/watch?v=D_5T6KMTRb8)

> Note: If you have found better crash course videos, please submit a change PR so we can take a look at it. Thank you!

## For Windows Users
As per our experience, we would prefer using machines with either Linux or MacOS.
If you are a Windows user, we would suggest enabling WSL on your Windows laptop or run a virtual machine.
- [Install Linux on Windows with WSL](https://learn.microsoft.com/en-us/windows/wsl/install)
- [Set up a WSL development environment](https://learn.microsoft.com/en-us/windows/wsl/setup/environment)
- [Remote Explorer - VSCode Extension](https://marketplace.visualstudio.com/items?itemName=ms-vscode.remote-explorer)

## Faucets
Request test ETH from the ff. faucets

### Sepolia (ETH PoS Testnet)
- [Infura Faucet](https://www.infura.io/faucet/sepolia)
- [Alchemy Sepolia Faucet](https://sepoliafaucet.com/)

### Bridge Sepolia to Arbitrum Sepolia
Bridge - https://bridge.arbitrum.io/?destinationChain=arbitrum-sepolia&sourceChain=sepolia

## Development Pre-requisite
- IDE (Preferred: [Visual Studio Code](https://code.visualstudio.com/))
- [git](https://git-scm.com/downloads)
- nvm: [Windows](https://github.com/coreybutler/nvm-windows) | [Linux/Mac](https://github.com/nvm-sh/nvm)

### VS Code Extensions
Here are some VS Code Extensions that could help you have a better development experience.
- [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
- [GitHub Copilot](https://marketplace.visualstudio.com/items?itemName=GitHub.copilot)
- [GitLens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)
- [Path Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense)
- [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)

## Initializing a Hardhat project
Follow the ff to initialize a new Hardhat project
```sh
mkdir my-hardhat-project
cd my-hardhat-project
npm init -y
npm i --save hardhat ethers @openzeppelin/contracts dotenv


# Initialize a new hardhat project
npx hardhat
# Create either JavaScript or TypeScript (recommended) project
# Hardhat project root: <Press enter>
# Do you want to add a .gitignore: y
# Install dependencies: y
```

## Hardhat Starter Kit
- Github Link: https://github.com/theblokcmates/hardhat-starter
- `git clone https://github.com/theblokcmates/hardhat-starter`

## Contribute
For change request, please clone and submit pull-request. Or e-mail at mark@theblokc.com
