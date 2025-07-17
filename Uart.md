UART
Universal asynchronous receiver/transmitter

Modos de transmissão: \
Duplex: Os dados podem ser transmitidos ou recebidos \
Simplex: Apenas uma direção. O dado pode apenas ser recebido ou enviado. \
Half Duplex: O dado pode ser transmitido nas duas direções, mas apenas uma direção por vez \
Full Duplex: O dado pode ser transmitido e recebido simultaneamente.

Modo assíncrono usa bytes de start e stop (para cada byte)
O bit de start é sempre 0
O bit de parada pode ser 1 bit ou 2 bits, é sempre 1

Parâmetros de configuração: \
Baudrate: É a velocidade de conexão. (Expressa em bits per second) \
Stop bit: A quantidade de bits de parada transmitida  \
Paridade: Par ou Impar. Utilizada para checar erros. \
Mode: Se o mode RX ou TX está habilitade ou desabilitado. \
Tamanho da palavra: Número de bits da dados que podem ser transmitidos ou recebidos. 8 ou 9. \
Fluxo de controle de Hardware: Especifica que o fluxo está habilitado ou desabilitado. \
