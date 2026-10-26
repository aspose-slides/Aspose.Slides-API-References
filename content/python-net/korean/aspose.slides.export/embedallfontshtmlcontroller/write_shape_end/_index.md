---
title: write_shape_end method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.export/embedallfontshtmlcontroller/write_shape_end/
weight: 60
---
## write_shape_end(self, generator, shape) {#ihtmlgenerator-ishape}
shape의 렌더링 전에 호출됩니다. 각 shape마다 한 번씩 호출됩니다. 이 함수가 generator에 무언가를 쓰면 현재 슬라이드 이미지 생성이 완료되고, 추가된 html 조각이 삽입되며, 이전 이미지 위에 새로운 이미지가 시작됩니다.

```python
def write_shape_end(self, generator, shape):
    ...
```

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| generator | [`IHtmlGenerator`](/slides/python-net/ko/aspose.slides.export/ihtmlgenerator) | 출력 객체. |
| shape | [`IShape`](/slides/python-net/ko/aspose.slides/ishape) | 마지막으로 렌더링되는 Shape. |

### 참조
* 클래스 [`EmbedAllFontsHtmlController`](/slides/python-net/ko/aspose.slides.export/embedallfontshtmlcontroller)
* 클래스 [`IHtmlGenerator`](/slides/python-net/ko/aspose.slides.export/ihtmlgenerator)
* 클래스 [`IShape`](/slides/python-net/ko/aspose.slides/ishape)
* 모듈 [`aspose.slides.export`](/slides/python-net/ko/aspose.slides.export)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)