---
title: HighlightRegex()
second_title: Aspose.Slides for C++ API リファレンス
description: 正規表現のすべての一致箇所を指定された色でハイライトします。
type: docs
weight: 157
url: /ja/aspose.slides/textframe/highlightregex/
---
## TextFrame::HighlightRegex(System::String, System::Drawing::Color, System::SharedPtr\<ITextHighlightingOptions\>) メソッド

正規表現のすべての一致箇所を指定された色でハイライトします。

```cpp
void Aspose::Slides::TextFrame::HighlightRegex(System::String regex, System::Drawing::Color highlightColor, System::SharedPtr<ITextHighlightingOptions> options) override
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| regex | [System::String](../../../system/string/) | ハイライトするテキストを取得するための正規表現のテキスト。 |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | テキストをハイライトする色。 |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextHighlightingOptions](../../itexthighlightingoptions/)\> | ハイライトのオプション。 |
## 備考

非推奨
:   代わりに HighlightRegex(Regex regex, Color highlightColor, IFindResultCallback callback) メソッドを使用してください。このメソッドはバージョン 24.10 のリリース後に削除されます。

次のコードサンプルは、正規表現を使用して [TextFrame](../) のテキストをハイライトする方法を示しています。 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

auto options = System::MakeObject<TextHighlightingOptions>();

// 10文字以上の単語をすべてハイライト
shape->get_TextFrame()->HighlightRegex(u"\\b[^\\s]{10,}\\b", System::Drawing::Color::get_Blue(), options);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## TextFrame::HighlightRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::Drawing::Color, System::SharedPtr\<IFindResultCallback\>) メソッド

正規表現のすべての一致箇所を指定された色でハイライトします。

```cpp
void Aspose::Slides::TextFrame::HighlightRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::Drawing::Color highlightColor, System::SharedPtr<IFindResultCallback> callback) override
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | ハイライトする文字列を取得するための正規表現 [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)。 |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | テキストをハイライトする色。 |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | 検索結果 [IFindResultCallback](../../ifindresultcallback/) を受け取るためのコールバックオブジェクト。 |
## 備考



次のコードサンプルは、正規表現を使用して [TextFrame](../) のテキストをハイライトする方法を示しています。 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");
// 10文字以上の単語をすべてハイライト
shape->get_TextFrame()->HighlightRegex(regex, System::Drawing::Color::get_Blue(), nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## 関連項目

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [String](../../../system/string/)
* クラス [Color](../../../system.drawing/color/)
* クラス [ITextHighlightingOptions](../../itexthighlightingoptions/)
* クラス [TextFrame](../)
* クラス [Regex](../../../system.text.regularexpressions/regex/)
* クラス [IFindResultCallback](../../ifindresultcallback/)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)