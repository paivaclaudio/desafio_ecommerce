# Descrição do Desafio
 
## Modelagem para e-commerce

O esquema deverá ser adicionado a um repositório do Github para futura avaliação do desafio de projeto. Adicione ao Readme a descrição do projeto conceitual para fornecer o contexto sobre seu esquema.

### Objetivo
Refine o modelo apresentado acrescentando os seguintes pontos:
-   Cliente PJ e PF – Uma conta pode ser PJ ou PF, mas não pode ter as duas informações;
-   Pagamento – Pode ter cadastrado mais de uma forma de pagamento;
-   Entrega – Possui status e código de rastreio;

## 
### Observações da Modelagem:
 - O tipo de cliente foi modelado nas entidades PessoaFisica e PessoaJuridica para armazenar os atributos mais especializados de cada entidade. Os relacionamentos destas entidades com a entidade Cliente é do tipo 1:1 com cardinalidade mínima 0.
 - Para as formas de pagamento, o diagrama contempla apenas cartões de crédito, mas pode ser facilmente remodelado para incluir formas de pagamento como Boleto, PIX, etc.
 - Para cada pedido poderá haver mais de uma tentativa de entrega, então o relacionamento entre Pedido e Rastreamento é 1:N
 - Foi criada uma entidade para cadastros das categorias de produto para padronização do cadastro de categorias e relacionada à Produto em um relacionamento 1:N.
