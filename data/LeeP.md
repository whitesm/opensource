## 1. 소개
-------
 오픈소스 소프트웨어란 소스 코드에 대한 접근, 자유로운 재배포, 파생 저작물의 작성, 제한 없는 사용 등을 허용하는 라이선스와 함께 배포되는 소프트웨어이다.

## 2. 역사
-------
+ 2.1. 초기  
> + 개괄
>
> 오픈소스 소프트웨어 또는 자유 소프트웨어는 오래전부터 존재했었다. 이는 프로그래머들이 컴퓨터 시스템을 생산적이고 유용하게 만들기 위해 툴, 기술, 응용 프로그램들을 개발하였다. 이 과정에서  서로의 개발품을 자유롭게 공유하고, 상대방의 결과물에 기여하기도 하였다. 초기에는 자원이 부족하여 서로 소프트웨어를 공유하면서 함께 발전시키는 것이 당연한 것이라고 생각되었다.  
>
> + 초기의 커뮤니티
>
> 초기부터 오픈 소스 소프트웨어의 개발과 사용을 중심으로 운영되었던 사용자들의 커뮤니티는 스스로 조직화될 필요를 느꼈다. 이런 커뮤니티의 최초 사례는 1950년대에 IBM의 쉐어와 유즈가 있고, 1961년에 설립된 데커스가 있다. 이 커뮤니티들은 사용자 개발 소프트웨어의 공개와 개발을 촉진시켰고, 서로의 소스를 공유하였다. 또, 소스코드와 알고리즘을 공개적으로 배포하고 보관한 ACM의 컬렉티드 알고리즘도 하나의 사례이다.  
> 또한, 1961년에 최초로 PDP-1을 도입한 MIT에서 현재의 해커문화가 발생하였다.
>
> + 오픈 소스 소프트웨어 운동의 시작
>
> 하지만 1970년대의 두 사건을 기점으로 사유 소프트웨어가 나타나기 시작한다.  
> 1970년대까지 소프트웨어는 통상 하드웨어 제조업자들에 의해 무료로 배포되었는데, 그들은 소프트웨어를 하드웨어에 끼워팔았다. 이는 소프트웨어의 개발비용이 낮아서 가능하였는데 개발비용이 높아짐에 따라 신흥 산업에서 소프트웨어를 독립적으로 판매하고자 하였다. 이런 상황에서  1969년에 미국 법무부가 하드웨어와 소프트웨어를 끼워팔기하던 IBM를 상대로 반독점 소송을 제기하였고, 이것을 계기로 소프트웨어의 상용 판매가 급증하였다. 또한, 이를 기점으로 제한적 라이선스하에서 판매되기 시작했다.  
> 소송이 제기되고 6년 후 마이크로컴퓨터의 베이직 인터프리터를 만든 빌 게이츠는 '취미로 소프트웨어를 개발하는 개발자들에게 보내는 공개 서한'이라는 편지를 공개한다. 이 편지에서 빌 게이츠는 시급 2달러 수준의 대가를 받으며 소프트웨어를 공유하는 것은 소프트웨어 개발자들을 다치게 하는 것이고, 정당한 대가의 지불은 고품질 소프트웨어를 개발하기 위해 중요한 것이라고 주장했다.  
> 위 두 사건은 오픈 소스 소프트웨어 운동의 시발점이 되었다.

+ 2.2. 유닉스와 오픈 소프트웨어  

