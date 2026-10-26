---
title: IParagraph class
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/iparagraph/
---
## IParagraph 클래스

텍스트의 단락을 나타냅니다.

IParagraph 유형은 다음 멤버를 노출합니다:

## 속성

| Property | Description |
| :- | :- |
| [`portions`](/slides/python-net/ko/aspose.slides/iparagraph/portions/) | 텍스트 구분의 컬렉션을 반환합니다.<br/>            읽기 전용 [`IPortionCollection`](/slides/python-net/ko/aspose.slides/iportioncollection). |
| [`paragraph_format`](/slides/python-net/ko/aspose.slides/iparagraph/paragraph_format/) | 이 단락에 대한 서식 객체를 반환합니다.<br/>            읽기 전용 [`IParagraphFormat`](/slides/python-net/ko/aspose.slides/iparagraphformat). |
| [`text`](/slides/python-net/ko/aspose.slides/iparagraph/text/) | 단락의 일반 텍스트를 가져오거나 설정합니다.<br/>            읽기/쓰기 **str**. |
| [`end_paragraph_portion_format`](/slides/python-net/ko/aspose.slides/iparagraph/end_paragraph_portion_format/) | 다른 구분이 마지막 구분 뒤에 삽입될 경우 사용할 구분 속성을 지정합니다.<br/>            |
| [`slide`](/slides/python-net/ko/aspose.slides/iparagraph/slide/) |  |
| [`presentation`](/slides/python-net/ko/aspose.slides/iparagraph/presentation/) |  |

## 메서드

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/ko/aspose.slides/iparagraph/get_image/#) | 단락의 이미지를 반환합니다. |
| [`get_image(self, scale_x, scale_y)`](/slides/python-net/ko/aspose.slides/iparagraph/get_image/#float-float) | 지정된 배율로 단락의 이미지를 반환합니다. |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/ko/aspose.slides/iparagraph/join_portions_with_same_formatting/#) | 같은 서식을 가진 실행을 결합합니다. |
| [`get_rect(self)`](/slides/python-net/ko/aspose.slides/iparagraph/get_rect/#) | 단락을 둘러싸는 사각형의 좌표를 가져옵니다. 사각형은 단락의 모든 텍스트 라인을 포함하며,<br/>            빈 라인도 포함합니다. |
| [`get_lines_count(self)`](/slides/python-net/ko/aspose.slides/iparagraph/get_lines_count/#) | 단락의 라인 수를 가져옵니다. |

### 참고
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)