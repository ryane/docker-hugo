# hugo docker image

## [2016-09-06 Tue 10:12]

I briefly tried to use this to build a hugo site from a docker container. This
worked in normal environments but it was ultimately an unsuccessful approach
when running a build in a jenkins slave that was running in docker and managed
by Kubernetes (via the Kubernetes Jenkins plugin).

see imm-jenkins, eschland.com and imm-gce-kube a GKE project I am using to host
my entire personal and business infrastructure.

There are other hugo images published and this one doesn't particularly offer
anything new.
