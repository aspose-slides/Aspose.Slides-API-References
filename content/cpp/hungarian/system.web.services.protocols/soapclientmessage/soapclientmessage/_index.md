---
title: SoapClientMessage()
second_title: Aspose.Slides C++ API referencia
description: Új példányt hoz létre.
type: docs
weight: 66
url: /hu/system.web.services.protocols/soapclientmessage/soapclientmessage/
---
## SoapClientMessage::SoapClientMessage(System::SharedPtr\<SoapHttpClientProtocol\>, System::SharedPtr\<SoapMethodStubInfo\>, String, System::ArrayPtr\<System::SharedPtr\<Object\>\>) konstruktor

Új példányt hoz létre.

```cpp
System::Web::Services::Protocols::SoapClientMessage::SoapClientMessage(System::SharedPtr<SoapHttpClientProtocol> client, System::SharedPtr<SoapMethodStubInfo> msi, String url, System::ArrayPtr<System::SharedPtr<Object>> parameters)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| client | [System::SharedPtr](../../../system/sharedptr/)\<[SoapHttpClientProtocol](../../soaphttpclientprotocol/)\> | A kliens proxy osztály egy példánya. |
| msi | [System::SharedPtr](../../../system/sharedptr/)\<SoapMethodStubInfo\> | A metódus stub információ. |
| url | [String](../../../system/string/) | Az XML webszolgáltatás URL-je. |
| parameters | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\> | Paraméterek gyűjteménye. |

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [SoapHttpClientProtocol](../../soaphttpclientprotocol/)
* Class [String](../../../system/string/)
* Class [Object](../../../system/object/)
* Class [SoapClientMessage](../)
* Namespace [System::Web::Services::Protocols](../../)
* Library [Aspose.Slides](../../../)