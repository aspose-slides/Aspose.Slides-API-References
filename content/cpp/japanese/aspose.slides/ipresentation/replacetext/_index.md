---
title: ReplaceText()
second_title: Aspose.Slides for C++ APIリファレンス
description: 指定されたテキストのすべての出現箇所を、別の指定されたテキストに置き換えます。
type: docs
weight: 482
url: /ja/aspose.slides/ipresentation/replacetext/
---
## IPresentation::ReplaceText(System::String, System::String, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) method


指定されたテキストのすべての出現箇所を別の指定されたテキストに置き換えます。

```cpp
virtual void Aspose::Slides::IPresentation::ReplaceText(System::String oldText, System::String newText, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback)=0
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| oldText | [System::String](../../../system/string/) | 置き換えられる文字列。 |
| newText | [System::String](../../../system/string/) | oldText のすべての出現箇所を置き換える文字列。 |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | テキスト検索オプション [ITextSearchOptions](../../itextsearchoptions/)。 |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | 検索結果を受け取るためのコールバック オブジェクト [IFindResultCallback](../../ifindresultcallback/)。 |
## 備考



以下のサンプルコードは、ある指定文字列を別の指定文字列に置き換える方法を示しています。
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");

auto textSearchOptions = System::MakeObject<TextSearchOptions>();
textSearchOptions->set_WholeWordsOnly(true);

// すべての単独の 'the' の出現箇所を '<em><strong>' に置き換える
presentation->ReplaceText(u"the", u"</strong></em>", textSearchOptions, nullptr);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [ITextSearchOptions](../../itextsearchoptions/)
* Class [IFindResultCallback](../../ifindresultcallback/)
* Class [IPresentation](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)