---
title: set_JpegQuality()
second_title: Aspose.Slides for C++ API 레퍼런스
description: PDF 문서 내부의 JPEG 이미지 품질을 결정하는 값을 설정합니다. uint8_t을 씁니다.
type: docs
weight: 235
url: /ko/aspose.slides.export/pdfoptions/set_jpegquality/
---
## PdfOptions::set_JpegQuality(uint8_t) 메서드

PDF 문서 내부의 JPEG 이미지 품질을 결정하는 값을 설정합니다. **uint8_t**을(를) 씁니다.

```cpp
void Aspose::Slides::Export::PdfOptions::set_JpegQuality(uint8_t value) override
```

## 비고

문서에 JPEG 이미지가 포함된 경우에만 효과가 있습니다.

PDF 형식으로 저장할 때 문서 내부 이미지의 품질을 가져오거나 설정하려면 이 속성을 사용합니다. 값은 0에서 100 사이이며, 0은 최저 품질이지만 최대 압축을 의미하고 100은 최고 품질이지만 최소 압축을 의미합니다.

기본값은 **100**입니다.

## 참조

* 클래스 [PdfOptions](../)
* 네임스페이스 [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)