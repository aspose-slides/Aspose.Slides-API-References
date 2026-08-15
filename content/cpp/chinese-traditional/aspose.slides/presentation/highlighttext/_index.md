---
title: HighlightText()
second_title: Aspose.Slides for C++ API 參考文件
description: 以指定的顏色突出顯示樣本文字的所有匹配項。
type: docs
weight: 495
url: /zh-hant/aspose.slides/presentation/highlighttext/
---
## Presentation::HighlightText(System::String, System::Drawing::Color) 方法

以指定的顏色突出顯示樣本文字的所有匹配項。

```cpp
void Aspose::Slides::Presentation::HighlightText(System::String text, System::Drawing::Color highlightColor) override
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | 要突出顯示的文字。 |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | 用於突出顯示文字的顏色。 |

## 備註

以下程式碼範例說明如何在 PowerPoint 簡報中突出顯示文字。 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");

// 突出顯示所有獨立的 'the' 出現
presentation->HighlightText(u"the", System::Drawing::Color::get_Violet());
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## Presentation::HighlightText(System::String, System::Drawing::Color, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) 方法

以指定的顏色突出顯示樣本文字的所有匹配項。

```cpp
void Aspose::Slides::Presentation::HighlightText(System::String text, System::Drawing::Color highlightColor, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback) override
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | 要突出顯示的文字。 |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | 用於突出顯示文字的顏色。 |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | 文字搜尋選項 [ITextSearchOptions](../../itextsearchoptions/)。 |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | 接收搜尋結果的回呼物件 [IFindResultCallback](../../ifindresultcallback/)。 |

## 備註

以下程式碼範例說明如何在 PowerPoint 簡報中突出顯示文字。 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");

auto textSearchOptions = System::MakeObject<TextSearchOptions>();
textSearchOptions->set_WholeWordsOnly(true);

// 突出顯示所有獨立的 'the' 出現
presentation->HighlightText(u"the", System::Drawing::Color::get_Violet(), textSearchOptions, nullptr);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [Color](../../../system.drawing/color/)
* Class [Presentation](../)
* Class [ITextSearchOptions](../../itextsearchoptions/)
* Class [IFindResultCallback](../../ifindresultcallback/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)