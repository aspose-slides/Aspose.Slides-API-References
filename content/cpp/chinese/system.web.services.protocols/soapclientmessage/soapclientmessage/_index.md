---
title: SoapClientMessage()
second_title: Aspose.Slides C++ API 参考
description: 构造一个新实例。
type: docs
weight: 66
url: /zh/system.web.services.protocols/soapclientmessage/soapclientmessage/
---
## SoapClientMessage::SoapClientMessage(System::SharedPtr\<SoapHttpClientProtocol\>, System::SharedPtr\<SoapMethodStubInfo\>, String, System::ArrayPtr\<System::SharedPtr\<Object\>\>) 构造函数


构造一个新实例。

```cpp
System::Web::Services::Protocols::SoapClientMessage::SoapClientMessage(System::SharedPtr<SoapHttpClientProtocol> client, System::SharedPtr<SoapMethodStubInfo> msi, String url, System::ArrayPtr<System::SharedPtr<Object>> parameters)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| client | [System::SharedPtr](../../../system/sharedptr/)\<[SoapHttpClientProtocol](../../soaphttpclientprotocol/)\> | 客户端代理类的实例。 |
| msi | [System::SharedPtr](../../../system/sharedptr/)\<SoapMethodStubInfo\> | 方法存根信息。 |
| url | [String](../../../system/string/) | XML Web 服务的 URL。 |
| parameters | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\> | 参数的集合。 |

## 另请参见

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* 类 [SoapHttpClientProtocol](../../soaphttpclientprotocol/)
* 类 [String](../../../system/string/)
* 类 [Object](../../../system/object/)
* 类 [SoapClientMessage](../)
* 命名空间 [System::Web::Services::Protocols](../../)
* 库 [Aspose.Slides](../../../)