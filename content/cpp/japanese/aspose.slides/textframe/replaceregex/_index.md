---
title: ReplaceRegex()
second_title: Aspose.Slides for C++ API リファレンス
description: 正規表現に一致するすべての文字列を指定された文字列に置き換えます。
type: docs
weight: 183
url: /ja/aspose.slides/textframe/replaceregex/
---
## TextFrame::ReplaceRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::String, System::SharedPtr\<IFindResultCallback\>) method


正規表現に一致するすべての文字列を指定された文字列に置き換えます。

```cpp
void Aspose::Slides::TextFrame::ReplaceRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::String newText, System::SharedPtr<IFindResultCallback> callback) override
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | 置換対象の文字列を取得する正規表現[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)です。 |
| newText | [System::String](../../../system/string/) | 置換対象の文字列のすべての出現箇所を置き換える文字列です。 |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | 置換操作の結果[IFindResultCallback](../../ifindresultcallback/)を保存するためのコールバックオブジェクトです。 |
## 備考



以下のサンプルコードは、正規表現を使用してテキストを指定された文字列に置き換える方法を示しています。 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");

// Replace all words with 10 or more characters with '<em><strong>'
shape->get_TextFrame()->ReplaceRegex(regex, u"</strong></em>", nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [Regex](../../../system.text.regularexpressions/regex/)
* クラス [String](../../../system/string/)
* クラス [IFindResultCallback](../../ifindresultcallback/)
* クラス [TextFrame](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)