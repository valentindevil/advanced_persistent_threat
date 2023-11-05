# advanced_persistent_threat
## APT 3
APT3, also known as Gothic Panda, Pirpi, UPS Team, or Buckeye, has been found to have used hacking tools that belonged to NSA-linked groups in its attacks. The discovery was made by a team of security researchers from Symantec. According to the team’s intel report, Buckeye used variants of tools by Equation Group -- an APT group linked with NSA. In fact, the China-based group used these tools for more than a year before the Shadow Brokers leak happened.

Buckeye, which was known for carrying out spying operations on US systems, mainly abused zero-day vulnerabilities with the help of these tools.

### What were the tools?

In March 2016, Buckeye was known to be using a variant of DoublePulsar tool which was leaked by the Shadow Brokers in 2017. It was delivered to victims using a trojan known as ***‘Bemstour’***.
Shadow Brokers exposed a number of exploit tools by Equation group in 2017, which included DoublePulsar, FuzzBunch, EternalBlue, EternalSynergy, and EternalRomance. Some of them were also allegedly used by Buckeye.
Where were the tools used?

The earliest instance of Buckeye using the variants of Equation Group’s tools was on a target in Hong Kong. The attack was perpetrated on March 31, 2016.
The group also used these tools on an education institution in Belgium. This was carried out an hour after the Hong Kong attack.
It is speculated that Buckeye used the tools in other attacks until it became defunct in 2017.
A note on Bemstour and DoublePulsar

The Bemstour trojan is used to deliver a variant of the DoublePulsar backdoor. Following which, DoublePulsar injects a secondary payload that runs only in memory. This payload allowed attackers to access compromised computers even after DoublePulsar was removed.

Earlier versions of Bemstour trojan did not include the process of uninstalling DoublePulsar implant. This was added only in later versions.

### How did Buckeye get them?

The researchers suggest that the group might have closely followed Equation Group’s attacks before using their tools. ***“Based on the timing of the attacks and the features of the tools and how they are constructed, one possibility is that Buckeye may have engineered its own version of the tools from artifacts found in captured network traffic, possibly from observing an Equation Group attack,”*** they said in the blog.

They also hint other possibilities such as vulnerable Equation Group servers or the group’s members switching sides to leak tools.

Despite Buckeye being defunct since 2017, the Equation Group tools it used was evident in attacks launched in 2018. It is still not ascertained who used the tools.


The researchers also indicate that another malware family known as Filensfer was used by Buckeye.

***“Over the past three years, Filensfer has been deployed against organizations in Luxembourg, Sweden, Italy, the UK, and the U.S. Targets included organizations in the telecoms, media, and manufacturing sectors. While Symantec has never observed the use of Filensfer alongside any known Buckeye tools, information shared privately by another vendor included evidence of Filensfer being used in conjunction with known Buckeye malware,”*** they told.

Following its closure, it is believed that Buckeye passed the repurposed tools to a different attack group.
 https://cyware.com/news/chinese-threat-actor-group-apt3-used-nsa-linked-tools-to-target-organizations-says-new-report-ab7ce6f1
