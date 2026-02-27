📋 Sistema de Cadastro - Java Swing

Projeto simples de cadastro de usuário desenvolvido em Java utilizando a biblioteca gráfica Swing.
A aplicação permite inserir dados pessoais e exibi-los em uma caixa de diálogo ao clicar no botão Salvar.

🚀 Funcionalidades

✅ Campo para Nome

✅ Seleção de Idade através de JSlider (0 a 100 anos)

✅ Campo para CPF

✅ Campo para Cidade

✅ Campo para Bairro

✅ Campo para Estado

✅ Seleção de Gênero:

Masculino

Feminino

Outro

✅ Exibição dos dados cadastrados via JOptionPane

✅ Interface com tema Nimbus (Look and Feel)

🖥️ Interface

A interface foi construída utilizando componentes do javax.swing, incluindo:

JTextField

JLabel

JButton

JRadioButton

JSlider

JOptionPane

O controle de idade é feito por um Slider, e o valor selecionado é atualizado dinamicamente na tela.

🛠️ Tecnologias Utilizadas

Java

Java Swing

IDE compatível com GUI Builder (ex: NetBeans)

📦 Estrutura do Projeto
cadastro/
 ├── Tela.java

Tela.java → Classe principal que contém toda a interface gráfica e a lógica do formulário.

▶️ Como Executar

Clone o repositório:

git clone https://github.com/seu-usuario/seu-repositorio.git

Abra o projeto em sua IDE (recomendado: NetBeans).

Execute a classe:

Tela.java

Ou compile manualmente:

javac Tela.java
java Tela
🧠 Lógica do Sistema

Ao clicar no botão SALVAR:

Os valores digitados são capturados.

O gênero selecionado é verificado.

Todos os dados são exibidos em uma janela modal utilizando:

JOptionPane.showMessageDialog()
🎯 Objetivo do Projeto

Este projeto tem como objetivo:

Praticar desenvolvimento de interfaces gráficas com Swing

Trabalhar com eventos (ActionListener e ChangeListener)

Manipular componentes gráficos

Aplicar lógica condicional em formulários

📌 Melhorias Futuras

 Validação de campos obrigatórios

 Máscara para CPF

 Agrupamento dos RadioButtons com ButtonGroup

 Botão funcional para fechar a aplicação

 Persistência de dados (arquivo ou banco de dados)
