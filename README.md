# Rede para o show da banda de Miguel

Esse projeto, desenvolvido para o curso Arquitetos de Nuvem AWS, da Proz Educação, aborda a necessidade de comunicação eficiente entre a equipe de produção durante o show da banda de Miguel. Para isso, foi necessário criar uma rede em topologia estrela, no Cisco Packet Tracer, permitindo a comunicação fluida entre os membros da equipe.

A topologia escolhida é a estrela, onde todos os computadores da equipe se conectam a um switch central. Essa topologia oferece as seguintes vantagens:

*   **Centralização:** Facilita o gerenciamento e a resolução de problemas.
*   **Escalabilidade:** Permite a adição de novos dispositivos facilmente.
*   **Confiabilidade:** A falha de um dispositivo não afeta os demais.


## Configuração

A rede consiste em um switch central conectando quatro PCs, representando os membros da equipe de produção.

    *   PC1 (vocalista): 192.168.1.10
    *   PC2 (baixista): 192.168.1.11
    *   PC3 (baterista): 192.168.1.12
    *   PC4 (guitarrista): 192.168.1.13

![images](https://github.com/phatima05/proz-topologia-de-rede/blob/main/images/Topologia_Rede_CISCO.png)


A imagem abaixo, apresenta a resposta do ping feito do PC1 (192.168.1.10) para o PC2 (192.168.1.11), para demonstrar a conectividade da rede:

![images](https://github.com/phatima05/proz-topologia-de-rede/blob/main/images/Rede_CISCO.png)

```
Projeto: ![images](https://github.com/phatima05/proz-topologia-de-rede/blob/main/images/Rede.pkt)
