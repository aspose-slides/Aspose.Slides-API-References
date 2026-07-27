---
title: Add()
second_title: Referencia de la API de Aspose.Slides para C++
description: Añade subtítulos cerrados WebVTT al final de la colección.
type: docs
weight: 27
url: /es/aspose.slides/icaptionscollection/add/
---
## ICaptionsCollection::Add(System::String, System::String) método


Añade subtítulos cerrados WebVTT al final de la colección.

```cpp
virtual System::SharedPtr<ICaptions> Aspose::Slides::ICaptionsCollection::Add(System::String label, System::String filePath)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| label | [System::String](../../../system/string/) | La etiqueta de los subtítulos cerrados. |
| filePath | [System::String](../../../system/string/) | La ruta al archivo WebVTT. |

### Valor devuelto

La instancia [ICaptions](../../icaptions/) añadida.

## ICaptionsCollection::Add(System::String, System::SharedPtr\<System::IO::Stream\>) método


Añade subtítulos cerrados WebVTT al final de la colección desde un flujo.

```cpp
virtual System::SharedPtr<ICaptions> Aspose::Slides::ICaptionsCollection::Add(System::String label, System::SharedPtr<System::IO::Stream> stream)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| label | [System::String](../../../system/string/) | La etiqueta de los subtítulos cerrados. |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | El flujo de entrada que contiene datos en formato WebVTT. |

### Valor devuelto

La instancia [ICaptions](../../icaptions/) añadida.

## Véase también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [ICaptions](../../icaptions/)
* Clase [String](../../../system/string/)
* Clase [ICaptionsCollection](../)
* Clase [Stream](../../../system.io/stream/)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)