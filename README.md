* Web server
* WAS(Web Application Server)
* REST API
* CSR(Client Side Rendering) vs SSR(Server Side Rendering)
* SPA(Single Page Application) vs MPA(Multi Page Application)
<br/>


* 제플린과 피그마 사용법


* 도커에서 리눅스 형태
![image](https://user-images.githubusercontent.com/107205708/212620369-9db838e1-c74b-4650-af0d-b6ce9c815ed7.png)

* 도커에서 동일한 웹서버(아파치)를 왜 여러 개의 컨테이너를 만들어서 띄우는 경우는 언제인가?

* MySQL은 포트를 안지정해줘도 되나?
* React에서 onClick함수에 매개변수를 줬을 때와 안줬을 때의 차이 -> 매개변수를 줬을 경우에는 ()=>{} 익명함수로 감싸줘야 함.
* 도커에서 compose up하고, down하면 컨테이너를 매번 그냥 삭제하는 것인지? 
  * 삭제한다고 생각하는데 삭제되면 컨테이너에 있던 데이터는 볼륨에 가서 임시저장이 된다고 생각하는데 맞는지?
  * 이미지는 Dockerfile에 있다고 생각하는데, 이미지의 내용을 바꿔주고 싶으면 Dockerfile의 내용을 바꿔주면 되는게 맞는가
Dockerfile --(Build)--> Image --(Create)--> Container
