---
title: write_font method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.export/embedallfontshtmlcontroller/write_font/
weight: 50
---
## write_font(self, generator, original_font, substituted_font, font_style, font_weight, font_data) {#ihtmlgenerator-ifontdata-ifontdata-str-str-bytes}
데이터를 base64 형식으로 HTML 문서 자체에 기록합니다


```python
def write_font(self, generator, original_font, substituted_font, font_style, font_weight, font_data):
    ...
```


| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| generator | [`IHtmlGenerator`](/slides/python-net/ko/aspose.slides.export/ihtmlgenerator) | HTML 생성기 |
| original_font | [`IFontData`](/slides/python-net/ko/aspose.slides/ifontdata) | 직렬화될 폰트 |
| substituted_font | [`IFontData`](/slides/python-net/ko/aspose.slides/ifontdata) | 대체된 폰트(폰트 대체가 발생한 경우), 그렇지 않으면 None |
| font_style | **str** | 폰트 스타일 |
| font_weight | **str** | 폰트 두께 |
| font_data | **bytes** | 폰트 데이터 |



### 참고
* 클래스 [`EmbedAllFontsHtmlController`](/slides/python-net/ko/aspose.slides.export/embedallfontshtmlcontroller)
* 클래스 [`IFontData`](/slides/python-net/ko/aspose.slides/ifontdata)
* 클래스 [`IHtmlGenerator`](/slides/python-net/ko/aspose.slides.export/ihtmlgenerator)
* 모듈 [`aspose.slides.export`](/slides/python-net/ko/aspose.slides.export)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)