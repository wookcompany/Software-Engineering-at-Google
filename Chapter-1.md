# 핵심 정리

### 1. 소프트웨어 엔지니어링과 프로그래밍은 다르다. 프로그래밍(개발)은 코드 생산을 말한다. 반면 소프트웨어 엔지니어링(개발 + 유지보수 + 확장)은 프로그래밍을 확장하여 소프트웨어 수명이 다할 때 까지 코드를 유지 보수하는 문제까지 고려하는 것을 말한다.
-> 나는 그동안 프로그래밍을 했는가 소프트웨어 엔지니어링을 했는가를 생각해보면 의식적으로는 프로그래밍인 것 같다. 물론 아키텍쳐, 모듈화 등 유지보수와 확장성을 위해 고려된 환경 속에서 개발을 하려고했지만 의식적으로는 소프트웨어 엔지니어링이라고 생각을 하면서 접근하지는 않았던 것 같다. 같은 코드를 작성하는 행위에서 조금 더 소프트웨어 엔지니어링적인 부분을 생각해보며 개발에 접근해보면 좋을 것 같다.

### 2. 단명하는 코드와 장수하는 코드를 같은 방법으로 프로젝트에 접근하는 것은 안일한 생각이다.
-> 테스트 코드를 작성하더라도 장수하는 코드에 높은 우선 순위를 두고, 개발 자체에서도 중요도와 확장성을 고려하여 장수하는 코드에 우선순위와 노력을 더 기울이자.

### 3. 코드의 기대 수명이 길수록 의존성, 기술, 제품 요구사항 변경에 대응이 가능해야 지속 가능한 소프트웨어입니다. 여러 이유로 변경을 받아들이지 않기로 선택하더라도 변경할 수 있는 역량 자체는 필요합니다.
-> 긴 수명의 코드일 수록 여러 이유와 관계없이 확장이나 변경 가능한 역량자체는 가능하도록 코드를 개발 및 유지보수해야한다.

### 4. 하이럼의 법칙은 사용자가 많다면 API 명세서에 적어놓은 내용이나 설명이 중요하지 않다.
-> API 변경 더 넓게는 코드 수정에 관한 내용이다. 사용자(개발 인원)이 많을 수록 변경하기 어렵다는 이야기로 받아들여지며 초기에 잘 작성해야한다는 것을 의미한다.

### 5. 조직에서 반복적으로 수행하는 모든 작업은 필요 인력 측면에서 확장 가능(선형 증가 혹은 그 이하) 하게 변해야한다.
-> 반복적으로 하는 일을 자동화 해보자. 배포, 테스트, 컴파일, 깃 등 반복적으로 사용하는 시간을 줄이는 노력을 해보자.


### 6. 개발 프로세스를 포함한 소프트웨어 개발 업무의 많은 것의 효율은 눈치 채기 어렵게 천천히 나빠지는 경향이 있습니다. 끓는 물의 개구리가 되지 않도록 주의합니다.
-> 시간이 지날수록 코드의 수는 많아지고 생산성은 떨어진다. 하지만 그 안에서 눈치채지 못하고 적응할 수 있다. 이를 주의하고 지속적으로 개선하자.

### 7. 의사 결정을 데이터로 기반으로하겠다는 생각은 좋은 출발입니다. 하지만 현실에서의 의사 결정 대부분은 데이터, 가정, 선례, 논의를 종합하여 이루어집니다. 하지만 데이터로만으로 결정되는 경우는 드물다. 
-> 데이터 기반도 좋지만 객관적인 데이터인지 생각해볼 필요가 있고 데이터가 없는 경우도 많다. 정답은 아닐테니 끊임 없이 고민하고 가정과 선례, 논의를 통해서 프로젝트의 방향을 좋은 쪽으로 이끌자.

### 8. 데이터 주도 방식은 시간이 흘러 데이터가 변하면(혹은 가정이 무너지면) 프로젝트의 방향이 바뀔 수 있음을 뜻한다.
-> 데이터 기반으로 하는 가정은 물론 좋은 방법이지만 시간이 흐르거나 가정이 무너지면 그에 맞게 유동적으로 변해야한다. 프로젝트의 방향은 지속적으로 수정해야한다.
