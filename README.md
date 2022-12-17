# Using the Blockdaemon Crypto Address Transactions API #
Blockdaemon's crypto address transactions API allows developers to retrieve a list of transactions that an address was involved in, ordered from most recent to least recent. This API is useful for tracking the movement of cryptocurrency within a particular address or for analyzing patterns of activity. It is also helpful for developers who need to keep track of their own transactions or those of their users. By using this API, developers can easily access transaction data without having to manually search through the blockchain.

[Crypto Address Transactions API](https://www.worldindata.com/api/Blockdaemon-crypto-address-transactions-api)

The API marketplace of Worldindata aims to provide developers with a comprehensive overview of various third-party APIs. One of the main goals of this platform is to make it easier for developers to understand how these APIs work and how they can be integrated into their own projects. The marketplace features a range of APIs from different categories, including finance, social media, and e-commerce. It also provides detailed documentation and examples to help developers get started with using the APIs.


## Industry, Sectors, and Markets for the API ##

**Industry and Sectors**
- cryptocurrency
- blockchain
- investment
- finance

**Client Types**
- cryptocurrency platforms
- crypto exchanges
- investment platforms




## JSON output, Parameters and Objects ##
The GET /{protocol}/{network}/account/{address}/txs endpoint allows users to retrieve a list of transactions associated with a specific crypto address, organized from newest to oldest.

**Filter Parameters**
- protocol
- network
- address
- assets
- from
- to
- order
- continuation
- limit


```
{
  "total": 1,
  "items": [
    {
      "id": "0xF00Fa860473130C1df10707223E66Cb4B839B165",
      "date": 1571222657,
      "block_id": "0xaf2948aba2ed8cc7d5b7d4e4f4164a7c8819efc94d30aab3fce6904df68dbc07",
      "status": "completed",
      "assets": [
        "ethereum/native/eth"
      ],
      "nonce": 0,
      "num_events": 0,
      "meta": null,
      "events": [
        {
          "amount": 5000000000,
          "block_id": "string",
          "block_number": 0,
          "date": 0,
          "decimals": 0,
          "denomination": "string",
          "destination": "1A1zP1eP5QGefi2DMPTfTL5SLmv7DivfNa",
          "id": "string",
          "meta": null,
          "source": "string",
          "transaction_id": "string",
          "type": "string"
        }
      ]
    }
  ],
  "continuation": {
    "meta": {
      "paging": {
        "next_page_token": "string"
      }
    }
  }
}

```
**Objects**
- total
- items
- id
- date
- block_id
- status
- assets
- nonce
- num_events
- meta
- events
- amount
- block_id
- block_number
- date
- decimals
- denomination
- destination
- id
- meta

## SDK ##

Software Development Kits (SDKs) for the Blockdaemon transactions of address API are available in a variety of programming languages, including JAVA, JavaScript, Python, PHP, and Ruby. These SDKs make it easier for developers to integrate the API into their projects and take advantage of its capabilities.


### Disclaimer of infringement ###
Worldindata is a platform that showcases third-party APIs and strives to make data more accessible and user-friendly. We are not the owners of the data but rather provide a means for developers to connect with data providers. As fans of the crypto address transactions API and Blockdaemon, we hope to provide valuable resources for developers looking to work with these tools. Please note that the use of any data or API from Worldindata is subject to the terms and conditions of the respective data provider.


[Worldindata](https://www.worldindata.com)
