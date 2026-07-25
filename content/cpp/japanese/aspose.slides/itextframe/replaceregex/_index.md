---
title: ReplaceRegex()
second_title: Aspose.Slides for C++ API リファレンス
description: 正規表現のすべての一致を指定された文字列に置き換えます。
type: docs
weight: 157
url: /ja/aspose.slides/itextframe/replaceregex/
---
## ITextFrame::ReplaceRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::String, System::SharedPtr\<IFindResultCallback\>) メソッド

正規表現のすべての一致を指定された文字列に置き換えます。

```cpp
virtual void Aspose::Slides::ITextFrame::ReplaceRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::String newText, System::SharedPtr<IFindResultCallback> callback)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | 置換対象文字列を取得する正規表現 [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)。 |
| newText | [System::String](../../../system/string/) | 置換対象文字列のすべての出現を置換する文字列。 |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | 検索結果 [IFindResultCallback](../../ifindresultcallback/) を受け取るためのコールバックオブジェクト。 |

## 備考

次のコードサンプルは、正規表現を使用してテキストを指定された文字列で置換する方法を示しています。 ```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");

// Replace all words with 10 or more characters with '<em><strong>'
shape->get_TextFrame()->ReplaceRegex(regex, u"</strong></em>", nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [Regex](../../../system.text.regularexpressions/regex/)
* クラス [String](../../../system/string/)
* クラス [IFindResultCallback](../../ifindresultcallback/)
* クラス [ITextFrame](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)