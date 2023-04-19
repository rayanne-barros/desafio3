#  Análise das aplicações: 
Comparando os gráficos do visual VM, podemos observar que no spring webflux o número de threads é bem menor que no spring mvc (spring webflux menor que 50 threads e o no spring mvc mais de 200 threads) e o consumo da CPU também é mais baixo comparado com o spring mvc. Isso se dar pelo fato do spring webflux ser uma programação assíncrona e não bloqueante, ou seja, várias requisições são feitas paralelamente; já no caso do spring mvc por ser uma programação síncrona e bloqueante é feita uma requisição por vez, aqui bloqueasse todas as requisições posteriores até que a atual seja processada.

##Spring webflux (vus: 500)
<br>
<img src="https://i.postimg.cc/XNpsbQnb/webflux500novo.png" alt="Imagem do Projeto" width="800" height=""/>

##Spring webflux (vus: 1000)
<br>
<img src="https://i.postimg.cc/5tsjn9Cw/webflux1000novo.png" alt="Imagem do Projeto" width="800" height=""/>

##Spring webflux (vus: 2000)
<br>
<img src="https://i.postimg.cc/zvgwR2fH/webflux2000novo.png" alt="Imagem do Projeto" width="800" height=""/>
<br>

##Spring MVC (vus: 500)
<br>
<img src="https://i.postimg.cc/8c68JwG7/mvc500.png" alt="Imagem do Projeto" width="800" height=""/>

##Spring MVC (vus: 1000)
<br>
<img src="https://i.postimg.cc/qMQfttVX/mvc1000.png" alt="Imagem do Projeto" width="800" height=""/>

##Spring MVC (vus: 2000)
<br>
<img src="https://i.postimg.cc/MHx4Hw9F/mvc2000.png" alt="Imagem do Projeto" width="800" height=""/>
