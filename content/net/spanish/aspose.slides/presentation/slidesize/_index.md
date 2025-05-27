---
title: SlideSize
second_title: Referencia de la API Aspose.Slides para .NET
description: Devuelve el objeto de tamaño de diapositiva. Solo lectura ISlideSizeaspose.slides/islidesize.
type: docs
weight: 250
url: /es/aspose.slides/presentation/slidesize/
---

## Propiedad Presentation.SlideSize

Devuelve el objeto de tamaño de diapositiva. Solo lectura [`ISlideSize`](../../islidesize).

```csharp
public ISlideSize SlideSize { get; }
```

### Ejemplos

El siguiente ejemplo muestra cómo cambiar el tamaño de la diapositiva en una presentación de PowerPoint.

```csharp
[C#]
using (Presentation pres = new Presentation("pres-4x3-aspect-ratio.pptx"))
{
    pres.SlideSize.SetSize(SlideSizeType.OnScreen16x9, SlideSizeScaleType.DoNotScale);
    pres.Save("pres-4x3-aspect-ratio.pptx", SaveFormat.Pptx);
}
```

El siguiente ejemplo muestra cómo establecer el tamaño de la diapositiva con respecto a la escala de contenido para una presentación de PowerPoint.

```csharp
[C#]
// Instanciar un objeto Presentation que representa un archivo de presentación
using(Presentation presentation = new Presentation("AccessSlides.pptx")) {
  using(Presentation auxPresentation = new Presentation()) {
    ISlide slide = presentation.Slides[0];
    // Establecer el tamaño de la diapositiva de las presentaciones generadas al de la fuente
    presentation.SlideSize.SetSize(540, 720, SlideSizeScaleType.EnsureFit); // Se utiliza el método SetSize para establecer el tamaño de la diapositiva con escala de contenido para garantizar el ajuste
    presentation.SlideSize.SetSize(SlideSizeType.A4Paper, SlideSizeScaleType.Maximize); // Se utiliza el método SetSize para establecer el tamaño de la diapositiva maximizando el tamaño del contenido
    // Guardar la Presentación en el disco
    auxPresentation.Save("Set_Size&Type_out.pptx", SaveFormat.Pptx);
  }
}
```

El siguiente ejemplo muestra cómo especificar tamaños de diapositivas personalizados en una presentación de PowerPoint.

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    pres.SlideSize.SetSize(780, 540, SlideSizeScaleType.DoNotScale); // Tamaño de papel A4
    pres.Save("pres-a4-slide-size.pptx", SaveFormat.Pptx);
}
```

### Ver También

* interfaz [ISlideSize](../../islidesize)
* clase [Presentation](../../presentation)
* espacio de nombres [Aspose.Slides](../../presentation)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->