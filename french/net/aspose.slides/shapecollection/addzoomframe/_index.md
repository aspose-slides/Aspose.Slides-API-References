---
title: AddZoomFrame
second_title: Référence de l'API Aspose.Slides pour .NET
description: Ajoute un nouvel objet Zoom à la fin dune collection.
type: docs
weight: 220
url: /fr/net/aspose.slides/shapecollection/addzoomframe/
---
## AddZoomFrame(float, float, float, float, ISlide) {#addzoomframe}

Ajoute un nouvel objet Zoom à la fin d'une collection.

```csharp
public IZoomFrame AddZoomFrame(float x, float y, float width, float height, ISlide slide)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| x | Single | Coordonnée X d'un nouveau cadre ZoomSingle. |
| y | Single | Coordonnée Y d'un nouveau cadre ZoomSingle. |
| width | Single | Largeur d'un nouveau cadre ZoomSingle. |
| height | Single | Hauteur d'un nouveau cadre ZoomSingle. |
| slide | ISlide | L'objet de diapositive référencé par le cadre Zoom[`ISlide`](../../islide). |

### Return_Value

Objet Zoom créé[`IZoomFrame`](../../izoomframe).

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | La diapositive référencée n'appartient pas à la présentation actuelle. |

### Exemples

Cet exemple montre comment ajouter un objet Zoom à la fin d'une collection (en supposant qu'il y a au moins deux diapositives dans la présentation "Presentation.pptx") :

```csharp
[C#]
using (Presentation pres = new Presentation("Presentation.pptx"))
{
    IZoomFrame zoomFrame = pres.Slides[0].Shapes.AddZoomFrame(150, 20, 50, 50, pres.Slides[1]);
}
```

### Voir également

* interface [IZoomFrame](../../izoomframe)
* interface [ISlide](../../islide)
* class [ShapeCollection](../../shapecollection)
* espace de noms [Aspose.Slides](../../shapecollection)
* Assemblée [Aspose.Slides](../../../)

---

## AddZoomFrame(float, float, float, float, ISlide, IPPImage) {#addzoomframe_1}

Ajoute un nouvel objet Zoom à la fin d'une collection.

```csharp
public IZoomFrame AddZoomFrame(float x, float y, float width, float height, ISlide slide, 
    IPPImage image)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| x | Single | Coordonnée X d'un nouveau cadre ZoomSingle. |
| y | Single | Coordonnée Y d'un nouveau cadre ZoomSingle. |
| width | Single | Largeur d'un nouveau cadre ZoomSingle. |
| height | Single | Hauteur d'un nouveau cadre ZoomSingle. |
| slide | ISlide | L'objet de diapositive référencé par le cadre Zoom[`ISlide`](../../islide). |
| image | IPPImage | L'image de la diapositive référencée[`IPPImage`](../../ippimage) |

### Return_Value

Objet Zoom créé[`IZoomFrame`](../../izoomframe).

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | La diapositive référencée n'appartient pas à la présentation actuelle. |

### Exemples

Cet exemple montre comment ajouter un objet Zoom à la fin d'une collection (en supposant qu'il y a au moins deux diapositives dans la présentation "Presentation.pptx") :

```csharp
[C#]
using (Presentation pres = new Presentation("Presentation.pptx"))
{
    IPPImage image = pres.Images.AddImage(Image.FromFile("image.png"));
    IZoomFrame zoomFrame = pres.Slides[0].Shapes.AddZoomFrame(150, 20, 50, 50, pres.Slides[1], image);
}
```

### Voir également

* interface [IZoomFrame](../../izoomframe)
* interface [ISlide](../../islide)
* interface [IPPImage](../../ippimage)
* class [ShapeCollection](../../shapecollection)
* espace de noms [Aspose.Slides](../../shapecollection)
* Assemblée [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->