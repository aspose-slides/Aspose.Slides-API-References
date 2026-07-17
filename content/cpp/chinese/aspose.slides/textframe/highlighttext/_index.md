---
title: HighlightText()
second_title: Aspose.Slides for C++ API 参考
description: 使用指定颜色突出显示所有匹配的示例文本。
type: docs
weight: 131
url: /zh/aspose.slides/textframe/highlighttext/
---
## TextFrame::HighlightText(System::String, System::Drawing::Color) 方法


将所有匹配的示例文本使用指定颜色进行突出显示。

```cpp
void Aspose::Slides::TextFrame::HighlightText(System::String text, System::Drawing::Color highlightColor) override
```


### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | 要突出显示的文本示例。 |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | 用于突出显示文本的颜色。 |

## TextFrame::HighlightText(System::String, System::Drawing::Color, System::SharedPtr\<ITextHighlightingOptions\>) 方法


将所有匹配的示例文本使用指定颜色进行突出显示。

```cpp
void Aspose::Slides::TextFrame::HighlightText(System::String text, System::Drawing::Color highlightColor, System::SharedPtr<ITextHighlightingOptions> options) override
```


### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | 要突出显示的文本。 |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | 用于突出显示文本的颜色。 |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextHighlightingOptions](../../itexthighlightingoptions/)\> | 突出显示选项。 |
## 备注


已弃用
:   使用 HighlightText(string text, Color highlightColor, ITextSearchOptions options) 方法代替。该方法将在 24.10 版发布后被移除。


以下示例代码演示如何在 [TextFrame](../) 中突出显示文本。 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

// highlighting all words 'important'
shape->get_TextFrame()->HighlightText(u"title", System::Drawing::Color::get_LightBlue());

auto textHighlightOptions = System::MakeObject<TextHighlightingOptions>();
textHighlightOptions->set_WholeWordsOnly(true);

// highlighting all separate 'the' occurrences
shape->get_TextFrame()->HighlightText(u"to", System::Drawing::Color::get_Violet(), textHighlightOptions);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## TextFrame::HighlightText(System::String, System::Drawing::Color, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) 方法


将所有匹配的示例文本使用指定颜色进行突出显示。

```cpp
void Aspose::Slides::TextFrame::HighlightText(System::String text, System::Drawing::Color highlightColor, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback) override
```


### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | 要突出显示的文本。 |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | 用于突出显示文本的颜色。 |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | 文本搜索选项 [ITextSearchOptions](../../itextsearchoptions/)。 |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | 用于接收搜索结果 [IFindResultCallback](../../ifindresultcallback/) 的回调对象。 |
## 备注



以下代码示例演示如何在 [TextFrame](../) 中突出显示文本。 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

// 突出显示所有单词 'important'
shape->get_TextFrame()->HighlightText(u"important", System::Drawing::Color::get_LightBlue());

auto textSearchOptions = System::MakeObject<TextSearchOptions>();
textSearchOptions->set_WholeWordsOnly(true);

// 突出显示所有单独的 'the' 出现
shape->get_TextFrame()->HighlightText(u"the", System::Drawing::Color::get_Violet(), textSearchOptions, nullptr);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [String](../../../system/string/)
* 类 [Color](../../../system.drawing/color/)
* 类 [TextFrame](../)
* 类 [ITextHighlightingOptions](../../itexthighlightingoptions/)
* 类 [ITextSearchOptions](../../itextsearchoptions/)
* 类 [IFindResultCallback](../../ifindresultcallback/)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)