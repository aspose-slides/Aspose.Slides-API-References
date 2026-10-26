---
title: ReplaceRegex()
second_title: Aspose.Slides C++ API 参考
description: 用指定的字符串替换正则表达式的所有匹配项。
type: docs
weight: 495
url: /zh/aspose.slides/ipresentation/replaceregex/
---
## IPresentation::ReplaceRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::String, System::SharedPtr\<IFindResultCallback\>) 方法


用指定的字符串替换正则表达式的所有匹配项。

```cpp
virtual void Aspose::Slides::IPresentation::ReplaceRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::String newText, System::SharedPtr<IFindResultCallback> callback)=0
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | 用于获取待替换字符串的正则表达式[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)。 |
| newText | [System::String](../../../system/string/) | 用于替换所有待替换字符串出现位置的字符串。 |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | 用于接收搜索结果[IFindResultCallback](../../ifindresultcallback/)的回调对象。 |
## 备注



下面的代码示例展示了如何使用正则表达式和指定的字符串替换文本。 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");

// Replace all words with 10 or more characters with '<em><strong>'
presentation->ReplaceRegex(regex, u"</strong></em>", nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [Regex](../../../system.text.regularexpressions/regex/)
* 类 [String](../../../system/string/)
* 类 [IFindResultCallback](../../ifindresultcallback/)
* 类 [IPresentation](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)