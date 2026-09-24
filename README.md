# Aula-4-Sistem.Distri

## Aula-4---Comunicação-de-Alto-Nível-RPC
Este repositório tem como objetivo documentar as atividades práticas e reflexões propostas na disciplina de Sistemas Distribuídos, servindo como registro de aprendizado e evidência das práticas realizadas em laboratório. Sinta-se à vontade para explorar os arquivos e acompanhar a evolução dos conceitos ao longo do semestre.

O que foi proposto em aula
A quarta aula teve como foco apresentar a Comunicação de Alto Nível: RPC (Chamada de Procedimento Remoto), retomando a comunicação por sockets estudada nas aulas anteriores e mostrando por que programar diretamente com send(), recv(), sendto() e recvfrom() pode aumentar a complexidade do código.


## Atividade Prática — Mini Calculadora Distribuída
Objetivo: perceber a diferença entre trocar mensagens manualmente e invocar operações remotas.
Vamos criar um servidor que oferece operações matemáticas remotamente.
O cliente não implementará as operações: ele solicitará a execução ao servidor.
Usaremos apenas recursos da biblioteca padrão do Python: xmlrpc.server e xmlrpc.client.
Não será necessário instalar Flask, Django ou bibliotecas externas.
Arquivos: servidor_rpc.py e cliente_rpc.py.

É necessário ter o python baixado e de preferencia utilizar uma IDE.
Para Utilizar o arquivo recomendo que baixe o Zip pois já está estruturado para uso, também disponibilizei o uso por copiar o txt... Basica será apenas necessario usar um terminal e executar o programa da calculadora.
