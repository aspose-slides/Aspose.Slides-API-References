---
title: ReplaceRegex()
second_title: Aspose.Slides C++ API 参考
description: 使用指定的字符串替换正则表达式的所有匹配项。
type: docs
weight: 183
url: /zh/aspose.slides/textframe/replaceregex/
---
## TextFrame::ReplaceRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::String, System::SharedPtr\<IFindResultCallback\>) 方法

使用指定的字符串替换正则表达式的所有匹配项。

```cpp
void Aspose::Slides::TextFrame::ReplaceRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::String newText, System::SharedPtr<IFindResultCallback> callback) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | 用于获取待替换字符串的正则表达式[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)。 |
| newText | [System::String](../../../system/string/) | 用于替换所有待替换字符串出现的字符串。 |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | 用于保存替换操作结果[IFindResultCallback](../../ifindresultcallback/)的回调对象。 |
## 备注



以下示例代码展示了如何使用正则表达式和指定的字符串替换文本。 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");

// Replace all words with 10 or more characters with '<em><strong>'
shape->get_TextFrame()->ReplaceRegex(regex, u"</strong></em>", nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## 另请参阅

* 类型别名 [SharedPtr](../../../system/sharedptr/)
* 类 [Regex](../../../system.text.regularexpressions/regex/)
* 类 [String](../../../system/string/)
* 类 [IFindResultCallback](../../ifindresultcallback/)
* 类 [TextFrame](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)