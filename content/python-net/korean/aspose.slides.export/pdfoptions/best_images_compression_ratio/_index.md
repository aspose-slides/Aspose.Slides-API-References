---
title: best_images_compression_ratio property
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.export/pdfoptions/best_images_compression_ratio/
weight: 60
---
## best_images_compression_ratio 속성
각 이미지에 대해 기본 압축 대신 가장 효과적인 압축을 자동으로 선택해야 하는지를 나타냅니다.  
            **bool**.true 로 설정하면 프레젠테이션의 모든 이미지에 대해 가장 적절한 압축 알고리즘이 선택되어 결과 PDF 문서의 크기가 작아집니다.  
            최고의 이미지 압축 비율 선택은 계산 비용이 많이 들며 추가적인 RAM을 사용하고, 이 옵션은 기본적으로 **bool**.false 입니다.


### 비고

기본값은 **bool**.false 입니다.

### 정의:
```python
@property
def best_images_compression_ratio(self):
    ...

@best_images_compression_ratio.setter
def best_images_compression_ratio(self, value):
    ...
```

### 참고
* 클래스 [`PdfOptions`](/slides/python-net/ko/aspose.slides.export/pdfoptions)
* 모듈 [`aspose.slides.export`](/slides/python-net/ko/aspose.slides.export)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)