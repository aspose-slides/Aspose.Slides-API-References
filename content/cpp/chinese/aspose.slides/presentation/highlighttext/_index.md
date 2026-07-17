---
title: HighlightText()
second_title: Aspose.Slides C++ API 参考
description: 使用指定颜色突出显示所有匹配的示例文本。
type: docs
weight: 495
url: /zh/aspose.slides/presentation/highlighttext/
---
## Presentation::HighlightText(System::String, System::Drawing::Color) 方法

突出显示所有匹配的示例文本，使用指定的颜色。

```cpp
void Aspose::Slides::Presentation::HighlightText(System::String text, System::Drawing::Color highlightColor) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | 要突出显示的文本。 |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | 用于突出显示文本的颜色。 |
## 备注

下面的代码示例展示了如何在 PowerPoint 演示文稿中突出显示文本。 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");

// 突出显示所有单独的 'the' 出现
presentation->HighlightText(u"the", System::Drawing::Color::get_Violet());
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## Presentation::HighlightText(System::String, System::Drawing::Color, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) 方法

突出显示所有匹配的示例文本，使用指定的颜色。

```cpp
void Aspose::Slides::Presentation::HighlightText(System::String text, System::Drawing::Color highlightColor, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | 要突出显示的文本。 |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | 用于突出显示文本的颜色。 |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | 文本搜索选项[ITextSearchOptions](../../itextsearchoptions/)。 |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | 用于接收搜索结果[IFindResultCallback](../../ifindresultcallback/)的回调对象。 |
## 备注

下面的代码示例展示了如何在 PowerPoint 演示文稿中突出显示文本。 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");

auto textSearchOptions = System::MakeObject<TextSearchOptions>();
textSearchOptions->set_WholeWordsOnly(true);

// 突出显示所有单独的 'the' 出现
presentation->HighlightText(u"the", System::Drawing::Color::get_Violet(), textSearchOptions, nullptr);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [String](../../../system/string/)
* 类 [Color](../../../system.drawing/color/)
* 类 [Presentation](../)
* 类 [ITextSearchOptions](../../itextsearchoptions/)
* 类 [IFindResultCallback](../../ifindresultcallback/)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)