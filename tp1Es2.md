
#WORDPRESS

##Índice

1. [Introdução](#introdução)
2. [Principais desenvolvedores e equipe de desenvolvimento](#principais-desenvolvedores-e-equipe-de-desenvolvimento)
3. [Evolução do sistema principais releases e novidades de cada uma](#evolução-do-sistema-principais-releases-e-novidades-de-cada-uma)
4. [Principais frameworks, ferramentas e linguagens usadas no desenvolvimento](#principais-frameworks-ferramentas-e-linguagens-usadas-no-desenvolvimento)
5. [Arquitetura do Wordpress](#arquitetura-do-wordpress)
6. [Diagrama do banco de Dados](#diagrama-do-banco-de-dados)
6. [Hierarquia dos Arquivos de Template](#hierarquia-dos-arquivos-de-template)
7. [Padrões de código](#padrões-de-código)
8. [Referências](#referências)



##Introdução


<p align = "justify">O Wordpress é uma plataforma semântica para publicação pessoal, focada na estética, nos padrões Web e na usabilidade. Foi produzido e vem sendo atualizado por colaboradores de todo o mundo. O wordpress tem o propósito de facilitar ao usuário a publicação de conteúdo web e é o maior CMS (Content Management System ou Sistema de Gerenciamento de Conteúdo) do mundo, com cerca de 70% do mercado. </p>

<p align = "justify">A linguagem PHP é a mais utilizada no desenvolvimento do sistema back-end. As linguagens Javascript, HTML e CSS são utilizadas para as soluções front-end. </p>

<p align = "justify">Wordpress é fácil de ser instalado e segundo o site do sistema a sua instalação leva cerca de 5 minutos para ser concluida. As suas atualizações são simples e podem ser realizadas automaticamente a partir das versões mais recentes. O Wordpress possui uma comunidade mundial de desenvolvedores e usuários que juntos fazem com que a ferramenta evolua continuamente. </p>


<p align = "justify">Os recursos nativos do Wordpress foram produzidos para tornar a experiência de publicação do usuário simples e agradável. O Wordpress é dotado de sistema de temas, API para a criação de plugins dentre outras coisas.</p>

<p align = "justify">O usuário ao utilizar o Wordpress poderá personalizar a aparência do seu site utilizando XHTML e CSS. Também é dado a liberdade para que o usuário crie seu próprio tema. Além disso, o usuário tem a liberdade de escrever e utilizar os seus próprios plugins em PHP. </p>
<p align = "justify">O Wordpress possui uma comunidade mundial de desenvolvedores e usuários que juntos fazem com que a ferramenta evolua continuamente. </p>


##Principais desenvolvedores e equipe de desenvolvimento


<p align = "justify">A equipe de desenvolvimento do Wordpress é formada em sua maioria por pessoas de sua comunidade.  O Wordpress possui uma comunidade mundial de desenvolvedores e usuários que juntos fazem com que a ferramenta evolua continuamente.</p>


<p align = "justify">A organização tem uma parceria com a corporação Automattic, onde Matthew Mullenweg e Ryan Boren, dois dos desenvolvedores primários do WordPress e também outros desenvolvedores do software são funcionários. Outros desenvolvedores importantes são: Mark Jaquith, Andrew Nacin, Andrew Ozz e Peter Westwood. O Wordpress possui uma comunidade mundial de desenvolvedores e usuários que juntos fazem com que a ferramenta evolua continuamente. </p>


<p align = "justify">Dentre os membros da comunidade, existe a classe dos WP testers, um grupo de pessoas que testa os lançamentos voluntariamente. Eles tem acesso aos nightly builds (versão mais recente que reflete as últimas mudanças feitas no código), versões Beta e Release Candidates. Analisando essas versões, eles podem encontrar e reportar erros em uma lista de emails especial, ou na ferramenta Trac (open source e de interface web para controle de mudanças em projetos de desenvolvimento de software) do projeto. O Wordpress possui uma comunidade mundial de desenvolvedores e usuários que juntos fazem com que a ferramenta evolua continuamente. </p>


Os times e suas respectivas funções são: 

**Core** - Responsáveis por escrever código, corrigir bugs, debater decisões e outras coisas relacionadas ao desenvolvimento da ferramenta. Não é necessário ter uma vasta experiência em PHP. Se a pessoa apenas estuda programação já pode ser aceita no time.

**Design** - Focado no design e desenvolvimento da interface do usuário. Realizam discussões regulares sobre mockups, design e user testing.

**Mobile** - Responsáveis pelo desenvolvimento de apps para iOS e Android. São requisitados profissionais aptos a programar em Java, Objective-C ou Swift. Também são necessários designers, especialistas em experiência de usuário e testers.

**Acessibility** - O grupo a11y fornece o conhecimento de acessibilidade necessário para o projeto. 

**Polyglots** - Responsáveis pela tradução do software ou desenvolvimento de tradutores.

**Support** - O Fórum do Wordpress é o local onde são colocados diversas questões relacionadas a erros, dificuldades de uso, bugs e etc. Qualquer membro pode responder as questões e contribuir para sanar as dúvidas dos outros.

**Themes** - Esse time revisa e aprova cada tema submetido ao Wordpress.

**Documentation** - Responsáveis por escrever a documentação de tudo, incluindo do código, manuais, developer.wordpress.org, admin help, inline docs e tudo que requerer uma explicação por palavras.

**Community** - Esta equipe supervisiona eventos oficiais, programas de orientação, busca de contribuintes, e outras formas de fazer a comunidade crescer.

**Plugins** - Fiscalizam novos plugins adicionados e então analisam se violam a segurança e/ou as orientações do software.

**Training** - A equipe de treinamento cria planos de aula para download e materiais relacionados para instrutores usarem em um ambiente de oficina ao vivo.

**Meta** - A equipe Meta é responsável pela manutenção e gerenciamento de websites do domínio wordpress.org. Erros e bugs devem ser apresentados em tickets criados no site.

**TV** - Aprovar e publicar todos os vídeos em wordpress.tv, bem como ajudar a WordCamps (conferência organizada pela comunidade Wordpress) na pós-produção e legendagem de vídeos publicados.

**Flow** - Esse time verifica o fluxo de todo o ecossistema Wordpress em todos os dispositivos disponíveis. Testam, documentam e relatam experiências de usuários.





##Evolução do sistema principais releases e novidades de cada uma.

<p align = "justify">b2 / Cafelog, mais comumente conhecido como B2 ou Cafelog foi o precursor do WordPress. Estima-se que esse gerenciador de conteúdos foi instalado em mais de 2 mil blogs. Ele foi escrito em PHP para uso com o MySQL por Michel Valdrighi, que agora é um desenvolvedor contribuindo para WordPress. O Wordpress apareceu pela primeira vez em 2003 como um esforço conjunto entre Matt Mullenweg e Mike Little para criar um fork do b2. Foi o amigo de  Mullenweg, Christine Selleck Tremoulet, quem sugeriu o nome WordPress</p>
<p align = "justify">Desde a versão 1.0 todas as versões do Wordpress tem o codinome de um artista de jazz e a seguir são relatadas as principais releases. O Wordpress possui uma comunidade mundial de desenvolvedores e usuários que juntos fazem com que a ferramenta evolua continuamente. </p>


>**Versão** - 1.0
**Codinome** - Davis
**Data de Lançamento** - 03 de janeiro de 2004
**Descrição** - Possibilidade de criar URL amigável. Foi criado o arquivo rápido de configuração wp-config.php. O administrador pode moderar, configurar e aprovar os comentários antes se serem publicados no blog. Foi adicionado suporte a XFN e assinaturas atom.

>**Versão** - 1.2
**Codinome** - Mingus
**Data de Lançamento** - 22 de maio de 2004
**Descrição** - Introdução ao suporte de plugins (até hoje é usado a mesma estrutura)

>**Versão** - 1.5
**Codinome** - Strayhorn
**Data de Lançamento** - 17 de fevereiro de 2005
**Descrição** - Possibilidade de criar páginas estáticas e suporte temas/design com um tema padrão incluído.


>**Versão** - 1.52.0
**Codinome** - Duke
**Data de Lançamento** - 31 de dezembro de 2005
**Descrição** - Nesta versão veio o editor WYSIWYG, melhorias nas ferramentas de administração, o upload de imagens, melhora na velocidade do sistema, mudanças na forma de importar informações, e uma completa revisão do BackEnd. No WordPress 2.0 também veio com uma grande variedade de informações para os desenvolvedores de plugins.

>**Versão** - 2.1
**Codinome** - Ella
**Data de Lançamento** - 22 de janeiro de 2007
**Descrição** - Correções de segurança, re-design da interface, melhorando o painel de edição com a auto correção e o auto-save, e uma melhora nas opções de administração.

>**Versão** - 2.2
**Codinome** - Getz
**Data de Lançamento** - 16 de maio de 2007
**Descrição** - Na versão 2.2 veio o tão esperado suporte para widgets em temas, e uma mudança no feed Atom, e uma substancial melhora de velocidade.

>**Versão** - 2.3
**Codinome** - Dexter
**Data de Lançamento** - 24 de setembro de 2007
**Descrição** - Adição de suporte nativo a tags, um novo sistema de categorias e uma melhora das notificações de atualizações. Nesta versão também foi incluído o suporte completo ao Atom 1.0, junto com o protocolo de publicação e incluiu algumas correções de segurança, já muito necessárias.

>**Versão** - 2.5
**Codinome** - Brecker
**Data de Lançamento** - 29 de março de 2008
**Descrição** - Novamente um completo re-design da adminstração e o site do WordPress também ganhou uma completa modificação para acompanhar o estilo.

>**Versão** - 2.6
**Codinome** - Tyner
**Data de Lançamento** - 15 de junho de 2008
**Descrição** - Tyner trouxe controle de versão dos conteúdos publicados e tornou o Wordpress um gerenciador ainda mais poderoso.

>**Versão** - 2.7
**Codinome** - Coltrane
**Data de Lançamento** - 11 de dezembro de 2008
**Descrição** - Novo re-design da administração e atualização automática de plugins pela administração (back-end).

>**Versão** - 2.8
**Codinome** - Baker
**Data de Lançamento** - 10 de junho de 2009
**Descrição** - Baker trouxe melhoras na velocidade e a instalação de temas direto do painel de administração (back-end). 

>**Versão** - 2.9
**Codinome** - Carmen
**Data de Lançamento** - 19 de dezembro de 2009
**Descrição** - Carmen trouxe uma estrutura de lixeira, um editor de imagens , atualização em massa de plugins.

>**Versão** - 3.0
**Codinome** - Thelonious
**Data de Lançamento** - 17 de junho de 2010
**Descrição** - Thelonius trouxe um novo tema padrão chamado "Twenty Ten". A versão marca a fusão do Wordpress com o Wordpress MU, permitindo a existência de vários blogs em uma única instalação. Nesta versão, também foram corrigidos mais de 1200 bugs.

>**Versão** - 3.1
**Codinome** - Reinhardt
**Data de Lançamento** - 23 de fevereiro de 2011
**Descrição** - Reinhardt teve como novidade mais notória a adição da Admin Bar, a qual aparece em todas as páginas do blog quando o administrador está conectado, além de maior facilidade de acesso a funções críticas.

>**Versão** - 3.2
**Codinome** - Gershwin
**Data de Lançamento** - 4 de julho de 2011
**Descrição** - Gershwin teve como principal objectivo tornar o WordPress mais rápido e leve.

>**Versão** - 3.3
**Codinome** - Sonny
**Data de Lançamento** - 12 de dezembro de 2011
**Descrição** - Essa release objetivou tornar o WordPress mais amigável para principiantes e também lançou-se um importador especial para Tumblr.

>**Versão** - 3.4
**Codinome** -  Green
**Data de Lançamento** - 14 de junho de 2012
**Descrição** - Green pretende facilitar a personalização de temas e cabeçalhos, de embeds do Twitter e das legendas de imagens.

>**Versão** - 3.5
**Codinome** - Elvin
**Data de Lançamento** - 11 de dezembro de 2012
**Descrição** - Suporte para Tela retina, seletor de cores mais intuitivo, novo tema: Twenty Twelve

>**Versão** - 3.6
**Codinome** - Oscar
**Data de Lançamento** - 01 de agosto de 2013
**Descrição** - Um novo tema, Twenty Thirteen, preparado para apresentar os conteúdos de forma rica e com muitas cores. O editor de Menus está mais simples de entender e de usar. 

>**Versão** - 3.7
**Codinome** - Basie
**Data de Lançamento** - 24 de outubro de 2013
**Descrição** - Foram adicionadas atualizações automáticas para a manutenção e atualizações de segurança. Um melhor suporte global para traduções com a ajuda da comunidade mundial.

>**Versão** - 3.8
**Codinome** - Parker
**Data de Lançamento** - 12 de dezembro de 2013
**Descrição** - Novo visual para todo o painel de administração que é responsivo e se adapta a qualquer resolução de tela. A busca por temas ficou ainda mais interativa com o usuário e para simbolizar o novo visual, o tema Twenty Fourteen foi adicionado ao padrão de instalação do WordPress.

>**Versão** - 3.9
**Codinome** - Smith
**Data de Lançamento** - 16 de abril de 2014
**Descrição** - Pré-visualização de widgets e novo instalador de  temas. Refinamentos de interface do usuário quando se trabalha com mídia no editor. Também trouxe de volta algumas das configurações avançadas de visualização das imagens e para os desenvolvedores de tema, foi adicionado suporte HTML5. 

>**Versão** - 4.0
**Codinome** - Benny
**Data de Lançamento** - 04 de setembro de 2014
**Descrição** - É possível explorar os uploads em uma visualização lado a lado. Uma nova tela de detalhes, torna a visualização e edição de qualquer quantidade de mídia na sequência. Uma URL do YouTube se transforma em um vídeo incorporado. Melhorias no editor de texto. Existem mais de 30.000 plugins livres e abertos no repositório oficial de plugins do WordPress e a versão 4.0 deixa mais fácil a busca por eles, com novas métricas, pesquisa melhorada, e uma experiência de navegação mais visual, exibindo o ícone do plugin. Na instalação, agora é possível escolher o idioma, e em seguida ocorre o download dos arquivos de tradução. A variável wp_lang que definia a linguagem  foi descontinuada.

>**Versão** - 4.1
**Codinome** - Dinah
**Data de Lançamento** - 18 de dezembro de 2014
**Descrição** - Novo tema padrão: Twenty Fifteen. Quando se começa a digitar no editor, todas as distrações como barra lateral e botões desaparecem e retornam quando necessário. Tradução para 44 idiomas. Incorporado a função de inserir vídeos do Vine colando apenas a sua URL no editor. O instalador de plugins passa a sugerir plugins para o usuário.

>**Versão** - 4.2
**Codinome** - Powell
**Data de Lançamento** - 23 de abril de 2015
**Descrição** - Adicionado suporte a vários novos caracteres, incluindo caracteres nativos chineses, japoneses e coreanos, símbolos musicais e matemáticos, e hieróglifos. Melhoramento dos recursos “Personalizar” e “Publique isso”. Suporte a incorporação dos sites Tumblr e Kickstarter. Atualização disponível de Plugin agora é feita de forma silenciosa, não mais recarregando a página.

>**Versão** - 4.3
**Codinome** - Billie
**Data de Lançamento** - 18 de agosto de 2015
**Descrição** - Melhorias na formatação do conteúdo e personalização do site. Foram adicionados atalhos no editor de texto WYSIWYG. Na segurança, ao adicionar novos usuários ao site ou quando editar um perfil, o WordPress automaticamente gerará uma senha segura. Por padrão, agora as páginas não estarão habilitadas a permitir comentários.

>**Versão** - 4.4
**Codinome** - Clifford
**Data de Lançamento** - 08 de dezembro de 2015
**Descrição** - Foi adicionado o novo tema padrão, chamado de Twenty Sixteen. Foi criado um novo modo de trabalhar com imagens responsivas utilizando o atributo srcset na tag img, com HTML5. Com isso, o servidor pode escolher qual imagem carregar. Agora é possível anexar posts de outros sites WordPress, apenas colando a url do post no editor. A REST API foi incluída ao core do sistema e os termos passam a poder ter metadados de forma mais simples. Foi adicionado a classe WP_Network que faz surgir a function_network_option que facilita o uso de diversas redes de sites. O “Personalizar" foi melhorado.

>**Versão** - 4.5
**Codinome** - Coleman
**Data de Lançamento** - 12 de abril de 2016
**Descrição** - Melhorias na interface e editor de texto. Pré-visualização de celular, tablet e visão de desktop diretamente no “Personalizar”. Temas agora suportam logotipos. Carregamento mais rápido de imagens. Nova função wp_add_inline_script() permite a adição de scripts extras.

>**Versão** - 4.6
**Codinome** - Pepper
**Data de Lançamento** - 16 de agosto de 2016
**Descrição** - Agora tanto os plugins e temas podem ser instalados, atualizados ou excluídos sem recarregar a página. O painel do WordPress agora aproveita as fontes que o usuário já tem, tornando o carregamento mais rápido. O editor verifica automaticamente erros acidentais nos links criados pelo usuário e também salva no navegador tudo que é digitado, permitindo recuperação a qualquer momento.



##Principais frameworks, ferramentas e linguagens usadas no desenvolvimento.


<p align = "justify">As principais linguagens utilizadas são PHP, Javascript, HTML e CSS.</p>

<p align = "justify">Para controle de versão são utilizadas  duas ferramentas SVN e o Git.</p>
<p align = "justify">Para desenvolvimento local os desenvolvedores utilizam os seguintes frameworks: </p>

- MAMP: MAMP é acrônimo para a combinação Mac, Apache, MySql e PHP e se refere ao conjunto de programas comumente usados para desenvolver sites dinâmicos sobre sistemas operacionais Apple Macintosh, MAC OS X.
- WAMP: WAMP é acrônimo para a combinação Windows Apache MySQL PHP. WAMP é o termo usado para denominar os softwares que efetuam a instalação automática de vários softwares de forma que facilitem e agilizem a instalação dos mesmos.
- Vagrant: é um programa de código aberto para construir e manter ambientes de desenvolvimento virtuais.
- XAMPP: XAMPP é um servidor independente de plataforma, software livre, que consiste principalmente na base de dados MySQL, o qual foi substituído pelo MariaDB, o servidor web Apache e os interpretadores para linguagens de script: PHP e Perl. O nome provem da abreviação de X (para qualquer dos diferentes sistemas operativos), Apache, MariaDB, PHP, Perl. Atualmente XAMPP está disponível para Microsoft Windows, GNU/Linux, Solaris, e MacOS X. 

<p align = "justify">
Para automatizar as tarefas como minificação e concatenação de arquivos, deploy, dentre outras que, na maioria das vezes são tarefas em aplicações Javascript é utilizado o GRUNT, uma aplicação de linha de comando que basicamente escreve as tarefas em JavaScript utilizando Node.Js. Para utilizar o Grunt em um projeto, é necessário que exista dois arquivos: o Gruntfile.js e o package.json. Eles devem estar na raiz (diretório principal, root) do projeto.</p>

<p align = "justify">Caso o projeto já utilize o Grunt (isto é, exista os arquivos Gruntfile.js e package.json), para rodar é bem simples. Segue um exemplo de criação do Grunt em um sistema Linux:</p>

// Acesse a pasta do projeto
cd project-folder
 
// Instale as dependências
sudo npm install
 
// Rode o Grunt
grunt
<p align = "justify">
Para iniciar um projeto com o Grunt existem algumas opções: Pode-se optar pelo grunt-init que gera o scaffolding para alguns modelos de aplicações, como:</p>

 jquery: cria um projeto para um plugin jQuery
 commonjs: cria um projeto para um módulo commonjs
 Gruntfile: cria um arquivo Gruntfile.js básico
 gruntplugin: cria um plugin grunt
 node: cria um módulo Node.JS
Você também pode baixar outros templates, além dos oficiais. Para criar um projeto a partir de um dos template como os descritos acima basta usar o comando:

grunt-init
Ou então iniciar o Grunt sem um template, criando os arquivos manualmente.
Antes, é necessário saber para que serve esses dois arquivos.


- Gruntfile.js: Esse é um arquivo JavaScript que são definidas e configuradas as tarefas a serem executadas pelo Grunt.
- package.json: Esse arquivo é usado pelo npm para armazenar as informações da aplicação, dados como nome, autor, repositório e dependências, e é por isso que o grunt precisa dele, para instalar as dependências e os plugins do grunt que seu projeto irá utilizar. Ao rodar o comando npm install, ele procura as dependências descritas nessa arquivo, e instala na pasta do projeto as mesmas com suas respectivas versões.

<p align = "justify">Para realizar os testes nos códigos PHP é utilizando o framework de teste PHPUnIt. Ele provê um ecossistema para a execução de testes unitários de forma automatizada. O PHPUnlt segue os princípios do TDD (Test driven development), ou desenvolvimento de software orientado a testes. Esse desenvolvimento se baseia em 3 passos, vermelho-verde-refatora:</p>

<p align = "justify">O vermelho é a escrita do primeiro teste antes mesmo da lógica existir. </p>
<p align = "justify">O verde é o ponto em que a lógica para que o teste previamente criado passe. Esta lógica deve ser desenvolvida da forma mais simples possível eliminando complexidades desnecessárias fazendo com que a evolução do código ocorra de forma segura.</p>
<p align = "justify">O refatora é a melhoria do código. Neste ponto são removidas duplicações, múltiplas responsabilidades e o código fica cada vez mais próximo de sua versão final.</p>
<p align = "justify">As informações referentes a como instalar e utilizar a ferramenta podem ser encontradas na página oficial do Wordpress.</p>
 
<p align = "justify">O QUnit é um framework utilizado para realizar testes em códigos Javascript, principalmente o projeto jQuery e plugins. Esta ferramenta é realmente simples de usar. Basicamente é preciso apenas incluir os arquivos qunit.js e qunit.css e ter uma estrutura básica de HTML para que a biblioteca funcione corretamente. </p>
<p align = "justify">As informações sobre a instalação e utilização do mesmo também podem ser encontradas no site oficial do Wordpress(https://wordpress.com).</p>





##Arquitetura do Wordpress 

<p align = "justify">Por ser desenvolvido de forma colaborativa por pessoas de todo mundo, uma boa organização de modularização é essencial para o sucesso do Wordpress.</p>
<p align = "justify">É importante destacar que a equipe do Wordpress preza por uma organização e entendimento do código por todos. </p>
<p align = "justify">As orientações de como devem ser registradas as alterações no codigo podem ser encpntradas na página oficial da ferramenta (https://wordpress.com).  O Wordpress possui uma comunidade mundial de desenvolvedores e usuários que juntos fazem com que a ferramenta evolua continuamente. </p>


<p align = "justify">O repositório oficial do Wordpress pode ser encontrado em [git://develop.git.wordpress.org][1]. Este repositório é responsável por armazenar todo o trabalho até então desenvolvido. O Wordpress possui uma comunidade mundial de desenvolvedores e usuários que juntos fazem com que a ferramenta evolua continuamente. </p>


O master branch contém a versão alpha da próxima release.




<p align = "justify">Sugestões de melhorias e soluções de falhas são lançadas como patches. O patch trata de um arquivo de texto que descreve a mudança no código identificando as mudanças que foram realizadas. O Wordpress possui uma comunidade mundial de desenvolvedores e usuários que juntos fazem com que a ferramenta evolua continuamente. </p>



![fluxo](https://cloud.githubusercontent.com/assets/22482177/22301063/5779a47a-e308-11e6-8bef-e86e71a16983.png)
>Exemplo de um fluxo seguido para a criação de um patch


###SRC
No git oficial do Wordpress a base de dados principal chamada core fica no diretório src, outros arquivos como index.php, wp-load.php também estão contidos neste diretório.
#### <i class="icon-folder-open"></i>wp-admin
#### <i class="icon-folder-open"></i>wp-content
#### <i class="icon-folder-open"></i>wp-includes
#### <i class="icon-file"></i>index.php
#### <i class="icon-file"></i>wp-activate.php
#### <i class="icon-file"></i>wp-blog-header.php
#### <i class="icon-file"></i>wp-comments-post.php
#### <i class="icon-file"></i>   wp-cron.php 

> Amostra do diretorio SRC



<p align = "justify">Os três diretórios apresentados e os arquivos listados compõe o diretório raíz de uma instalação padrão do Wordpress. O diretório "wp-admin" contém os arquivos e funções responsáveis pelo dashboard de administração do Wordpress e apenas usuários autenticados no sistema possuem acesso a este diretório. Já o diretório “wp-content” contém os arquivos de upload do usuário e é subdividido em três outros diretório: “themes”, “plugins” e “uploads”. Por fim, “wp-includes” contém todos os arquivos PHP's e classes que são necessárias para as operações do "core" do Wordpress. O Wordpress possui uma comunidade mundial de desenvolvedores e usuários que juntos fazem com que a ferramenta evolua continuamente. </p>





<p align = "justify">A principal tarefa do Wordpress é gerar páginas HTML dinamicamente. Podemos dizer que, para isso, ele usa duas entidades. A primeira delas é o código PHP que é o "núcleo" do Wordpress e a segunda é o banco de dados que equivale a "memória" do Wordpress. Toda informação gerada pelo sistema é armazenada no banco de dados. O Wordpress possui uma comunidade mundial de desenvolvedores e usuários que juntos fazem com que a ferramenta evolua continuamente. </p>


<p align = "justify">Quando um site Wordpress é visitado ou um post é publicado ou um comentário submetido ou uma busca é feita no sistema, por exemplo, acontece um processo similar que é uma "page request" ou requisição de página e o Wordpress é encarregado das operações internas até a conclusão da requisição. A seguir, apresentamos uma generalização do que ocorre nesse processo.O Wordpress possui uma comunidade mundial de desenvolvedores e usuários que juntos fazem com que a ferramenta evolua continuamente. </p>

![requisicao](https://cloud.githubusercontent.com/assets/22482177/22301686/a26e9402-e30a-11e6-8310-c68cbec136f1.png)

>- Navegador do usuário requisita uma página
- Wordpress chama a página PHP requisitada a partir da página index.php
- O “núcleo”, então, comunica com a “memória” e recupera os dados necessários (posts/páginas/comentários/etc.)
- A seguir, são combinados os dados recuperados com os dados dos plugins ativos, mais os dados dos temas e  um código HTML é gerado em tempo de execução
- Então, o código gerado é enviado ao web browser que fez a requisição para que ele exiba o conteúdo para o usuário 


<p align = "justify">O banco de dados utilizado pelo Wordpress armazena apenas informações textuais. Dados não-textuais como imagens, vídeos, documentos, etc, são armazenados no diretório “wp-content”. O Wordpress possui uma comunidade mundial de desenvolvedores e usuários que juntos fazem com que a ferramenta evolua continuamente. </p>




<p align = "justify">Um dos fatores que contribuem para o sucesso do Wordpress são os seus mais variados temas que podem ser utilizados pelo o usuario, o usuario tambem pode estar alterando estes temas tornando assim a sua experiência muito mais agradável e personalizada. Para permitir que a utilização dos temas seja feita de forma satisfatória é essencial uma boa organização e modularização dos códigos pertinentes a esta função. </p>
###WP-ADMIN
#### <i class="icon-folder-open"></i>css
#### <i class="icon-folder-open"></i>images
#### <i class="icon-folder-open"></i>includes
#### <i class="icon-folder-open"></i>js

#### <i class="icon-folder-open"></i>maint
#### <i class="icon-folder-open"></i>network
#### <i class="icon-folder-open"></i>user
#### <i class="icon-file"></i>about.php
#### <i class="icon-file"></i>admin-ajax.php
> Amostra wp-admin

Os diretorios css e js são responsáveis por estar armazenando os padrões de design a serem utilizados. 

<p align = "justify">Esse diretório contém diversos arquivos do dashboard do WordPress. Vale lembrar que funções como: escrever posts, moderar comentários e instalar plugins e temas são feitos via dashboard. O acesso a essa área é restrito aos usuários cadastrados e as funcionalidades estão limitadas aos diferentes tipos de usuários: Administrator, Contributor e Subscriber.</p>
<p align = "justify">O link para acesso ao dashboard é: http://wpexplorer.com/wp-admin. O Wordpress possui uma comunidade mundial de desenvolvedores e usuários que juntos fazem com que a ferramenta evolua continuamente. </p>



###WP-CONTENT

WP-CONTENT   é dividido em duas pastas principais “plugins” e “themes”. 
#### <i class="icon-folder-open"></i>plugins
#### <i class="icon-folder-open"></i>themes

#### <i class="icon-file"></i>index.php
> Amostra WP-CONTENT 

 <p align = "justify">A pasta mais importante é a pasta Themes, lá encontramos os designs desenvolvidos nas mais diferentes versões do Wordpress. Os designs são templates já definidos em temas que são disponíveis para serem utilizados pelo usuário. São desenvolvidos utilizando CSS e PHP. O CSS aqui é explorado com profundidade na busca da construção de um tema que seja interessante e que atenda as expectativas do usuario. Cada versão de temas é salva em um diretório específico. Assim em cada diretório temos uma subdivisão de acordo com o foco principal de um interface, os subdiretórios são denominados de colors, images, inc, js, languages. Colors contém códigos em CSS que definem as propriedades das cores a serem utilizadas no tema. O diretório imagens armazena imagens em formato .png, estas são as imagens que irão caracterizar  o tema que em questão. Outras imagens com o cabeçalho são salvas em formato .jpeg, estas são imagens que irão ilustrar a página com intuito de embelezá-la e a deixar mais agradavel pára o usuario.  O Wordpress possui uma comunidade mundial de desenvolvedores e usuários que juntos fazem com que a ferramenta evolua continuamente. </p>


<p align = "justify">Códigos de widgets que são elaborados maioritaO Wordpress possui uma comunidade mundial de desenvolvedores e usuários que juntos fazem com que a ferramenta evolua continuamente. </p>


<p align = "justify">A estrutura é destinada a manter tudo que for relevante para a aparência dos temas de forma organizada. Em algumas versões é definido um diretório para armazenar o código CSS separado. </p>
<p align = "justify">Com esta divisão, temos uma clara intenção da equipe do Wordpress de manter de forma organizada tudo que se destina a formalizar com será exibido o layout do usuario.  Contribuidores de todo o mundo podem facilmente entender como está sendo organizada a parte de temas, bem como sugerir alterações de forma precisa e sem colocar em risco o funcionamento do código. O Wordpress possui uma comunidade mundial de desenvolvedores e usuários que juntos fazem com que a ferramenta evolua continuamente. </p>






###WP-INCLUDES
Essa pasta contém os principais PHPs e classes que sao necessárias para as operações da parte central do código do Wordpress

#### <i class="icon-folder-open"></i>css
#### <i class="icon-folder-open"></i>images
#### <i class="icon-folder-open"></i>js
#### <i class="icon-folder-open"></i>pomo
#### <i class="icon-folder-open"></i>SimplePie
#### <i class="icon-folder-open"></i>Text
#### <i class="icon-folder-open"></i>theme-compat
#### <i class="icon-file"></i>admin-bar.php
#### <i class="icon-file"></i>atomlib.php

>Amostra do wp-includes

##Diagrama do banco de dados 

<p align = "justify">O diagrama abaixo fornece uma visão geral do banco de dados WordPress e as relações entre as tabelas criadas durante a instalação padrão do WordPress. A Visão Geral da Tabela abaixo inclui detalhes adicionais nas tabelas e colunas.</p>

![diagramaDB](https://cloud.githubusercontent.com/assets/22482177/22305817/b449a7dc-e31b-11e6-9e18-beb66c44ce0f.png)

##Hierarquia dos Arquivos de Template


<p align = "justify">WordPress usa a string da query para decidir qual template ou conjunto de templates deve ser usado para exibir a página. A string é a informação que está contida no link para cada parte do seu site. Ela vem após o ponto de interrogação inicial e pode conter um número de parâmetros separados por &.</p>

<p align = "justify">Simplificando, o WordPress pesquisa através da hierarquia de templates até encontrar um arquivo de template correspondente. Para determinar qual arquivo de modelo usar, o WordPress:</p>

- Combina cada string de consulta com um tipo de consulta para decidir qual página está sendo solicitada (por exemplo, uma página de pesquisa, uma página de categoria, etc.);
- Seleciona o template na ordem determinada pela hierarquia;
- Procura arquivos de template com nomes específicos no diretório do tema atual e usa o primeiro arquivo de template correspondente conforme especificado pela hierarquia.
- Com exceção do arquivo de template básico (index.php), você pode escolher se deseja implementar um template específico ou não.

<p align = "justify">Se o WordPress não conseguir encontrar um template com um nome correspondente, ele saltará para o próximo arquivo na hierarquia. Se o WordPress não conseguir encontrar nenhum arquivo de template correspondente, o arquivo index.php do tema será usado.</p>

<p align = "justify">O diagrama a seguir mostra quais arquivos de template são chamados para gerar uma página do WordPress baseado na hierarquia de arquivos.</p>

![hieraquia-de-template](https://cloud.githubusercontent.com/assets/22482177/22299498/11dda3f8-e303-11e6-93fa-d117c0e96481.png)


##Padrões de código:
 
 <p align = "justify">Com o propósito de criar uma base para colaboração e revisão dos vários aspectos do projeto de código aberto do WordPress, tanto para o core, templates e plugins, foi definido uma série de padrões e boas práticas para o desenvolvimento.O Wordpress possui uma comunidade mundial de desenvolvedores e usuários que juntos fazem com que a ferramenta evolua continuamente. </p>	<p align = "justify">Com o propósito de criar uma base para colaboração e revisão dos vários aspectos do projeto de código aberto do WordPress, tanto para o core, templates e plugins, foi definido uma série de padrões e boas práticas para o desenvolvimento.O Wordpress possui uma comunidade mundial de desenvolvedores e usuários que juntos fazem com que a ferramenta evolua continuamente. </p>
 
Existem padrões definidos para as linguagens: PHP, HTML, CSS e Javascript:
 
###PHP
####Identação:
<p align = "justify">A identação deve sempre refletir a estrutura lógica do código. Deve-se usar tabulações ao invés de espaços (com exceção de que se tenha um bloco de código que fica mais legível se alinhado). A regra geral é: tabulações devem ser usadas no começo da linha para identação enquanto espaços podem ser usados no meio das linhas para alinhamento.</p>

####elseif:
* Usar elseif ao invés de else if.

####Não usar atalhos para tags:
Sempre usar o nome completo nas tags
Correct:

<pre class="prettyprint">
<code class="lang-bsh">&lt?php ... ?>
&lt?php echo $var; ?></code></pre>
Incorrect:
<pre class="prettyprint">
<code class="lang-bsh">&lt? ... ?>
&lt?= $var ?></code></pre>

####Nomeclaturas:
* Usar letras em lowercase para variáveis, ações e nomes funções. Usar "_" como separador de palavras. 
* Não abreviar nomes desnecessáriamente
<pre class="prettyprint">
<code class="lang-bsh">function some_name( $some_variable ) { [...] }</code></pre>
* classes devem ter nomes iniciados com letras maiúsculas e separados por "_".
<pre class="prettyprint">
<code class="lang-bsh">class Walker_Category extends Walker { [...] }
class WP_HTTP { [...] }</code></pre>
* Constantes devem estar em uppercase e devem ser separadas por "_".
<pre class="prettyprint">
<code class="lang-bsh">define( 'DOING_AJAX', true );</code></pre>

###HTML
####Atributos e Tags:
* Precisam ser escritos em lowercase. 
* Como podem ser lidos por humanos ou máquinas existem dois padrões:

Para máquinas
<pre class="prettyprint">
<code class="lang-bsh">&ltmeta http-equiv="content-type" content="text/html; charset=utf-8" />
</code></pre>
Para humanos
<pre class="prettyprint">
<code class="lang-bsh">&lta href="http://example.com/" title="Description Here">Example.com&lt/a>
</code></pre>

####Identação:
Assim como PHP, a identação do HTML sempre precisa refletir a estrutura do código.

Correto
<pre class="prettyprint">
<code class="lang-bsh">&lt?php if ( ! have_posts() ) : ?>
   &ltdiv id="post-1" class="post">
      &lth1 class="entry-title">Not Found&lt/h1>
      &ltdiv class="entry-content">
         &ltp>Apologies, but no results were found.&lt/p>
         &lt?php get_search_form(); ?>
      &lt/div>
   &lt/div>
&lt?php endif; ?>

</code></pre> 

Incorreto
<pre class="prettyprint">
<code class="lang-bsh">      &lt?php if ( ! have_posts() ) : ?>
      &ltdiv id="post-0" class="post error404 not-found">
         &lth1 class="entry-title">Not Found&lt/h1>
         &ltdiv class="entry-content">
         &ltp>Apologies, but no results were found.&lt/p>
&lt?php get_search_form(); ?>
         &lt/div>
      &lt/div>
&lt?php endif; ?>
</code></pre>

###CSS
####Estrutura:

Correto:
<pre class="prettyprint"><code class="lang-bsh">&#x23;selector-1,
&#x23;selector-2,
&#x23;selector-3 {
   background: #fff;
   color: #000;
}</code></pre>

Incorreto:
<pre class="prettyprint"><code class="lang-bsh">&#x23;selector-1, &#x23;selector-2, &#x23;selector-3 {
   background: #fff;
   color: #000;
   }
 
&#x23;selector-1 { background: #fff; color: #000; 6 }</code></pre>
####Propriedades:
 
Correto:
 
<pre class="prettyprint"><code class="lang-bsh">&#x23;selector-1 {
   background: &#x23;fff;
   display: block;
   margin: 0;
   margin-left: 20px;
}</code></pre>
 
Incorreto:
<pre class="prettyprint"><code class="lang-bsh">&#x23;selector-1 {
   background:&#x23;FFFFFF;
   display: BLOCK;
   margin-left: 20PX;
   margin: 0;
}</code></pre>
 
####Valores:
 
Correto:
 
<pre class="prettyprint"><code class="lang-bsh">.class { /* Correct usage of quotes */
   background-image: url(images/bg.png);
   font-family: "Helvetica Neue", sans-serif;
   font-weight: 700;
}
 
.class { /* Correct usage of zero values */
   font-family: Georgia, serif;
   text-shadow: 0 -1px 0 rgba(0, 0, 0, 0.5),
                     0 1px 0 &#x23;fff;
}
</code></pre>
 
Incorreto:
<pre class="prettyprint"><code class="lang-bsh">.class { /* Avoid missing space and semicolon */
   background:#fff
}
 
.class { /* Avoid adding a unit on a zero value */
   margin: 0px 0px 20px 0px;
}
 
.class {
   font-family: Times New Roman, serif; /* Quote font names when required */
   font-weight: bold; /* Avoid named font weights */
}</code></pre>
 
 
###JavaScript

####Exemplo de bom espaçamento:
<pre class="prettyprint">
<code class="lang-bsh">var i;
 
if ( condicao) {
   facaAlgo( 'com uma string' );
} else if ( outraCondicao) {
   outraCoisa({
      chave: valor,
      outraChave: outroValor
   });
} else {
   algumaOutraCoisa( true );
}
 
// Diferente de jQuery, WordPress prefere espaço após o operador de negação !
// Isso também é feito nos padrões de PHP
while ( ! condicao) {
   iterando++;
}
 
for ( i = 0; i &lt 100; i++ ) {
   object[ array[ i ] ] = funcao( i );
   $( '.container' ).val( array[ i ] );
}
 
try {
   // expressões
} catch ( e ) {
   // expressões
}</code></pre>

####Arrays:
A criação de arrays em JavaScript deve ser feita com o construtor reduzido "[]" ao invés da notação new Array()

<pre class="prettyprint">
<code class="lang-bsh">var myArray = [];</code></pre>
Pode-se inicializar arrays durante a construção

<pre class="prettyprint">
<code class="lang-bsh">var myArray = [ 1, 'WordPress', 2, 'Blog' ];</code></pre>
Em JavaScript, arrays associativos são definidos como objetos.

####Objetos:
Criação dos objetos
<pre class="prettyprint">
<code class="lang-bsh">var meuObj= {};
//ou
var meuObj= new MétodoConstrutor();</code></pre>
Quanto as propriedades dos objetos:
<pre class="prettyprint">
<code class="lang-bsh">prop = object.nomeDaPropriedade;
prop = object[ variávelChave ];
prop = object['padrão'];
prop = object['chave-com-hiféns'];</code></pre>

####Iterações:
<pre class="prettyprint">
<code class="lang-bsh">var i;
// Bom e eficiente
var i, max;
 
// getItemCount() tem uma chamada apenas
for ( i = 0, max = getItemCount(); i &lt max; i++ ) {
   // faz algo
}
 
// Ruim e potencialmente ineficiente
// getItemCount() é chamado a cada iteração
for ( i = 0; i &lt getItemCount(); i++ ) {
   // faz algo
}</code></pre>

####JSHint:
<p align = "justify">JSHint é uma ferramenta de qualidade de código automatizada, escrita para capturar erros no código JavaScript. É utilizado no desenvolvimento do WordPress para verificar rapidamente se algum patch não introduziu nenhum erro de sintaxe ou de lógica no front-end.</p>


##Referências

- http://www.wpexplorer.com/wordpress-internal-function
- https://developer.wordpress.org/themes/basics/template-hierarchy/
- https://delftswa.github.io/chapters/joomla/
- https://www.optimizesmart.com/wordpress-ninja-15-minutes/
- https://tableless.com.br/grunt-voce-deveria-estar-usando/
- https://tableless.com.br/phpunit-como-iniciar-sem-dores/
- https://tableless.com.br/tdd-por-que-usar/
- https://d2mm.wordpress.com/2010/12/22/qunit-para-jquery/
- https://codex.wordpress.org/Database_Description
- git://develop.git.wordpress.org



