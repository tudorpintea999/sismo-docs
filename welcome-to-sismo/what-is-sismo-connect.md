---
description: The crypto-native SSO.
---

# What Is Sismo Connect?

Sismo Connect, a crypto-native single sign-on (SSO), enables applications to request any data aggregated in a user’s Data Vault. More precisely, applications can request that users prove ownership of Data Sources (EVM, Twitter, Telegram and GitHub accounts) and Data Gems (e.g. that they own a certain NFT or voted in a DAO). By abstracting the underlying complexities, Sismo Connect allows developers to implement zero-knowledge technology in their applications with only a few lines of code.

With Sismo Connect, developers can request multiple Data Gems at once, aggregating data from multiple web2 and web3 accounts. This allows applications to access more data without compromising user privacy. For a practical understanding, refer to these case studies.

For instance, Sismo Connect facilitates:

* Leveraging web2 social capital on web3 applications
* Aggregating user reputation from multiple blockchains
* Aggregating user data from multiple wallets without ‘doxing’

{% hint style="info" %}
Visit the Sismo App Store to explore applications built with Sismo Connect.
{% endhint %}

<figure><img src="../.gitbook/assets/Sismo Connect Flow.png" alt=""><figcaption></figcaption></figure>

## Empower Your App

Envision the Data Vault as an encrypted aggregator that securely stores various Data Sources, such as Ethereum addresses, GitHub, Twitter and Telegram accounts, and other attestations from relevant authorities.

Using Sismo Connect, you can implement any combination of the following functions in your application:

* **Authentication:** Your app can request users to prove ownership of Data Sources in their Data Vault. As such, your backend or smart contracts can easily authenticate that a user owns a specific Data Source, such as a GitHub, Twitter, Telegram or Ethereum account.
* **Selective disclosure:** Your app can request the granular and anonymized data aggregated in a user’s Data Vault, known as Data Gems. For example, a Data Gem could prove that a user owns a particular NFT or has committed to a certain GitHub repository. Leverage this data on your application for access control, reputation importation and other user-centric experiences.
* **Request signatures**: Your app can securely request and obtain user-signed messages, enabling trustless interactions, smart contract execution, and verifiable user authorization.

## Built With Sismo Connect: Case Studies

The case studies below showcase the power of Sismo Connect, demonstrating how it can benefit users and applications through concrete examples.

### Privacy Is Normal

To celebrate privacy as a fundamental human right, Sismo launched the "Privacy Is Normal" lottery. This application allows Tornado Cash users to enter a lottery to win a printed tribute to the protocol’s revolutionary code or its NFT equivalent.

By integrating Sismo Connect, Privacy Is Normal enables users to generate a ZK proof establishing they own a Tornado Cash depositing address without directly revealing it. In addition, users prove ownership of a Gitcoin Passport to add an effective layer of Sybil resistance, allowing only those users with adequate scores to participate.

{% hint style="success" %}
Read the full case study [here](https://sismo.notion.site/PROD-Sybil-resistant-anonymous-Lottery-gated-to-Tornado-Cash-users-1cdeef27f4d243f4a40c7aaa74e40ee9).
{% endhint %}

### The Merge Contributors

In recognition of the critical work done by Merge contributors during Ethereum's transition from Proof of Work (PoW) to Proof of Stake (PoS), Sismo launched the Merge Contributors Space. It integrates Sismo Connect to allow contributors to claim access to upcoming web3 events via an onchain ERC-721 NFT airdrop or offchain mailing list.

The Merge Contributors Space integrates Sismo Connect to enable users to prove they contributed to Ethereum’s Merge. If users have an eligible account in their Data Vault, they can generate a ZK proof to gain access to gated features in the Space. Thus, users only what is necessary instead of sensitive information. During the process, users receive their unique Vault ID specific to them and the application—eliminating the potential of double spends.

{% hint style="success" %}
Read the full case study here.
{% endhint %}