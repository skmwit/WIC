## 2018 교내 메이커톤 경진대회 WIC('Women in engineering Intensive Course')  
> 팀장/기획자 : 여혜민  
개발자 : 김하연, 명지연  
디자이너 : 윤혜원  
  
  
## :round_pushpin: 프로젝트 주제  
학교 주변 골목길 중 3곳의 실시간 안전 지수를 지도에 표시하는 웹 서비스  
  
    
## :wrench: 기술 스택  
- Server : Raspberry Pi, Django  
- Web : HTML, CSS, Ajax  
- Data :  
  (지도 API) <a href="https://apis.map.kakao.com/web/">다음 지도 api</a>  
    
  (기타 API) <a href="https://data.seoul.go.kr/together/guide/useGuide.do">서울시 열린데이터 광장</a>  
  (경찰서/치안 센터 유무) 500m 내에 경찰서가 있는지에 따라 점수 부여  
  (상권 활성화 지수) 서울시 우리마을 가게 상권 분석 서비스를 이용하여 골목길마다의 상권 활성화 지수를 기준으로 점수 산정  
  (유동 인구) 서울시 열린데이터 광장 '상권-추정유동인구' (deprecated)  
    
## :memo: 데이터 활용  
  
  ex1. 경찰서/치안 센터의 유무  
    
  <img src="https://github.com/skmwit/WIC/blob/main/image/police.png" width="600" height="450">  
  
  ex2. 상권 활성화 지수  
    
  <img src="https://github.com/skmwit/WIC/blob/main/image/store.png" width="600" height="450">  
  
  ex3. 유동 인구 (deprecated)  
  
  <img src="https://github.com/skmwit/WIC/blob/main/image/floatingPeople.png" width="600" height="450">  
  
  
## :computer: 웹 템플릿 및 결과  
  <a href="https://github.com/skmwit/WIC/blob/main/ppt/Hermap.PDF">발표자료</a>
  
  <a href="https://github.com/skmwit/WIC/tree/main/map/templates/map">Web FE 코드 확인하기</a>
  
  - 초기 화면  
  <img src="https://github.com/skmwit/WIC/blob/main/image/hermap_main.png" width="600" height="450">  
    
  - 종합 위험지수 지도 보기  
  <img src="https://github.com/skmwit/WIC/blob/main/image/totalscore.png" width="900" height="400">  
    
  <img src="https://github.com/skmwit/WIC/blob/main/image/totalscore_zoom.png" width="600" height="400">
    
  - 유동 인구수 반영 지도 보기 (8pm 이후)  
  <img src="https://github.com/skmwit/WIC/blob/main/image/fp.png" width="600" height="450">  
    
  <img src="https://github.com/skmwit/WIC/blob/main/image/fp2.png" width="900" height="400">  
    
  - 골목길 별 상권 활성화도 반영 지도 보기  
  <img src="https://github.com/skmwit/WIC/blob/main/image/store_map.png" width="700" height="400">  
    
  <img src="https://github.com/skmwit/WIC/blob/main/image/store_map_zoom.png" width="500" height="400">
    
    
