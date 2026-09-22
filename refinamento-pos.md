## 5. Refinamento pós-lançamento

# Caso após o lançamento, tivéssemos 30% de evasão na etapa de validação, podemos:

Entender junto do cliente (B2B) se a Mia é um bot de Prospecção ou de Gestão de Base. Caso seja um número receptivo de prospecção, talvez não exista a necessidade de solicitarmos o documento e início, pode ser apenas um erro de jornada, porque como iremos acessar as ofertas do usuário que não é cliente, se ele não tem contrato na base previamente? Talvez uma qualificação de lead trouxesse mais resultado.
Para a Gestão de Base: O banco não ofereceria um número apenas de oferta, sem ser um número com consulta, então mudar a abordagem para algo como: “Para acessar sua conta, confirme o número do seu CPF. 👇”
Traçar uma rota alternativa: Um teste A|B com a hipótese de que usuários que visualizam o produto primeiro, tem menor evasão. Em caso de notificação ativa, não é boa prática pedir documento de início, sendo que você está contatando o usuário. Pode gerar denúncia e bloqueio do número junto a meta. Colocar 70/20, 70% para o fluxo antigo e 20% para o novo, com qualificação de lead, com aumento progressivo conforme resultado.
Trackings: fluxo trackeado para entendermos os inputs inesperados dos usuários, respostas de CSAT. Usuário sempre se manifesta.
Conferir também se Mia possui verificado. 

## Sugestões

Validar por fluxo determinísticos e não por LLM. Por melhor que a IA esteja calibrada, ela pode em algum momento delirar e dar erro, que geram custos desnecessários. Colocar essas validações através de RegEx e Cascata de Validação, diminui os custos e faz o Agent trabalhar onde realmente precisa, como casos de atrito ou compreensão de propostas. Custo menor = budget para novos projetos.

Precisamos entender também que se temos o números do usuário, temos os dados dele. Hoje os meios de comunicação estão muito atualizados, precisamos saber quando conectar para pedir ou não um dado do usuário e a IA trabalhar para isso.
