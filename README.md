# aula23PRO
O aluno irá projetar a classe cannonBall (Bala de Canhão). Ele também vai criar o canhão em movimento para ajustar o ângulo do tiro das balas e atirá-las

-  começar criando o arquivo CannonBall.js na pasta js e adicioná-lo ao arquivo index.html.
-  criar a classe CannonBall
-  criar o constructor do CannonBall
-  criar o display CannonBall
-  no sketch.js criar o new CannonBall e chamar o display
-  no sketch.js criar o angleMode(DEGREES);  angle = 15;
-  no cannon.js criar o if keyIsDown (pedir para aluno testar pois vai estar bugado)
-  acrescentar no display do cannon: translate(this.x, this.y); para desbugar a posição de origem para rotacionar
-  restringir a rotação do canhão no if acrescentando  && this.angle<70 e no outro if && this.angle>-30

-  Queremos que a bala de
canhão seja disparada no
ângulo que o canhão está
apontando.


- Para fazer isso, a biblioteca p5 tem uma função
predefinida chamada p5.Vector.fromAngle().

- converter o
ângulo para radianos.
- Isso é feito multiplicando o valor do ângulo por (pi/180),
que é (3,14/180), para que nosso código funcione de
maneira adequada.


