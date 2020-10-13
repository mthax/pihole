# pihole
# This my public little Repo for my RPi Pihole Server running on Ubuntu
# Security Critial information like keys gets removed, but things like a well configured sshd_config or a hostname isnt very security critial if it isnt public. 
# This isnt thought as a copy and run it "thing". Configuration fits for me, might not fit for you, might even throw an error on your system if you copy it 1to1.
# My main goal from this Repo is, to easily restore configuration files in case of failure or to use it as a base configuration to work with. 
# Not every config file has max. security as the goal ( like the pihole sshd_config ). SSH Forwarding ( and similar Options ) for example are enabled there as a Quality of Life  Feature and since its a well locked down private LAN with pubkey etc etc., the risk is minimal. If there is an allready a intruder using that, you have a much bigger problem than SSH Forwarding. If that system would be public, that would be a whole differnet story
