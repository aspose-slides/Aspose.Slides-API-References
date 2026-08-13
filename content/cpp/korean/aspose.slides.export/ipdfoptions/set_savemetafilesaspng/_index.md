---
title: set_SaveMetafilesAsPng()
second_title: Aspose.Slides for C++ API 참조
description: 프레젠테이션에 사용된 모든 메타파일을 PNG 이미지로 변환하려면 true를 지정합니다. bool 형식으로 씁니다.
type: docs
weight: 300
url: /ko/aspose.slides.export/ipdfoptions/set_savemetafilesaspng/
---
## IPdfOptions::set_SaveMetafilesAsPng(bool) 메서드

프레젠테이션에 사용된 모든 메타파일을 PNG 이미지로 변환하려면 true를 반환합니다. **bool** 형식으로 씁니다.

```cpp
virtual void Aspose::Slides::Export::IPdfOptions::set_SaveMetafilesAsPng(bool value)=0
```

## 비고

Default is **true**. Pdf document can contain vector graphics and raster images. If SaveMetafilesAsPng is set to true then source Metafile image is converted to Png format and saved to Pdf as a raster image. If SaveMetafilesAsPng is set to false then source Metafile is converted to Pdf vector graphics. Each approach has advantages and disadvantages. For example, if Metafile is converted to PNG, then some quality loss is possible during resulting document scaling. If Metafile is converted to Pdf vector graphics, then performance issues in Pdf viewing tool are possible.

## 참조

* 클래스 [IPdfOptions](../)
* 네임스페이스 [Aspose::Slides::Export](../../)
* 라이브러리 [Aspose.Slides](../../../)