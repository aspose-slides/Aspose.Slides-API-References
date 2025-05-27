---
title: AddSmartArt
second_title: Referencia de la API de Aspose.Slides para .NET
description: Agregar diagrama SmartArt.
type: docs
weight: 180
url: /es/aspose.slides/shapecollection/addsmartart/
---

## Método ShapeCollection.AddSmartArt

Agregar diagrama SmartArt.

```csharp
public ISmartArt AddSmartArt(float x, float y, float width, float height, 
    SmartArtLayoutType layoutType)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | Single | La coordenada X para el lado izquierdo del marco del diagrama. |
| y | Single | La coordenada Y para el lado izquierdo del marco del diagrama. |
| width | Single | El ancho del marco del diagrama. |
| height | Single | La altura del marco del diagrama. |
| layoutType | SmartArtLayoutType | El tipo de diagrama SmartArt |

### Valor de Retorno

Crea diagrama SmartArt.

### Ejemplos

El siguiente ejemplo muestra cómo agregar una forma inteligente en la presentación de PowerPoint.

```csharp
[C#]
using (Presentation pres = new Presentation())
{
	Slide slide = pres.Slides[0];
	SmartArt smart = slide.Shapes.AddSmartArt(0, 0, 400, 400, SmartArtLayoutType.BasicBlockList);
}
```

### Ver También

* interface [ISmartArt](../../../aspose.slides.smartart/ismartart)
* enum [SmartArtLayoutType](../../../aspose.slides.smartart/smartartlayouttype)
* class [ShapeCollection](../../shapecollection)
* namespace [Aspose.Slides](../../shapecollection)
* assembly [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->