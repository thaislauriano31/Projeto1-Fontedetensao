# Projeto: Fonte de Tensão Ajustável

O objetivo deste projeto, da disciplina SSC0180 - Eletrônica para Computação, é desenvolver uma fonte de tensão ajustável entre 3V e 12V para 100mA.



# Componentes usados:

- **Transformador**: é responsável por receber a tensão da tomada e diminuí-la, através de suas espiras e alteração do fluxo magnético que passa por elas.

- **Diodos**: são dispositivos que permitem a passagem de corrente elétrica apenas em uma direção. Assim, podem ser utilizados para retificar a onda da corrente alternada. Cada diodo consome 0,7 V de tensão. Como são utilizados 2 de cada vez, sempre haverá um decréscimo de 1,4 V.

   ![image](https://user-images.githubusercontent.com/83373458/127049512-0a5a28b2-f349-46d1-933e-0340b1e11137.png)


- **Capacitor**:  é responsável por diminuir o ripple (variação entre o pico máximo e mínimo de tensão). Quando a tensão provinda da ponte retificadora chega ao capacitor, ele se carrega enquanto essa tensão for maior do que a tensão de sua carga interna. Quando ela for menor que a tensão interna, o capacitor passará a suprir o circuito e descarregar.

- **Diodo Zener**: é o diodo responsável pela regulação da tensão, “cortando” o ripple. Se a tensão estiver acima da sua especificação, o diodo zener fará com que a tensão diminua para o especificado.
  - Exemplo de uso de um Zener e seus cálculos:
  
  ![image](https://user-images.githubusercontent.com/83373458/127048457-799e4ea3-d32b-4ffe-9d59-01be08589564.png)
      ![image](https://user-images.githubusercontent.com/83373458/127049271-e5d84dad-2c8d-4303-9935-9d290a06551d.png)

- **Potenciômetro**: é um resistor com resistência ajustável, o que permite variar a tensão a que a carga está sujeita entre 3V e 12V.

- **Transistor**: é um componente que permite a passagem de corrente elétrica de forma ajustável, funcionando como um interruptor eletrônico.

# Valores dos componentes:

| Quantidade | Componente | Valor |
|------------|------------|-------|
| 1 | Transformador 110V para 18V| [20,40](https://www.multcomercial.com.br/transformador-de-tensao-127-220v-para-18v18v-500ma.html)| 
| 4 | Diodo 1N4004 | [0,52](https://www.baudaeletronica.com.br/diodo-1n4004.html) (4 x 0,13) |
| 1 | Capacitor | [0,67](https://www.americanas.com.br/produto/3151870134?opn=YSMESP) |
| 1 | Diodo Zener 13V | [0,21](https://www.baudaeletronica.com.br/diodo-zener-1n4743-13v-1w.html) |
| 1 | Potenciômetro 5k ohm | [1,74](https://www.moduloeletronica.com.br/produto/potenciometro-linear-5k-wh148-1-l20-3t-mini-pci-zx/3137583/)|
| 1 | Transistor NPN | [0,22](https://www.baudaeletronica.com.br/transistor-npn-bc337.html)|
| 1 | LED 5mm | [0,25](https://www.baudaeletronica.com.br/led-difuso-5mm-vermelho.html)|
| 1 | Resistor 1k ohm | [0,06](https://www.baudaeletronica.com.br/resistor-1k-5-1-4w.html)|
| 1 | Resistor 2,2k ohm | [0,06](https://www.baudaeletronica.com.br/resistor-750k-5-1-4w.html)|
| 1 | Resistor 750 ohm | [0,06](https://www.baudaeletronica.com.br/resistor-750k-5-1-4w.html)|
|**Total:**| | **24,76**|

#  Circuito no Falstad
![image](https://user-images.githubusercontent.com/83373458/127062046-21b91843-8a78-46f5-85c3-d25232b66909.png)

Link do circuito: https://tinyurl.com/yjoj8fdw

# Cálculos:

![image](https://user-images.githubusercontent.com/83373458/127064325-d9090c79-19df-4197-9793-083a7b63e7e1.png)


# Alunos:

- Thaís Lauriano
- Susy Dutra 
- Gustavo Sampaio
- Reynaldo Coronatto
