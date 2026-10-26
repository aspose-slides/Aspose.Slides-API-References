---
title: HighlightRegex()
second_title: Aspose.Slides for C++ API 参考
description: 使用指定的颜色突出显示正则表达式的所有匹配项。
type: docs
weight: 157
url: /zh/aspose.slides/textframe/highlightregex/
---
## TextFrame::HighlightRegex(System::String, System::Drawing::Color, System::SharedPtr\<ITextHighlightingOptions\>) 方法

使用指定的颜色突出显示正则表达式的所有匹配项。

```cpp
void Aspose::Slides::TextFrame::HighlightRegex(System::String regex, System::Drawing::Color highlightColor, System::SharedPtr<ITextHighlightingOptions> options) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| regex | [System::String](../../../system/string/) | 用于获取要突出显示的文本的正则表达式。 |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | 用于突出显示文本的颜色。 |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextHighlightingOptions](../../itexthighlightingoptions/)\> | 高亮选项。 |
## 备注

已弃用
:   Use HighlightRegex(Regex regex, Color highlightColor, IFindResultCallback callback) method instead. The method will be removed after release of version 24.10.
改用 HighlightRegex(Regex regex, Color highlightColor, IFindResultCallback callback) 方法。该方法将在版本 24.10 发布后移除。

以下代码示例演示了如何在 [TextFrame](../) 中使用正则表达式突出显示文本。

```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

auto options = System::MakeObject<TextHighlightingOptions>();

// 突出显示所有长度为10个或更多字符的单词
shape->get_TextFrame()->HighlightRegex(u"\\b[^\\s]{10,}\\b", System::Drawing::Color::get_Blue(), options);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## TextFrame::HighlightRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::Drawing::Color, System::SharedPtr\<IFindResultCallback\>) 方法

使用指定的颜色突出显示正则表达式的所有匹配项。

```cpp
void Aspose::Slides::TextFrame::HighlightRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::Drawing::Color highlightColor, System::SharedPtr<IFindResultCallback> callback) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | 用于获取要突出显示的字符串的正则表达式 [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)。 |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | 用于突出显示文本的颜色。 |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | 用于接收搜索结果 [IFindResultCallback](../../ifindresultcallback/) 的回调对象。 |
## 备注



以下代码示例演示了如何在 [TextFrame](../) 中使用正则表达式突出显示文本。

```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");
// 突出显示所有长度为10个或更多字符的单词
shape->get_TextFrame()->HighlightRegex(regex, System::Drawing::Color::get_Blue(), nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [String](../../../system/string/)
* 类 [Color](../../../system.drawing/color/)
* 类 [ITextHighlightingOptions](../../itexthighlightingoptions/)
* 类 [TextFrame](../)
* 类 [Regex](../../../system.text.regularexpressions/regex/)
* 类 [IFindResultCallback](../../ifindresultcallback/)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)