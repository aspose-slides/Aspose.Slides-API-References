---
title: CollectHeaders()
second_title: Aspose.Slides pro C++ API Reference
description: Nastaví interní kolekci SOAP hlaviček.
type: docs
weight: 326
url: /cs/system.web.services.protocols/soapmessage/collectheaders/
---
## SoapMessage::CollectHeaders(System::SharedPtr\<Object\>, System::ArrayPtr\<System::SharedPtr\<SoapHeaderMapping\>\>, SoapHeaderDirection) metoda

Nastaví interní kolekci SOAP hlaviček.

```cpp
void System::Web::Services::Protocols::SoapMessage::CollectHeaders(System::SharedPtr<Object> target, System::ArrayPtr<System::SharedPtr<SoapHeaderMapping>> headers, SoapHeaderDirection direction)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| target | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Objekt, ze kterého se získají SOAP hlavičky. |
| headers | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<SoapHeaderMapping\>\> | Kolekce hlaviček, ze které bude naplněna interní kolekce. |
| direction | [SoapHeaderDirection](../../soapheaderdirection/) | Směr SOAP hlavičky. |

## Viz také

* Enum [SoapHeaderDirection](../../soapheaderdirection/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Object](../../../system/object/)
* Class [SoapMessage](../)
* Namespace [System::Web::Services::Protocols](../../)
* Library [Aspose.Slides](../../../)