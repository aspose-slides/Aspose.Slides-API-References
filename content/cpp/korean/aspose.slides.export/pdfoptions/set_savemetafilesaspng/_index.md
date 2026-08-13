---
title: set_SaveMetafilesAsPng()
second_title: Aspose.Slides for C++ API 참조
description: true를 사용하여 프레젠테이션에 사용된 모든 메타파일을 PNG 이미지로 변환합니다. bool 형식으로 씁니다.
type: docs
weight: 339
url: /ko/aspose.slides.export/pdfoptions/set_savemetafilesaspng/
---
## PdfOptions::set_SaveMetafilesAsPng(bool) 메서드


프레젠테이션에 사용된 모든 메타파일을 PNG 이미지로 변환하려면 true를 사용합니다. **bool** 형식으로 씁니다.

```cpp
void Aspose::Slides::Export::PdfOptions::set_SaveMetafilesAsPng(bool value) override
```

## 비고


기본값은 **true**입니다. Pdf 문서는 벡터 그래픽과 래스터 이미지를 포함할 수 있습니다. SaveMetafilesAsPng가 true로 설정된 경우, 원본 Metafile 이미지는 Png 형식으로 변환되어 래스터 이미지로 Pdf에 저장됩니다. SaveMetafilesAsPng가 false로 설정된 경우, 원본 Metafile은 Pdf 벡터 그래픽으로 변환됩니다. 각 접근 방식에는 장단점이 있습니다. 예를 들어, Metafile이 PNG로 변환되면 결과 문서 스케일링 시 품질 손실이 발생할 수 있습니다. Metafile이 Pdf 벡터 그래픽으로 변환되면 Pdf 뷰어 도구에서 성능 문제가 발생할 수 있습니다. 
## 참고

* 클래스 [PdfOptions](../)
* 네임스페이스 [Aspose::Slides::Export](../../)
* 라이브러리 [Aspose.Slides](../../../)