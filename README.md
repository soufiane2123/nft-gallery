# NFT Gallery

Create your own NFT gallery for any ERC721/ERC1155 NFT collection on [any EVM-compatible chain].

View the metadata of all NFTs in the collection, including features such as pagination, filtering, and search.

## Using This Repo

To create your own version of this template, you can use the following steps:

Run this command from the terminal to clone this project:

```bash
git clone https://github.com/soufiane2123/nft-gallery.git
cd nft-gallery
yarn install
```

## Environment Variables

To run this project, you will need to add environment variables. Check the `.env.example` file for all the environment variables required and add it to `.env` file or set them up on your hosting provider.

### 1. Configure Parameters

Go to the `parameters.ts` and update the following values:

1. `contractAddress`: The smart contract address of your NFT collection.
2. `chain`: The name of the chain that your smart contract is deployed to.
3. `blockExplorer`: (Optional) - The block explorer to open when user's click on historical events of each NFT.

### 3. Customize the Styling

Update the styles in the respective components by changing the [Tailwind](https://tailwindcss.com/) classes.
