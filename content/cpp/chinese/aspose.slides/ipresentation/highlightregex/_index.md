---
title: HighlightRegex()
second_title: Aspose.Slides for C++ API 参考
description: 使用指定颜色突出显示正则表达式的所有匹配项。
type: docs
weight: 469
url: /zh/aspose.slides/ipresentation/highlightregex/
---
## IPresentation::HighlightRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::Drawing::Color, System::SharedPtr\<IFindResultCallback\>) method

使用指定颜色突出显示正则表达式的所有匹配项。

```cpp
virtual void Aspose::Slides::IPresentation::HighlightRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::Drawing::Color highlightColor, System::SharedPtr<IFindResultCallback> callback)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | 正则表达式 [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/) 用于获取要高亮的字符串。 |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | 用于高亮文本的颜色。 |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | 用于接收搜索结果 [IFindResultCallback](../../ifindresultcallback/) 的回调对象。 |
## 备注

以下代码示例展示了如何使用正则表达式在 PowerPoint [Presentation](../../presentation/) 中突出显示文本。 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");

// highlighting all words with 10 or more characters
presentation->HighlightRegex(regex, System::Drawing::Color::get_Blue(), nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## 另请参阅

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [Regex](../../../system.text.regularexpressions/regex/)
* 类 [Color](../../../system.drawing/color/)
* 类 [IFindResultCallback](../../ifindresultcallback/)
* 类 [IPresentation](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)