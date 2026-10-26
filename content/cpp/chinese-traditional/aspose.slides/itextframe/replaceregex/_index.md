---
title: ReplaceRegex()
second_title: Aspose.Slides for C++ API 參考文件
description: 將正則表達式的所有匹配項目取代為指定的字串。
type: docs
weight: 157
url: /zh-hant/aspose.slides/itextframe/replaceregex/
---
## ITextFrame::ReplaceRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::String, System::SharedPtr\<IFindResultCallback\>) 方法

將正規表達式的所有匹配項目取代為指定的字串。

```cpp
virtual void Aspose::Slides::ITextFrame::ReplaceRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::String newText, System::SharedPtr<IFindResultCallback> callback)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | 正則表達式 [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/) 用於取得要取代的字串。 |
| newText | [System::String](../../../system/string/) | 用於取代所有待取代字串的字串。 |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | 接收搜尋結果 [IFindResultCallback](../../ifindresultcallback/) 的回呼物件。 |

## 備註

以下程式碼範例示範如何使用正則表達式搭配指定的字串來取代文字。 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");

// Replace all words with 10 or more characters with '<em><strong>'
shape->get_TextFrame()->ReplaceRegex(regex, u"</strong></em>", nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## 另請參閱

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [Regex](../../../system.text.regularexpressions/regex/)
* 類別 [String](../../../system/string/)
* 類別 [IFindResultCallback](../../ifindresultcallback/)
* 類別 [ITextFrame](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)