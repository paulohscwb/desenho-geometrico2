<link rel="stylesheet" href="../../imagens/style.css">

<script type="text/x-mathjax-config">
  MathJax.Hub.Config({
    showProcessingMessages: false,
    tex2jax: { inlineMath: [['$','$'],['\\(','\\)']] }
  });
</script>
<script type="text/javascript" src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-MML-AM_HTMLorMML"></script>

<h2 id="inicio">Exercícios Propostos do Módulo 2</h2>
<h3>Espirais e elipses</h3> 
  <details open><summary>Exercício Proposto 2.1: exercício 3 da pág. 21</summary>
  <img src="../../modulo2/apostila_nova_2022b-21a.png" />
  <div class="combo"><details class="sub"><summary>&#x1f4cf; &#x1f4d0; Resolução</summary>
	<p>Vamos construir um triângulo equilátero circunscrito em uma elipse. São dados os focos, a distância <b>2a</b> da cônica e a direção <b>r</b> de um dos lados do triângulo.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="001p" name="sl">
			   <label for="001p"></label>
			   <img src="21_02_01.png"/>
			   <figcaption>Vamos iniciar encontrando a circunferência diretriz <b>&gamma;<sub>1</sub></b>, com centro em <b>F<sub>1</sub></b> e raio <b>2a</b>. Construindo o segmento <b>PF<sub>2</sub> &perp; r</b>, determinamos o ponto <b>F'<sub>2</sub></b> na circunferência diretriz.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="002p" name="sl">
			   <label for="002p"></label>
			   <img src="21_02_02.png"/>
			   <figcaption>Uma das retas tangentes é a mediatriz de <b>F<sub>2</sub>F'<sub>2</sub></b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="003p" name="sl">
			   <label for="003p"></label>
			   <img src="21_02_03.png"/>
			   <figcaption>Escolha um ponto <b>Q &isin; t</b> e construa um ângulo de 60&deg; a partir de <b>t</b>. Esta será a direção do segundo lado do triângulo equilátero.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="004p" name="sl">
			   <label for="004p"></label>
			   <img src="21_02_04.png"/>
			   <figcaption>Construindo o segmento <b>F''<sub>2</sub>F<sub>2</sub></b> perpendicular à direção do segundo lado do triângulo equilátero...</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="005p" name="sl">
			   <label for="005p"></label>
			   <img src="21_02_05.png"/>
			   <figcaption>... temos a posição da segunda reta tangente <b>t'</b>, mediatriz de <b>F<sub>2</sub>F''<sub>2</sub></b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="006p" name="sl">
			   <label for="006p"></label>
			   <img src="21_02_06.png"/>
			   <figcaption>Escolha um ponto <b>R &isin; t'</b> e construa um ângulo de 60&deg; a partir de <b>t'</b>. Esta será a direção do terceiro lado do triângulo equilátero.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="007p" name="sl">
			   <label for="007p"></label>
			   <img src="21_02_07.png"/>
			   <figcaption>Construindo o segmento <b>F'''<sub>2</sub>F<sub>2</sub></b> perpendicular à direção do terceiro lado do triângulo equilátero...</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="008p" name="sl">
			   <label for="008p"></label>
			   <img src="21_02_08.png"/>
			   <figcaption>... temos a posição da terceira reta tangente <b>t''</b>, mediatriz de <b>F<sub>2</sub>F'''<sub>2</sub></b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="009p" name="sl">
			   <label for="009p"></label>
			   <img src="21_02_09.png"/>
			   <figcaption>O triângulo equilátero <b>&#9651;ABC</b> fica circunscrito na elipse.</figcaption>
		   </li>
		</ul>
		<img src="21_02_00.png" class="fundo"/>
  </details></div></details>
  <details open><summary>Exercício Proposto 2.2: exercício 3 da pág. 23</summary>
  <img src="../../modulo2/apostila_nova_2022b-23.png" />
  <div class="combo"><details class="sub"><summary>&#x1f4cf; &#x1f4d0; Resolução</summary>
	<p>Vamos construir os elementos principais de uma elipse dada por dois vértices e uma reta tangente.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="010p" name="sl">
			   <label for="010p"></label>
			   <img src="23_01_01.png"/>
			   <figcaption>Vamos iniciar encontrando o segmento o centro da elipse, construindo a mediatriz de <b>A<sub>1</sub>A<sub>2</sub></b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="011p" name="sl">
			   <label for="011p"></label>
			   <img src="23_01_02.png"/>
			   <figcaption>Construindo a circunferência principal, com centro <b>O</b> e raio <b>OA<sub>1</sub> = OA<sub>2</sub></b>, encontramos pos pontos <b>L</b> e <b>L'</b> na reta tangente <b>t</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="012p" name="sl">
			   <label for="012p"></label>
			   <img src="23_01_03.png"/>
			   <figcaption>Como <b>L</b> e <b>L'</b> são os pés das perpendiculares às retas tangentes que passam pelos focos da elipse, quando construirmos as retas perpendiculares à reta <b>t</b> que passam por <b>L</b> e <b>L'</b>, determinamos os focos da elipse na reta <b>A<sub>1</sub>A<sub>2</sub></b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="013p" name="sl">
			   <label for="013p"></label>
			   <img src="23_01_04.png"/>
			   <figcaption>Determine os vértices <b>B<sub>1</sub></b> e <b>B<sub>2</sub></b>, na mediatriz de <b>A<sub>1</sub>A<sub>2</sub> </b>, tais que <b>B<sub>1</sub>F<sub>2</sub> = B<sub>2</sub>F<sub>2</sub> = a</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="014p" name="sl">
			   <label for="014p"></label>
			   <img src="23_01_05.png"/>
			   <figcaption>Unindo o foco <b>F<sub>2</sub></b> com o ponto <b>F'<sub>1</sub></b>, simétrico de <b>F<sub>1</sub></b> em relação à reta tangente, determinamos o ponto de tangência <b>T</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="015p" name="sl">
			   <label for="015p"></label>
			   <img src="23_01_06.png"/>
			   <figcaption>Para finalizar, basta construir a elipse à mão livre.</figcaption>
		   </li>
		</ul>
		<img src="23_01_00.png" class="fundo"/>
  </details></div></details>
  <details open style="border-bottom: 1px solid #a2dec0;"><summary>Exercício Proposto 2.3: exercício 3 da pág. 25</summary>
  <img src="../../modulo2/apostila_nova_2022b-25b.png" />
  <div class="combo"><details class="sub"><summary>&#x1f4cf; &#x1f4d0; Resolução</summary>
	<p>Vamos construir os elementos principais de uma elipse dada pelo diâmetro <b>2b</b> e pela excentricidade.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="016p" name="sl">
			   <label for="016p"></label>
			   <img src="25_03_01.png"/>
			   <figcaption>Vamos iniciar encontrando o segmento <b>2b</b> e a <b>med<sub>B<sub>1</sub>B<sub>2</sub></sub></b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="017p" name="sl">
			   <label for="017p"></label>
			   <img src="25_03_02.png"/>
			   <figcaption>Usando o teorema de Tales, determinamos a proporção da excentricidade $\mathsf{ {c \over a} = {1 \over 3}}$ fazendo $\mathsf{ {O1 \over O3} = {1 \over 3}}$. Logo, encontramos um ponto vértice <b>B'<sub>1</sub> &isin; OB<sub>1</sub></b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="018p" name="sl">
			   <label for="018p"></label>
			   <img src="25_03_03.png"/>
			   <figcaption>Construindo o segmento paralelo a <b>1B'<sub>1</sub></b> que passa por <b>B<sub>1</sub></b>, encontramos o foco <b>F<sub>1</sub></b> na mediatriz de <b>B<sub>1</sub>B<sub>2</sub></b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="019p" name="sl">
			   <label for="019p"></label>
			   <img src="25_03_04.png"/>
			   <figcaption>Encontre o simétrico de <b>F<sub>1</sub></b> em relação ao centro da elipse.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="020p" name="sl">
			   <label for="020p"></label>
			   <img src="25_03_05.png"/>
			   <figcaption>A <b>Circunf(O<sub>1</sub>, a)</b> determina os vértices <b>A<sub>1</sub></b> e <b>A<sub>2</sub></b> na mediatriz de <b>B<sub>1</sub>B<sub>2</sub></b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="021p" name="sl">
			   <label for="021p"></label>
			   <img src="25_03_06.png"/>
			   <figcaption>Para finalizar, basta construir a elipse à mão livre.</figcaption>
		   </li>
		</ul>
		<img src="25_03_00.png" class="fundo"/>
  </details></div></details>