> 초기 컴퓨터 시스템은 다중사용자 지원을 하지 않았다. 이를 해결하기 위해 1960년대 MIT에서 시스템이 제안되었고, 1964년에 벨 연구소와 제너럴 일렉트로닉의 공동 연구로 계승되었다. 이는 데니스 리치와 켄 톰슨이 유닉스를 만드는 데에 바탕이 되었다. 1974년에 리치와 톰슨이 유닉스 운영체제의 근간이 되는 핵심 개념을 발표하였다. 당시 유닉스의 공식적인 법인체인 AT&T에게 전화 사업이외의 사업에 대해 양보 명령이 내려졌기 때문에 유닉스는 어떠한 지원없이 무상으로 제공되었다. 리치가 개발한 유닉스와 C프로그래밍 언어는 매우 인기가 있었고, 수많은 대학과 컴퓨터 연구소, 해커들에게 빠르게 퍼져나갔다.  
> 유닉스는 AT&T의 공식적인 지원이 없었기때문에 프로그래머, 학생들과 연구원들의 사용자들은 발생한 문제를 직접 해결해야했다. 이 과정에서 서로간의 아이디어, 정보, 프로그램 및 버그 수정본을 공유하였다. 또한, 사용자들이 더 편하게 개발하도록 커니핸과 플라우거는 몇몇 핵심 유틸리티의 구현을 쉽게 이해할 수 있는 책을 소스코드와 함께 출판하였고, 사용자들은 각 유틸리티를 강화하고 다양한 아키텍쳐에 포팅하기 위해 공동으로 협력하였다. 1978년에 그들은 공식적으로 STUG라는 사용자 그룹을 구성하였다.
> 사용자 그룹도 형성되고, 책도 발간되는 등의 발전을 이루지만, AT&T가 유닉스를 상용화함에 따라 1979년에 시스템 소스 코드에 접근 제한을 두는 라이선스를 가진 버전 7을 배포하였다. 이로 인해 유닉스는 대학 교육과정에서 사용할 수 없었고, 오픈 소스 소프트웨어 운동에 자극을 주게된다.
>
 + 2.3. 해커문화
>
> 1970년대 후반과 1980년대에는 컴퓨터 네트워킹과 개인용 워크 스테이션이라는 주제가 OSS의 주요 동력이었다. 이 동력들은 새롭고 세계적인 규모로, 협력을 증대하고 생산성을 향상시킬 수 있는 소프트웨어와 정보의 교환과 분배를 가능하게 하였다. 각 프로그래머 그룹은 자신의 문화, 토론, 활동 규약, 속어, 심지어 믿음과 윤리를 가지고 형성하였고 서로 연결되어 있었다.
>
+ 2.4. 주요 사건
> + 개괄
>
> 사유 소프트웨어의 수가 증가함에 따라 오픈 소스 소프트웨어 운동을 가속화하였다. 오픈소스 소프트웨어 지지자들은 많은 핵심적인 개발 활동들을 이끌면서, 누구나 오픈소스 운영체제와 애플리케이션을 자유롭게 사용하게 만들 필요성을 느꼈다. 이를 위한 사건들 중 본 단락에서는 버클리 대학, MIT AI 연구소, 브리제 대학의 활동을 중점으로 소개하며, 최초의 오픈 소스 소프트웨어에 대해서도 다룰 것이다.  
>
> + 버클리 소프트웨어 배포판(Berkeley Software Distribution, BSD)
>
> 미국 캘리포니아 주립대학교 버클리 분교와 벨 연구소는 1974년과 1977년 사이에 유닉스의 성장을 위해 협력하였다. 이 시기에 BSD는 향상된 기능과 툴, 유틸리티를 가진 유닉스 버전으로 개선되었다. 또한, BSD는 처음 AT&T로부터 받은 제한적 소스 라이선스로 전 세계 많은 연구기관들과 공유하였다. 이로써 연구기관들이 소스 코드를 분석하고 수정할 수 있도록 하였다.
 BSD의 두번째 버전이 1978년에 나왔고, 버클리의 새로운 32비트 VAX 컴퓨터에 유닉스의 상위 버전을 사용하므로써 1979년에 3BSD의 확산을 주도하였다. 또한, 미국의 방위 고등연구 계획국(DARPA)는 운영 체제를 통합하기로 결정하였으며, 그 기준을 유닉스로 지정하였다. 그리고 유닉스와 유사한 운영체제인 BSD의 새 버전인 4BSD가 기관당 라이선스 계약의 형태로 만들어졌다. TCP/IP의 모든 스택을 포함한 4.3BSD 첫번째 버전과 같은 주요 버전들이 뒤를 이었다.  
 하지만 버전들은 모두 AT&T의 독점적인 라이선스를 따랐기 때문에 소스코드 라이선스가 매우 비쌌으며, 몇몇 연구기관과 업체에서는 AT&T 라이선스에서 탈피한 소스 코드에 관심을 표명했다. 버클리에서는 이 요청을 받아 1989년부터 시작하여 1991년에 AT&T와 관련된 소스를 모두 수정하여 새로운 라이선스인 BSD 라이선스라는 이름의 무료 배포 라이선스로 이끌었다.  
