---
title: ReplaceRegex()
second_title: Aspose.Slides for C++ API 參考
description: 將正則表達式的所有匹配項替換為指定的字串。
type: docs
weight: 183
url: /zh-hant/aspose.slides/textframe/replaceregex/
---
## TextFrame::ReplaceRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::String, System::SharedPtr\<IFindResultCallback\>) 方法

將正則表達式的所有匹配項替換為指定的字串。

```cpp
void Aspose::Slides::TextFrame::ReplaceRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::String newText, System::SharedPtr<IFindResultCallback> callback) override
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | 正則表達式 [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/) 用於取得要替換的字串。 |
| newText | [System::String](../../../system/string/) | 用於將所有要替換的字串替換為此字串。 |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | 用於儲存取代操作結果 [IFindResultCallback](../../ifindresultcallback/) 的回呼物件。 |

## 備註

以下範例程式碼示範如何使用正則表達式搭配指定的字串進行文字取代。 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");

// Replace all words with 10 or more characters with '<em><strong>'
shape->get_TextFrame()->ReplaceRegex(regex, u"</strong></em>", nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## 另請參閱

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [Regex](../../../system.text.regularexpressions/regex/)
* 類別 [String](../../../system/string/)
* 類別 [IFindResultCallback](../../ifindresultcallback/)
* 類別 [TextFrame](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)