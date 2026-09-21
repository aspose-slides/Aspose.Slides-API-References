---
title: IPortion class
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/iportion/
---
## IPortion 클래스

텍스트 단락 내의 텍스트 일부를 나타냅니다.

IPortion 형식은 다음 구성원을 노출합니다:

## 속성

| 속성 | 설명 |
| :- | :- |
| [`portion_format`](/slides/python-net/ko/aspose.slides/iportion/portion_format/) | 명시적으로 설정된 서식 속성을 포함하고, 상속이 적용되지 않은 텍스트 부분의 서식 개체를 반환합니다.<br/>            읽기 전용 [`IPortionFormat`](/slides/python-net/ko/aspose.slides/iportionformat). |
| [`text`](/slides/python-net/ko/aspose.slides/iportion/text/) | 부분의 일반 텍스트를 가져오거나 설정합니다.<br/>            읽기/쓰기 **str**. |
| [`field`](/slides/python-net/ko/aspose.slides/iportion/field/) | 이 부분의 필드를 반환합니다.<br/>            읽기 전용 [`IField`](/slides/python-net/ko/aspose.slides/ifield). |
| [`slide`](/slides/python-net/ko/aspose.slides/iportion/slide/) |  |
| [`presentation`](/slides/python-net/ko/aspose.slides/iportion/presentation/) |  |

## 메서드

| 메서드 | 설명 |
| :- | :- |
| [`add_field(self, field_type)`](/slides/python-net/ko/aspose.slides/iportion/add_field/#ifieldtype) | 이 부분을 자동 업데이트되는 필드로 변환합니다. |
| [`add_field(self, internal_string)`](/slides/python-net/ko/aspose.slides/iportion/add_field/#str) | 이 부분을 자동 업데이트되는 필드로 변환합니다. |
| [`remove_field(self)`](/slides/python-net/ko/aspose.slides/iportion/remove_field/#) | 이 필드 부분을 일반 부분으로 변환합니다. |
| [`get_rect(self)`](/slides/python-net/ko/aspose.slides/iportion/get_rect/#) | 부분을 둘러싼 사각형의 좌표를 가져옵니다. 사각형은 부분에 있는 텍스트 줄 전체를 포함하며,<br/>            빈 줄도 포함합니다. |
| [`get_coordinates(self)`](/slides/python-net/ko/aspose.slides/iportion/get_coordinates/#) | 부분의 시작 좌표를 가져옵니다. 점의 X 좌표는 <br/>            첫 문자와 왼쪽 사이드 베어링을 포함한 부분을 나타냅니다. 점의 Y 좌표는 <br/>            상단 사이드 베어링을 포함합니다. |


### 관련 항목
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)