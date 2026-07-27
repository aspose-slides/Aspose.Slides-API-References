---
title: GetPresentationInfo()
second_title: Referencia de la API de Aspose.Slides para C++
description: Obtiene información sobre la presentación en el archivo especificado.
type: docs
weight: 14
url: /es/aspose.slides/ipresentationfactory/getpresentationinfo/
---
## IPresentationFactory::GetPresentationInfo(System::String) método


Obtiene información sobre la presentación en el archivo especificado.

```cpp
virtual System::SharedPtr<IPresentationInfo> Aspose::Slides::IPresentationFactory::GetPresentationInfo(System::String file)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | [Presentation](../../presentation/) archivo. |

### Valor de retorno

[Presentation](../../presentation/) información

## IPresentationFactory::GetPresentationInfo(System::SharedPtr\<System::IO::Stream\>) método


Obtiene información sobre la presentación en el flujo especificado.

```cpp
virtual System::SharedPtr<IPresentationInfo> Aspose::Slides::IPresentationFactory::GetPresentationInfo(System::SharedPtr<System::IO::Stream> stream)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | [Presentation](../../presentation/) flujo. |

### Valor de retorno

[Presentation](../../presentation/) información.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IPresentationInfo](../../ipresentationinfo/)
* Clase [String](../../../system/string/)
* Clase [IPresentationFactory](../)
* Clase [Stream](../../../system.io/stream/)
* Espacio de nombres [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)