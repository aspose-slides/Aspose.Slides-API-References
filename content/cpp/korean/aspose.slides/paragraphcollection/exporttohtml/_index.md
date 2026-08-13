---
title: ExportToHtml()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 단락을 HTML로 변환하고 String 객체로 반환합니다.
type: docs
weight: 170
url: /ko/aspose.slides/paragraphcollection/exporttohtml/
---
## ParagraphCollection::ExportToHtml(int32_t, int32_t, System::SharedPtr\<Export::ITextToHtmlConversionOptions\>) method

지정된 단락을 HTML로 변환하고 String 객체로 반환합니다.

```cpp
System::String Aspose::Slides::ParagraphCollection::ExportToHtml(int32_t firstParagraphIndex, int32_t paragraphsCount, System::SharedPtr<Export::ITextToHtmlConversionOptions> options) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| firstParagraphIndex | **int32_t** | 첫 번째 단락 인덱스 **int32_t** |
| paragraphsCount | **int32_t** | [Paragraph](../../paragraph/) 개수 **int32_t** |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ITextToHtmlConversionOptions](../../../aspose.slides.export/itexttohtmlconversionoptions/)\> | 변환 옵션 [Export::ITextToHtmlConversionOptions](../../../aspose.slides.export/itexttohtmlconversionoptions/) |

### 반환 값

생성된 HTML.

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [String](../../../system/string/)
* 클래스 [ITextToHtmlConversionOptions](../../../aspose.slides.export/itexttohtmlconversionoptions/)
* 클래스 [ParagraphCollection](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)