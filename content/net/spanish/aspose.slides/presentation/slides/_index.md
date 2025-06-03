---
title: Slides
second_title: Referencia de API de Aspose.Slides para .NET
description: Devuelve una lista de todas las diapositivas que están definidas en la presentación. Solo lectura ISlideCollectionaspose.slides/islidecollection.
type: docs
weight: 230
url: /es/aspose.slides/presentation/slides/
---

## Propiedad Presentation.Slides

Devuelve una lista de todas las diapositivas que están definidas en la presentación. Solo lectura [`ISlideCollection`](../../islidecollection).

```csharp
public ISlideCollection Slides { get; }
```

### Ejemplos

El siguiente ejemplo muestra cómo establecer el color de fondo de las diapositivas de una presentación de PowerPoint.

```csharp
[C#]
// Instanciar la clase Presentation que representa el archivo de la presentación
using (Presentation pres = new Presentation())
{
    // Establecer el color de fondo de la primera ISlide en Azul
    pres.Slides[0].Background.Type = BackgroundType.OwnBackground;
    pres.Slides[0].Background.FillFormat.FillType = FillType.Solid;
    pres.Slides[0].Background.FillFormat.SolidFillColor.Color = Color.Blue;
    pres.Save("ContentBG_out.pptx", SaveFormat.Pptx);
}
```

El siguiente ejemplo muestra cómo establecer la imagen de fondo de las diapositivas de una presentación de PowerPoint.

```csharp
[C#]
// Instanciar la clase Presentation que representa el archivo de la presentación
using (Presentation pres = new Presentation("SetImageAsBackground.pptx"))
{
    // Establecer el fondo con una imagen
    pres.Slides[0].Background.Type = BackgroundType.OwnBackground;
    pres.Slides[0].Background.FillFormat.FillType = FillType.Picture;
    pres.Slides[0].Background.FillFormat.PictureFillFormat.PictureFillMode = PictureFillMode.Stretch;
    // Establecer la imagen
    System.Drawing.Image img = (System.Drawing.Image)new Bitmap(dataDir + "Tulips.jpg");
    // Agregar imagen a la colección de imágenes de la presentación
    IPPImage imgx = pres.Images.AddImage(img);
    pres.Slides[0].Background.FillFormat.PictureFillFormat.Picture.Image = imgx;
    // Escribir la presentación en disco
    pres.Save("ContentBG_Img_out.pptx", SaveFormat.Pptx);
}
```

El siguiente ejemplo muestra cómo agregar la transición de diapositiva a la presentación.

```csharp
[C#]
// Instanciar la clase Presentation para cargar el archivo de presentación fuente
using (Presentation presentation = new Presentation("AccessSlides.pptx"))
{
    // Aplicar transición de tipo círculo en la diapositiva 1
    presentation.Slides[0].SlideShowTransition.Type = TransitionType.Circle;
    // Aplicar transición de tipo combinación en la diapositiva 2
    presentation.Slides[1].SlideShowTransition.Type = TransitionType.Comb;
    // Escribir la presentación en disco
    presentation.Save("SampleTransition_out.pptx", SaveFormat.Pptx);
}
```

El siguiente ejemplo muestra cómo agregar una transición avanzada de diapositiva.

```csharp
[C#]
// Instanciar la clase Presentation que representa un archivo de presentación
using (Presentation pres = new Presentation("BetterSlideTransitions.pptx"))
{
    // Aplicar transición de tipo círculo en la diapositiva 1
    pres.Slides[0].SlideShowTransition.Type = TransitionType.Circle;
    // Establecer el tiempo de transición en 3 segundos
    pres.Slides[0].SlideShowTransition.AdvanceOnClick = true;
    pres.Slides[0].SlideShowTransition.AdvanceAfterTime = 3000;
    // Aplicar transición de tipo combinación en la diapositiva 2
    pres.Slides[1].SlideShowTransition.Type = TransitionType.Comb;
    // Establecer el tiempo de transición en 5 segundos
    pres.Slides[1].SlideShowTransition.AdvanceOnClick = true;
    pres.Slides[1].SlideShowTransition.AdvanceAfterTime = 5000;
    // Aplicar transición de tipo zoom en la diapositiva 3
    pres.Slides[2].SlideShowTransition.Type = TransitionType.Zoom;
    // Establecer el tiempo de transición en 7 segundos
    pres.Slides[2].SlideShowTransition.AdvanceOnClick = true;
    pres.Slides[2].SlideShowTransition.AdvanceAfterTime = 7000;
    // Escribir la presentación en disco
    pres.Save("SampleTransition_out.pptx", SaveFormat.Pptx);
}
```

### Véase También

* interfaz [ISlideCollection](../../islidecollection)
* clase [Presentation](../../presentation)
* espacio de nombres [Aspose.Slides](../../presentation)
* ensamblaje [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->