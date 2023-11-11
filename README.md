# LuzNoEscuro
Projeto de Objetos Inteligentes Conectados

Os componentes de hardware utilizados serão: Arduino UNO, fios de ligação de ponte, LDR 5 mohm, LED genérico, resistor 10k ohm e um resistor 220 ohm. O software usado será o Arduino IDE.
O LDR é colocado em um ambiente onde ele pode detectar a intensidade da luz ambiente.
O LDR está conectado em série com o resistor de 10k ohms para formar um divisor de tensão. A tensão na junção entre o LDR e o resistor varia de acordo com a luz ambiente. Quando estiver escuro, a resistência do LDR será alta, e a tensão será menor. Quando estiver claro, a resistência do LDR será baixa, e a tensão será maior.
O Arduino está programado para ler a tensão na junção do LDR e do resistor usando uma de suas portas analógicas (por exemplo, A0). Através dessa leitura analógica, o Arduino pode determinar o nível de luminosidade no ambiente.
Com base na leitura do LDR, o Arduino decide se deve acender ou apagar o LED. Se o nível de luminosidade for inferior a um valor predefinido (indicando que está escuro), o Arduino acenderá o LED. Caso contrário, ele o apagará.
Acende no escuro, apaga no claro.