> 최근엔 4.4BSD와 더불어 NetBSD, FreeBSD, OpenBSD와 같은 운영체제를 오픈 소스로 배포하고 있다.
>
> + 미닉스
>
> 1987년에 암스테르담 브리제대학교의 앤드류 타넨바움이 유닉스가 제한적 라이선스로 배포됨에 따라 오픈 소스 운영체제인 미닉스를 배포했다. 이는 교육 목적으로 사용할 수 있는 마이크로커널 아키텍처 기반이며, 소스 코드를 학습과 연구를 위해 대학에서 사용할 수 있도록 하였다. 리눅스가 미닉스의 기반을 완전히 따른 것은 아니지만 리눅스 운영 체제의 디자인은 미닉스 설계 원칙에 의해 영향을 받은 것으로 간주된다.
>
> + GNU 프로젝트, 자유 소프트웨어 재단과 GPL
>
> MIT의 인공지능 연구실에서 사용되던 컴퓨터 시스템이 상용 운영 체제로 구동되는 새로운 하드웨어로 대체되었을 때, 주위에 형성되었던 오픈 소스 소프트웨어 프로그래머 커뮤니티는 점차적으로 붕괴하였다. 연구실 멤버인 리처드 스톨만은 오픈 소스 소프트웨어 커뮤니티를 다시 활발하게 만들기 위해 자유 소프트웨어의 개념에 도달하였다. 이를 통해 그는 GNU(GNU is Not Unix의 약자)라고 불렀던 유닉스 호환 운영 체제를 만드는 프로젝트를 시작하게 되었다.  
> 1985년에 GNU를 지원하기 위한 노력의 일환으로, 스톨만은 '소프트웨어를 공유하고 변경할 자유'를 촉진하기 위해 자유 소프트웨어 재단(FSF)을 설립했다. 그는 "내가 자유 소프트웨어를 말할 때, 나는 가격이 아닌 자유를 언급하는 것이다. 공짜 맥주가 아닌 말할 자유를 생각하라"라고 설명한 것으로 유명하다. FSF의 대부분의 수입은 자유 소프트웨어의 복사본이나 다른 관련 서비스의 판매에서 나왔으며, 부수적으로는 기부금으로부터 나왔다. 이 수입의 일부는 쉘과 C 라이브러리와 같은 기본적인 GNU 프로젝트를 수행하기 위해 개발자들을 고용하는데 사용되었다.
> 같은 1985년에 GNU 이맥스 편집기를 출시하였고, 이를 네트워크상에 무료로 배포하거나 유료 패키지의 테이프로 내놓았다. GNU 시스템은 GNU 컴파일러와 같은 다른 자유 소프트어 프로젝트들의 코드를 포함하였다. 또한, 다른 프로그램을 포팅하여 새로운 운영체제를 위한 준비를 하였다.  
> 새로운 운영체제를 위한 준비를 하는 과정에서 스톨만은 그들의 작업물이 상용 패키지로 재포장되어 사용될 수 있다는 것이었다. 이를 방지하기 위해 공공 도메인 및 사유 소프트웨어 사이의 중간 방식으로 카피레프트의 개념이 개발되었다. 이런 개념은 1989년에 발표된 GPU 일반 공중 허가서(GPL)의 기초가 되었다.  
> 1991년에 대학원생이었던 리누스 토발즈는 미닉스를 사용하여 유닉스 시스템에 대한 공부를 하고 있었다. 그는 미닉스가 자신이 원하는 성능에 미치지 못함을 알게 되었고, 미닉스의 개념을 타넨바움이 생각했던 것보다 더 발전시키기 위해 노력했다. 그렇게 개발된 리눅스 커널이 GNU와 결합하여 완전한 GNU 운영 체제를 주도하게 되었다.
>
> + 최초의 오픈 소스 소프트웨어 애플리케이션들
>
> + X-Window
>
> 다른 사이트의 기여와 더불어 MIT에서 개발한 X-Window 시스템은 오랫동안 그래픽 사용자 인터페이스(GUI) 개발의 토대가 되었다. X-Window의 성공은 소스 코드를 공개하고 자유 재량이 허용된 라이선스를 적용했기 때문이며, 여러 개발자의 의지가 상당 부분 작용했다고 볼 수 있다.
>
> + TeX
>
> TeX은 1978년 도널드 크누스에 의해 개발되었으며, 1982년에 재개발되어 배포되었다. 이것은 가장 정교한 문서 시스템으로 인정받고 있다. TeX은 단순한 문서 시스템이 아니며, 프로그래밍이 가능한 프로그램이다. 또한, 현재에서는 논문작성, 프로그래밍 등으로 사용되고 있다.
>

