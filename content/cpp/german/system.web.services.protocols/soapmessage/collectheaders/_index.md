---
title: CollectHeaders()
second_title: Aspose.Slides für C++ API-Referenz
description: Legt die interne Sammlung der SOAP-Header fest.
type: docs
weight: 326
url: /de/system.web.services.protocols/soapmessage/collectheaders/
---
## SoapMessage::CollectHeaders(System::SharedPtr\<Object\>, System::ArrayPtr\<System::SharedPtr\<SoapHeaderMapping\>\>, SoapHeaderDirection) method


Legt die interne Sammlung der SOAP-Header fest.

```cpp
void System::Web::Services::Protocols::SoapMessage::CollectHeaders(System::SharedPtr<Object> target, System::ArrayPtr<System::SharedPtr<SoapHeaderMapping>> headers, SoapHeaderDirection direction)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| target | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Das Objekt, aus dem die SOAP-Header abgerufen werden. |
| headers | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<SoapHeaderMapping\>\> | Eine Sammlung von Headern, aus der die interne Sammlung gefüllt wird. |
| direction | [SoapHeaderDirection](../../soapheaderdirection/) | Die Richtung des SOAP-Headers. |

## Siehe auch

* Enum [SoapHeaderDirection](../../soapheaderdirection/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [Object](../../../system/object/)
* Klasse [SoapMessage](../)
* Namensraum [System::Web::Services::Protocols](../../)
* Bibliothek [Aspose.Slides](../../../)