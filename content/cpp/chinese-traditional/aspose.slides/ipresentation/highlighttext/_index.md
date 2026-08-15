---
title: HighlightText()
second_title: Aspose.Slides for C++ API 參考
description: 以指定的顏色突顯樣本文字的所有匹配項。
type: docs
weight: 456
url: /zh-hant/aspose.slides/ipresentation/highlighttext/
---
## IPresentation::HighlightText(System::String, System::Drawing::Color) 方法


以指定的顏色突顯樣本文字的所有匹配項。

```cpp
virtual void Aspose::Slides::IPresentation::HighlightText(System::String text, System::Drawing::Color highlightColor)=0
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | 要標記的文字。 |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | 要用來標記文字的顏色。 |
## 備註



以下程式碼範例示範如何在 PowerPoint 簡報中標記文字。 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");

// 突顯所有單獨的 'the' 出現
presentation->HighlightText(u"the", System::Drawing::Color::get_Violet());
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## IPresentation::HighlightText(System::String, System::Drawing::Color, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) 方法


以指定的顏色突顯樣本文字的所有匹配項。

```cpp
virtual void Aspose::Slides::IPresentation::HighlightText(System::String text, System::Drawing::Color highlightColor, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback)=0
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | 要標記的文字。 |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | 要用來標記文字的顏色。 |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | 文字搜尋選項 [ITextSearchOptions](../../itextsearchoptions/)。 |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | 接收搜尋結果的回呼物件 [IFindResultCallback](../../ifindresultcallback/)。 |
## 備註



以下程式碼範例示範如何在 PowerPoint 簡報中標記文字。 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");

auto textSearchOptions = System::MakeObject<TextSearchOptions>();
textSearchOptions->set_WholeWordsOnly(true);

// 突顯所有單獨的 'the' 出現
presentation->HighlightText(u"the", System::Drawing::Color::get_Violet(), textSearchOptions, nullptr);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## 另請參閱

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [String](../../../system/string/)
* 類別 [Color](../../../system.drawing/color/)
* 類別 [IPresentation](../)
* 類別 [ITextSearchOptions](../../itextsearchoptions/)
* 類別 [IFindResultCallback](../../ifindresultcallback/)
* 命名空間 [Aspose::Slides](../../)
* 程式庫 [Aspose.Slides](../../../)