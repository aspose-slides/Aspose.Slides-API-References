---
title: FormatText()
second_title: Referencia de la API de Aspose.Slides para C++
description: Esta función se llama antes de renderizar la porción de texto a SVG para permitir al usuario controlar el SVG resultante.
type: docs
weight: 1
url: /es/aspose.slides.export/isvgshapeandtextformattingcontroller/formattext/
---
## ISvgShapeAndTextFormattingController::FormatText(System::SharedPtr\<ISvgTSpan\>, System::SharedPtr\<IPortion\>, System::SharedPtr\<ITextFrame\>) método

Esta función se llama antes de renderizar la porción de texto a SVG para permitir al usuario controlar el SVG resultante.

```cpp
virtual void Aspose::Slides::Export::ISvgShapeAndTextFormattingController::FormatText(System::SharedPtr<ISvgTSpan> svgTSpan, System::SharedPtr<IPortion> portion, System::SharedPtr<ITextFrame> textFrame)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| svgTSpan | [System::SharedPtr](../../../system/sharedptr/)\<[ISvgTSpan](../../isvgtspan/)\> | Objeto para controlar la generación de tspan SVG. |
| portion | [System::SharedPtr](../../../system/sharedptr/)\<[IPortion](../../../aspose.slides/iportion/)\> | Porción fuente. |
| textFrame | [System::SharedPtr](../../../system/sharedptr/)\<[ITextFrame](../../../aspose.slides/itextframe/)\> | Marco de texto de la porción fuente. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [ISvgTSpan](../../isvgtspan/)
* Clase [IPortion](../../../aspose.slides/iportion/)
* Clase [ITextFrame](../../../aspose.slides/itextframe/)
* Clase [ISvgShapeAndTextFormattingController](../)
* Espacio de nombres [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)