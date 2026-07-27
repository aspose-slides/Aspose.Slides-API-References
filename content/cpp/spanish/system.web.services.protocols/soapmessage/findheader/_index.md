---
title: FindHeader()
second_title: Referencia de API de Aspose.Slides para C++
description: Encuentra el mapeo del encabezado por el tipo de encabezado especificado.
type: docs
weight: 352
url: /es/system.web.services.protocols/soapmessage/findheader/
---
## SoapMessage::FindHeader(System::ArrayPtr\<System::SharedPtr\<SoapHeaderMapping\>\>, const TypeInfo\&) método


Encuentra el mapeo del encabezado por el tipo de encabezado especificado.

```cpp
System::SharedPtr<SoapHeaderMapping> System::Web::Services::Protocols::SoapMessage::FindHeader(System::ArrayPtr<System::SharedPtr<SoapHeaderMapping>> headersInfo, const TypeInfo &headerType)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| headersInfo | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<SoapHeaderMapping\>\> | La colección de los mapeos de encabezado. |
| headerType | const [TypeInfo](../../../system/typeinfo/)\& | El tipo de encabezado a buscar. |

### Valor de retorno

El mapeo del encabezado.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Clase [TypeInfo](../../../system/typeinfo/)
* Clase [SoapMessage](../)
* Espacio de nombres [System::Web::Services::Protocols](../../)
* Library [Aspose.Slides](../../../)