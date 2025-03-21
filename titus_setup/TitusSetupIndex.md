---
layout: page
title: Guide to run titus event display on SBND machines
---

## For setting up your VNC (it’s faster and recommended if you are remote)
step1 : Copy the following text into your local (e.g. laptop's) $HOME/.ssh/config.  If the config file does not exist, create it..
Host sbndgpvm03
  HostName sbndgpvm03.fnal.gov
  User yadav
  ForwardAgent yes
  ForwardX11 yes
  ForwardX11Trusted yes
  GSSAPIAuthentication yes
  GSSAPIDelegateCredentials yes
  LocalForward 5901 localhost:64855

Change username and sbndgpvm number (if you prefer any other machine out of four we have)
