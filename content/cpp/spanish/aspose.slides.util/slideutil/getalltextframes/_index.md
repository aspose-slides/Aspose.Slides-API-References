---
title: GetAllTextFrames()
second_title: Referencia de API de Aspose.Slides para C++
description: Devuelve todos los marcos de texto en una presentación PPTX.
type: docs
weight: 79
url: /es/aspose.slides.util/slideutil/getalltextframes/
---
## SlideUtil::GetAllTextFrames(System::SharedPtr\<IPresentation\>, bool) method

Devuelve todos los marcos de texto en una presentación PPTX.

```cpp
static System::ArrayPtr<System::SharedPtr<ITextFrame>> Aspose::Slides::Util::SlideUtil::GetAllTextFrames(System::SharedPtr<IPresentation> pres, bool withMasters)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[IPresentation](../../../aspose.slides/ipresentation/)\> | Presentación escaneada. |
| withMasters | **bool** | Determina si se deben escanear las diapositivas maestras. |

### Valor de retorno

Matriz de objetos [TextFrame](../../../aspose.slides/textframe/).

## Véase también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [ITextFrame](../../../aspose.slides/itextframe/)
* Clase [IPresentation](../../../aspose.slides/ipresentation/)
* Clase [SlideUtil](../)
* Espacio de nombres [Aspose::Slides::Util](../../)
* Biblioteca [Aspose.Slides](../../../)