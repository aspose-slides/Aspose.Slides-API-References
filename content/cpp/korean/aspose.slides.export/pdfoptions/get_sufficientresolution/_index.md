---
title: get_SufficientResolution()
second_title: Aspose.Slides for C++ API 레퍼런스
description: PDF 문서 내부 이미지의 해상도를 결정하는 값을 반환합니다.
type: docs
weight: 352
url: /ko/aspose.slides.export/pdfoptions/get_sufficientresolution/
---
## PdfOptions::get_SufficientResolution() 메서드


PDF 문서 내부 이미지의 해상도를 결정하는 값을 반환합니다.

```cpp
float Aspose::Slides::Export::PdfOptions::get_SufficientResolution() override
```

## 비고


속성은 파일 크기, 내보내기 시간 및 이미지 품질에 영향을 줍니다.

기본값은 **96**입니다.

이 매개변수의 효과는 몇 가지 요소에 따라 달라집니다. 알고리즘은 속성 값, 원본 이미지 크기 및 이미지 프레임 크기에 따라 최적의 출력 이미지 크기를 얻으려고 시도합니다. 유사한 속성 값을 사용하면 동일한 결과가 나올 수 있습니다. 가시적인 효과를 얻기 위해 16 또는 32 단계를 사용하는 것이 권장됩니다.

읽기 **float**. 
## 참조

* 클래스 [PdfOptions](../)
* 네임스페이스 [Aspose::Slides::Export](../../)
* 라이브러리 [Aspose.Slides](../../../)