---
title: FillFormat
second_title: Aspose.Slides para .NET Referencia de API
description: Devuelve el formato de relleno del viñeta de un párrafo. Solo lectura IFillFormatEffectiveDataaspose.slides/ifillformateffectivedata.
type: docs
weight: 30
url: /es/aspose.slides/ibulletformateffectivedata/fillformat/
---

## Propiedad IBulletFormatEffectiveData.FillFormat

Devuelve el formato de relleno del viñeta de un párrafo. Solo lectura [`IFillFormatEffectiveData`](../../ifillformateffectivedata).

```csharp
public IFillFormatEffectiveData FillFormat { get; }
```

### Ejemplos

Este ejemplo demuestra la recuperación de los datos efectivos de relleno de la viñeta.

```csharp
[C#]
using (Presentation pres = new Presentation("SomePresentation.pptx"))
{
    // Suponga que la primera forma en la primera diapositiva es una AutoShape con algún texto...
    // Salida de información sobre las viñetas de los párrafos de texto
    AutoShape autoShape = (AutoShape)pres.Slides[0].Shapes[0];
    foreach (Paragraph para in autoShape.TextFrame.Paragraphs)
    {
        IBulletFormatEffectiveData bulletFormatEffective = para.ParagraphFormat.Bullet.GetEffective();
        Console.WriteLine("Tipo de viñeta: " + bulletFormatEffective.Type);
        if (bulletFormatEffective.Type != BulletType.None)
        {
            Console.WriteLine("Tipo de relleno de viñeta: " + bulletFormatEffective.FillFormat.FillType);
            switch (bulletFormatEffective.FillFormat.FillType)
            {
                case FillType.Solid:
                    Console.WriteLine("Color de relleno sólido: " + bulletFormatEffective.FillFormat.SolidFillColor);
                    break;
                case FillType.Gradient:
                    Console.WriteLine("Cantidad de paradas de gradiente: " + bulletFormatEffective.FillFormat.GradientFormat.GradientStops.Count);
                    foreach (IGradientStopEffectiveData gradStop in bulletFormatEffective.FillFormat.GradientFormat.GradientStops)
                        Console.WriteLine(gradStop.Position + ": " + gradStop.Color);
                    break;
                case FillType.Pattern:
                    Console.WriteLine("Estilo de patrón: " + bulletFormatEffective.FillFormat.PatternFormat.PatternStyle);
                    Console.WriteLine("Color frontal: " + bulletFormatEffective.FillFormat.PatternFormat.ForeColor);
                    Console.WriteLine("Color de fondo: " + bulletFormatEffective.FillFormat.PatternFormat.BackColor);
                    break;
            }
        }
        Console.WriteLine();
    }
}
```

### Véase también

* interfaz [IFillFormatEffectiveData](../../ifillformateffectivedata)
* interfaz [IBulletFormatEffectiveData](../../ibulletformateffectivedata)
* espacio de nombres [Aspose.Slides](../../ibulletformateffectivedata)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->