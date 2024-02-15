# Arduino-LED-Button-Programs

Este repositório contém cinco programas Arduino que demonstram como ler a entrada de dois botões e controlar a saída de dois LEDs usando diferentes instruções condicionais e operadores. Os programas também usam uma técnica de debounce para evitar múltiplas contagens de um único pressionamento de botão.

## Programas

Os programas estão localizados na pasta `src` e cada um tem uma breve descrição de sua lógica e funcionalidade.

- **LED_Blink.ino**: Este programa faz o LED L1 piscar a cada segundo, independentemente dos botões.
- **LED_Blink_With_Button.ino**: Este programa faz o LED L1 piscar a cada segundo somente quando o botão b0 é pressionado.
- **LED_Blink_With_Two_Buttons.ino**: Este programa faz o LED L1 piscar a cada segundo somente quando o botão b0 é pressionado e o LED L2 piscar a cada segundo somente quando o botão b1 é pressionado.
- **LED_Blink_With_Two_Buttons_Using_AND_Operator.ino**: Este programa faz os LEDs L1 e L2 piscarem a cada segundo somente quando ambos os botões b0 e b1 são pressionados simultaneamente, usando o operador lógico AND.
- **LED_Blink_With_Two_Buttons_Using_OR_Operator.ino**: Este programa faz os LEDs L1 e L2 piscarem a cada segundo quando qualquer um dos botões b0 ou b1 é pressionado, usando o operador lógico OR.

## Imagens

![Esquemático do projeto](images/Aula_Pratica_1_schematics.jpg)

Esquema do projeto.

![Imagem do projeto](images/Aula_Pratica_1.png)

Imagem do projeto montado em uma protoboard.

## Licença

Este projeto está licenciado sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.
