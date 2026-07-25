---
title: HighlightText()
second_title: C++ 用 Aspose.Slides API リファレンス
description: 指定された色でサンプルテキストのすべての一致箇所をハイライトします。
type: docs
weight: 456
url: /ja/aspose.slides/ipresentation/highlighttext/
---
## IPresentation::HighlightText(System::String, System::Drawing::Color) メソッド


指定された色でサンプル テキストのすべての一致箇所をハイライトします。

```cpp
virtual void Aspose::Slides::IPresentation::HighlightText(System::String text, System::Drawing::Color highlightColor)=0
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | ハイライトするテキスト。 |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | テキストをハイライトする色。 |
## 備考



以下のコードサンプルは、PowerPoint プレゼンテーションでテキストをハイライトする方法を示しています。 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");

// すべての別々の 'the' の出現箇所をハイライトします
presentation->HighlightText(u"the", System::Drawing::Color::get_Violet());
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## IPresentation::HighlightText(System::String, System::Drawing::Color, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) メソッド


指定された色でサンプル テキストのすべての一致箇所をハイライトします。

```cpp
virtual void Aspose::Slides::IPresentation::HighlightText(System::String text, System::Drawing::Color highlightColor, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback)=0
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | ハイライトするテキスト。 |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | テキストをハイライトする色。 |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | テキスト検索オプション[ITextSearchOptions](../../itextsearchoptions/)。 |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | 検索結果を受け取るためのコールバックオブジェクト[IFindResultCallback](../../ifindresultcallback/)。 |
## 備考



以下のコードサンプルは、PowerPoint プレゼンテーションでテキストをハイライトする方法を示しています。 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");

auto textSearchOptions = System::MakeObject<TextSearchOptions>();
textSearchOptions->set_WholeWordsOnly(true);

// すべての別々の 'the' の出現箇所をハイライトします
presentation->HighlightText(u"the", System::Drawing::Color::get_Violet(), textSearchOptions, nullptr);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [String](../../../system/string/)
* クラス [Color](../../../system.drawing/color/)
* クラス [IPresentation](../)
* クラス [ITextSearchOptions](../../itextsearchoptions/)
* クラス [IFindResultCallback](../../ifindresultcallback/)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)