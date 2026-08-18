# PRÉ-ANÁLISE DE CEDENTE — TELLUS ENGENHARIA LTDA

**Status: incompleta.** As consultas processuais (eproc TJSC e eproc JFSC) não foram
executadas — ver item 6. Este documento reúne a identificação conferida, o escopo
definido e o protocolo pronto para rodar. Não é o relatório final e não deve ser
enviado ao cliente nesta forma.

---

## 1. IDENTIFICAÇÃO

| Campo | Dado |
|---|---|
| Solicitante | Pavei Soluções Financeiras |
| Autora do pedido | Jadna Batista Dolzan — Coordenadora Financeira — jadna.dolzan@paveisf.com.br |
| Data do pedido | 13/08/2026, 17h38 |
| Destinatários | Rafael, Felipe e cadastros@felipeadv.com.br |
| Cedente | Tellus Engenharia Ltda |
| CNPJ | 19.793.670/0001-30 (matriz) |
| Endereço | Rua Manoel Florentino Machado, nº 335, Centro, Imbituba/SC, CEP 88.780-000 |
| Sócia informada | Graziela Fernandes Laureano — CPF 026.258.419-07 |
| Relacionadas indicadas | Nenhuma |

**Documentos recebidos:** pedido por correio eletrônico de 13/08/2026 com quatro
anexos (2 MB), dos quais foram examinados até agora o comprovante de inscrição e
situação cadastral no CNPJ e a Carteira Nacional de Habilitação da sócia. A 7ª
alteração contratual consta como anexo do e-mail, mas **ainda não foi examinada**.

## 2. O QUE OS DOCUMENTOS EXAMINADOS MOSTRAM

**Comprovante de inscrição no CNPJ** (emitido em 13/08/2026, 16h05):

- Data de abertura: 18/02/2014
- Natureza jurídica: 206-2 — Sociedade Empresária Limitada
- Porte: DEMAIS
- Atividade principal: 41.20-4-00 — Construção de edifícios
- Atividades secundárias: 41.10-7-00 (incorporação de empreendimentos imobiliários);
  68.10-2-01 (compra e venda de imóveis próprios); 68.10-2-02 (aluguel de imóveis próprios)
- Situação cadastral: ATIVA — data da situação cadastral 12/02/2025
- Contato: tellusengenharia98@gmail.com — (48) 9694-9328

**CNH da sócia:** Graziela Fernandes Laureano, nascida em 10/11/1979 em Campinas/SP,
CPF 026.258.419-07, identidade 3591093 SSP/SC, filiação José Altair Laureano e
Marileis Fernandes Laureano, registro 02714773580, validade 08/02/2033.

## 3. ESCOPO DEFINIDO PARA A PESQUISA

Pelo domicílio da cedente em Imbituba/SC, e do mesmo critério estendido à sócia:

- Tribunal de Justiça de Santa Catarina, 1º grau, sistema eproc
- Justiça Federal da Seção Judiciária de Santa Catarina, sistema eproc

Dois documentos a pesquisar: CNPJ 19.793.670/0001-30 e CPF 026.258.419-07 — quatro
consultas ao todo.

## 4. GRADE DE COBERTURA — A PREENCHER

| Pesquisado | Documento | TJSC 1º grau | Justiça Federal (SC) |
|---|---|---|---|
| Tellus Engenharia Ltda | 19.793.670/0001-30 | *pendente* | *pendente* |
| Graziela Fernandes Laureano | 026.258.419-07 | *pendente* | *pendente* |

## 5. PROTOCOLO DE CONSULTA (padrão do escritório)

1. Consulta **por documento**, nunca por nome, com o tipo de pesquisa ajustado para
   CPF/CNPJ. Isso é especialmente importante neste caso — ver o primeiro ponto do item 7.
2. Filtro **"Exibir Baixados" marcado**, para alcançar processos em curso e encerrados.
3. **Consulta de controle** em cada base, com documento de empresa cuja litigiosidade
   já é conhecida do escritório, para provar que a base respondeu — sem isso, um
   "nada consta" não se distingue de falha de consulta.
