---
title: set_JpegQuality()
second_title: Aspose.Slides C++ API 참조
description: PDF 문서 내부 JPEG 이미지의 품질을 결정하는 값을 설정합니다. uint8_t을 씁니다.
type: docs
weight: 92
url: /ko/aspose.slides.export/ihtmloptions/set_jpegquality/
---
## IHtmlOptions::set_JpegQuality(uint8_t) 메서드

PDF 문서 내부 JPEG 이미지의 품질을 결정하는 값을 설정합니다. **uint8_t**을(를) 씁니다.

```cpp
virtual void Aspose::Slides::Export::IHtmlOptions::set_JpegQuality(uint8_t value)=0
```

## 비고

문서에 JPEG 이미지가 포함된 경우에만 효과가 있습니다.

PDF 형식으로 저장할 때 문서 내부 이미지의 품질을 가져오거나 설정하려면 이 속성을 사용합니다. 값은 0에서 100 사이이며, 0은 최악의 품질이지만 최대 압축을 의미하고, 100은 최상의 품질이지만 최소 압축을 의미합니다.

기본값은 **95**입니다.

## 참고

* 클래스 [IHtmlOptions](../)
* 네임스페이스 [Aspose::Slides::Export](../../)
* 라이브러리 [Aspose.Slides](../../../)