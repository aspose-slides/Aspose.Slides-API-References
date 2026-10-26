---
title: MathPortion class
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.mathtext/mathportion/
---
## MathPortion 클래스

수학적 컨텍스트가 포함된 부분을 나타냅니다.

**Inheritance:**[`MathPortion`](/slides/python-net/ko/aspose.slides.mathtext/mathportion) → [`Portion`](/slides/python-net/ko/aspose.slides/portion)

MathPortion 타입은 다음 멤버를 노출합니다:

## 생성자

| 생성자 | 설명 |
| :- | :- |
| [`__init__(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathportion/__init__/#) | MathPortion 클래스를 새 인스턴스로 초기화합니다. |

## 속성

| 속성 | 설명 |
| :- | :- |
| [`portion_format`](/slides/python-net/ko/aspose.slides.mathtext/mathportion/portion_format/) | 상속이 적용되지 않은 텍스트 부분의 명시적으로 설정된 서식 속성을 포함하는 서식 객체를 반환합니다.<br/>            읽기 전용 [`IPortionFormat`](/slides/python-net/ko/aspose.slides/iportionformat). |
| [`text`](/slides/python-net/ko/aspose.slides.mathtext/mathportion/text/) | 부분의 일반 텍스트를 가져오거나 설정합니다.<br/>            읽기/쓰기 **str**. |
| [`field`](/slides/python-net/ko/aspose.slides.mathtext/mathportion/field/) | 이 부분의 필드를 반환합니다.<br/>            읽기 전용 [`IField`](/slides/python-net/ko/aspose.slides/ifield). |
| [`math_paragraph`](/slides/python-net/ko/aspose.slides.mathtext/mathportion/math_paragraph/) | 수학 단락 |
| [`slide`](/slides/python-net/ko/aspose.slides.mathtext/mathportion/slide/) |  |
| [`presentation`](/slides/python-net/ko/aspose.slides.mathtext/mathportion/presentation/) |  |

## 메서드

| 메서드 | 설명 |
| :- | :- |
| [`add_field(self, field_type)`](/slides/python-net/ko/aspose.slides.mathtext/mathportion/add_field/#ifieldtype) | 이 부분을 자동으로 업데이트되는 필드로 변환합니다. |
| [`add_field(self, internal_string)`](/slides/python-net/ko/aspose.slides.mathtext/mathportion/add_field/#str) | 이 부분을 자동으로 업데이트되는 필드로 변환합니다. |
| [`remove_field(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathportion/remove_field/#) | 이 필드 부분을 단순 부분으로 변환합니다. |
| [`get_rect(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathportion/get_rect/#) | 부분을 둘러싼 사각형의 좌표를 가져옵니다. 사각형은 빈 줄을 포함한 부분의 모든 텍스트 줄을 포함합니다. |
| [`get_coordinates(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathportion/get_coordinates/#) | 부분의 시작 좌표를 가져옵니다. X 좌표는 첫 번째 문자에서 왼쪽 측면 베어링을 포함한 부분 시작을 나타냅니다. Y 좌표는 상단 측면 베어링을 포함합니다. |


### 참고
* 클래스 [`MathPortion`](/slides/python-net/ko/aspose.slides.mathtext/mathportion)
* 클래스 [`Portion`](/slides/python-net/ko/aspose.slides/portion)
* 모듈 [`aspose.slides.mathtext`](/slides/python-net/ko/aspose.slides.mathtext)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)