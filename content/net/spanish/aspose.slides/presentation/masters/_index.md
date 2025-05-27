---
title: Maestros
second_title: Referencia de API de Aspose.Slides para .NET
description: Devuelve una lista de todas las diapositivas maestras que están definidas en la presentación. Colección IMasterSlideCollection de solo lectura aspose.slides/imasterslidecollection.
type: docs
weight: 180
url: /es/aspose.slides/presentation/masters/
---

## Propiedad Presentation.Masters

Devuelve una lista de todas las diapositivas maestras que están definidas en la presentación. Colección de solo lectura [`IMasterSlideCollection`](../../imasterslidecollection).

```csharp
public IMasterSlideCollection Masters { get; }
```

### Ejemplos

El siguiente ejemplo muestra cómo agregar imágenes a las diapositivas maestras de una presentación de PowerPoint.

```csharp
[C#]
using (Presentation pres = new Presentation())
{
    ISlide slide = pres.Slides[0];
    IMasterSlide masterSlide = slide.LayoutSlide.MasterSlide;
    IPPImage image = pres.Images.AddImage(File.ReadAllBytes("image.png"));
    masterSlide.Shapes.AddPictureFrame(ShapeType.Rectangle, 10, 10, 100, 100, image);
    pres.Save("pres.pptx", SaveFormat.Pptx);
}
```

El siguiente ejemplo muestra cómo cambiar el color de fondo de la diapositiva maestra de una presentación de PowerPoint.

```csharp
[C#]
// Instanciar la clase Presentation que representa el archivo de presentación
using (Presentation pres = new Presentation())
{
    // Establecer el color de fondo de la máquina ISlide a Verde Bosque
    pres.Masters[0].Background.Type = BackgroundType.OwnBackground;
    pres.Masters[0].Background.FillFormat.FillType = FillType.Solid;
    pres.Masters[0].Background.FillFormat.SolidFillColor.Color = Color.ForestGreen;
    // Guardar la presentación en disco
    pres.Save("SetSlideBackgroundMaster_out.pptx", SaveFormat.Pptx);
}
```

El siguiente ejemplo muestra cómo agregar un diseño de diapositiva a una presentación de PowerPoint.

```csharp
[C#]
// Instanciar la clase Presentation que representa el archivo de presentación
using (Presentation presentation = new Presentation("AccessSlides.pptx"))
{
    // Intentar buscar por tipo de diseño de diapositiva
    IMasterLayoutSlideCollection layoutSlides = presentation.Masters[0].LayoutSlides;
    ILayoutSlide layoutSlide = layoutSlides.GetByType(SlideLayoutType.TitleAndObject) ?? layoutSlides.GetByType(SlideLayoutType.Title);
    if (layoutSlide == null)
    {
        // La situación cuando una presentación no contiene algunos tipos de diseños.
        // El archivo de presentación solo contiene tipos de diseño en blanco y personalizado.
        // Pero las diapositivas de diseño con tipos personalizados tienen diferentes nombres de diapositiva,
        // como "Título", "Título y Contenido", etc. Y es posible utilizar estos
        // nombres para la selección de diapositivas de diseño.
        // También es posible usar el conjunto de tipos de formas de marcador de posición. Por ejemplo,
        // La diapositiva de título debe tener solo un tipo de marcador de posición de Título, etc.
        foreach (ILayoutSlide titleAndObjectLayoutSlide in layoutSlides)
        {
            if (titleAndObjectLayoutSlide.Name == "Title and Object")
            {
                layoutSlide = titleAndObjectLayoutSlide;
                break;
            }
        }
        if (layoutSlide == null)
        {
            foreach (ILayoutSlide titleLayoutSlide in layoutSlides)
            {
                if (titleLayoutSlide.Name == "Title")
                {
                    layoutSlide = titleLayoutSlide;
                    break;
                }
            }
            if (layoutSlide == null)
            {
                layoutSlide = layoutSlides.GetByType(SlideLayoutType.Blank);
                if (layoutSlide == null)
                {
                    layoutSlide = layoutSlides.Add(SlideLayoutType.TitleAndObject, "Title and Object");
                }
            }
        }
    }
    // Agregar diapositiva vacía con el diseño de diapositiva agregado
    presentation.Slides.InsertEmptySlide(0, layoutSlide);
    // Guardar presentación
    presentation.Save("AddLayoutSlides_out.pptx", SaveFormat.Pptx);
}
```

### Ver También

* interfaz [IMasterSlideCollection](../../imasterslidecollection)
* clase [Presentation](../../presentation)
* espacio de nombres [Aspose.Slides](../../presentation)
* ensamblaje [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->