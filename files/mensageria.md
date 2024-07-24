# Mensageria

Mensageria é o sistema de troca de mensagens entre sistemas ou aplicações para comunicação assíncrona. Isso permite que diferentes componentes de software se comuniquem de maneira eficiente e desacoplada. Mensageria é amplamente utilizada em arquiteturas distribuídas, microserviços e sistemas de eventos. 

Aqui estão alguns conceitos e componentes chave relacionados à mensageria:

1. _**Fila de Mensagens**_: Armazena mensagens que são enviadas por produtores e lidas por consumidores. Exemplos: RabbitMQ, Amazon SQS.
   
2. _**Tópico**_: Em sistemas de publicação/assinatura (pub/sub), mensagens são publicadas em tópicos e entregues a todos os consumidores inscritos nesse tópico. Exemplos: Apache Kafka, Google Pub/Sub.
   
3. _**Produtor**_: Componente que envia mensagens para uma fila ou tópico.
   
4. _**Consumidor**_: Componente que lê mensagens de uma fila ou tópico.
   
5. _**Broker de Mensagens**_: Software intermediário que gerencia a transmissão de mensagens entre produtores e consumidores. Ele garante a entrega e pode incluir funcionalidades como persistência de mensagens, confirmação de entrega e ordenação. Exemplos: RabbitMQ, Apache Kafka, ActiveMQ.
   
6. _**Mensagens**_: Unidades de dados enviadas entre sistemas. As mensagens podem ser simples, contendo texto ou dados binários, ou complexas, como objetos serializados.
   
7. _**Garantias de Entrega**_: Políticas que garantem como e quando as mensagens são entregues. Pode ser pelo menos uma vez, no máximo uma vez ou exatamente uma vez.

A mensageria é fundamental para criar sistemas robustos e escaláveis, permitindo que componentes funcionem de forma independente e resiliente a falhas.

[Voltar para o Índice](/README.md)