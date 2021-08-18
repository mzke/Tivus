# Tivus

Este aplicativo foi construído para atender minhas necessidades de instalação e/ou atualização de aplicativos em rede local.

Embora eu tenha usado aplicativos como WPKG e EMCO, algumas vezes sentia necessidade de possíbilitar que o próprio usuário efetuasse a instalação de aplicativos mas ele não tinha privilégios suficientes para isso.

O conceito do Tivus é bastante simples:

- Um repósitório na sua rede local onde ficam armazenados os instaladores e/ou atualizadores dos seus aplicativos.
- Um aplicativo de linha de comando onde o administrador define comandos de instalação de cada aplicativo.
- Um agente instalado em cada computador com Windows que recebe a lista de aplicativos da nuvem e roda o comando de instalação como administrador.
