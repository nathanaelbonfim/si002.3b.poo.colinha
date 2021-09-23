# Colinha - Nathanael



### Revisão: orientação a objeto





### O que é o Swing?

É uma biblioteca para trabalhar com interface gráfica no JAVA, é compatível com o AWT (Adbstract Window Toolkit).

### Componentes Swing

| Nome                | Função                                                       | Caso de uso                                                  |
| ------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| JFrame              | É o elemento usado para criar janelas. Serve como base para adição dos outros elementos. É aqui que são especificadas as dimensões, visibilidade e o menu superior. | Criação de uma nova tela na aplicação.                       |
| JInternalFrame      | Permite colocar janelas virtuais dentro de uma janela JFrame | Novas subtelas sem abrir novas janelas.                      |
| JPanel              | Um container (espaço) para que sejam colocados novos componentes dentro. Normalmente usado para criação de layouts e subdivisões. | Espaço uma barra lateral.                                    |
| JMenuBar            | Barra de menus na parte superior da tela                     |                                                              |
| JMenu               | Item da JMenuBar                                             |                                                              |
| JMenuItem           | Item do menu dentro do JMenu (pode ser colocado recursivamente com jm.add(jmi) para criação de submenus) | Menu (JMenu) com os estados e submenus (JMenuItem) com as cidades. |
| ActionListener      | Uma interface (implements) para receber eventos (evt.getSource() == Object) | Buscar qual item foi clicado em uma JMenuBar                 |
| FocusListener       | Interface para detectar que o usuário selecionou um campo ou objeto. | Verificar se um input foi clicado ou se o usuário saiu dele. |
| JFormattedTextField | Entrada de dados com máscara ou outro formato em particular, data, por exemplo. Para formatar, usa-se a mesma sintaxe de máscara do Excel. | Formatar a entrada de dados para colocar os pontos do CPF.   |
| JTextField          | Campo de texto padrão do Swing                               | Entrada de código de produto                                 |
| JLabel              | Etiqueta, normalmente usada para identificar um campo de entrada ou texto normal. | Identificar  visualmente o campo de entrada de Endereço.     |
| JButton             | Botão padrão do Swing. Precisa ser combinado com o ActionListener para executar ações. | Botão 'Incluir' para cadastrar um novo registro no banco.    |
| BorderLayout        | Ferramenta de layout que permite adicionar componentes de acordo com coordenadas geográfica (south, north, west). Usado em conjunto com JFrame/InternalFrame.getContentPane() e outros que permitam esse método. | Criação de uma sidebar no sistema com BorderLayout(gapHorizontal, gapVertical) |
| GridBagLayout       | Gerenciador de layout que permite adicionar componentes em partes específicas da tela com as GridBagConstrainsts | Adicionar o espaço para colocar botões na sidebar.           |
| GridBagContraints   | Objeto com um conjunto de constantes com a finalidade de definir métricas de separação e orientação ao GridBagLayout. | Colocar um elemento ao centro e no topo ocupando 2 colunas em um GridBagLayout |
| Insets              | Padding (espaçamento) e Margin (margem) dos elementos dentro de um GridBagConstrainsts | Espaço entre os botões de ação.                              |
| GridLayout          | Ferramenta para organização do layout que distribui a largura e altura dos componentes de acordo com espaço disponível (estica e encolhe tudo) | Botões de ação na barra superior de um sistema.              |



