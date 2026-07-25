---
title: AddFromHtml()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたHTML文字列からテキストをコレクションに追加します。
type: docs
weight: 92
url: /ja/aspose.slides/iparagraphcollection/addfromhtml/
---
## IParagraphCollection::AddFromHtml(System::String) メソッド

指定されたHTML文字列からテキストをコレクションに追加します。

```cpp
virtual void Aspose::Slides::IParagraphCollection::AddFromHtml(System::String text)=0
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | HTMLテキスト。 |

## IParagraphCollection::AddFromHtml(System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) メソッド

指定されたHTML文字列からテキストをコレクションに追加します。

```cpp
virtual void Aspose::Slides::IParagraphCollection::AddFromHtml(System::String text, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | HTMLテキスト。 |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | リゾルバーコールバックオブジェクトで、URI を解決し参照されたオブジェクトを取得します。 |
| uri | [System::String](../../../system/string/) | HTML ドキュメントを追加するための URI。相対リンクの解決に使用されます。 |

## 備考

リゾルバーを指定すると脆弱性が発生する可能性があります。注意して使用してください。

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [String](../../../system/string/)
* クラス [IParagraphCollection](../)
* クラス [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)