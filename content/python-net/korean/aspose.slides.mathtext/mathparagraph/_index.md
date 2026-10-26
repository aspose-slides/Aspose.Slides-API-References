---
title: MathParagraph class
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.mathtext/mathparagraph/
---
## MathParagraph 클래스

수학 블록(IMathBlock)의 컨테이너인 수학 단락

The MathParagraph type exposes the following members:

## 생성자

| 생성자 | 설명 |
| :- | :- |
| [`__init__(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathparagraph/__init__/#) | Initializes a new instance of the MathParagraph class. |
| [`__init__(self, math_block)`](/slides/python-net/ko/aspose.slides.mathtext/mathparagraph/__init__/#imathblock) | Initializes a new instance of the MathParagraph class. |

## 속성

| 속성 | 설명 |
| :- | :- |
| [`justification`](/slides/python-net/ko/aspose.slides.mathtext/mathparagraph/justification/) | 단락 정렬 <br/>            Default value: CenteredAsGroup |
| [`count`](/slides/python-net/ko/aspose.slides.mathtext/mathparagraph/count/) | 컬렉션에 실제로 포함된 요소 수를 가져옵니다.<br/>            Read-only **int**. |

지정된 인덱스에 있는 항목을 가져옵니다.
            Read-only [`IMathBlock`](/slides/python-net/ko/aspose.slides.mathtext/imathblock).

## 인덱서

| 이름 | 설명 |
| :- | :- |
| [`[index]`](/slides/python-net/ko/aspose.slides.mathtext/mathparagraph/__getitem__/) | 가져올 항목의 0부터 시작하는 인덱스 |

## 메서드

| 메서드 | 설명 |
| :- | :- |
| [`clear(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathparagraph/clear/#) | 컬렉션의 모든 요소를 제거합니다. |
| [`add(self, math_block)`](/slides/python-net/ko/aspose.slides.mathtext/mathparagraph/add/#imathblock) | 컬렉션 끝에 IMathBlock을 추가합니다. |
| [`remove(self, math_block)`](/slides/python-net/ko/aspose.slides.mathtext/mathparagraph/remove/#imathblock) | 컬렉션에서 특정 객체의 첫 번째 발생을 제거합니다. |
| [`contains(self, math_block)`](/slides/python-net/ko/aspose.slides.mathtext/mathparagraph/contains/#imathblock) | 컬렉션에 특정 값이 포함되어 있는지 확인합니다. |
| [`index_of(self, math_block)`](/slides/python-net/ko/aspose.slides.mathtext/mathparagraph/index_of/#imathblock) | 컬렉션에서 특정 IMathBlock의 인덱스를 확인합니다. |
| [`insert(self, index, math_block)`](/slides/python-net/ko/aspose.slides.mathtext/mathparagraph/insert/#int-imathblock) | 지정된 인덱스에 IMathBlock을 컬렉션에 삽입합니다. |
| [`remove_at(self, index)`](/slides/python-net/ko/aspose.slides.mathtext/mathparagraph/remove_at/#int) | 컬렉션의 지정된 인덱스에 있는 항목을 제거합니다. |
| [`write_as_math_ml(self, stream)`](/slides/python-net/ko/aspose.slides.mathtext/mathparagraph/write_as_math_ml/#iorawiobase) | 이 [`MathParagraph`](/slides/python-net/ko/aspose.slides.mathtext/mathparagraph)의 내용을 MathML로 저장합니다 |
| [`to_latex(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathparagraph/to_latex/#) | LaTeX 형식의 수학 방정식을 가져옵니다 |

### 참고
* 클래스 [`IMathBlock`](/slides/python-net/ko/aspose.slides.mathtext/imathblock)
* 모듈 [`aspose.slides.mathtext`](/slides/python-net/ko/aspose.slides.mathtext)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)