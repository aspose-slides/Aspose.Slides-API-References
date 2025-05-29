---
title: ApplyDefaultParagraphIndentsShifts
second_title: Referencia de API de Aspose.Slides para .NET
description: Establece desplazamientos predeterminados distintos de cero para el sangrado efectivo de párrafos y MarginLeft cuando se habilitan viñetas, como lo hace PowerPoint si se habilitan las viñetas/numeración de párrafos en él. Si las viñetas están deshabilitadas, entonces simplemente restablece el sangrado de párrafos y MarginLeft como lo hace PowerPoint si se deshabilitan las viñetas/numeración de párrafos en él. Los desplazamientos de indentación se aplican en relación con el contexto de viñeta actual - IBulletFormat.Type .NumberedBulletStyle y FontHeight de la primera porción. Se aplican desplazamientos de indentación distintos de cero al sangrado efectivo y MarginLeft del párrafo actual, haciendo que los valores resultantes sean valores locales.
type: docs
weight: 110
url: /es/aspose.slides/bulletformat/applydefaultparagraphindentsshifts/
---

## Método BulletFormat.ApplyDefaultParagraphIndentsShifts

Establece desplazamientos predeterminados distintos de cero para el sangrado efectivo de párrafos y MarginLeft cuando se habilitan viñetas (como lo hace PowerPoint si se habilitan las viñetas/numeración de párrafos en él). Si las viñetas están deshabilitadas, entonces simplemente restablece el sangrado de párrafos y MarginLeft (como lo hace PowerPoint si se deshabilitan las viñetas/numeración de párrafos en él). Los desplazamientos de indentación se aplican en relación con el contexto de viñeta actual - IBulletFormat.Type, .NumberedBulletStyle y FontHeight de la primera porción. Se aplican desplazamientos de indentación distintos de cero al sangrado efectivo y MarginLeft del párrafo actual (haciendo que los valores resultantes sean valores locales).

```csharp
public void ApplyDefaultParagraphIndentsShifts()
```

### Excepciones

| excepción | condición |
| --- | --- |
| InvalidOperationException | Llamar a este método no tiene importancia y lanza InvalidOperationException en los siguientes casos: si el objeto formateado padre no es un párrafo (por ejemplo, llamar a ITextStyle.DefaultParagraphFormat.Bullet.ApplyDefaultParagraphIndentsShifts() lanzará una excepción); o si el párrafo no se agregó a ninguna colección ITextFrame.Paragraphs (añádalo primero); |

### Véase también

* clase [BulletFormat](../../bulletformat)
* espacio de nombres [Aspose.Slides](../../bulletformat)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->