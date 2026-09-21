---
title: jpeg_quality property
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides.export/ihtmloptions/jpeg_quality/
weight: 80
---
## jpeg_quality 속성
PDF 문서 내부의 JPEG 이미지 품질을 결정하는 값을 반환하거나 설정합니다.
읽기/쓰기 **int**.


### 비고

문서에 JPEG 이미지가 포함된 경우에만 효과가 있습니다.

PDF 형식으로 저장할 때 문서 내부 이미지의 품질을 가져오거나 설정하려면 이 속성을 사용합니다.
값은 0에서 100까지이며, 0은 최악의 품질이지만 최대 압축을 의미하고, 100은 최고의 품질이지만 최소 압축을 의미합니다.

기본값은 **95** 입니다.

### 정의:
```python
@property
def jpeg_quality(self):
    ...

@jpeg_quality.setter
def jpeg_quality(self, value):
    ...
```


### 참조
* 클래스 [`IHtmlOptions`](/slides/python-net/ko/aspose.slides.export/ihtmloptions)
* 모듈 [`aspose.slides.export`](/slides/python-net/ko/aspose.slides.export)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)