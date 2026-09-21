---
title: jpeg_quality property
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.export/htmloptions/jpeg_quality/
weight: 90
---
## jpeg_quality 속성
Returns or sets a value determining the quality of the JPEG images inside PDF document.
읽기/쓰기 **int**.

### 비고

Has effect only when a document contains JPEG images.

Use this property to get or set the quality of the images inside a document when saving in PDF format.
The value may vary from 0 to 100 where 0 means worst quality but maximum compression and 100 means best quality but minimum compression.

The default value is **95** .

### 정의:
```python
@property
def jpeg_quality(self):
    ...

@jpeg_quality.setter
def jpeg_quality(self, value):
    ...
```

### 참고
* 클래스 [`HtmlOptions`](/slides/python-net/ko/aspose.slides.export/htmloptions)
* 모듈 [`aspose.slides.export`](/slides/python-net/ko/aspose.slides.export)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)