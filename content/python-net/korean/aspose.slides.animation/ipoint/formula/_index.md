---
title: formula property
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides.animation/ipoint/formula/
weight: 10
---
## 수식 속성
값, from, to, by 속성 내의 수식은 다음으로 구성될 수 있습니다:
            표준 산술 연산자: ‘+’, ‘-‘, ‘*’, ‘/’, ‘^’, ‘%’ (mod)
            상수: ‘pi’ ‘e’
            조건 연산자: ‘abs’, ‘min’, ‘max’, ‘?’ (if)
            비교 연산자: '==', '>=', '', '!=', '!'
            삼각 연산자: ‘sin()’, ‘cos()’, ‘tan()’, ‘asin()’, ‘acos()’, ‘atan()’
            자연 로그 ‘ln()’
            속성 참조(호스트 지원 속성)
            
            예시: "#ppt_x+(cos(-2*pi*(1-$))*-#ppt_x-sin(-2*pi*(1-$))*(1-#ppt_y))*(1-$)"
            읽기/쓰기 **str**.

### 정의:
```python
@property
def formula(self):
    ...

@formula.setter
def formula(self, value):
    ...
```


### 참고
* 클래스 [`IPoint`](/slides/python-net/ko/aspose.slides.animation/ipoint)
* 모듈 [`aspose.slides.animation`](/slides/python-net/ko/aspose.slides.animation)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)