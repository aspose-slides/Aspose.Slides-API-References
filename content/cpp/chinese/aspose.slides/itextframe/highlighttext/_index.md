---
title: HighlightText()
second_title: Aspose.Slides for C++ API 参考
description: 使用指定颜色突出显示示例文本的所有匹配项。
type: docs
weight: 105
url: /zh/aspose.slides/itextframe/highlighttext/
---
## ITextFrame::HighlightText(System::String, System::Drawing::Color) 方法

将示例文本的所有匹配项使用指定颜色进行突出显示。

```cpp
virtual void Aspose::Slides::ITextFrame::HighlightText(System::String text, System::Drawing::Color highlightColor)=0
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | 要突出显示的文本。 |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | 用于突出显示文本的颜色。 |

## ITextFrame::HighlightText(System::String, System::Drawing::Color, System::SharedPtr\<ITextHighlightingOptions\>) 方法

将示例文本的所有匹配项使用指定颜色进行突出显示。

```cpp
virtual void Aspose::Slides::ITextFrame::HighlightText(System::String text, System::Drawing::Color highlightColor, System::SharedPtr<ITextHighlightingOptions> options)=0
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | 要突出显示的文本。 |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | 用于突出显示文本的颜色。 |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextHighlightingOptions](../../itexthighlightingoptions/)\> | 突出显示选项。 |

已弃用
:   请改用 HighlightText(string text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback) 方法。该方法将在 24.10 版发布后被移除。

## ITextFrame::HighlightText(System::String, System::Drawing::Color, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) 方法

将示例文本的所有匹配项使用指定颜色进行突出显示。

```cpp
virtual void Aspose::Slides::ITextFrame::HighlightText(System::String text, System::Drawing::Color highlightColor, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback)=0
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | 要突出显示的文本。 |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | 用于突出显示文本的颜色。 |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | 文本搜索选项 [ITextSearchOptions](../../itextsearchoptions/)。 |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | 用于接收搜索结果的回调对象 [IFindResultCallback](../../ifindresultcallback/)。 |

## 备注

以下代码示例展示了如何在 [TextFrame](../../textframe/) 中突出显示文本。 
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

## 另请参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [String](../../../system/string/)
* 类 [Color](../../../system.drawing/color/)
* 类 [ITextFrame](../)
* 类 [ITextHighlightingOptions](../../itexthighlightingoptions/)
* 类 [ITextSearchOptions](../../itextsearchoptions/)
* 类 [IFindResultCallback](../../ifindresultcallback/)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)