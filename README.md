# Kusama Treasury Funding Proposals (KTFPs)

<p align="center">
  <img src="./src/Kusama-expect-chaos.png" height="250">
</p>

> **Sometimes Chaos Can Benefit from Structure :** The purpose of this repository is to structure the discussion around spending proposals of the treasury and therefore to reduce the risk to lose the reserved deposit. 

---


- [:bird: About](#bird-about)
- [:pencil: Process](#pencil-process)
  - [Submit a Proposal](#submit-a-proposal)
  - [Proposal Discussion](#proposal-discussion)
- [:bulb: Help](#bulb-help)
  - [Additional Information](#additional-information)
  - [Real-time conversation](#real-time-conversation)
- [:information_source: License](#information_source-license)

## :bird: About 

The [Kusama](https://kusama.network/) treasury is a pot of funds collected through transaction fees, slashing, inefficiencies in the chain's staking set, and lost deposits. The funds held in the treasury can be spent by making a spending proposal.

When a stakeholder wishes to propose a spend from the treasury, they must reserve a deposit totaling 5% of the proposed spend or 20 KSM (whichever is higher). This deposit will be slashed if the proposal is rejected, and returned if the proposal was accepted.

**The purpose of this repository is to structure the discussion around spending proposals of the treasury and therefore to reduce the risk to lose the reserved deposit.** 

## :pencil: Process

### 1. Submit an Off-Chain Proposal
1. [Fork](https://github.com/w3f/KTFPs/fork) this repository
2. In the newly created fork, create a **copy** of the [ktfp-template.md](./Proposals/ktfp-template.md). In other words: In the GitHub web interface, you need to create a new file and copy the content of the [ktfp-template.md](./Proposals/ktfp-template.md) inside the new file. Don't change the template file directly!
3. Label the file as "proposal_name.md".
4. Fill out the template with the details of your project.
5. Once you have completed the proposal, click on "create new pull request".

### 2. Proposal Discussion

Open pull requests to this repository are also open for discussion. If the committee agrees to fund a proposal the corresponding pull request will be merged into the repository. If the committee declines funding, the pull request will be declined as well. 

Therefore, getting approval by the committee on GitHub should reduce the risk to get slashed once the proposal is submitted on-chain. You can find a list of the current council members on the [Polkadot JS App](https://polkadot.js.org/apps/#/council).

Here is a list of GitHub accounts of council members, to make it easier to see if a council member approved your spending proposal (might be outdated):
* [FEDERICO](https://github.com/fgimenez)
* [GAV](https://github.com/gavofyork)
* [JACO](https://github.com/jacogr)
* [SHAWN TABRIZI](https://github.com/shawntabrizi)

### 3. Creating the an On-Chain Proposal

[See the Polkadot Wiki](https://wiki.polkadot.network/docs/en/learn-treasury#creating-the-proposal) for more information.

## :bulb: Help

### Additional Information

* [Kusama Website](https://kusama.network/)
* [Kusama Forum](https://forum.kusama.network/)
* [Kusama Twitter](https://twitter.com/kusamanetwork)
* [Kusama Network: User Guide](https://guide.kusama.network/en/latest/)
* [Kusama Reddit](https://www.reddit.com/r/Kusama/)

### Real-time conversation
Riot channels for real-time discussions about Kusama: 

* [Kusama Watercooler](https://riot.im/app/#/room/#kusamawatercooler:polkadot.builders)
* [Kusama Direction](https://riot.w3f.tech/#/room/#kusama:matrix.parity.io)

## :information_source: License
[Apache License 2.0](./LICENSE)