+ 2.5. 사유 스프트웨어와 오픈 소스 소프트웨어

## 3. 라이선스와 상용화
-------
+ 개괄
>
> 라이선스는 오픈 소스 소프트웨어가 상업화되면서 더더욱 중요해졌다. 또한, 기업이 발전하면서 여러가지 라이선스가 나오기 시작했다. 본 단락에서는 기업과 오픈 소스 소프트웨어의 주요 역사, 오픈 소스 소프트웨어를 활용한 방법, 라이선스과 비즈니스 모델을 다룰 것이다.
>
+ 3.1. 기업 - 오픈 소스 소프트웨어 주요 역사
>
> + 오픈 소스 소프트웨어 벤더의 출현
>
> 오픈 소스 소프트웨어가 대세가 되면서 새로운 기업들이 이를 통한 혜택을 보고 있었다. 기존의 많은 사유 소프트웨어 기업들도 오픈 소스 소프트웨어의 움직임을 따라가기 시작하였고, 오픈 소스 소프트웨어를 공부하기 시작했다.  
> 오픈 소스 소프트웨어 벤더와 유통업자가 출현하면서 오픈소스 소프트웨어 라이선스는 새로운 재정 모델과 비즈니스 모델을 기반으로 한 하이브리드 솔루션으로 적용되었다. 또한 오픈 소스 소프트웨어를 중심으로 새로운 카테고리 서비스가 제공되었고, 사유 소프트웨어 기업들도 제품의 소스 코드를 조금씩 공개하기 시작하였다.  
> 
> + 라이선싱 이슈와 오픈 소스 이니셔티브
>
> 1997년에 데비안 GNU/리눅스 배포판 프로젝트의 리더인 브루스 페렌스는 '데비안 우리의 약속'과 '데비안 자유 소프트웨어 지침'을 제안하며, '자유'라고 주장하는 소프트웨어들이 가진 서로 다른 많은 라이선스들의 문제점을 지적했다. 이를 기반으로 자유소프트웨어의 현상과 문화에 대한 연구하고 집필한 에릭 레이몬드와 함께 OSI를 설립했다. 그들의 목적은 소프트웨어 라이선스에 대한 실용적인 접근방식을 수립하고, 오픈소스 소프트웨어의 상업적 이용을 촉진시키는 것이었다.  
> OSI는 소프트웨어 사용자에 대한 몇 가지 자유를 보장하는 오픈 소스 정의를 개발했다. 이는 OSS 라이선스를 위한 지침이다. 오픈 소스 소프트웨어라는 용어를 제시했지만 FSF의 저항과 부딪혔다.
>
>
+ 3.2. 라이선스
>
> ![Alt text](http://ieeexplore.ieee.org/ielx5/5599996/5600280/5600285/html/img/5600285-fig-1-large.gif "Open Source License") 
>
> + 공공 도메인 (Public Domain)
>
> 소유자가 자신의 저작물에 대한 저작권을 보호할 필요가 없고 배포와 라이선스의 제한도 없다고 선언되는 라이선스이다. 이 경우, 특별한 허가 없이 수정, 복사, 배포, 판매를 할 수 있다.
>
> + 카피레프트
>
> 카피레프트는 소프트웨어를 재생산, 개작 또는 배포하는 권리를 허용하는 오픈 소스 라이선스의 한 형태이다. 그러나 파생 저작물에 같은 라이선스가 붙도록 강요한다.
>
> + GPL
>
> 리처드 스톨만에 의해 1980년에 만들어졌으며, GPL 라이선스 소프트웨어로부터 파생된 저작물의 소스 코드는 GPL 라이선스로 배포해야한다는 '전염성'을 가장 큰 특징으로 갖는다.
>
+ 3.3. 비지니스 모델
>
> 
>
## 4. 영향 및 미래
-------

+ 4.1. 산업에 미치는 영향
>
> 
>
+ 4.2. 사회에 미치는 영향
>
> 
>
+ 4.3. 연구 및 전망
>
> 
>

## 5. 출처
+ 10,000 피트에서 바라본 오픈 소스 소프트웨어
+ BSD 파트 : 위키백과
