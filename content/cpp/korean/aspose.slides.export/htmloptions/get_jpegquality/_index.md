---
title: get_JpegQuality()
second_title: Aspose.Slides for C++ API 참조
description: PDF 문서 내부 JPEG 이미지의 품질을 결정하는 값을 반환합니다. 읽기 전용 uint8_t.
type: docs
weight: 144
url: /ko/aspose.slides.export/htmloptions/get_jpegquality/
---
## HtmlOptions::get_JpegQuality() 메서드


PDF 문서 내부 JPEG 이미지의 품질을 결정하는 값을 반환합니다. 읽기 전용 **uint8_t**.

```cpp
uint8_t Aspose::Slides::Export::HtmlOptions::get_JpegQuality() override
```

## 비고


문서에 JPEG 이미지가 포함된 경우에만 영향을 미칩니다.

PDF 형식으로 저장할 때 문서 내부 이미지의 품질을 가져오거나 설정하려면 이 속성을 사용합니다. 값은 0부터 100까지이며, 0은 최악의 품질이지만 최대 압축을 의미하고, 100은 최고의 품질이지만 최소 압축을 의미합니다.

기본값은 **95**입니다.
## 관련 항목

* 클래스 [HtmlOptions](../)
* 네임스페이스 [Aspose::Slides::Export](../../)
* 라이브러리 [Aspose.Slides](../../../)