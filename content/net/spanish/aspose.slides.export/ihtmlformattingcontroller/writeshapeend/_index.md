---
title: WriteShapeEnd
second_title: Referencia de API de Aspose.Slides para .NET
description: Llamado antes de renderizar formas. Se llama una vez por cada forma. Si esta función escribe algo en el generador, la generación de la imagen de la diapositiva actual se finalizará, se insertará el fragmento html añadido y se comenzará una nueva imagen encima de la anterior.
type: docs
weight: 30
url: /es/aspose.slides.export/ihtmlformattingcontroller/writeshapeend/
---

## Método IHtmlFormattingController.WriteShapeEnd

Llamado antes de renderizar la forma. Se llama una vez por cada forma. Si esta función escribe algo en el generador, la generación de la imagen de la diapositiva actual se finalizará, se insertará el fragmento html añadido y se comenzará una nueva imagen encima de la anterior.

```csharp
public void WriteShapeEnd(IHtmlGenerator generator, IShape shape)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| generator | IHtmlGenerator | Objeto de salida. |
| shape | IShape | Forma que se renderiza al final. |

### Véase También

* interfaz [IHtmlGenerator](../../ihtmlgenerator)
* interfaz [IShape](../../../aspose.slides/ishape)
* interfaz [IHtmlFormattingController](../../ihtmlformattingcontroller)
* espacio de nombres [Aspose.Slides.Export](../../ihtmlformattingcontroller)
* ensamblaje [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->