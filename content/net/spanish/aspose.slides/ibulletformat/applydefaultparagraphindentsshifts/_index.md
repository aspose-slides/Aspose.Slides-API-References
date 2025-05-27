---
title: ApplyDefaultParagraphIndentsShifts
second_title: Referencia de API de Aspose.Slides para .NET
description: Establece desplazamientos predeterminados no nulos para el Indent y MarginLeft efectivos del párrafo cuando se habilitan viñetas, como lo hace PowerPoint si se habilitan viñetas/numeración de párrafos en él. Si las viñetas están deshabilitadas, simplemente restablezca el Indent y MarginLeft del párrafo como lo hace PowerPoint si se deshabilitan viñetas/numeración de párrafos en él. Los desplazamientos de sangrías se aplican en relación con el contexto actual de la viñeta - IBulletFormat.Type, .NumberedBulletStyle y FontHeight de la primera porción. Los desplazamientos de sangrías no nulas se aplican al Indent y MarginLeft efectivos del párrafo actual, haciendo que los valores resultantes sean valores locales.
type: docs
weight: 110
url: /es/aspose.slides/ibulletformat/applydefaultparagraphindentsshifts/
---

## Método IBulletFormat.ApplyDefaultParagraphIndentsShifts

Establece desplazamientos predeterminados no nulos para el Indent y MarginLeft efectivos del párrafo cuando se habilitan viñetas (como lo hace PowerPoint si se habilitan viñetas/numeración de párrafos en él). Si las viñetas están deshabilitadas, simplemente restablezca el Indent y MarginLeft del párrafo (como lo hace PowerPoint si se deshabilitan viñetas/numeración de párrafos en él). Los desplazamientos de sangrías se aplican en relación con el contexto actual de la viñeta - IBulletFormat.Type, .NumberedBulletStyle y FontHeight de la primera porción. Los desplazamientos de sangrías no nulas se aplican al Indent y MarginLeft efectivos del párrafo actual (haciéndolos valores locales).

```csharp
public void ApplyDefaultParagraphIndentsShifts()
```

### Excepciones

| excepción | condición |
| --- | --- |
| InvalidOperationException | Llamar a este método no importa y lanzará InvalidOperationException en los siguientes casos: si el objeto formateado padre no es un párrafo (por ejemplo, llamar a ITextStyle.DefaultParagraphFormat.Bullet.ApplyDefaultParagraphIndentsShifts() lanzará una excepción); o si el párrafo no se ha agregado a ninguna colección ITextFrame.Paragraphs (agregue primero); |

### Ver también

* interfaz [IBulletFormat](../../ibulletformat)
* espacio de nombres [Aspose.Slides](../../ibulletformat)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->