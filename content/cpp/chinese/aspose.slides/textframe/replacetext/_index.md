---
title: ReplaceText()
second_title: Aspose.Slides C++ API 参考
description: 将指定文本的所有出现替换为另一个指定文本。
type: docs
weight: 170
url: /zh/aspose.slides/textframe/replacetext/
---
## TextFrame::ReplaceText(System::String, System::String, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) 方法

将指定文本的所有出现替换为另一个指定文本。

```cpp
void Aspose::Slides::TextFrame::ReplaceText(System::String oldText, System::String newText, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| oldText | [System::String](../../../system/string/) | 要被替换的字符串。 |
| newText | [System::String](../../../system/string/) | 用于替换所有 oldText 出现的字符串。 |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | 文本搜索选项 [ITextSearchOptions](../../itextsearchoptions/)。 |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | 用于保存替换操作结果的回调对象 [IFindResultCallback](../../ifindresultcallback/)。 |
## 备注

以下示例代码展示了如何将一个指定字符串替换为另一个指定字符串。
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

auto textSearchOptions = System::MakeObject<TextSearchOptions>();
textSearchOptions->set_WholeWordsOnly(true);

// 将所有单独的 'the' 出现替换为 '<em><strong>'
shape->get_TextFrame()->ReplaceText(u"the", u"</strong></em>", textSearchOptions, nullptr);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## 参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [String](../../../system/string/)
* 类 [ITextSearchOptions](../../itextsearchoptions/)
* 类 [IFindResultCallback](../../ifindresultcallback/)
* 类 [TextFrame](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)