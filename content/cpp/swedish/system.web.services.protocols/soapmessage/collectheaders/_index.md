---
title: CollectHeaders()
second_title: Aspose.Slides för C++ API-referens
description: Ställer in den interna samlingen av SOAP-huvuden.
type: docs
weight: 326
url: /sv/system.web.services.protocols/soapmessage/collectheaders/
---
## SoapMessage::CollectHeaders(System::SharedPtr\<Object\>, System::ArrayPtr\<System::SharedPtr\<SoapHeaderMapping\>\>, SoapHeaderDirection) metod

Ställer in den interna samlingen av SOAP-huvuden.

```cpp
void System::Web::Services::Protocols::SoapMessage::CollectHeaders(System::SharedPtr<Object> target, System::ArrayPtr<System::SharedPtr<SoapHeaderMapping>> headers, SoapHeaderDirection direction)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| target | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Objektet för att hämta SOAP-huvuden från. |
| headers | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<SoapHeaderMapping\>\> | En samling av huvuden som den interna samlingen ska fyllas med. |
| direction | [SoapHeaderDirection](../../soapheaderdirection/) | Riktning för SOAP-huvudet. |

## Se även

* Enum [SoapHeaderDirection](../../soapheaderdirection/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klass [Object](../../../system/object/)
* Klass [SoapMessage](../)
* Namnrymd [System::Web::Services::Protocols](../../)
* Bibliotek [Aspose.Slides](../../../)