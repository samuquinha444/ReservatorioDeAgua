# ReservatorioDeAgua
## Controle de Boias

## Visão Geral
Este programa simula o controle de um sistema com três boias que indicam o estado de funcionamento de um equipamento. Ele permite verificar se as boias estão ligadas ou desligadas e toma decisões com base nesses estados.

## Funcionalidades
- Solicita ao usuário o estado de cada uma das três boias (ligada ou desligada).
- Realiza ações específicas com base nas combinações de estados das boias.
- Exibe mensagens indicativas sobre o que deve ser feito (ligar registro, solicitar técnico, etc.).

## Como Funciona

### Entradas
O usuário deve fornecer três entradas:
1. **Boia 1**: (0 para desligada, 1 para ligada)
2. **Boia 2**: (0 para desligada, 1 para ligada)
3. **Boia 3**: (0 para desligada, 1 para ligada)

### Saídas
Com base nas entradas, o programa fornecerá uma das seguintes respostas:
- **Ligar Registro!**: Quando as boias 1 e 2 estão desligadas ou quando a boia 3 está ligada e as outras estão desligadas.
- **Erro Sensor!**: Quando as boias 2 e 3 estão ligadas e a boia 1 está desligada.
- **Ligar Bomba!**: Quando a boia 1 está ligada e a boia 2 está desligada.
- **Manter bomba desligada!**: Quando todas as boias estão ligadas.

### Exemplo de Uso
1. Compile e execute o programa.
2. Siga as instruções na tela para inserir o estado de cada boia.
3. O programa exibirá a ação a ser tomada com base nas suas entradas.

## Tratamento de Erros
- O programa verifica se as entradas são válidas (números) e exibe uma mensagem de erro caso contrário.

## Conclusão
Esse programa é uma simulação simples que pode ser expandida para incluir mais funcionalidades ou integrações com sistemas de monitoramento real. Ele é útil para entender como combinar condições e gerenciar entradas do usuário em C#.

## Licença
Este projeto está licenciado sob a Licença MIT. Sinta-se à vontade para modificar e distribuir conforme necessário.
