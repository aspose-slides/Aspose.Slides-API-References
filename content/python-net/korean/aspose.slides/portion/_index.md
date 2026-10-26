---
title: Portion class
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides/portion/
---
## Portion 클래스

텍스트 단락 안에 있는 텍스트 부분을 나타냅니다.

Portion 타입은 다음 멤버를 노출합니다:

## 생성자

| 생성자 | 설명 |
| :- | :- |
| [`__init__(self)`](/slides/python-net/ko/aspose.slides/portion/__init__/#) | Portion 클래스의 새 인스턴스를 초기화합니다. |
| [`__init__(self, str)`](/slides/python-net/ko/aspose.slides/portion/__init__/#str) | Portion 클래스의 새 인스턴스를 초기화합니다. |
| [`__init__(self, portion)`](/slides/python-net/ko/aspose.slides/portion/__init__/#portion) | Portion 클래스의 새 인스턴스를 초기화합니다. |

## 속성

| 속성 | 설명 |
| :- | :- |
| [`portion_format`](/slides/python-net/ko/aspose.slides/portion/portion_format/) | 텍스트 부분에 대해 상속이 적용되지 않은 명시적으로 설정된 서식 속성을 포함하는 서식 개체를 반환합니다.<br/>            읽기 전용 [`IPortionFormat`](/slides/python-net/ko/aspose.slides/iportionformat). |
| [`text`](/slides/python-net/ko/aspose.slides/portion/text/) | 부분의 일반 텍스트를 가져오거나 설정합니다.<br/>            읽기/쓰기 **str**. |
| [`field`](/slides/python-net/ko/aspose.slides/portion/field/) | 이 부분의 필드를 반환합니다.<br/>            읽기 전용 [`IField`](/slides/python-net/ko/aspose.slides/ifield). |
| [`slide`](/slides/python-net/ko/aspose.slides/portion/slide/) |  |
| [`presentation`](/slides/python-net/ko/aspose.slides/portion/presentation/) |  |

## 메서드

| 메서드 | 설명 |
| :- | :- |
| [`add_field(self, field_type)`](/slides/python-net/ko/aspose.slides/portion/add_field/#ifieldtype) | 이 부분을 자동 업데이트되는 필드로 변환합니다. |
| [`add_field(self, internal_string)`](/slides/python-net/ko/aspose.slides/portion/add_field/#str) | 이 부분을 자동 업데이트되는 필드로 변환합니다. |
| [`remove_field(self)`](/slides/python-net/ko/aspose.slides/portion/remove_field/#) | 이 필드 부분을 단순 부분으로 변환합니다. |
| [`get_rect(self)`](/slides/python-net/ko/aspose.slides/portion/get_rect/#) | 부분을 둘러싸는 직사각형의 좌표를 가져옵니다. 직사각형은 부분에 있는 모든 텍스트 행을 포함하며,<br/>            빈 행도 포함합니다. |
| [`get_coordinates(self)`](/slides/python-net/ko/aspose.slides/portion/get_coordinates/#) | 부분 시작점의 좌표를 가져옵니다. 점의 X 좌표는 첫 문자부터 시작하는 부분을 나타내며, 왼쪽 측면 베어링을 포함합니다.<br/>            Y 좌표는 <br/>            상단 측면 베어링을 포함합니다. |

### 참고
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)