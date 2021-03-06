# 도메인 네임이란?

---

### 1. 도메인이란?

인터넷을 정리할 때 간단하게 말했던 적이있지만 간단하게 **도메인(Domain)은 인터넷상의 주소**이다. 인터넷속에서 어떠한 정보를 찾거나 정보를 전송하기 위해서는 정보를 제공하고 전달받을 호스트 컴퓨터의 위치를 알아야하고 이를 도와주는 것이 도메인이다.

그러나 저번에도 말했듯 우리는 네트워크에서 IP주소중 IPv4를 써서 컴퓨터의 주소를 나타내지만 우리가 192.168.0.2와 같은 숫자를 기억하기는 쉽지 않을 것이다. 그렇기에 사람이 쉽게 읽고 사용하는 영문을 이용한 주소체계를 쓰는데 이것이 도메인이다.

### 2. 도메인 네임의 구조

도메인 네임은 알파벳과 숫자, '_'로 구성되어 있으며, .(점 : dot)으로 계층적으로 구분되어있다.

각 단계는 1단계, 2단계, 3단계도메인이라고 불리며, 단계가 높아질수록 도메인의 범위는 작아진다. 

**예시) 1단계 도메인 : test.kr(국가 도메인(KR)) / 2단계 도메인 : test.co.kr(사업체라는 것을 알려주는 CO) / 3단계 도메인 : 신청자가 원하는 이름으로 등록**

주소창에서 도메인 앞에 붙는 WWW는 도메인 네임이 아닌 '호스트 명'이다. 도메인을 보유하고 있다면 해당 도메인을 이용해 다양한 호스트 컴퓨터를 운영할 수 있다. 즉 test.co.kr이라는 도메인이 있다면 www.test.co.kr의 www자리위에 도메인 네임을 구성하는 영문, 숫자, _등으로 다양한 호스트명을 붙여 운영할 수 있다.

### 3. 도메인 네임의 체계

도메인 IP주소와 마찬가지로 전세계에서 유일해야 하므로 일정한 체계를 가지고 있고, 이것을 임으로 변경 및 생성이 불가능 하다.

인터넷의 모든 도메인은 루트라 불리는 도메인 이하에 아래 그림과 같은 역트리모양을 이루어 계층적으로 구성된다.

![도메인 역트리](https://user-images.githubusercontent.com/64365001/106473783-8d8d4200-64e7-11eb-8036-4202be3c6cc2.jpeg)

루트 도메인 아래의 단계를 1단계도메인 TLD : Top-Level Domain이라고 부르며, 그 다음단계를 2단계 도메인 SLD : Second-Level Domain이라고 부른다. .com, .net, .org같은 최상위 도메인의 경우 등록 요건만 맞추어 2단계부터 원하는 이름을 사용하여 도메인을 만들 수 있으며, 국가 최상위 도메인의 경우엔 해당 도메인을 관리하는 국아의 정책에 따라 2단계 혹은 3단계에서 도메인 네임을 선택 할 수 있게된다.

---

