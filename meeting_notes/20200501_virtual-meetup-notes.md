# Toronto Mesh Virtual Meet

- Date: 1 May 2020
- Attendees: (put your name if you want, no obligations)
    - benhylau
    - makeworld
    - Hank
    - ehmry/Emery
    - Yurko
    - Dave C
    - Curtis M

## Notes

### City of Toronto

- City has been trying to address the need for internet access (primarily through "digital inclusion file")
    - not main mandate, not prepared with budget to handle this
- COVID has shut down a lot of physical locations, making disparities in internet access more apparent- these are often the same people who are in dire need of accessing city services
- try to use city position to go out and try to ask ppl for help
- city has established relations with many of the large vendors in this sector
- scrum together as many initiatives as we could from private sector
- couple days ago, City [announced a bunch of initiatives](https://www.toronto.ca/home/media-room/news-releases-media-advisories/?nrkey=2602C9B7580A0CD285258558006CE262) the team has managed to pull together
- City doesn't know who has internet, the ISPs know - not City
- identified pockets with high potential need, asked around for help
    - e.g. Bell will light up 10 towers for free (~6months)
    - e.g. Rogers extend corporate social responsibility program that is already in place
- ISPs can (essentially) just "turn on" access, "donating" a share
- novel approach: partnership with Cisco, firms called ONIX, BAI & Beanfield Metroconnect
- trying to figure out where we have connection spots: BAI, Toronto Public Library, ...
    - piggybacking on existing access points
- Cisco donated > 1,000 access points
- now we are just figuring out what we can do with these resources
- earlier today (4-30) there was a meeting with partners to located 3 towers representing areas with particular need
- city is desperate for good news, the press release was a little early (shocking to everyone)
    - media releases can be an organizing force (prompting concrete action)
- end goal, City want longer life of donated Cisco APs than this period, City owns them
    - important are dimensions of maintenance and sustainability
    - Is there a role here for Toronto Mesh?
        - advice, labour, access to city property, whatever... the city is very available and amenable
- makeworld: where are the access points?
    - depends on the need, focusing on indoor space
    - Toronto Public Health, try to avoid public space WiFi bc we are in social distancing
    - goal is to get people access in their domiciles, especially lower income groups
- yurko: Meraki licensing model, what is the agreement (perpetual / 3 year?)
    - probably not perpetual license, not clear on this yet
    - aware of subscription model, on the radar
- yurko: towers timelines?
    - "6 months" not sure afterwards yet
    - may become bigger political question at that time
    - businesses may think this may result in future biz
- meshnet, freifunk
- cisco very focused on fixing the current problem
    - [MR74](https://meraki.cisco.com/products/wireless/mr74)/[84](https://meraki.cisco.com/products/wireless/mr84) don't run OpenWRT
        - yurko: "yet"
        - felix: "likely never"
    - City, we don't want e-waste
        - rewriting "how does the City select tech"
            - "defective by design", "right to repair", etc.
        - primary goal is to get internet out there, eye out for long-term stuff
        - - understood that the city must accept these donations, and must do so without requirements
- Ben: some other interesting points beyond the Cisco APs
    - newly lit up towers
    - TPL as access point
    - opportunities to create new ways for community groups to relate to the municipal government, even as a parallel process
        - AL: the city is responding to an urgent need, but this means revisiting older commitments
            - TPL, (Toronto Hydro) lamp-posts all have different politics, negotiate from much different perspectives
            - AL can help navigate these politics, gather information for Toronto Mesh "empowered residents" to approach councillors and other decision-makers
    - TPL is an interesting case- they are hit hard by COVID, and libraries are conspicuous, ubiquitous, and well loved public assets
        - Toronto Mesh has network and capacity building as a core component
        - scaling active membership is essential to avoid over-reliance on a central core
    - F: we're figuring out how to very quickly deploy infrastructure. Many of the people capable of building infrastructure might be thinking with a longer view to thing s(Cisco has a 3 year timeframe)
        - can Toronto Mesh use this as an opportunity to get closer to some of the more sympathetic ISPs?
- get partnership with an ISP to provide transit
    - what infra are we building right now that we can hook onto in future?
    - play the long game
- igel: if we figure out hardware, how do we handle heavy routing and switching? (some architecture stuff I can't really summarize)
- F: at FF, we built at the hardware level for specific features, but newer routers are not compatible with these suites- they are becoming more and more locked down
    - can we remove hardware components from our mesh understandings?
    - go ben!
- centralized exit point with one of the ISP partners
- try to link back nodes thru internet
- freifunk, unprotected network, ppl connecting know that, but vulnerable population
- can we use the MR network as backhaul
    - as NYCmesh used LINKNYC mesh for backhaul
- Toronto Mesh HAS hardware, but lacks geography
- Hank: TO has identified potential users who *need* internet ASAP, what is the plan to educate ppl to involve?
    - proposal is not exactly for a community network, but will be providing free access from existing towers
    - starting with towers, identified 3 towers, all property managers on board with helping
    - generated a map of all possible places they want to target, triaging these
    - towers are purpose built rental buildings
    - city is getting donations of home internet access for people in eligible buildings
    - TCHC housing has cell towers on top of them, with fibers connected to them
- Michel Merseau would be a person to contact here - his PhD research has focused on building community internet infrastructure in TCHC
- benhylau: from the City's perspective, what is the value of involving a community network initiative? (given the COVID response seems covered)
    - Alex: All of the short term plans have been addressed by the private sector however they are time-limited donations which may not cover everywhere that we want it.
    - longer-term, City is interested in the community perspective
    - City did a broadband study some years ago, conclusion is every house is wired for broadband, it's just a cost problem
    - there are potential benefits in terms of market shape (more options), affordability, and network resilience
    - city is also interested in the /principle/ of community engagement
        - civic participation, makes the network democratic
            - *value alignments wow! :o*
    - access is only part of the digital divide - literacy and capacity to use and understand networks are also problematic and more endemic
    - Toronto Mesh sees the practice of network building as a process of empowerment that builds a resilient and democratic ecosystem
- F: hardest part is to get people excited for this - internet is generally understood only from a consumptive medium
    - how to get ppl interested? opportunity to build infra that allow ppl to get excited about
        - provide content
        - build services
        - we also need to expand beyond the consumptive frame
- data governance, privacy, we need to connect to that
    - this is the material layer
    - COVID is but a foil to make our structural problems more visible
- for people to understand, they need something to look at- a space needs to be made
    - like a real, bona fide network
    - a design initiative that could really show people the value of this practice
- if access is all of a sudden free, we should ask "Why isn't it free all the time?"
- if we build it, infrastructure is free (as in freedom, if not in beer)
- opportunity to provide discoverability through geolocated networks and software connected to your neighborhood, not some abstract network from California
    - why order thru Uber? order t
- AL: Toronto Mesh is identified, city is very interested in listening
    - might be an invite to ppl in the civic tech community, Toronto Mesh can
- timeline for all these things: ASAP - GANTT FREE AND AGILE
- City timeline is ASAP
    - Jira board to track things :)
- is Cisco backing the backhaul?
    - just hardware
    - using the mesh Meraki
- what does Toronto mesh want to solve?
    - Hank: in Toronto, there isn't a huge problem with "fast" and "expensive"
    - Toronto Mesh tries to solve an ideological problem
    - Yurko: opportunity here, here are 10 buildings... what happens after 6 months?
    - City has a limited time fix, we have a permanent fix
    - skill building?
- Hank: decide on a goal
    - ...

### Project in India

- ehmry: cheap 4G everywhere, not providing internet
- aim to _not_ provide internet
- yurko: why build this network?
    - ehmry: work here mostly related to audio
    - recording knowledge, put into some archive
    - focus on applications, but mesh is in and of itself not the goal
    - building resilient community networks is however a welcome side effect

### Toronto Mesh Next Steps

- yj: The Wilkinson Box -> https://raw.githubusercontent.com/Toronto Meshnet/documents/master/images/20190221_meetup-drawings/shrinks99.jpg
- felix: creating the knowledge