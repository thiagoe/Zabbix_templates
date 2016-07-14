# Zabbix_templates

Este template executa uma descoberta SNMP buscando as OID que informam o numero de clientes conectados aos painéis mikrotik. 
Instruções:
- É necessário criar uma expressão regular para filtrar os resultados. Faça adequação e acordo com seu ambiente
Os temos comuns são:
1»vlan[Result is FALSE]
2»loop[Result is FALSE]
3»eth[Result is FALSE]
4»ppoe[Result is FALSE]
- Na regra de descoberta aplique o filtro de acordo com nome escolhido na expressão regular.
Meu contato:
thiago3@gmail.com
