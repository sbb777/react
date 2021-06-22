
# react


##webcam

E:\git\react\webcam>npx create-react-app my-app
npx: installed 67 in 3.56s

## install dependencies
npm i @tensorflow/tfjs @tensorflow-models/body-pix react-webcam

## bodypix 화면상에 표시 FPS 가 너무 낮아
WebGL 하드웨어 가속을 아래와 같이 빨리 하니  화면이 번쩍임, (WebGL 하드웨어 가속 비활성화 하면 화면 번쩍임은 사라지나 FPS가 너무 낮음), 
Google Chrome 사용자

Google Chrome에서 WebGL 및 하드웨어 가속을 활성화했는지 확인하려면 다음을 수행하십시오.

Google Chrome 실행
주소 표시 줄에서 chrome://settings/?search=hardware로 이동
"사용 가능한 경우 하드웨어 가속 사용"이 켜져 있는지 확인합니다. 이미 켜져 있는 경우 끄면 일부 문제가 해결될 수도 있습니다.
Chrome 종료 및 다시 실행