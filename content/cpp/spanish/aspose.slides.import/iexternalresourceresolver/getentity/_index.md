---
title: GetEntity()
second_title: Referencia de la API de Aspose.Slides para C++
description: Asocia un URI a un objeto que contiene el recurso real.
type: docs
weight: 14
url: /es/aspose.slides.import/iexternalresourceresolver/getentity/
---
## IExternalResourceResolver::GetEntity(System::String) método


Asocia un URI a un objeto que contiene el recurso real.

```cpp
virtual System::SharedPtr<System::IO::Stream> Aspose::Slides::Import::IExternalResourceResolver::GetEntity(System::String absoluteUri)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| absoluteUri | [System::String](../../../system/string/) | URI absoluta al objeto. |

### Valor devuelto

Un objeto [System::IO::Stream](../../../system.io/stream/) o null si el recurso no se puede transmitir.

## Véase también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [Stream](../../../system.io/stream/)
* Clase [String](../../../system/string/)
* Clase [IExternalResourceResolver](../)
* Espacio de nombres [Aspose::Slides::Import](../../)
* Library [Aspose.Slides](../../../)