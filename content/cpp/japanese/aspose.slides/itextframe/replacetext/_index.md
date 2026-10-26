---
title: ReplaceText()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたテキストのすべての出現箇所を別の指定されたテキストに置き換えます。
type: docs
weight: 144
url: /ja/aspose.slides/itextframe/replacetext/
---
## ITextFrame::ReplaceText(System::String, System::String, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) メソッド

指定されたテキストのすべての出現箇所を別の指定されたテキストに置換します。

```cpp
virtual void Aspose::Slides::ITextFrame::ReplaceText(System::String oldText, System::String newText, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| oldText | [System::String](../../../system/string/) | 置換される文字列です。 |
| newText | [System::String](../../../system/string/) | oldText のすべての出現箇所を置換する文字列です。 |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | テキスト検索オプション [ITextSearchOptions](../../itextsearchoptions/)。 |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | 検索結果を受け取るコールバックオブジェクト [IFindResultCallback](../../ifindresultcallback/)です。 |
## 備考

以下のサンプルコードは、指定された文字列を別の指定された文字列に置換する方法を示しています。
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

auto textSearchOptions = System::MakeObject<TextSearchOptions>();
textSearchOptions->set_WholeWordsOnly(true);

// すべての単独の 'the' の出現箇所を '<em><strong>' に置換します
shape->get_TextFrame()->ReplaceText(u"the", u"</strong></em>", textSearchOptions, nullptr);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [String](../../../system/string/)
* クラス [ITextSearchOptions](../../itextsearchoptions/)
* クラス [IFindResultCallback](../../ifindresultcallback/)
* クラス [ITextFrame](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)