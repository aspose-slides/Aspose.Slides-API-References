---
title: CollectHeaders()
second_title: Riferimento API Aspose.Slides per C++
description: Imposta la raccolta interna delle intestazioni SOAP.
type: docs
weight: 326
url: /it/system.web.services.protocols/soapmessage/collectheaders/
---
## SoapMessage::CollectHeaders(System::SharedPtr\<Object\>, System::ArrayPtr\<System::SharedPtr\<SoapHeaderMapping\>\>, SoapHeaderDirection) method


Imposta la raccolta interna delle intestazioni SOAP.

```cpp
void System::Web::Services::Protocols::SoapMessage::CollectHeaders(System::SharedPtr<Object> target, System::ArrayPtr<System::SharedPtr<SoapHeaderMapping>> headers, SoapHeaderDirection direction)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| target | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | L'oggetto da cui ottenere le intestazioni SOAP. |
| headers | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<SoapHeaderMapping\>\> | Una raccolta di intestazioni dalla quale verrà riempita la collezione interna. |
| direction | [SoapHeaderDirection](../../soapheaderdirection/) | La direzione dell'intestazione SOAP. |

## Vedi anche

* Enum [SoapHeaderDirection](../../soapheaderdirection/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [Object](../../../system/object/)
* Classe [SoapMessage](../)
* Namespace [System::Web::Services::Protocols](../../)
* Libreria [Aspose.Slides](../../../)