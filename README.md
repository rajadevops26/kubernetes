# kubernetes
We need to install kubernetes before we required pre-requasities
WE NEED 2+ CPUS AND RAM 4GB+ REQUIRED(ie t2.mediam)
 
Family	        Type	    vCPUs 	Memory (GiB)	Instance Storage (GB) 
General purpose	t2.nano	    1	    0.5	          EBS only	
General purpose	t2.micro	  1	    1	            EBS only	
General purpose	t2.small	  1	    2	            EBS only	
General purpose	t2.medium 	2	    4	            EBS only	
General purpose	t2.large	  2	    8	            EBS only	
General purpose	t2.xlarge	  4	    16	          EBS only	
General purpose	t2.2xlarge	8	    32	          EBS only	

US East (N. Virginia) COST 
$0.0464 per On Demand Linux t2.medium Instance Hour1.580 Hrs$0.07
$0.0928 per On Demand Linux t2.large Instance Hour2.193 Hrs$0.20

and enable ports 6443 and 443 on aws security groups
if u want ping agent enable allipv4traffic
