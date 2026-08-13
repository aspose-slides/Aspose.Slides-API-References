---
title: WriteFont()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 데이터를 base64 형식으로 HTML 문서 자체에 기록합니다
type: docs
weight: 105
url: /ko/aspose.slides.export/embedallfontshtmlcontroller/writefont/
---
## EmbedAllFontsHtmlController::WriteFont(System::SharedPtr\<IHtmlGenerator\>, System::SharedPtr\<IFontData\>, System::SharedPtr\<IFontData\>, System::String, System::String, System::ArrayPtr\<uint8_t\>) 메서드

Writes data as base64 into HTML document itself

```cpp
virtual void Aspose::Slides::Export::EmbedAllFontsHtmlController::WriteFont(System::SharedPtr<IHtmlGenerator> generator, System::SharedPtr<IFontData> originalFont, System::SharedPtr<IFontData> substitutedFont, System::String fontStyle, System::String fontWeight, System::ArrayPtr<uint8_t> fontData)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| generator | [System::SharedPtr](../../../system/sharedptr/)\<[IHtmlGenerator](../../ihtmlgenerator/)\> | HTML 생성기 |
| originalFont | [System::SharedPtr](../../../system/sharedptr/)\<[IFontData](../../../aspose.slides/ifontdata/)\> | 직렬화할 글꼴 |
| substitutedFont | [System::SharedPtr](../../../system/sharedptr/)\<[IFontData](../../../aspose.slides/ifontdata/)\> | 대체 글꼴(글꼴 대체가 발생한 경우), null otherwise |
| fontStyle | [System::String](../../../system/string/) | 글꼴 스타일 |
| fontWeight | [System::String](../../../system/string/) | 글꼴 굵기 |
| fontData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 글꼴 데이터 |

## 참조

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 타입정의 [ArrayPtr](../../../system/arrayptr/)
* 클래스 [IHtmlGenerator](../../ihtmlgenerator/)
* 클래스 [IFontData](../../../aspose.slides/ifontdata/)
* 클래스 [String](../../../system/string/)
* 클래스 [EmbedAllFontsHtmlController](../)
* 네임스페이스 [Aspose::Slides::Export](../../)
* 라이브러리 [Aspose.Slides](../../../)