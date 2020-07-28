# tack_paper_doc
This repo is to share some slides and videos for the SIGCOMM2020 paper “[TACK: Improving Wireless Transport Performance by Taming Acknowledgments](http://conferences.sigcomm.org/sigcomm/2020/)”.

## Abstract 

The shared nature of the wireless medium induces contention between data transport and backward signaling, such as acknowledgement. The current way of TCP acknowledgment induces control overhead which is counter-productive for TCP performance especially in wireless local area network (WLAN) scenarios. In this paper, we present a new acknowledgement called TACK ("Tame ACK"), as well as its TCP implementation TCP-TACK. TCP-TACK works on top of commodity WLAN, delivering high wireless transport goodput with minimal control overhead in the form of ACKs, without any hardware modification. To minimize ACK frequency, TACK abandons the legacy received-packet-driven ACK. Instead, it balances byte-counting ACK and periodic ACK so as to achieve a controlled ACK frequency. Evaluation results show that TCP-TACK achieves significant advantages over legacy TCP in WLAN scenarios due to less contention between data packets and ACKs. Specifically, TCP-TACK reduces over 90% of ACKs and also obtains an improvement of ∼28% on goodput. We further find it performs equally well as high-speed TCP variants in wide area network (WAN) scenarios, this is attributed to the advancements of the TACK-based protocol design in loss recovery, round-trip timing, and send rate control.

