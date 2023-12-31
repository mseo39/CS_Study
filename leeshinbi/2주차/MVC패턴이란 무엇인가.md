# MVC 패턴 
: Model+View+Controller 가 합쳐진 것으로,   
소프트웨어 개발에서 사용되는 디자인 패턴 중 하나로,   
애플리케이션의 구성 요소를 세 가지 주요 부분 (모델, 뷰 컨트롤러)으로 나눠 관리하고 상호작용하는 방식이다.

![image](https://github.com/leeshinbi/CS_Study/assets/109641586/1d6ed01e-70db-4668-9fb5-a1530263bf8f)

# MVC의 세가지 주요 구성 방식
:star:MODEL(모델)   

- 애플리케이션 상태의 캡슐화
- 상태 쿼리에 대한 응답
- 애플리케이션의 기능 표현
- 변경을 뷰에 통지 

:star:VIEW(뷰)   

- 모델을 화면에 시각적으로 표현
- 모델에게 업데이트 요청
- 사용자가 입력을 컨트롤러에 전달
- 컨트롤러가 뷰를 선택하도록 허용

:star:CONTROLLER(컨트롤러)

- 어플리케이션의 행위 정의
- 사용자 액션에 대한 모델 업데이트와 매핑
- 응답에 대한 뷰 선택 

# MVC 패턴은 왜 사용할까? 
: 코드를 영역 별로 분리하면 컴포넌트 간의 결합도가 낮아져,    
컴포넌트 변경이 다른 영역 컴포넌트에 영향을 주지 않는다.    
*따라서 기능 확장과 변경이 편리해진다.*
