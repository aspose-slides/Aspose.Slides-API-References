---
title: HighlightText()
second_title: Aspose.Slides C++ API 참조
description: 지정된 색상으로 샘플 텍스트와 일치하는 모든 항목을 강조 표시합니다.
type: docs
weight: 456
url: /ko/aspose.slides/ipresentation/highlighttext/
---
## IPresentation::HighlightText(System::String, System::Drawing::Color) 메서드

지정된 색상으로 샘플 텍스트와 일치하는 모든 항목을 강조 표시합니다.

```cpp
virtual void Aspose::Slides::IPresentation::HighlightText(System::String text, System::Drawing::Color highlightColor)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | 강조 표시할 텍스트입니다. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | 텍스트를 강조 표시할 색상입니다. |
## 비고

다음 코드 샘플은 PowerPoint 프레젠테이션에서 텍스트를 강조 표시하는 방법을 보여줍니다. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");

// highlighting all separate 'the' occurrences
presentation->HighlightText(u"the", System::Drawing::Color::get_Violet());
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## IPresentation::HighlightText(System::String, System::Drawing::Color, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) 메서드

지정된 색상으로 샘플 텍스트와 일치하는 모든 항목을 강조 표시합니다.

```cpp
virtual void Aspose::Slides::IPresentation::HighlightText(System::String text, System::Drawing::Color highlightColor, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | 강조 표시할 텍스트입니다. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | 텍스트를 강조 표시할 색상입니다. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | 텍스트 검색 옵션 [ITextSearchOptions](../../itextsearchoptions/)입니다. |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | 검색 결과를 받기 위한 콜백 객체 [IFindResultCallback](../../ifindresultcallback/)입니다. |
## 비고

다음 코드 샘플은 PowerPoint 프레젠테이션에서 텍스트를 강조 표시하는 방법을 보여줍니다. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");

auto textSearchOptions = System::MakeObject<TextSearchOptions>();
textSearchOptions->set_WholeWordsOnly(true);

// 별개의 'the' 발생을 모두 강조
presentation->HighlightText(u"the", System::Drawing::Color::get_Violet(), textSearchOptions, nullptr);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## 관련 보기

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [String](../../../system/string/)
* 클래스 [Color](../../../system.drawing/color/)
* 클래스 [IPresentation](../)
* 클래스 [ITextSearchOptions](../../itextsearchoptions/)
* 클래스 [IFindResultCallback](../../ifindresultcallback/)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)