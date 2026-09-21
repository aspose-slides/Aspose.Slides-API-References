---
title: Point class
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides.animation/point/
---
## Point 클래스

애니메이션 포인트를 나타냅니다.

Point 유형은 다음 멤버를 노출합니다:

## 생성자

| 생성자 | 설명 |
| :- | :- |
| [`__init__(self)`](/slides/python-net/ko/aspose.slides.animation/point/__init__/#) | 기본 생성자. |
| [`__init__(self, time, value, formula)`](/slides/python-net/ko/aspose.slides.animation/point/__init__/#float-any-str) | 시간, 값 및 수식으로 애니메이션 포인트를 생성합니다. |

## 속성

| 속성 | 설명 |
| :- | :- |
| [`time`](/slides/python-net/ko/aspose.slides.animation/point/time/) | 시간 값을 나타냅니다.<br/>            읽기/쓰기 **float**. |
| [`value`](/slides/python-net/ko/aspose.slides.animation/point/value/) | 포인트 값을 나타냅니다.<br/>            가능한 타입: bool, ColorFormat, float, int, string.<br/>            읽기/쓰기 **any**. |
| [`formula`](/slides/python-net/ko/aspose.slides.animation/point/formula/) | 값, from, to, by 속성 내의 수식은 다음으로 구성될 수 있습니다:<br/>            표준 산술 연산자: ‘+’, ‘-‘, ‘*’, ‘/’, ‘^’, ‘%’ (mod)<br/>            상수: ‘pi’ ‘e’<br/>            조건 연산자: ‘abs’, ‘min’, ‘max’, ‘?’ (if)<br/>            비교 연산자: '==', '>=', '', '!=', '!'<br/>            삼각 연산자: ‘sin()’, ‘cos()’, ‘tan()’, ‘asin()’, ‘acos()’, ‘atan()’<br/>            자연 로그 ‘ln()’<br/>            속성 참조(호스트 지원 속성)<br/>            <br/>            예를 들어: "#ppt_x+(cos(-2*pi*(1-$))*-#ppt_x-sin(-2*pi*(1-$))*(1-#ppt_y))*(1-$)"<br/>            읽기/쓰기 **str**. |

### 참조
* 모듈 [`aspose.slides.animation`](/slides/python-net/ko/aspose.slides.animation)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)