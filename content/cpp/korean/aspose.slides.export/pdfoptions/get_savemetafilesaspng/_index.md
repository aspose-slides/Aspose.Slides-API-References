---
title: get_SaveMetafilesAsPng()
second_title: Aspose.Slides C++ API 참조
description: 프레젠테이션에서 사용되는 모든 메타파일을 PNG 이미지로 변환하려면 true를 사용합니다. bool을 읽습니다.
type: docs
weight: 326
url: /ko/aspose.slides.export/pdfoptions/get_savemetafilesaspng/
---
## PdfOptions::get_SaveMetafilesAsPng() 메서드


프레젠테이션에서 사용되는 모든 메타파일을 PNG 이미지로 변환하려면 true를 사용합니다. **bool**을 읽습니다.

```cpp
bool Aspose::Slides::Export::PdfOptions::get_SaveMetafilesAsPng() override
```

## 비고


기본값은 **true**입니다. Pdf 문서는 벡터 그래픽과 래스터 이미지를 포함할 수 있습니다. SaveMetafilesAsPng가 true로 설정된 경우 소스 Metafile 이미지가 Png 형식으로 변환되어 Pdf에 래스터 이미지로 저장됩니다. SaveMetafilesAsPng가 false로 설정된 경우 소스 Metafile이 Pdf 벡터 그래픽으로 변환됩니다. 각 접근 방식에는 장단점이 있습니다. 예를 들어 Metafile이 PNG로 변환되면 결과 문서의 스케일링 중에 품질 손실이 발생할 수 있습니다. Metafile이 Pdf 벡터 그래픽으로 변환되는 경우 Pdf 뷰어에서 성능 문제가 발생할 수 있습니다. 
## 참조

* 클래스 [PdfOptions](../)
* 네임스페이스 [Aspose::Slides::Export](../../)
* 라이브러리 [Aspose.Slides](../../../)