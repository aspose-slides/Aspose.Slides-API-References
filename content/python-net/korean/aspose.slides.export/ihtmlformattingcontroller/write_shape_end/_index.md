---
title: write_shape_end method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.export/ihtmlformattingcontroller/write_shape_end/
weight: 30
---
## write_shape_end(self, generator, shape) {#ihtmlgenerator-ishape}
shape의 렌더링 전에 호출됩니다. 각 shape마다 한 번 호출됩니다. 이 함수가 generator에 아무것도 쓰면 현재 슬라이드 이미지 생성이 완료되고, 추가된 html 조각이 삽입되며 새로운 이미지가 이전 이미지 위에 시작됩니다.

```python
def write_shape_end(self, generator, shape):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| generator | [`IHtmlGenerator`](/slides/python-net/ko/aspose.slides.export/ihtmlgenerator) | 출력 객체. |
| shape | [`IShape`](/slides/python-net/ko/aspose.slides/ishape) | 마지막으로 렌더링되는 shape. |

### 관련 항목
* 클래스 [`IHtmlFormattingController`](/slides/python-net/ko/aspose.slides.export/ihtmlformattingcontroller)
* 클래스 [`IHtmlGenerator`](/slides/python-net/ko/aspose.slides.export/ihtmlgenerator)
* 클래스 [`IShape`](/slides/python-net/ko/aspose.slides/ishape)
* 모듈 [`aspose.slides.export`](/slides/python-net/ko/aspose.slides.export)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)