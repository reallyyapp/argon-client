
## Quick start

Install with `yarn` and launch the app with `yarn start`. By default, the app is configured to connect to the Ethereum Rinkeby testnet.

For connecting to other chains / deployments, a few useful npm scripts are provided:

- Ethereum Mainnet: `yarn start:mainnet` will launch the app, configured to connect to the Ethereum mainnet
- Local development: `yarn start:local` will launch the app, configured to connect to our [aragen](https://github.com/aragon/aragen) local development environment. It will also use the local IPFS daemon, if it detects one exists. If you're using the [aragonCLI](http://github.com/aragon/aragon-cli), you'll want to run this to connect to its local chain.

**Note**: Windows users may need to install the [windows-build-tools](https://www.npmjs.com/package/windows-build-tools) before installing this project's dependencies.

More [configuration options](docs/CONFIGURATION.md) are available, and depending on your needs, you may find the [frontend development setup guide](docs/FRONTEND_SETUP.md) helpful.
