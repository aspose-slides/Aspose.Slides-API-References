---
title: CollectHeaders()
second_title: Aspose.Slides for C++ API リファレンス
description: SOAP ヘッダーの内部コレクションを設定します。
type: docs
weight: 326
url: /ja/system.web.services.protocols/soapmessage/collectheaders/
---
## SoapMessage::CollectHeaders(System::SharedPtr\<Object\>, System::ArrayPtr\<System::SharedPtr\<SoapHeaderMapping\>\>, SoapHeaderDirection) メソッド

SOAP ヘッダーの内部コレクションを設定します。

```cpp
void System::Web::Services::Protocols::SoapMessage::CollectHeaders(System::SharedPtr<Object> target, System::ArrayPtr<System::SharedPtr<SoapHeaderMapping>> headers, SoapHeaderDirection direction)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| target | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | SOAP ヘッダーを取得する対象オブジェクトです。 |
| headers | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<SoapHeaderMapping\>\> | 内部コレクションが埋められるヘッダーのコレクションです。 |
| direction | [SoapHeaderDirection](../../soapheaderdirection/) | SOAP ヘッダーの方向です。 |

## 参照

* Enum [SoapHeaderDirection](../../soapheaderdirection/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Object](../../../system/object/)
* Class [SoapMessage](../)
* Namespace [System::Web::Services::Protocols](../../)
* Library [Aspose.Slides](../../../)