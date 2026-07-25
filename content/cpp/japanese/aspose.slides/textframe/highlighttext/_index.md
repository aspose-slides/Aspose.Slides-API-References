---
title: HighlightText()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された色でサンプルテキストのすべての一致箇所をハイライトします。
type: docs
weight: 131
url: /ja/aspose.slides/textframe/highlighttext/
---
## TextFrame::HighlightText(System::String, System::Drawing::Color) メソッド

指定された色でサンプルテキストのすべての一致箇所をハイライトします。

```cpp
void Aspose::Slides::TextFrame::HighlightText(System::String text, System::Drawing::Color highlightColor) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | ハイライトするテキストサンプル。 |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | テキストをハイライトする色。 |

## TextFrame::HighlightText(System::String, System::Drawing::Color, System::SharedPtr\<ITextHighlightingOptions\>) メソッド

指定された色でサンプルテキストのすべての一致箇所をハイライトします。

```cpp
void Aspose::Slides::TextFrame::HighlightText(System::String text, System::Drawing::Color highlightColor, System::SharedPtr<ITextHighlightingOptions> options) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | ハイライトするテキスト。 |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | テキストをハイライトする色。 |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextHighlightingOptions](../../itexthighlightingoptions/)\> | ハイライトのオプション。 |

## 備考

非推奨:   代わりに HighlightText(string text, Color highlightColor, ITextSearchOptions options) メソッドを使用してください。このメソッドはバージョン 24.10 のリリース後に削除されます。

次のサンプルコードは、[TextFrame](../) でテキストをハイライトする方法を示しています。 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

// highlighting all words 'important'
shape->get_TextFrame()->HighlightText(u"title", System::Drawing::Color::get_LightBlue());

auto textHighlightOptions = System::MakeObject<TextHighlightingOptions>();
textHighlightOptions->set_WholeWordsOnly(true);

// highlighting all separate 'the' occurrences
shape->get_TextFrame()->HighlightText(u"to", System::Drawing::Color::get_Violet(), textHighlightOptions);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## TextFrame::HighlightText(System::String, System::Drawing::Color, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) メソッド

指定された色でサンプルテキストのすべての一致箇所をハイライトします。

```cpp
void Aspose::Slides::TextFrame::HighlightText(System::String text, System::Drawing::Color highlightColor, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | ハイライトするテキスト。 |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | テキストをハイライトする色。 |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | テキスト検索オプション [ITextSearchOptions](../../itextsearchoptions/)。 |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | 検索結果受信用のコールバックオブジェクト [IFindResultCallback](../../ifindresultcallback/)。 |

## 備考

次のコードサンプルは、[TextFrame](../) でテキストをハイライトする方法を示しています。 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

// 「important」単語をすべてハイライト
shape->get_TextFrame()->HighlightText(u"important", System::Drawing::Color::get_LightBlue());

auto textSearchOptions = System::MakeObject<TextSearchOptions>();
textSearchOptions->set_WholeWordsOnly(true);

// 「the」単語のすべての個別出現をハイライト
shape->get_TextFrame()->HighlightText(u"the", System::Drawing::Color::get_Violet(), textSearchOptions, nullptr);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [String](../../../system/string/)
* クラス [Color](../../../system.drawing/color/)
* クラス [TextFrame](../)
* クラス [ITextHighlightingOptions](../../itexthighlightingoptions/)
* クラス [ITextSearchOptions](../../itextsearchoptions/)
* クラス [IFindResultCallback](../../ifindresultcallback/)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)