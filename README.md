# semi-study


반도체 공부

:memo:
:wrench:
:book:

:pencil2:

:bulb:

:computer:
:crescent_moon:
:octocat::monkey_face:
:droplet:

:fire:
:star:
# 

📝

🔴
🔵💙💚🔋
# 💻

# 📁 ✏ 📌 📋 🍀 🌼  💧 🐵 
⬛ㅎㅇ
◼ HI

✔️
# ⚠
⚠
☕️⛔

❓ ❗
❗
❔
❕


:white_exclamation:

IDM = 종합 반도체 업체(삼성,인텔,하이닉스)
Fabless = 반도체 설계기술만 있고, 생산라인은 없음(퀄컴)
foundry = 생산라인만 있음. (제조:TSMC)

스택기법 = 쌓아서 집적도를 높힘.
트렌치기법 = trench(해구)를 파서 집적도를 높힘.

# zeroconf (zero configuration networking)
- dns나 ip를 이용하지않는 자동적으로 설정되는 네트워킹 기법

랑데뷰 프로토콜 : 따로 설정없이 서로 네트워킹함

목적지가 준비되었을때 패킷 보냄.(포트가 열려있거나?)

버퍼를 필요하지 않아 긴메세지를 보낼때 효율적임(데이터를 버퍼에 복사하는 과정 생략)


# < 반도체 8대 공정 공부> 

1. 웨이퍼 제조
 - 잉곳 만들기(모래Si를 녹여 원기둥의 잉곳 만듬)
 - 잉곳 절단(다이아몬드 톱을 이용하여 얇게 슬라이싱)
 - 표면 연마(매끄럽게 듬)=Polishing
 - 세척과 검사
2. 산화공정
 - 습식산화(반응이빠르고 두껍지만 질이 떨어짐) =  수증기를 사용하여 속도 빠름
 - 건식 산화(반응이 느리고 얇지만 질이 좋음) = O2만 사용하여 속도는 느림
3. 포토공정
 - 감광액을 표면에 바르고
 -  포토 마스크를 위에 얹고 강한 자외선을 통과시킴.(노광 과정)
 - 현상액을 뿌리면 positive(현상액)과 negative(자외선 받은 부분)로 나눠짐.
4. 식각공정(Eching)
- 

5. 박막공정 (증착 = Deposition) 
 - PVD (physical vapor depostion)
 - CVD ( Chemical Vapor Deposition)

6. 금속배선공정
 

7. EDS(Electrical Die Sorting) / sorting = 양품 불량품 분류하다.
- 양품인지 불량품인지 전기적 동작여부를 판별하는 공정
- Electrical Test -> Burn-In -> repair 가능한 칩은 다시 공정 투입
                                                         불가능한 칩은 Inking(특정 표시)를 통해 공정x
8. 패키징
- 메모리 SSD 모듈 제조
- 속도,온도에 따른 테스트


마스크 : 전자회로가 그려진 유리 판 


산화공정 : 산소를 넣어 si 윗부분을 Sio2로 만들어 절역막 등 생성
(산화막은 오염물질, 불순물로부터 보호)

웨이퍼에  감광액을 바르고 구우면 포토공정 세팅 완료

포토 마스크를 웨이퍼 위에 두고 자외선을 통과시키면 회로패턴을 웨이퍼에 그려줌

현상액을 통해 빛부분은 날아가고(증발), 다른부분은 남음.

현상액이 남은곳은 남겨두고, 나머지(회로부분)은 부식시킨다. 

그 후에 나머지(회로부분) 감광액도 황산용액으로 제거.

이제 위에 박막(Thin Film)을 입혀 전기적특성을 가지게 함.(회로, 현상액 전체 도포)
증착(Deposition) : 웨이퍼 위에 물질을 넣어 전기적인 특성을 갖게하는 과정

순수한 반도체는 규소로 되어있어 전기가 통하지 않으나 불순물(이온)을 넣음
이온: 가스입자로 만들어 웨이퍼 전면에 균일하게 넣어줌. 

금속 배선 공정 : 회로 패턴에 따라 금속선을 이어줌(칩 다리와 회로를 연결)


# PNP접합 다이오드 드레인 게이트 소스 공부하기!

2일차: 모스펫 jfet 공부
