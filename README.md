# Open Source Climate DAO

_Using the blockchain, we construct a Distributed Autonomous organization (DAO) which balances the needs of key stakeholders involved in climate action._

## Beer or Bordeaux?

One problem with climate change is that it's abstract to most people.  We might believe that something is happening, but what does it all mean?  CO2 PPM and 1.5 versus 3 degrees of warming by 2100 -- these are not numbers that most people could relate to.  Similarly, when companies announce a climate plan, most consumers don't relate to it.

In contrast, people spend a lot of time thinking about beer, wine, a ski vacation, or a trip to Venice.  Now that climate change is endangering beer and wine production, reducing snowfall, and inundating Venice, could these signals be something that people could relate to and act on?

With a Climate DAO, we hope to increase popular engagement by tying climate action to things people relate to.  

## User Story

Imagine a company, or Sponsor,  wants to do something positive about climate change.  It decides to become a “carbon neutral” company by making its operations more efficient and offsetting its net emissions.  So it allocates funds for climate action projects, from improving efficiency, changing its products and supply chain, to substituting fossil fuel with renewable energy and purchasing carbon offsets.

The Sponsor will want its Customers (or even members of the general public) to feel good about what it’s doing and in the long term continue to buy from the Sponsor.  Customers care about climate change very much and would prefer to shop with companies that are doing something positive for the environment.  But they don’t know too much about the specifics of carbon offsets, renewable energy, and the Sponsor’s particular operations.  Left on their own, they don’t know if they could trust the Sponsor’s claims.

A third group, Experts, are then brought in.  They have reputations for being fair, honest, and knowledgeable.  The Sponsor company hires them to develop and monitor the Sponsor’s climate action program, with the hope that their reputation would make the Customers trust its program and that their expertise would make the program more effective.

## Key Requirements 

To be successful, this program would need to balance the needs of all the stakeholders:

* Sponsor want Customers’ engagement and approval
* Customers want real, believable climate action
* Experts want to continue to build their reputation while earning a premium for their work because of the reputation they have

## Traditional Approaches

The traditional approach would be for the Sponsor to hire the Experts, develop a set of guidelines for the climate action program, and then pay them to run the program.  The problem with this approach is that:

* There is little engagement for the Customers, so they end up not caring about or even trusting what the Sponsor is doing.  This could lead to mutual disillusionment and the Company to abandon its program eventually.
* The program gets “locked in” to both the written guidelines and the Experts.  This does not encourage Experts to innovate, but instead to follow the guidelines, even if better options become available later.

An alternative is an “open for all” discussion or even vote on Twitter or Reddit.  The problem with this approach is the low quality of the discussion, which ultimately causes inaction.

## The DAO

DAO standards for Distributed Autonomous Organization, and it uses the blockchain's properties of immutable records, decentralized transactions, and smart contracts to make collective decisions.  For more information about DAO's, see [DAOStack](http://daostack.io).

Instead, let’s structure a DAO:

* Sponsor gives Reputation tokens to both Customers and Experts.
* Experts are given enough tokens to reach a quorum for a decision if the Customers do not vote.  (see below.)
* Customers have enough tokens to override the Experts if they vote together.
* Right ratio of total tokens is Experts 1 to Customers 3 or 4?
* Climate action proposals are put up for a vote by the DAO.  Proposals may be:
    * Change packaging to reduce waste
    * Replace truck shipping with rail shipping
    * Install solar panels at the corporate offices
    * Purchase Renewable Energy Certificates to offset factory energy use
    * Purchase carbon offsets which protect Amazon rainforest
    * Purchase carbon offsets which install methane digesters at landfills
    * etc. etc.
* Each vote requires staking of tokens
* Votes are anonymous
* Voting is quadratic: Each additional vote requires staking more tokens
* Votes can have 3 choices:
    * Accept - Proposal is valid, and I want us to do this
    * Decline - Proposal is valid, but I don’t want us to do this
    * Reject - Proposal is invalid.  I don’t agree that this is a legitimate project.
* Sponsor pays everybody who votes based on number of tokens staked
    * This is a substitute for paying fees to Experts to manage the program
    * Experts should be able to earn a fee by “putting their reputation at stake”
* Proposals are decided based on votes.  
    * A quorum or minimum number of votes is required to make a decision. 
    * Quorum decisions will have a waiting period for more votes, so all Customers can participate if they’re interested.
    * The voting deadline is extended to allow more people to vote.

* Based on the votes:
    * Accepted - Proposal goes forward.  Voters who voted for Accept get bonus Reputation tokens based on the tokens staked.
    * Declined - Proposal does not go forward.  No bonus Reputation tokens.
    * Rejected - Proposal does not go forward.  Those who staked Reputation tokens on a rejected proposal lose their tokens.

## Properties of the DAO

* Customers are more engaged with Sponsor's climate action program
* Experts make most decisions but Customers can participate and override them
* Experts earn premium (fees) for voting by staking their reputations
* Dynamic rebalancing of Experts group

## Curated Marketplace

One extension of this DAO would be to create a curated marketplace where:

* The members choose which companies to buy from
* The companies pay an affiliate commission to the DAO
* The DAO allocates reputation tokens to members based on purchases and some to experts as well
* The DAO allocates commissions to
    * Pay for overhead
    * Pay for voting
    * Pay for offsets
