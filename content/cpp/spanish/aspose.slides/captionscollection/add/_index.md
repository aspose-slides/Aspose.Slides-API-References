---
title: Add()
second_title: Referencia de API de Aspose.Slides para C++
description: Agrega subtítulos cerrados WebVTT al final de la colección.
type: docs
weight: 27
url: /es/aspose.slides/captionscollection/add/
---
## CaptionsCollection::Add(System::String, System::String) método


Añade subtítulos cerrados WebVTT al final de la colección.

```cpp
System::SharedPtr<ICaptions> Aspose::Slides::CaptionsCollection::Add(System::String label, System::String filePath) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| label | [System::String](../../../system/string/) | La etiqueta de los subtítulos cerrados. |
| filePath | [System::String](../../../system/string/) | La ruta al archivo WebVTT. |

### Valor devuelto

La instancia [ICaptions](../../icaptions/) añadida.

## CaptionsCollection::Add(System::String, System::SharedPtr\<System::IO::Stream\>) método


Añade subtítulos cerrados WebVTT al final de la colección a partir de un flujo.

```cpp
System::SharedPtr<ICaptions> Aspose::Slides::CaptionsCollection::Add(System::String label, System::SharedPtr<System::IO::Stream> stream) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| label | [System::String](../../../system/string/) | La etiqueta de los subtítulos cerrados. |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | El flujo de entrada que contiene datos en formato WebVTT. |

### Valor devuelto

La instancia [ICaptions](../../icaptions/) añadida.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [ICaptions](../../icaptions/)
* Clase [String](../../../system/string/)
* Clase [CaptionsCollection](../)
* Clase [Stream](../../../system.io/stream/)
* Espacio de nombres [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)