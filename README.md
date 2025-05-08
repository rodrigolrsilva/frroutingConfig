# frroutingConfig

Tentativa de utilização do FRRouting (fork do Quagga) para estabelecimento de namespaces afim de criar uma topologia que permitisse utilizar OSPF e RIP para analisar a performance nessa mesma topologia. 
Devido a problemas com o daemon mgmtd não funcionou, esse daemon impedia a criação de sockets apropriados para o OSPF/RIP e, no processo, impedia a comunicação com o vtysh. Explicado em detalhes no PDF com o passo-a-passo.
