---
title: ReplaceRegex()
second_title: Aspose.Slides 的 C++ API 參考
description: 將正則表達式的所有匹配項取代為指定的字串。
type: docs
weight: 495
url: /zh-hant/aspose.slides/ipresentation/replaceregex/
---
## IPresentation::ReplaceRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::String, System::SharedPtr\<IFindResultCallback\>) 方法

使用指定的字串取代正規表達式的所有匹配項。

```cpp
virtual void Aspose::Slides::IPresentation::ReplaceRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::String newText, System::SharedPtr<IFindResultCallback> callback)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | 正則表達式 [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/) 用於取得要取代的字串。 |
| newText | [System::String](../../../system/string/) | 用於取代所有要被取代的字串之字串。 |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | 接收搜尋結果 [IFindResultCallback](../../ifindresultcallback/) 的回呼物件。 |

## 備註

以下程式碼範例示範如何使用正規表達式搭配指定的字串取代文字。

```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");

// Replace all words with 10 or more characters with '<em><strong>'
presentation->ReplaceRegex(regex, u"</strong></em>", nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## 相關參考

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [Regex](../../../system.text.regularexpressions/regex/)
* 類別 [String](../../../system/string/)
* 類別 [IFindResultCallback](../../ifindresultcallback/)
* 類別 [IPresentation](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)