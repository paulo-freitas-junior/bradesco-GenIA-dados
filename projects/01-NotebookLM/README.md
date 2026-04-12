# Projeto 01 - Explorando o NotebookLM

<div align="center">
  <img src="/images/project01/notebooklm.jpg" width="100%" alt="NotebookLM">
  </div>

[![Status](https://img.shields.io/badge/status-concluído-blue)](https://github.com/paulo-freitas-junior/neo4j-bootcamp-2026/blob/main/README.md)

---
## Contexto e Objetivos

Projeto visa explorar os recursos oferecidos pelo NotebookLM gerando uma base de conhecimento focada no assunto sobre **Pesca Esportiva no Brasil.**

**O notebook se encontra neste [link](https://notebooklm.google.com/notebook/4488a404-9217-45b0-bff0-702841d96dec/preview)**

---
## Os objetivos desse Notebook abragem:

 - Explicar de forma clara e objetiva os contextos sobre a Pesca Esportiva, sua origem até os dias atuais;
 - Ser um guia completo de diversas modalidades de pesca;
 - Descrever as boas práticas aplicadas desde visão sustentável até manutenção de equipamentos;
 - Descrição dos equipamentos necessários para determinadas modalidades de pesca e para espécies específicas de peixes;
 - Utilização de equipamentos de proteção adequados;
 - Regulamentação da Pesca no Brasil, diretrizes, Leis, Licenças e Calendários específicos por temporada
 - Locais de pesca bem como espécies de peixes mais procurados em diferentes modalidades;
 - Apresentação didática de técnicas tanto para iniciantes como profissionais na modalidade de Pesca Esportiva;

---

## Estrutura visual do **mapa mental** gerado pelo NotebookLM
<div align="center">
  <img src="/images/project01/Project01_NotebookLM Mind Map.png" width="100%" alt="Mapa Mental">
  </div>

---
## Curadoria de Fontes:

As fontes escolhidas para elaboração desse notebook foram desde textos, artigos, arquivos PDF disponibilizados on-line até vídeos no Youtube de canais que abordam o tema som seriedade e responsabilidade.
    Todos os link´s disponibiliados podem ser encontrados [neste arquivo](/projects/01-NotebookLM/links.txt).

---
## Resumos estruturados por assuntos:

### **Conceitos e Fundamentos**
*   **Definição da Pesca Esportiva:** Atividade de lazer e desporto que proíbe expressamente a comercialização do pescado.
*   **Diferença entre Pesca Amadora e Predatória:** O foco na preservação e no respeito aos tamanhos mínimos e períodos de defeso.
*   **Evolução Cultural da Pesca:** A transição de uma atividade puramente extrativista para um setor focado na conservação e no valor do peixe vivo.

### **Sustentabilidade e Conservação**
*   **O Pilar do "Pesque e Solte":** Prática fundamental para garantir a manutenção dos estoques pesqueiros para futuras gerações.
*   **Taxas de Sobrevivência Pós-Soltura:** Estudos indicam que peixes devolvidos corretamente têm mais de 90% de chance de sobrevivência.
*   **O Valor do Peixe Vivo:** Como a pesca esportiva gera mais retorno econômico através do turismo do que o abate do animal.

### **Equipamentos e Ferramentas**
*   **Escolha da Tralha Ideal:** A importância de usar varas, linhas e carretilhas compatíveis com o porte do peixe para evitar exaustão extrema.
*   **Anzóis e a Segurança do Peixe:** Vantagens do anzol circular e da remoção das farpas para minimizar lesões internas.
*   **Acessórios de Contenção:** Uso de alicates tipo *boga-grip* e puçás de silicone para proteger o muco e a boca do peixe.

### **Técnicas de Manejo e Manuseio**
*   **A Regra dos Dois Pontos de Apoio:** A necessidade de segurar o peixe horizontalmente para não danificar seus órgãos internos.
*   **Revitalização e Soltura Correta:** Técnicas para oxigenar as brânquias contra a correnteza antes de liberar o animal.
*   **Minimização do Tempo Fora d'Água:** O limite crítico de 30 segundos para fotos e manuseio a fim de evitar o estresse fisiológico.

### **Legislação e Regulamentação**
*   **Licenciamento Obrigatório:** A necessidade da Licença de Pesca Amadora emitida pelo IBAMA/MPA para praticar a atividade legalmente.
*   **Monitoramento da Atividade:** A obrigatoriedade do preenchimento de formulários de captura para auxiliar na gestão pesqueira nacional.
*   **Normas para Competições:** Regras específicas para a organização de torneios que promovam a educação ambiental e o turismo.

### **Ictiofauna e Espécies Alvo**
*   **Gigantes de Couro:** Estratégias e equipamentos pesados para a captura de Pirararas e Piraíbas.
*   **Peixes Redondos em Pesqueiros:** Técnicas específicas para Tambacus e Tambaquis usando sistemas de superfície ou fundo.
*   **Protagonistas das Águas Brasileiras:** O comportamento agressivo e as técnicas de arremesso para Tucunarés, Dourados e Robalos.

### **Impacto Socioeconômico**
*   **Motor do Turismo Regional:** Como os torneios de pesca injetam milhões de reais em comunidades ribeirinhas.
*   **Geração de Emprego e Renda:** A importância dos guias de pesca e da cadeia de serviços vinculada ao setor.
*   **Desenvolvimento Sustentável:** O papel da pesca esportiva como alternativa econômica à pesca comercial predatória.

---
## Engenharia de Prompts e "Cicatrizes":

Estes prompts visão buscar informações baseando-se nas fontes inseridas. A ideia de criação dos mesmos foi focar em tópicos específicos abordados em **negrito**. O foco não é apenas apresentar o que é a Pesca Esportiva e como iniciar na mesma, mas mostrar os impactos positivos que a modalidade trás para vários setores.

Os prompts e suas respectivas respostas podem ser visualidados no arquivo [prompts.md](/projects/01-NotebookLM/prompts.md).

### Prompts utilizados no experimento do notebook:

1.  **Fundamentos e Ética:** 
Prompt: "Explique a diferença conceitual entre **pesca amadora e pesca esportiva** de acordo com a legislação brasileira (Lei 11.959/2009) e discuta como a filosofia do **pesque e solte** transforma a atividade de um simples extrativismo em uma ferramenta de conservação ambiental."

2.  **Equipamento e Sobrevivência:** 
Prompt: "Como a escolha correta da **tralha de pesca** (vara, linha e anzol) influencia diretamente o 'tempo de briga' e, consequentemente, as taxas de sobrevivência do peixe após a soltura? Relacione o uso de **anzóis sem farpa** e equipamentos adequados ao acúmulo de ácido lático no animal."

3.  **Legislação e Monitoramento:** 
Prompt: "Quais são as principais exigências da **Portaria SAP/MAPA nº 616/2022** para o pescador amador e como o preenchimento do **Formulário de Monitoramento** contribui para a gestão sustentável dos estoques pesqueiros no Brasil?"

4.  **Manejo e Biologia:** 
Prompt: "O que é o **barotrauma** em espécies de profundidade e quais são os dispositivos e técnicas recomendados (como o **BFDD**) para garantir que o peixe retorne à flutuabilidade neutra sem procedimentos invasivos perigosos?"

5.  **Impacto Socioeconômico e Comunidades:** 
Prompt: "De que maneira o **Turismo de Pesca** pode servir como alternativa de renda para comunidades ribeirinhas e pescadores artesanais, e qual o papel do guia de pesca na educação ambiental do turista?"

6.  **Sustentabilidade em Áreas Protegidas:** 
Prompt: "Como a pesca esportiva é regulamentada em **Unidades de Conservação e Terras Indígenas**? Discuta a importância do plano de manejo e do rito de consulta às comunidades tradicionais para evitar conflitos territoriais."

7.  **Desafios das Espécies Invasoras:** 
Prompt: "Explique os riscos ambientais da introdução de **espécies exóticas invasoras** (como o tucunaré fora de sua bacia original) pela pesca amadora e discuta o dilema ético do pescador esportivo ao capturar esses exemplares."

8.  **Boas Práticas de Manuseio:** 
Prompt: "Quais são os **'3 Princípios' da Keep Fish Wet** e por que ações simples, como manter o peixe na **horizontal**, molhar as mãos para preservar o muco e minimizar o tempo fora d'água, são vitais para a saúde pós-soltura?"

9.  **Políticas Públicas e Futuro:** 
Prompt: "Analise os quatro programas essenciais do **Plano Nacional para o Desenvolvimento Sustentável da Pesca Amadora e Esportiva (PNPA) 2024-2034**. Como esses eixos projetam o crescimento do setor para a próxima década?"

10. **Ciência e Pesquisa:** 
Prompt: "Discuta a importância da **ciência cidadã** na coleta de dados biológicos. Como o engajamento de pescadores e guias pode auxiliar pesquisadores a entender o comportamento de espécies ameaçadas, como o **Mero**?"

---
### Glossário de Pesca Esportiva

*   **Anzol Circular (Circle Hook):** Modelo de anzol desenvolvido para fisgar o peixe no "canivete" (canto da boca), evitando que o animal engula a isca e sofra lesões internas graves.
*   **Arremesso (Casting):** Ação fundamental de lançar a isca na água utilizando a vara e o molinete/carretilha. O termo também se refere à capacidade de peso (gramatura) que uma vara suporta lançar sem danos.
*   **Baitcasting:** Modalidade que utiliza carretilhas de tambor rotativo, permitindo arremessos de alta precisão em estruturas como troncos e galhadas.
*   **Barotrauma:** Lesão causada pela rápida expansão dos gases na bexiga natatória quando o peixe é trazido rapidamente de grandes profundidades para a superfície, podendo causar a eversão de órgãos internos.
*   **Bexiga Natatória (Vesícula Gasosa):** Órgão interno que controla a flutuabilidade do peixe através do volume de gases.
*   **Blank:** O corpo principal ou "caniço" da vara de pesca, responsável por sua resistência e ação.
*   **Brânquias (Guelras):** Órgãos respiratórios e de osmorregulação dos peixes, extremamente sensíveis e que nunca devem ser tocados pelo pescador.
*   **Briga:** O período de luta entre o pescador e o peixe após a fisgada. Recomenda-se que seja breve para evitar a exaustão extrema e o acúmulo de ácido lático no animal.
*   **Carretilha:** Equipamento de armazenamento de linha com carretel rotativo, indicado para pescadores mais experientes por oferecer maior precisão e controle.
*   **Defeso:** Período de restrição ou proibição da pesca para proteger a reprodução das espécies e garantir a manutenção dos estoques.
*   **Encharutar:** Termo usado quando o peixe abocanha a isca artificial de forma profunda, dificultando a remoção do anzol.
*   **Fly Fishing (Pesca com Mosca):** Técnica técnica e estética que utiliza varas longas e linhas pesadas para arremessar iscas extremamente leves (moscas) feitas artesanalmente.
*   **Isca Artificial:** Artefatos feitos de plástico, madeira ou metal que simulam o movimento de presas vivas para atrair predadores.
*   **Isca Natural:** Qualquer atrativo de origem vegetal ou animal, vivo ou morto, que serve de alimento para os peixes.
*   **Licença de Pesca Amadora:** Documento obrigatório emitido por órgãos governamentais (como o IBAMA ou MPA) que autoriza legalmente a prática da pesca por lazer ou desporto no Brasil.
*   **Líder (Leader):** Trecho final da linha, geralmente de fluorocarbono ou monofilamento mais grosso, que fica em contato direto com o peixe e oferece resistência à abrasão.
*   **Molinete (Spinning):** Equipamento com carretel fixo, mais fácil de operar para iniciantes, pois reduz a chance de emaranhados de linha ("cabeleiras").
*   **Muco:** Camada viscosa protetora que reveste o corpo do peixe, possuindo propriedades fungicidas e bactericidas essenciais para sua saúde.
*   **Pesca Amadora/Esportiva:** Atividade praticada por lazer ou desporto, sem fins comerciais, onde o pescado não é fonte de subsistência ou renda.
*   **Pesque e Solte (Catch and Release):** Prática de devolver o peixe vivo e em boas condições à água imediatamente após a captura, visando a conservação ambiental.
*   **Protocolo RAMP (Reflex Action Mortality Predictors):** Ferramenta de campo usada para avaliar a vitalidade do peixe através de testes de reflexos antes da soltura, prevendo suas chances de sobrevivência.
*   **Puçá (Passaguá):** Rede de mão utilizada para auxiliar o embarque seguro do peixe. Na pesca esportiva, recomenda-se que seja feita de silicone ou borracha para não remover o muco do animal.
*   **Revitalização:** Técnica de segurar o peixe horizontalmente contra a correnteza para que a água oxigene as brânquias antes da soltura definitiva.

---
## Considerações Finais

Analisando os Resumos em vídeo, Apresentações, Relatórios e Cartões didáticos gerados pelo NotebookLM conforme as diretrizes apontados na **nota adicionada** nas Fontes e conforme todo o material inserido, uma vez que possuo bom conhecimento sobre o assunto, pude verificar que o NotebookLM elaborou materiais concisos, de qualidade tanto visual (o que me surpreendeu e muito) bem como dentro das fontes foi capaz de organizar os conteúdos de forma correta e dentro do perfil didático solicitado.

O resumo em vídeo vale muito a pena assistir.