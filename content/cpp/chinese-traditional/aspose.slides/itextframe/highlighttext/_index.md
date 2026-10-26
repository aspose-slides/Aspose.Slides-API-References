---
title: HighlightText()
second_title: Aspose.Slides for C++ API 參考
description: 將樣本文字的所有匹配項以指定的顏色加亮。
type: docs
weight: 105
url: /zh-hant/aspose.slides/itextframe/highlighttext/
---
## ITextFrame::HighlightText(System::String, System::Drawing::Color) 方法

將樣本文字的所有匹配項以指定的顏色加亮。

```cpp
virtual void Aspose::Slides::ITextFrame::HighlightText(System::String text, System::Drawing::Color highlightColor)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | 要加亮的文字。 |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | 用於加亮文字的顏色。 |

## ITextFrame::HighlightText(System::String, System::Drawing::Color, System::SharedPtr\<ITextHighlightingOptions\>) 方法

將樣本文字的所有匹配項以指定的顏色加亮。

```cpp
virtual void Aspose::Slides::ITextFrame::HighlightText(System::String text, System::Drawing::Color highlightColor, System::SharedPtr<ITextHighlightingOptions> options)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | 要加亮的文字。 |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | 用於加亮文字的顏色。 |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextHighlightingOptions](../../itexthighlightingoptions/)\> | 加亮選項。 |

已棄用  
:   請改用 HighlightText(string text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback) 方法。此方法將在版本 24.10 發布後移除。

## ITextFrame::HighlightText(System::String, System::Drawing::Color, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) 方法

將樣本文字的所有匹配項以指定的顏色加亮。

```cpp
virtual void Aspose::Slides::ITextFrame::HighlightText(System::String text, System::Drawing::Color highlightColor, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | 要加亮的文字。 |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | 用於加亮文字的顏色。 |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | 文字搜尋選項 [ITextSearchOptions](../../itextsearchoptions/)。 |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | 用於接收搜尋結果 [IFindResultCallback](../../ifindresultcallback/) 的回呼物件。 |

## 備註

以下程式碼範例示範如何在 [TextFrame](../../textframe/) 中加亮文字。  
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

// highlighting all words 'important'
shape->get_TextFrame()->HighlightText(u"important", System::Drawing::Color::get_LightBlue());

auto textSearchOptions = System::MakeObject<TextSearchOptions>();
textSearchOptions->set_WholeWordsOnly(true);

// highlighting all separate 'the' occurrences
shape->get_TextFrame()->HighlightText(u"the", System::Drawing::Color::get_Violet(), textSearchOptions, nullptr);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## 另請參閱

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [String](../../../system/string/)
* 類別 [Color](../../../system.drawing/color/)
* 類別 [ITextFrame](../)
* 類別 [ITextHighlightingOptions](../../itexthighlightingoptions/)
* 類別 [ITextSearchOptions](../../itextsearchoptions/)
* 類別 [IFindResultCallback](../../ifindresultcallback/)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)