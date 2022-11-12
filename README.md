# :rocket: Projeto MongoDB - Commerce :rocket:

Este repositório consiste em 32 queries (NoSql) realizadas mediante aos desafios designados pelo projeto "Commerce" proposto pela trybe. 


<table role="table">
<thead>
<tr>
<th><em>Requisito</em></th>
<th align="center"><em>Avaliação</em></th>
</tr>
</thead>
<tbody>
<tr>
<td>1 - Retorne a quantidade de documentos inseridos na coleção <code class="notranslate">produtos</code></td>
<td align="center"><g-emoji class="g-emoji" alias="heavy_check_mark" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png"><img class="emoji" alt="heavy_check_mark" height="20" width="20" src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png"></g-emoji></td>
</tr>
<tr>
<td>10 - Retorne o <code class="notranslate">nome</code> de todos os lanches que tenham o percentual de <code class="notranslate">proteínas</code> maior ou igual a <code class="notranslate">30</code> e menor ou igual a <code class="notranslate">40</code></td>
<td align="center"><g-emoji class="g-emoji" alias="heavy_check_mark" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png"><img class="emoji" alt="heavy_check_mark" height="20" width="20" src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png"></g-emoji></td>
</tr>
<tr>
<td>11 - Retorne o <code class="notranslate">nome</code> do produto, a quantidade de <code class="notranslate">curtidas</code> e quantos itens foram <code class="notranslate">vendidos</code> dos produtos que não sejam iguais a <code class="notranslate">Big Mac</code> e <code class="notranslate">McChicken</code></td>
<td align="center"><g-emoji class="g-emoji" alias="heavy_check_mark" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png"><img class="emoji" alt="heavy_check_mark" height="20" width="20" src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png"></g-emoji></td>
</tr>
<tr>
<td>12 - Adicione <code class="notranslate">ketchup</code> aos <code class="notranslate">ingredientes</code> para todos os sanduíches menos o <code class="notranslate">McChicken</code>, garantindo que não haja duplicidade nos <code class="notranslate">ingredientes</code></td>
<td align="center"><g-emoji class="g-emoji" alias="heavy_check_mark" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png"><img class="emoji" alt="heavy_check_mark" height="20" width="20" src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png"></g-emoji></td>
</tr>
<tr>
<td>13 - Inclua o campo <code class="notranslate">criadoPor</code> em todos os documentos, colocando <code class="notranslate">Ronald McDonald</code> no valor desse campo</td>
<td align="center"><g-emoji class="g-emoji" alias="heavy_check_mark" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png"><img class="emoji" alt="heavy_check_mark" height="20" width="20" src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png"></g-emoji></td>
</tr>
<tr>
<td>14 - Crie uma query que retorne todos os lanches que possuem <em>picles</em> em seus ingredientes e mostre apenas os <code class="notranslate">3</code> primeiros itens contidos no array <code class="notranslate">valoresNutricionais</code></td>
<td align="center"><g-emoji class="g-emoji" alias="heavy_check_mark" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png"><img class="emoji" alt="heavy_check_mark" height="20" width="20" src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png"></g-emoji></td>
</tr>
<tr>
<td>15 - Adicione o campo <code class="notranslate">avaliacao</code> em todos os documentos da coleção e efetue alterações nesse campo</td>
<td align="center"><g-emoji class="g-emoji" alias="heavy_check_mark" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png"><img class="emoji" alt="heavy_check_mark" height="20" width="20" src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png"></g-emoji></td>
</tr>
<tr>
<td>16 - Adicione o campo <code class="notranslate">ultimaModificacao</code> com a data corrente somente no sanduíche <code class="notranslate">Big Mac</code></td>
<td align="center"><g-emoji class="g-emoji" alias="heavy_check_mark" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png"><img class="emoji" alt="heavy_check_mark" height="20" width="20" src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png"></g-emoji></td>
</tr>
<tr>
<td>17 - Retorne a quantidade total de produtos em uma nova coleção chamada <code class="notranslate">resumoProdutos</code></td>
<td align="center"><g-emoji class="g-emoji" alias="heavy_check_mark" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png"><img class="emoji" alt="heavy_check_mark" height="20" width="20" src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png"></g-emoji></td>
</tr>
<tr>
<td>18 - Inclua <code class="notranslate">bacon</code> no final da lista de <code class="notranslate">ingredientes</code> dos sanduíches <code class="notranslate">Big Mac</code> e <code class="notranslate">Quarteirão com Queijo</code></td>
<td align="center"><g-emoji class="g-emoji" alias="heavy_check_mark" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png"><img class="emoji" alt="heavy_check_mark" height="20" width="20" src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png"></g-emoji></td>
</tr>
<tr>
<td>19 - Remova o item <code class="notranslate">cebola</code> de todos os sanduíches</td>
<td align="center"><g-emoji class="g-emoji" alias="heavy_check_mark" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png"><img class="emoji" alt="heavy_check_mark" height="20" width="20" src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png"></g-emoji></td>
</tr>
<tr>
<td>2 - Ordene a coleção <code class="notranslate">produtos</code> pela quantidade de lanches vendidos em ordem crescente, mostrando apenas o <code class="notranslate">nome</code> e a quantidade de lanches <code class="notranslate">vendidos</code></td>
<td align="center"><g-emoji class="g-emoji" alias="heavy_check_mark" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png"><img class="emoji" alt="heavy_check_mark" height="20" width="20" src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png"></g-emoji></td>
</tr>
<tr>
<td>20 - Remova o primeiro <code class="notranslate">ingrediente</code> do sanduíche <code class="notranslate">Quarteirão com Queijo</code></td>
<td align="center"><g-emoji class="g-emoji" alias="heavy_check_mark" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png"><img class="emoji" alt="heavy_check_mark" height="20" width="20" src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png"></g-emoji></td>
</tr>
<tr>
<td>21 - Remova o último <code class="notranslate">ingrediente</code> do sanduíche <code class="notranslate">Cheddar McMelt</code></td>
<td align="center"><g-emoji class="g-emoji" alias="heavy_check_mark" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png"><img class="emoji" alt="heavy_check_mark" height="20" width="20" src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png"></g-emoji></td>
</tr>
<tr>
<td>22 - Adicione a quantidade de vendas dos sanduíches por dia da semana</td>
<td align="center"><g-emoji class="g-emoji" alias="heavy_check_mark" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png"><img class="emoji" alt="heavy_check_mark" height="20" width="20" src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png"></g-emoji></td>
</tr>
<tr>
<td>23 - Insira os valores <code class="notranslate">combo</code> e <code class="notranslate">tasty</code> no <em>array</em> <code class="notranslate">tags</code> de todos os sanduíches e aproveite para deixar os valores em ordem alfabética ascendente (A a Z)</td>
<td align="center"><g-emoji class="g-emoji" alias="heavy_check_mark" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png"><img class="emoji" alt="heavy_check_mark" height="20" width="20" src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png"></g-emoji></td>
</tr>
<tr>
<td>24 - Ordene em todos os documentos os valores do <em>array</em> <code class="notranslate">valoresNutricionais</code> pelo campo <code class="notranslate">percentual</code> de forma decrescente</td>
<td align="center"><g-emoji class="g-emoji" alias="heavy_check_mark" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png"><img class="emoji" alt="heavy_check_mark" height="20" width="20" src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png"></g-emoji></td>
</tr>
<tr>
<td>25 - Adicione o valor <code class="notranslate">muito sódio</code> ao final do <em>array</em> <code class="notranslate">tags</code> nos produtos em que o <code class="notranslate">percentual</code> de <code class="notranslate">sódio</code> seja maior ou igual a <code class="notranslate">40</code></td>
<td align="center"><g-emoji class="g-emoji" alias="heavy_check_mark" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png"><img class="emoji" alt="heavy_check_mark" height="20" width="20" src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png"></g-emoji></td>
</tr>
<tr>
<td>26 - Adicione o valor <code class="notranslate">contém sódio</code> ao final do <em>array</em> <code class="notranslate">tags</code> nos produtos em que o <code class="notranslate">percentual</code> de <code class="notranslate">sódio</code> seja maior do que <code class="notranslate">20</code> e menor do que <code class="notranslate">40</code></td>
<td align="center"><g-emoji class="g-emoji" alias="heavy_check_mark" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png"><img class="emoji" alt="heavy_check_mark" height="20" width="20" src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png"></g-emoji></td>
</tr>
<tr>
<td>27 - Conte quantos produtos contém <code class="notranslate">Mc</code> no nome, sem considerar letras maiúsculas ou minúsculas</td>
<td align="center"><g-emoji class="g-emoji" alias="heavy_check_mark" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png"><img class="emoji" alt="heavy_check_mark" height="20" width="20" src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png"></g-emoji></td>
</tr>
<tr>
<td>28 - Conte quantos produtos têm <code class="notranslate">4</code> ingredientes</td>
<td align="center"><g-emoji class="g-emoji" alias="heavy_check_mark" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png"><img class="emoji" alt="heavy_check_mark" height="20" width="20" src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png"></g-emoji></td>
</tr>
<tr>
<td>29 - Renomeie o campo <code class="notranslate">descricao</code> para <code class="notranslate">descricaoSite</code> em todos os documentos</td>
<td align="center"><g-emoji class="g-emoji" alias="heavy_check_mark" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png"><img class="emoji" alt="heavy_check_mark" height="20" width="20" src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png"></g-emoji></td>
</tr>
<tr>
<td>3 - Retorne o lanche mais vendido, mostrando apenas o <code class="notranslate">nome</code> e a quantidade do lanche mais vendido</td>
<td align="center"><g-emoji class="g-emoji" alias="heavy_check_mark" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png"><img class="emoji" alt="heavy_check_mark" height="20" width="20" src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png"></g-emoji></td>
</tr>
<tr>
<td>30 - Remova o campo <code class="notranslate">curtidas</code> do item <code class="notranslate">Big Mac</code></td>
<td align="center"><g-emoji class="g-emoji" alias="heavy_check_mark" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png"><img class="emoji" alt="heavy_check_mark" height="20" width="20" src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png"></g-emoji></td>
</tr>
<tr>
<td>31 - Retorne o <code class="notranslate">nome</code> dos sanduíches em que o número de <code class="notranslate">curtidas</code> é maior que o número de sanduíches <code class="notranslate">vendidos</code></td>
<td align="center"><g-emoji class="g-emoji" alias="heavy_check_mark" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png"><img class="emoji" alt="heavy_check_mark" height="20" width="20" src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png"></g-emoji></td>
</tr>
<tr>
<td>32 - Retorne o <code class="notranslate">nome</code> e a quantidade de vendas (<code class="notranslate">vendidos</code>) dos sanduíches em que o número de vendas é múltiplo de <code class="notranslate">5</code></td>
<td align="center"><g-emoji class="g-emoji" alias="heavy_check_mark" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png"><img class="emoji" alt="heavy_check_mark" height="20" width="20" src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png"></g-emoji></td>
</tr>
<tr>
<td>4 - Retorne os lanches que tiveram vendas maiores que <code class="notranslate">50</code> e menores que <code class="notranslate">100</code>, mostrando apenas o nome e a quantidade de lanches <code class="notranslate">vendidos</code> em ordem crescente</td>
<td align="center"><g-emoji class="g-emoji" alias="heavy_check_mark" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png"><img class="emoji" alt="heavy_check_mark" height="20" width="20" src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png"></g-emoji></td>
</tr>
<tr>
<td>5 - Retorne o <code class="notranslate">nome</code>, as <code class="notranslate">curtidas</code> e <code class="notranslate">vendidos</code> dos lanches que tiveram quantidade de <code class="notranslate">curtidas</code> igual a <code class="notranslate">36</code> ou tenham a quantidade de vendas igual a <code class="notranslate">85</code></td>
<td align="center"><g-emoji class="g-emoji" alias="heavy_check_mark" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png"><img class="emoji" alt="heavy_check_mark" height="20" width="20" src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png"></g-emoji></td>
</tr>
<tr>
<td>6 - Retorne o <code class="notranslate">nome</code> e as <code class="notranslate">curtidas</code> dos lanches que tiveram curtidas maiores que <code class="notranslate">10</code> e menores que <code class="notranslate">100</code></td>
<td align="center"><g-emoji class="g-emoji" alias="heavy_check_mark" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png"><img class="emoji" alt="heavy_check_mark" height="20" width="20" src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png"></g-emoji></td>
</tr>
<tr>
<td>7 - Retorne o <code class="notranslate">nome</code> e <code class="notranslate">vendidos</code> dos lanches que tenham sido <code class="notranslate">vendidos</code> com uma quantidade diferente de <code class="notranslate">50</code> e em que o campo <code class="notranslate">tags</code> não exista</td>
<td align="center"><g-emoji class="g-emoji" alias="heavy_check_mark" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png"><img class="emoji" alt="heavy_check_mark" height="20" width="20" src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png"></g-emoji></td>
</tr>
<tr>
<td>8 - Delete os lanches com menos de <code class="notranslate">50</code> <code class="notranslate">curtidas</code> e retorne o <code class="notranslate">nome</code> dos lanches que restaram no banco</td>
<td align="center"><g-emoji class="g-emoji" alias="heavy_check_mark" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png"><img class="emoji" alt="heavy_check_mark" height="20" width="20" src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png"></g-emoji></td>
</tr>
<tr>
<td>9 - Retorne o <code class="notranslate">nome</code> de todos os lanches que possuam <code class="notranslate">calorias</code> abaixo de <code class="notranslate">500</code></td>
<td align="center"><g-emoji class="g-emoji" alias="heavy_check_mark" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png"><img class="emoji" alt="heavy_check_mark" height="20" width="20" src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png"></g-emoji></td>
</tr>
</tbody>
</table>
