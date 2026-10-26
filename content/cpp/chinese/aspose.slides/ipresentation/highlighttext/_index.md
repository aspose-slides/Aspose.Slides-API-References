---
title: HighlightText()
second_title: Aspose.Slides C++ API 参考
description: 使用指定的颜色突出显示示例文本的所有匹配项。
type: docs
weight: 456
url: /zh/aspose.slides/ipresentation/highlighttext/
---
## IPresentation::HighlightText(System::String, System::Drawing::Color) 方法

使用指定的颜色突出显示示例文本的所有匹配项。

```cpp
virtual void Aspose::Slides::IPresentation::HighlightText(System::String text, System::Drawing::Color highlightColor)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | 要突出显示的文本。 |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | 用于突出显示文本的颜色。 |

## 备注

以下代码示例展示了如何在 PowerPoint 演示文稿中突出显示文本。 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");

// highlighting all separate 'the' occurrences
presentation->HighlightText(u"the", System::Drawing::Color::get_Violet());
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## IPresentation::HighlightText(System::String, System::Drawing::Color, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) 方法

使用指定的颜色突出显示示例文本的所有匹配项。

```cpp
virtual void Aspose::Slides::IPresentation::HighlightText(System::String text, System::Drawing::Color highlightColor, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | 要突出显示的文本。 |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | 用于突出显示文本的颜色。 |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | 文本搜索选项 [ITextSearchOptions](../../itextsearchoptions/)。 |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | 用于接收搜索结果 [IFindResultCallback](../../ifindresultcallback/) 的回调对象。 |

## 备注

以下代码示例展示了如何在 PowerPoint 演示文稿中突出显示文本。 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");

auto textSearchOptions = System::MakeObject<TextSearchOptions>();
textSearchOptions->set_WholeWordsOnly(true);

// 突出显示所有单独的 'the' 出现
presentation->HighlightText(u"the", System::Drawing::Color::get_Violet(), textSearchOptions, nullptr);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## 另请参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [String](../../../system/string/)
* 类 [Color](../../../system.drawing/color/)
* 类 [IPresentation](../)
* 类 [ITextSearchOptions](../../itextsearchoptions/)
* 类 [IFindResultCallback](../../ifindresultcallback/)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)