---
title: HighlightRegex()
second_title: Aspose.Slides for C++ APIリファレンス
description: 指定された色で正規表現のすべての一致箇所をハイライトします。
type: docs
weight: 131
url: /ja/aspose.slides/itextframe/highlightregex/
---
## ITextFrame::HighlightRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::Drawing::Color, System::SharedPtr\<IFindResultCallback\>) メソッド

指定された色で正規表現のすべての一致箇所をハイライトします。

```cpp
virtual void Aspose::Slides::ITextFrame::HighlightRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::Drawing::Color highlightColor, System::SharedPtr<IFindResultCallback> callback)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | ハイライト対象の文字列を取得する正規表現[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)。 |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | テキストをハイライトする色。 |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | 検索結果[IFindResultCallback](../../ifindresultcallback/)を受け取るコールバックオブジェクト。 |
## 備考

次のコードサンプルは、正規表現を使用して[TextFrame](../../textframe/)でテキストをハイライトする方法を示しています。 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");

// highlighting all words with 10 or more characters
shape->get_TextFrame()->HighlightRegex(regex, System::Drawing::Color::get_Blue(), nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## ITextFrame::HighlightRegex(System::String, System::Drawing::Color, System::SharedPtr\<ITextHighlightingOptions\>) メソッド

指定された色で正規表現のすべての一致箇所をハイライトします。

```cpp
virtual void Aspose::Slides::ITextFrame::HighlightRegex(System::String regex, System::Drawing::Color highlightColor, System::SharedPtr<ITextHighlightingOptions> options)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| regex | [System::String](../../../system/string/) | ハイライト対象のテキストを取得する正規表現のテキスト。 |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | テキストをハイライトする色。 |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextHighlightingOptions](../../itexthighlightingoptions/)\> | ハイライトオプション。 |

非推奨
:   代わりにHighlightRegex(Regex regex, Color highlightColor, IFindResultCallback callback)メソッドを使用してください。このメソッドはバージョン24.10のリリース後に削除されます。

## 関連項目

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [Regex](../../../system.text.regularexpressions/regex/)
* クラス [Color](../../../system.drawing/color/)
* クラス [IFindResultCallback](../../ifindresultcallback/)
* クラス [ITextFrame](../)
* クラス [String](../../../system/string/)
* クラス [ITextHighlightingOptions](../../itexthighlightingoptions/)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)