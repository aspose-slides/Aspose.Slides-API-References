---
title: ReplaceText()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたテキストのすべての出現箇所を、別の指定したテキストに置換します。
type: docs
weight: 521
url: /ja/aspose.slides/presentation/replacetext/
---
## Presentation::ReplaceText(System::String, System::String, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) メソッド


置き換えられるテキストのすべての出現箇所を、別の指定したテキストに置換します。

```cpp
void Aspose::Slides::Presentation::ReplaceText(System::String oldText, System::String newText, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback) override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| oldText | [System::String](../../../system/string/) | 置換される文字列です。 |
| newText | [System::String](../../../system/string/) | oldText のすべての出現箇所を置換する文字列です。 |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | テキスト検索オプション [ITextSearchOptions](../../itextsearchoptions/)。 |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | 検索結果を受け取るコールバックオブジェクト [IFindResultCallback](../../ifindresultcallback/)。 |
## 備考



以下のサンプルコードは、指定された文字列を別の指定された文字列に置換する方法を示しています。 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");

auto textSearchOptions = System::MakeObject<TextSearchOptions>();
textSearchOptions->set_WholeWordsOnly(true);

// すべての単独の 'the' の出現箇所を '<em><strong>' に置き換えます
presentation->ReplaceText(u"the", u"</strong></em>", textSearchOptions, nullptr);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [ITextSearchOptions](../../itextsearchoptions/)
* Class [IFindResultCallback](../../ifindresultcallback/)
* Class [Presentation](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)