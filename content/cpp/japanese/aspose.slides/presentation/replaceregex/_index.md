---
title: ReplaceRegex()
second_title: Aspose.Slides for C++ API リファレンス
description: 正規表現のすべての一致箇所を指定された文字列に置換します。
type: docs
weight: 534
url: /ja/aspose.slides/presentation/replaceregex/
---
## Presentation::ReplaceRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::String, System::SharedPtr\<IFindResultCallback\>) method

正規表現のすべての一致箇所を指定された文字列に置換します。

```cpp
void Aspose::Slides::Presentation::ReplaceRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::String newText, System::SharedPtr<IFindResultCallback> callback) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | 置換対象文字列を取得するための正規表現 [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)。 |
| newText | [System::String](../../../system/string/) | 置換対象文字列のすべての出現箇所を置換する文字列。 |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | 検索結果 [IFindResultCallback](../../ifindresultcallback/) を受け取るためのコールバックオブジェクト。 |

## 備考

以下のコードサンプルは、正規表現を使用してテキストを指定された文字列で置換する方法を示しています。
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");

// Replace all words with 10 or more characters with '<em><strong>'
presentation->ReplaceRegex(regex, u"</strong></em>", nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [Regex](../../../system.text.regularexpressions/regex/)
* クラス [String](../../../system/string/)
* クラス [IFindResultCallback](../../ifindresultcallback/)
* クラス [Presentation](../)
* 名前空間 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)