4. Salvar o HTML de cada consulta como evidência, no padrão
   `EVIDENCIA-TJSC-CNPJ-19793670000130.html`, `EVIDENCIA-JFSC-CPF-02625841907.html`,
   mais os dois de controle.
5. Registrar se alguma consulta devolveu o aviso do sistema sobre entidades com
   muitos processos.

## 6. POR QUE AS CONSULTAS NÃO FORAM FEITAS

A sessão em que esta análise foi preparada roda na nuvem, e a política de rede do
ambiente bloqueia o acesso aos tribunais. Foi testado diretamente:

| Destino | Resultado |
|---|---|
| eproc1g.tjsc.jus.br | bloqueado no proxy de saída |
| eproc.jfsc.jus.br | bloqueado no proxy de saída |
| webmail-seguro.com.br | bloqueado no proxy de saída |

Os agregadores privados de dados processuais e cadastrais (Jusbrasil, Econodata,
cnpj.biz) estão igualmente bloqueados — e, ainda que não estivessem, não substituem
a consulta direta ao eproc que o padrão do escritório exige.

As consultas precisam ser executadas em sessão com navegador — a máquina do Rafael,
com o Chrome logado.

## 7. PONTOS DE ATENÇÃO JÁ IDENTIFICADOS

**Homonímia relevante — pesquisar só por CNPJ.** Existem ao menos quatro empresas
com "Tellus Engenharia" na razão social no país: a de Imbituba/SC (esta), uma em
Belo Horizonte/MG (Tellus Company Engenharia, CNPJ 10.289.103/0001-77), uma em
São Paulo/SP (Tellus Engenharia e Arquitetura, CNPJ 39.777.437/0001-71) e uma em
Poços de Caldas/MG (CNPJ 54.744.520/0001-38). Qualquer pesquisa por nome vai
misturar as quatro e contaminar o relatório.

**Data da situação cadastral em 12/02/2025.** A empresa é de 2014, mas a data da
situação cadastral é recente. Isso pode ser mera atualização cadastral, mas também
pode indicar que a inscrição passou por alteração de situação e retornou a ativa.
Vale conferir na JUCESC ou no histórico da Receita antes de fechar o relatório.

**Perfil imobiliário.** Além da construção de edifícios, a cedente tem incorporação,
compra e venda e aluguel de imóveis próprios. É um perfil que costuma produzir
litígio de comprador — rescisão, distrato, atraso de obra, vício construtivo — e
também dá lastro patrimonial. Ambos os lados importam para o parecer, e é mais um
motivo para a consulta alcançar o polo passivo e o ativo.

**7ª alteração contratual não examinada.** É o documento que fecha o quadro
societário, o capital e quem administra. O pedido informou uma única sócia, mas uma
sétima alteração sugere histórico societário movimentado — sócios que saíram nos
últimos anos podem justificar consulta adicional por CPF.

**Domicílio da sócia a confirmar.** Nascida em Campinas/SP, com identidade emitida em
SC. A CNH recebida não traz endereço. Se o domicílio dela não for catarinense, o
escopo precisa alcançar também o tribunal do domicílio dela.

**Verificar grupo econômico.** O pedido não indicou relacionadas. Convém confirmar,
na alteração contratual e no quadro societário, se há outra pessoa jurídica ligada
à sócia — inclusive porque há empresa atuando no mesmo ramo sob nome semelhante
("Tellus Empreendimentos"), o que precisa ser esclarecido antes de afirmar que não
há grupo não informado.

## 8. O QUE FALTA PARA FECHAR O RELATÓRIO

1. Executar as quatro consultas e as duas de controle, conforme o item 5.
2. Examinar a 7ª alteração contratual e o quarto anexo do e-mail.
3. Preencher a grade do item 4, a síntese quantitativa e a relação completa de processos.
4. Gerar o PDF em papel timbrado no padrão `Relatorio-Analise-Cedente-TELLUS-ENGENHARIA.pdf`
   e arquivá-lo no Drive, em `JA ANALISADOS`, na subpasta `2026-08-18 - TELLUS ENGENHARIA LTDA`,
   com a pasta `evidencias` ao lado.
