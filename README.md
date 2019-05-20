# utils-OLT8820G

Facilitador de configuração e gestão da OLT 8820G Intelbras

Criado por Vinicius Macedo

**Fluxo do Script**

#### Verifica se todas as dependencias estão instaladas

* Se sim: Continua com o Script	 

* Se não: Verifica se é Root, se sim tenta instalar, se não dá um erro solicitando que o usuário inicie como root.

#### Coleta as Informações

* Solicita IP de gerenciamento da OLT	

* Solicita Usuario OLT	

* Solicita a Senha da OLT

* Se nada for informado, ele utiliza as informações Default IP: 192.168.1.1 usuario e senha intelbras	

* Pergunta se vai ser acessada via SSH ou Telnet
