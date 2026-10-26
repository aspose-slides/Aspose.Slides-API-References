---
title: GetPresentationInfo()
second_title: Referencia de API de Aspose.Slides para C++
description: Crea un nuevo objeto PresentationInfo a partir del archivo y enlaza la presentación a él.
type: docs
weight: 27
url: /es/aspose.slides/presentationfactory/getpresentationinfo/
---
## PresentationFactory::GetPresentationInfo(System::String) método

Crea un nuevo objeto [PresentationInfo](../../presentationinfo/) a partir del archivo y enlaza la presentación a él.

```cpp
System::SharedPtr<IPresentationInfo> Aspose::Slides::PresentationFactory::GetPresentationInfo(System::String file) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | [Presentation](../../presentation/) archivo. |

### Valor de retorno

[Presentation](../../presentation/) información vinculada a la presentación.

## PresentationFactory::GetPresentationInfo(System::SharedPtr\<System::IO::Stream\>) método

Crea un nuevo objeto [PresentationInfo](../../presentationinfo/) a partir del flujo y enlaza la presentación a él. Obtiene información sobre la presentación en el flujo especificado.

```cpp
System::SharedPtr<IPresentationInfo> Aspose::Slides::PresentationFactory::GetPresentationInfo(System::SharedPtr<System::IO::Stream> stream) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | [Presentation](../../presentation/) flujo. |

### Valor de retorno

[Presentation](../../presentation/) información vinculada a la presentación.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IPresentationInfo](../../ipresentationinfo/)
* Clase [String](../../../system/string/)
* Clase [PresentationFactory](../)
* Clase [Stream](../../../system.io/stream/)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)