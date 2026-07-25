---
title: SoapClientMessage()
second_title: Aspose.Slides for C++ API リファレンス
description: 新しいインスタンスを作成します。
type: docs
weight: 66
url: /ja/system.web.services.protocols/soapclientmessage/soapclientmessage/
---
## SoapClientMessage::SoapClientMessage(System::SharedPtr\<SoapHttpClientProtocol\>, System::SharedPtr\<SoapMethodStubInfo\>, String, System::ArrayPtr\<System::SharedPtr\<Object\>\>) constructor

新しいインスタンスを作成します。

```cpp
System::Web::Services::Protocols::SoapClientMessage::SoapClientMessage(System::SharedPtr<SoapHttpClientProtocol> client, System::SharedPtr<SoapMethodStubInfo> msi, String url, System::ArrayPtr<System::SharedPtr<Object>> parameters)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| client | [System::SharedPtr](../../../system/sharedptr/)\<[SoapHttpClientProtocol](../../soaphttpclientprotocol/)\> | クライアントプロキシクラスのインスタンス。 |
| msi | [System::SharedPtr](../../../system/sharedptr/)\<SoapMethodStubInfo\> | メソッドスタブ情報。 |
| url | [String](../../../system/string/) | XML Web サービスの URL。 |
| parameters | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\> | パラメータのコレクション。 |

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* クラス [SoapHttpClientProtocol](../../soaphttpclientprotocol/)
* クラス [String](../../../system/string/)
* クラス [Object](../../../system/object/)
* クラス [SoapClientMessage](../)
* 名前空間 [System::Web::Services::Protocols](../../)
* Library [Aspose.Slides](../../../)