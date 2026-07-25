---
title: GetUrl()
second_title: Aspose.Slides for C++ API リファレンス
description: "外部オブジェクトへの URL を返します。このメソッドは ILinkEmbedController::GetObjectStoringLocation が LinkEmbedDecision::Link を返した場合に常に呼び出され、ILinkEmbedController::GetObjectStoringLocation が LinkEmbedDecision::Embed を返した場合に呼び出されることがありますが、埋め込みは不可能です。同じオブジェクト ID に対して複数回呼び出すことができます。"
type: docs
weight: 14
url: /ja/aspose.slides.export/ilinkembedcontroller/geturl/
---
## ILinkEmbedController::GetUrl(int32_t, int32_t) メソッド

外部オブジェクトへの URL を返します。このメソッドは [ILinkEmbedController::GetObjectStoringLocation](../getobjectstoringlocation/) が [LinkEmbedDecision::Link](../../linkembeddecision/) を返した場合に常に呼び出され、[ILinkEmbedController::GetObjectStoringLocation](../getobjectstoringlocation/) が [LinkEmbedDecision::Embed](../../linkembeddecision/) を返した場合に呼び出されることがありますが、埋め込みは不可能です。同じオブジェクト ID に対して複数回呼び出すことができます。

```cpp
virtual System::String Aspose::Slides::Export::ILinkEmbedController::GetUrl(int32_t id, int32_t referrer)=0
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| id | **int32_t** | オブジェクト ID。この ID は操作全体で一意です。 |
| referrer | **int32_t** | 参照元オブジェクトの ID または 0（オブジェクトがルート ドキュメントによって参照されている場合）。相対リンクの生成に使用できる場合があります。 |

### 戻り値

外部オブジェクトの Url、またはこのオブジェクトを無視すべき場合は null を返します。

## 参照

* クラス [String](../../../system/string/)
* クラス [ILinkEmbedController](../)
* 名前空間 [Aspose::Slides::Export](../../)
* ライブラリ [Aspose.Slides](../../../)