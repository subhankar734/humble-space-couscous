git clone https://github.com/BillionsNetwork/verified-agent-identity

cd verified-agent-identity

npm install shell-quote @iden3/js-iden3-auth @0xpolygonid/js-sdk ethers uuid cross-fetch

cd scripts

node createNewEthereumIdentity.js

node manualLinkHumanToAgent.js --challenge '{"name":"CryptoTelugu","description":"CryptoTelugu Agent"}'
