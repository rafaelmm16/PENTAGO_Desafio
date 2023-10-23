# PENTAGO_Desafio
Desafio da PENTAGO, utilizando o Bizagi Modeler e Studio

``Desafio - Processo de Pagamento de Contas``

<div>
<p align="justify">
O objetivo deste processo é realizar um controle básico das contas pagas de uma empresa.
Este processo começa com a Solicitação de Pagamento sendo realizada pelo Requisitante, que poderá anexar algum documento que comprove a necessidade de pagamento e deverá informar uma breve descrição do item que será pago, o valor que deverá ser pago e a forma de pagamento, e caso a forma de pagamento escolhida seja boleto ou cheque deverá ser informado se é à vista ou parcelado em até quantas vezes (sendo limitado em até 6x) gerando uma instância (ou token) de processo para Realizar Baixa do Pagamento de cada parcela.
Após realizada a Solicitação de Pagamento, o processo deve seguir para a Aprovação da Gestão, que poderá Aprovar, Retornar para Revisão ou Reprovar a solicitação de pagamento, no caso de Retornar para Revisão o fluxo deverá permitir que o Requisitante modifique ou finalize a solicitação. Caso seja Aprovado, a solicitação deverá seguir para a Área de Pagamentos.
A Área de Pagamentos deverá Realizar Baixa do Pagamento da conta solicitada, informando a Data e o Valor Pago e caso a forma de pagamento seja cheque deverá ser informada a data de compensação.
Feito o pagamento da conta o usuário Requisitante deverá ser notificado do pagamento (poderá ser gerado um recibo como template e anexado ao e-mail).
</p>
</div>

---
# PROCESSO
>1.	Solicitação de Pagamento (Requisitante)
o	Anexar documento comprovante
o	Informar descrição, valor e forma de pagamento
o	Se boleto ou cheque, informar se é à vista ou parcelado (até 6x)
o	Gerar instância para Realizar Baixa do Pagamento de cada parcela
>2.	Aprovação da Gestão
o	Pode Aprovar, Retornar para Revisão ou Reprovar a solicitação
o	Se Retornar para Revisão, permitir que o Requisitante modifique ou finalize a solicitação
o	Se Aprovado, seguir para a Área de Pagamentos
>3.	Área de Pagamentos
o	Realizar Baixa do Pagamento da conta solicitada
o	Informar Data e Valor Pago
o	Se cheque, informar data de compensação
>4.	Notificação ao Requisitante
o	Após o pagamento da conta, notificar o Requisitante (gerar recibo e anexar ao e-mail)

