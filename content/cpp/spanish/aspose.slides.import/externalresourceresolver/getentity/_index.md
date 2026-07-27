---
title: GetEntity()
second_title: Referencia de API de Aspose.Slides para C++
description: Asocia un URI a un objeto que contiene el recurso real.
type: docs
weight: 14
url: /es/aspose.slides.import/externalresourceresolver/getentity/
---
## ExternalResourceResolver::GetEntity(System::String) método

Asocia un URI a un objeto que contiene el recurso real.

```cpp
System::SharedPtr<System::IO::Stream> Aspose::Slides::Import::ExternalResourceResolver::GetEntity(System::String absoluteUri) override
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| absoluteUri | [System::String](../../../system/string/) | URI absoluto del objeto. |

### Valor devuelto

Un objeto [System::IO::Stream](../../../system.io/stream/) o null si el recurso no se puede transmitir.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [Stream](../../../system.io/stream/)
* Clase [String](../../../system/string/)
* Clase [ExternalResourceResolver](../)
* Espacio de nombres [Aspose::Slides::Import](../../)
* Biblioteca [Aspose.Slides](../../../)