Rete priva di IPv4 pubblico
2 edifici sono stati dotati di quattro subnet, tutte comunicanti fra loro tramite router
Ogni piano è dotato di access point con un raggio di 140m collegato alla propria subnet
Sono stati eseguiti ping test che hanno dato esito positivo in tutte le casistiche 
Sono stati eseguiti ping test dai dispositivi collegati agli access point agli altri host collegati tramite cablaggio, tutti i test hanno dato esito positivo 
ATTENZIONE : gli host singoli rappresentano gruppi di 30 che per questioni pratiche sono state rappresentate con una sola unità
calcoli :
Subnet  	Host   Range	                Broadcast Address
1	        192.168.0.0-192.168.0.1       192.168.0.62	192.168.0.63
2	        192.168.0.64-192.168.0.65     192.168.0.126	192.168.0.127
3	        192.168.0.128-192.168.0.129   192.168.0.190	192.168.0.191
4	        192.168.0.192-192.168.0.193   192.168.0.254	192.168.0.255
