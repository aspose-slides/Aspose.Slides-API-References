---
title: set_SufficientResolution()
second_title: Aspose.Slides for C++ API 레퍼런스
description: PDF 문서 내부 이미지의 해상도를 결정하는 값을 설정합니다.
type: docs
weight: 326
url: /ko/aspose.slides.export/ipdfoptions/set_sufficientresolution/
---
## IPdfOptions::set_SufficientResolution(float) 메서드


PDF 문서 내부 이미지의 해상도를 결정하는 값을 설정합니다.

```cpp
virtual void Aspose::Slides::Export::IPdfOptions::set_SufficientResolution(float value)=0
```

## 비고


이 속성은 파일 크기, 내보내기 시간 및 이미지 품질에 영향을 줍니다.

기본값은 **96**입니다.

이 매개변수의 효과는 몇 가지 요소에 따라 달라집니다. 알고리즘은 속성 값, 원본 이미지 크기 및 이미지 프레임 크기에 따라 최상의 출력 이미지 크기를 얻으려고 합니다. 유사한 속성 값을 사용하면 동일한 결과가 나올 수 있습니다. 눈에 보이는 효과를 얻으려면 16 또는 32 단계를 사용하는 것이 권장됩니다.

쓰기 **float**. 
## 참조

* 클래스 [IPdfOptions](../)
* 네임스페이스 [Aspose::Slides::Export](../../)
* 라이브러리 [Aspose.Slides](../../../)