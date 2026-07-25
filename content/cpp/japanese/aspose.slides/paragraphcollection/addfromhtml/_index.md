---
title: AddFromHtml()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された HTML 文字列からテキストをコレクションに追加します。
type: docs
weight: 157
url: /ja/aspose.slides/paragraphcollection/addfromhtml/
---
## ParagraphCollection::AddFromHtml(System::String) メソッド

指定された HTML 文字列からテキストをコレクションに追加します。

```cpp
void Aspose::Slides::ParagraphCollection::AddFromHtml(System::String text) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | HTML テキスト。 |

## ParagraphCollection::AddFromHtml(System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) メソッド

指定された HTML 文字列からテキストをコレクションに追加します。

```cpp
void Aspose::Slides::ParagraphCollection::AddFromHtml(System::String text, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | HTML テキスト。 |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | URI を解決し、参照オブジェクトを取得するリゾルバー コールバック オブジェクト。 |
| uri | [System::String](../../../system/string/) | HTML ドキュメントを追加するための URI。相対リンクの解決に使用されます。 |

## 備考

リゾルバーを指定すると、脆弱性が発生する可能性があります。注意して使用してください。

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [String](../../../system/string/)
* クラス [ParagraphCollection](../)
* クラス [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)