---
title: CollectHeaders()
second_title: Referencia de la API de Aspose.Slides para C++
description: Establece la colección interna de los encabezados SOAP.
type: docs
weight: 326
url: /es/system.web.services.protocols/soapmessage/collectheaders/
---
## SoapMessage::CollectHeaders(System::SharedPtr\<Object\>, System::ArrayPtr\<System::SharedPtr\<SoapHeaderMapping\>\>, SoapHeaderDirection) método

Establece la colección interna de los encabezados SOAP.

```cpp
void System::Web::Services::Protocols::SoapMessage::CollectHeaders(System::SharedPtr<Object> target, System::ArrayPtr<System::SharedPtr<SoapHeaderMapping>> headers, SoapHeaderDirection direction)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| target | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | El objeto del que se obtienen los encabezados SOAP. |
| headers | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<SoapHeaderMapping\>\> | Una colección de encabezados a partir de la cual se rellenará la colección interna. |
| direction | [SoapHeaderDirection](../../soapheaderdirection/) | La dirección del encabezado SOAP. |

## Ver también

* Enum [SoapHeaderDirection](../../soapheaderdirection/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Object](../../../system/object/)
* Class [SoapMessage](../)
* Namespace [System::Web::Services::Protocols](../../)
* Library [Aspose.Slides](../../../)