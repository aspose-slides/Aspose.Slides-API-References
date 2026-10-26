---
title: get_JpegQuality()
second_title: Aspose.Slides C++ API 레퍼런스
description: PDF 문서 내부의 JPEG 이미지 품질을 결정하는 값을 반환합니다. uint8_t를 읽습니다.
type: docs
weight: 222
url: /ko/aspose.slides.export/pdfoptions/get_jpegquality/
---
## PdfOptions::get_JpegQuality() 메서드

PDF 문서 내부의 JPEG 이미지 품질을 결정하는 값을 반환합니다. 읽기 **uint8_t**.

```cpp
uint8_t Aspose::Slides::Export::PdfOptions::get_JpegQuality() override
```

## 비고

문서에 JPEG 이미지가 포함된 경우에만 영향을 미칩니다.

PDF 형식으로 저장할 때 문서 내부 이미지의 품질을 가져오거나 설정하려면 이 속성을 사용합니다. 값은 0에서 100 사이이며, 0은 최저 품질이지만 최대 압축을 의미하고, 100은 최고 품질이지만 최소 압축을 의미합니다.

기본값은 **100**입니다.

## 참고

* 클래스 [PdfOptions](../)
* 네임스페이스 [Aspose::Slides::Export](../../)
* 라이브러리 [Aspose.Slides](../../../)