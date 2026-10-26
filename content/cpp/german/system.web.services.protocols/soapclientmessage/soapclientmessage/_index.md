---
title: SoapClientMessage()
second_title: Aspose.Slides für C++ API Referenz
description: Konstruiert eine neue Instanz.
type: docs
weight: 66
url: /de/system.web.services.protocols/soapclientmessage/soapclientmessage/
---
## SoapClientMessage::SoapClientMessage(System::SharedPtr\<SoapHttpClientProtocol\>, System::SharedPtr\<SoapMethodStubInfo\>, String, System::ArrayPtr\<System::SharedPtr\<Object\>\>) Konstruktor

Konstruiert eine neue Instanz.

```cpp
System::Web::Services::Protocols::SoapClientMessage::SoapClientMessage(System::SharedPtr<SoapHttpClientProtocol> client, System::SharedPtr<SoapMethodStubInfo> msi, String url, System::ArrayPtr<System::SharedPtr<Object>> parameters)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| client | [System::SharedPtr](../../../system/sharedptr/)\<[SoapHttpClientProtocol](../../soaphttpclientprotocol/)\> | Eine Instanz der Client-Proxy-Klasse. |
| msi | [System::SharedPtr](../../../system/sharedptr/)\<SoapMethodStubInfo\> | Information zum Method-Stub. |
| url | [String](../../../system/string/) | Die URL eines XML-Webdienstes. |
| parameters | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\> | Eine Sammlung von Parametern. |

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [SoapHttpClientProtocol](../../soaphttpclientprotocol/)
* Klasse [String](../../../system/string/)
* Klasse [Object](../../../system/object/)
* Klasse [SoapClientMessage](../)
* Namensraum [System::Web::Services::Protocols](../../)
* Bibliothek [Aspose.Slides](../../../)