---
title: SoapClientMessage()
second_title: Aspose.Slides for C++ API 參考文件
description: 建立新的實例。
type: docs
weight: 66
url: /zh-hant/system.web.services.protocols/soapclientmessage/soapclientmessage/
---
## SoapClientMessage::SoapClientMessage(System::SharedPtr\<SoapHttpClientProtocol\>, System::SharedPtr\<SoapMethodStubInfo\>, String, System::ArrayPtr\<System::SharedPtr\<Object\>\>) 建構子

建立新的實例。

```cpp
System::Web::Services::Protocols::SoapClientMessage::SoapClientMessage(System::SharedPtr<SoapHttpClientProtocol> client, System::SharedPtr<SoapMethodStubInfo> msi, String url, System::ArrayPtr<System::SharedPtr<Object>> parameters)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| client | [System::SharedPtr](../../../system/sharedptr/)\<[SoapHttpClientProtocol](../../soaphttpclientprotocol/)\> | client 代理類別的實例。 |
| msi | [System::SharedPtr](../../../system/sharedptr/)\<SoapMethodStubInfo\> | 方法存根資訊。 |
| url | [String](../../../system/string/) | XML Web 服務的 URL。 |
| parameters | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\> | 參數的集合。 |

## 另見

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 型別定義 [ArrayPtr](../../../system/arrayptr/)
* 類別 [SoapHttpClientProtocol](../../soaphttpclientprotocol/)
* 類別 [String](../../../system/string/)
* 類別 [Object](../../../system/object/)
* 類別 [SoapClientMessage](../)
* 命名空間 [System::Web::Services::Protocols](../../)
* 函式庫 [Aspose.Slides](../../../)