# BGIN Identity & Privacy Enhancement Working Group DRAFT Charter

## 1) Working Group name:
IAM and Privacy Working Group (IPWG)

## 2) Purpose
The goal of IPWG is:

1. To develop guidances and good practice documents as well as policy recommendations for centralized crypto-assets exchanges that describe  

* Identity (including keys) and Access management for access to crypto-assets exchanges; 
* Identity (including keys) and Access management using Blockchain/DLT for Online resource access;
* Privacy and regulatory requireiments including AML/CFT considerations to be taken into account for the above. 

Both private and public sector use-cases are to be considered. 

2. To develop high-level concept note to address issues related to privacy ehnancing technologies and regulatory enforcement including AML/CFT in fully decentralized permissionless financial transactions (DeFi)

* Understanding exisiting and developing privacy enhancing technologies for DeFi;
* Understanding current regulatory requirements and their enforcement;
* Give consideratons on the way for balancing privacy and traceability for the purpose of prevention of financial crimes (ML/TF). 

3. To develop a guidebook on relevant technologies for non-technical persons

* Explanations on technologies in a plane and easy to understand manner for non-technical including public authorities.  

## 3) Scope
### In Scope
The group will document 

### Out of scope:
IDM and Credential Management that does not involve BC or DLT. 

## 4) Proposed Deliverables
The group proposes the following Specification deliverables:



## 5) Anticipated audience or users
The following stakeholders are conceived as the audience of the deliverable of this WG: 

* Crypto-currency Exchanges; 
* Distributed identity management deployers; 
* Management, architects, and implementers of IAM and claims transfer systems for blockchain/DLT access or the system that utilizes blockchain/DLT systems. 
* Financial and privacy regulators and enforcement authorities

## 6) Language
English

## 7) Method of work:
Online forums and issue tracking system with regular Video meetings and occasional face to face meetings. 

## 8) The basis for determining when the work is completed:
The work will be completed once it is apparent that maximal consensus on the draft has been achieved, consistent with the purpose and scope. Where applicable, it shall have more than three running code that is interoperable. 

# Background information
Although it is not clearly devidable, in the current blockchain based financial system, there are conceptually two different types of systems depending on the underlying technologies; centralized systems and decentralized permissionless systems. Both of them have been facing difficulties including handling identity, privacy and regulatory compliance, and key management issues. This working group will develop documents with the aim at addressing and mitigating these difficulties.  

1. Crypto currency exchanges
As we are painfully aware, identity and access management to crypto-currency exchanges 
In many cases, Fintech services such as aggregation services uses screen scraping and stores user passwords. This model is both brittle and insecure. To cope with the brittleness, it should utilize an API model with structured data and to cope with insecurity, it should utilize a token model such as OAuth [RFC6749, RFC6750].

There are some examples of API models such as OFX, but it uses SOAP/XML model. However, SOAP/XML model has grown unpopular among the developers. Also, the OFX does not deploy the token model but uses user password, causing insecurity.

This working group aims to rectify the situation by developing a REST/JSON model protected by OAuth.

2. Privacy and traceability issues for fully decentralized permissionless financial system (DeFi)
Fully decentralized permissionless financial system is still just an imaginary creature at this moment. However, no one can predict what will happen in mid-to-long term especially because of the rapid development of relevant technologies and enthuasism in blockchain community. 

In recent years, many privacy enhancing technologies for DeFi have been developed within the tech community with several aims including preserving user privacy and enhancing fungibility. Needless to say, privacy is important for users of financial services; however, at the same time, privacy could make it harder for enforcement authorities to find out and catch financial criminals. In recent yeasr, in particular after the publication of Libra proposal with the plan for transition to permmissionless system, regulatory authorities and AML/CFT authorities have more and more become keen on the implecation of decentralized permissionless system for financial regulations.

Sooner or later, DeFi needs to find the "clever" solution(s) to resolve these two (seemingly) conflicting needs; privacy enhancement and preventing financial crimes. At this moment, tech community and regulatory community making hard efforts in pursuing their own purposes without much communication and cooperation. This working group, first, provides place for different stakeholders to get together to learn each other and explore solution(s) for this difficult challenge.

## Related work:
JFSA (2019, Research on privacy and traceability of emerging blockchain based financial transactions, https://www.fsa.go.jp/en/policy/bgin/ResearchPaper_MRI.pdf

## Proposers

## Anticipated contributions:
