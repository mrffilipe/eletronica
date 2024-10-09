### **2. Componentes Passivos**

#### **2.1 Resistor**

- **Conceito**:  
  O resistor é um componente que oferece resistência ao fluxo de corrente elétrica em um circuito. Ele é usado para controlar a corrente, dividir tensão ou proteger componentes sensíveis a altas correntes. Em um circuito, resistores dissipam energia na forma de calor.

  **Símbolo**: Representado por uma linha "quebrada" ou zigue-zague em diagramas esquemáticos.

- **Tipos de Resistores**:
  - **Resistores Fixos**: Têm um valor de resistência constante.
  - **Resistores Variáveis (Potenciômetro/Trimpot)**: Podem alterar a resistência ao girar ou deslizar um contato.
  
- **Aplicações Comuns**:
  - **Divisores de Tensão**: Usados para criar uma tensão menor a partir de uma tensão maior. A fórmula do divisor de tensão em resistores é:
    \[
    V_{out} = V_{in} \times \frac{R_2}{R_1 + R_2}
    \]
  - **Resistores Pull-up e Pull-down**: Utilizados para garantir que um ponto de entrada (como uma porta de um microcontrolador) esteja sempre em um nível lógico definido, evitando flutuações indesejadas. Um resistor pull-up conecta o ponto à tensão de alimentação (lógica "1"), enquanto um pull-down conecta o ponto ao terra (lógica "0").

---

#### **2.2 Capacitor**

- **Conceito**:  
  O capacitor é um componente que armazena energia na forma de um campo elétrico. Ele consiste em duas placas condutoras separadas por um material isolante (dielétrico). Quando uma tensão é aplicada, uma carga elétrica se acumula nas placas, criando uma diferença de potencial entre elas.

  **Símbolo**: Duas linhas paralelas no esquema, representando as placas do capacitor.

- **Propriedades**:
  - **Capacitância**: A capacidade de um capacitor de armazenar carga. A unidade é o Farad (F), mas capacitores geralmente são encontrados em subunidades como microfarads (µF), nanofarads (nF) ou picofarads (pF).
  
  **Fórmula**:
  \[
  C = \frac{Q}{V}
  \]
  Onde \(C\) é a capacitância, \(Q\) é a carga acumulada e \(V\) é a tensão aplicada.

- **Tipos de Capacitores**:
  - **Capacitores Eletrolíticos**: Usados em circuitos que exigem alta capacitância, mas têm polaridade (devem ser conectados corretamente ao positivo e negativo).
  - **Capacitores Cerâmicos**: Não têm polaridade e são comumente usados em filtros e circuitos de alta frequência.

- **Aplicações**:
  - **Capacitor de Desacoplamento**: Utilizado para suavizar picos de tensão e ruídos em circuitos alimentados por fontes de energia, ajudando a estabilizar a alimentação.
  - **Capacitor como Filtro**: Utilizado em filtros passa-baixa e passa-alta, permitindo que certas frequências passem e bloqueando outras. Um exemplo é o uso em circuitos de fontes de alimentação para suavizar a tensão após a retificação (conversão de CA para CC).

  A fórmula para a impedância do capacitor (resistência que ele oferece à corrente alternada) é dada por:
  \[
  X_C = \frac{1}{2\pi f C}
  \]
  Onde \(f\) é a frequência e \(C\) é a capacitância.

---

#### **2.3 Indutor**

- **Conceito**:  
  O indutor é um componente que armazena energia em um campo magnético quando a corrente elétrica passa por ele. Ele consiste em um fio enrolado em torno de um núcleo (que pode ser de ar ou material ferromagnético).

  **Símbolo**: Representado por uma espiral em diagramas esquemáticos, indicando o enrolamento do fio.

- **Propriedades**:
  - **Indutância**: A capacidade de um indutor de armazenar energia em um campo magnético. A unidade é o Henry (H).
  
  **Fórmula**:
  \[
  V = L \frac{dI}{dt}
  \]
  Onde \(L\) é a indutância, \(V\) é a tensão e \(\frac{dI}{dt}\) é a taxa de variação da corrente ao longo do tempo.

- **Tipos de Indutores**:
  - **Indutores de Núcleo de Ar**: Usados em altas frequências.
  - **Indutores de Núcleo Ferromagnético**: Utilizados em circuitos de baixa frequência ou para armazenar grandes quantidades de energia.

- **Aplicações**:
  - **Filtro LC**: Utiliza indutores em combinação com capacitores para filtrar sinais em circuitos de alta frequência, como em fontes de alimentação chaveadas.
  - **Diodo Flyback**: Indutores são usados em conjunto com diodos flyback em circuitos com cargas indutivas, como motores ou relés, para proteger o circuito contra picos de tensão quando o campo magnético do indutor colapsa.

  A fórmula da impedância de um indutor é:
  \[
  X_L = 2\pi f L
  \]
  Onde \(f\) é a frequência e \(L\) é a indutância.