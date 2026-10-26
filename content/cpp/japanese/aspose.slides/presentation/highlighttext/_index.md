---
title: HighlightText()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された色でサンプルテキストのすべての一致箇所を強調表示します。
type: docs
weight: 495
url: /ja/aspose.slides/presentation/highlighttext/
---
## Presentation::HighlightText(System::String, System::Drawing::Color) メソッド

指定された色でサンプルテキストのすべての一致箇所を強調表示します。

```cpp
void Aspose::Slides::Presentation::HighlightText(System::String text, System::Drawing::Color highlightColor) override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | ハイライトするテキスト。 |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | テキストをハイライトする色。 |
## 備考

以下のコードサンプルは、PowerPoint プレゼンテーションでテキストをハイライトする方法を示しています。 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");

// highlighting all separate 'the' occurrences
presentation->HighlightText(u"the", System::Drawing::Color::get_Violet());
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## Presentation::HighlightText(System::String, System::Drawing::Color, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) メソッド

指定された色でサンプルテキストのすべての一致箇所を強調表示します。

```cpp
void Aspose::Slides::Presentation::HighlightText(System::String text, System::Drawing::Color highlightColor, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback) override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | ハイライトするテキスト。 |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | テキストをハイライトする色。 |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | テキスト検索オプション [ITextSearchOptions](../../itextsearchoptions/)。 |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | 検索結果を受け取るコールバックオブジェクト [IFindResultCallback](../../ifindresultcallback/)。 |
## 備考

以下のコードサンプルは、PowerPoint プレゼンテーションでテキストをハイライトする方法を示しています。 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");

auto textSearchOptions = System::MakeObject<TextSearchOptions>();
textSearchOptions->set_WholeWordsOnly(true);

// 個別の 'the' のすべての出現箇所をハイライト
presentation->HighlightText(u"the", System::Drawing::Color::get_Violet(), textSearchOptions, nullptr);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [String](../../../system/string/)
* クラス [Color](../../../system.drawing/color/)
* クラス [Presentation](../)
* クラス [ITextSearchOptions](../../itextsearchoptions/)
* クラス [IFindResultCallback](../../ifindresultcallback/)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)