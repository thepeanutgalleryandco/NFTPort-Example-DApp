# NFTPort-Example-DApp
This is an example DApp based on the NFTPort collection contract implementation.</br>
The [codeSTACKr minter-dapp](https://github.com/codeSTACKr/minter-dapp) repo was used as a base to create this repo.

If you would like to support my NFT collection, please take a look at the below.

[TheResidentLegendNFT Minting DApp](https://theresidentlegendnft.xyz/) </br>
[Steak-Bites Collection](https://opensea.io/collection/steak-bites)
## 1. Update info in js/constants.js
- Update the `contractAddress` and `chain` fields
- Update the other fields to suite the terms of your project if needed

## 2. Update images in images folder
- Update all images to your own images

## 3. Update info in index.html
- Update `Discord`, `Opensea` and `Twitter` links
- Update the image names to your own images and resize as needed
- Update the items in the slider list to compliment the number of images that you would like to use on your project
- Update About section
- Update Roadmap section
- Update Team section
- Update FAQ section
- Update Footer section

## 4. Update Styling Of Site
- Update the css/style.css and css/css2.css as needed
- Update / Add media sections for your Mobile, Tablet and Desktop modes

## 5. Whitelist
If you are going to make use of a whitelist, then you have to deploy the site to Netlify and follow the [codeSTACKr minter-dapp](https://github.com/codeSTACKr/minter-dapp) steps to add NFTPort environment variables. If you would like to use alternative hosting, then you will need to re-write the `functions/merkleProof.js` script and also update the `js/app.js` section where the whitelist check occurs.

## Example And Version Config
[v1.1 Example DApp](https://amazing-medovik-5ee285.netlify.app/)

Example Contract Address - 0xbc9d9bbBed97251b3E40cD25DAff8bC7d8e50C63 (Rinkeby)

### Deployment Config:
- name
- symbol
- owner
- maxSupply
- reservedSupply
- tokensPerMint
- treasuryAddress

### Runtime Config:
- baseURI
- metadataUpdatable
- publicMintPrice
- publicMintPriceFrozen
- presaleMintPrice
- presaleMintPriceFrozen
- publicMintStart
- presaleMintStart
- prerevealTokenURI
- presaleMerkleRoot
- royaltiesBps
- royaltiesAddress