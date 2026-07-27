---
title: GetTextBoxesContainsText()
second_title: Referencia de la API de Aspose.Slides para C++
description: Devuelve todos los marcos de texto en la diapositiva especificada que contienen el texto dado.
type: docs
weight: 66
url: /es/aspose.slides.util/slideutil/gettextboxescontainstext/
---
## SlideUtil::GetTextBoxesContainsText(System::SharedPtr\<IBaseSlide\>, System::String, bool) método


Devuelve todos los marcos de texto en la diapositiva especificada que contienen el texto dado.

```cpp
static System::ArrayPtr<System::SharedPtr<ITextFrame>> Aspose::Slides::Util::SlideUtil::GetTextBoxesContainsText(System::SharedPtr<IBaseSlide> slide, System::String text, bool checkPlaceholderText)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../../../aspose.slides/ibaseslide/)\> | La diapositiva en la que buscar. |
| text | [System::String](../../../system/string/) | El texto a buscar dentro de los marcos de texto. |
| checkPlaceholderText | **bool** | Indica si se deben incluir los marcos de texto que están vacíos, pero cuyo texto de marcador de posición contiene el texto buscado. |

### Valor devuelto

Una matriz de objetos [ITextFrame](../../../aspose.slides/itextframe/) que contienen el texto especificado.

## Véase también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [ITextFrame](../../../aspose.slides/itextframe/)
* Clase [IBaseSlide](../../../aspose.slides/ibaseslide/)
* Clase [String](../../../system/string/)
* Clase [SlideUtil](../)
* Espacio de nombres [Aspose::Slides::Util](../../)
* Biblioteca [Aspose.Slides](../../../)