![Imgur](https://i.imgur.com/E70YjmM.png)

위와 같은 구조로 서버를 설계함.

조건 
**WEB ip** : 172.19.11.91:80 , 172.19.11.92:80<br>
(※ NGINX load balancing 을 사용해야 한다.)<br>
**WAS ip** : 172.19.11.93:8000 , 172.19.11.94:8000<br>
**TF-Serving:** 172.19.11.57, 172.19.11.56<br>
