#Awesome-SDR

This repo contains traffic samples and references for my SDR workshop.

#Setup for using these samples

One NoElec SDR (RTL-SDR.com or HackRF One also work)

One Ubuntu or Kali OS (VM in VirtualBox or VMware works)

Install guest additions from "CD" (VM only, required for USB passthrough)

`sudo apt-get update && apt-get dist-upgrade`

`sudo apt-get install gqrx-sdr rtl-433 multimon-ng`

`sudo apt-get install snapd` (Kali)

`sudo systemctl enable --now snapd apparmor` (Kali)

`sudo snap install urh`

Add a sound card (VM only)

REBOOT! `sync; sync; sync; shutdown -r now`


#Learning Better SDR and DSP

https://smile.amazon.com/dp/B078MMXPRY

https://greatscottgadgets.com/sdr/

https://samy.pl/opensesame/

