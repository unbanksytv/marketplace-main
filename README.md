<h3 align="center">Degen Vibes</h3>
  <p align="center">
An open source NFT marketplace built on Reservoir.

<!-- ABOUT THE PROJECT -->
## About The Project


Degen Vibes is an open source marketplace that enables communities to easily launch their own NFT marketplace, accessing instant liquidity aggregated from other major marketplaces. The usual arguments for decentralization are censorship-resistance, trustless validation, or global populism—empowering anyone to participate in a system. But there's a simpler one too: universal liquidity. Tt's why decentralized orderbooks are the future
  
With each deployment, communities are given full control over their marketplace from designing their look and feel to setting their own marketplace fees.

For self hosted deployments you can simply fork this repository and follow the instructions below to configure and deploy your marketplace. 

<p align="right">(<a href="#top">back to top</a>)</p>

### Configuration
Reservoir Market is built to be fully configurable using environment variables. To preview your configuration locally you can copy the values you want to use from  `env.development`  or  `env.production`  into a new file called  `.env.local`.

Note: Environment variables can also be added during deployment via deployment platforms like [vercel](https://vercel.com/).

**Required Environment Variables**
| Environment Variable           | Required | Description                                                                         | Example              |
|--------------------------------|----------|-------------------------------------------------------------------------------------|---------------------|
| NEXT_PUBLIC_RESERVOIR_API_BASE | `true`   | The Reservoir API base URL. Available on Mainnet, Rinkeby, Goerli, and Optimism.                       | https://api-rinkeby.reservoir.tools/ https://api.reservoir.tools/ |
| NEXT_PUBLIC_CHAIN_ID           | `true`   | The Ethereum network to be used. 1 for Etherem Mainnet and 4 for Rinkeby Testnet, etc.   | 1 4                                                               |
| NEXT_PUBLIC_PROXY_API_BASE     | `true`   | The proxy API used to pass the Reservoir API key without exposing it to the client. | /api/reservoir                                                    |
| RESERVOIR_API_KEY              | `true`   | Reservoir API key provided by the Reservoir Protocol. [Get your own API key](https://api.reservoir.tools/#/0.%20Auth/postApikeys).         | 123e4567-e89b-12d3-a456-426614174000                              |
| NEXT_PUBLIC_ALCHEMY_ID              | `true`   | Alchemy API key required for buying items on mobile. [Get your own API key here](https://docs.alchemy.com/alchemy/introduction/getting-started#1.create-an-alchemy-key).         | 123e4567-e89b-12d3-a456-426614174000                              |

Please visit [our docs](https://docs.reservoir.tools/docs/marketplace-getting-started#configuration) to view all supported environment variables.

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- Contributing -->
## Contributing

Coming soon 👀
✨ Listing
✨ Multi-buy
✨ Cart management
✨ Token management

<p align="right">(<a href="#top">back to top</a>)</p>
