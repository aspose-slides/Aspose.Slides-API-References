---
title: InsertZoomFrame
second_title: Aspose.Sildes pour la référence API .NET
description: Crée un nouvel objet Zoom et l'insère dans une collection à l'index spécifié.
type: docs
weight: 360
url: /fr/aspose.slides/ishapecollection/insertzoomframe/
---

## InsertZoomFrame(int, float, float, float, float, ISlide) {#insertzoomframe}

Crée un nouvel objet Zoom et l'insère dans une collection à l'index spécifié.

```csharp
public IZoomFrame InsertZoomFrame(int index, float x, float y, float width, float height, 
    ISlide slide)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| index | Int32 | L'index basé sur zéro auquel le cadre Zoom doit être inséré. |
| x | Single | Coordonnée X d'un nouveau cadre Zoom Single. |
| y | Single | Coordonnée Y d'un nouveau cadre Zoom Single. |
| width | Single | Largeur d'un nouveau cadre Zoom Single. |
| height | Single | Hauteur d'un nouveau cadre Zoom Single. |
| slide | ISlide | L'objet diapositive référencé par le cadre Zoom [`ISlide`](../../islide). |

### Valeur de retour

Objet Zoom créé [`IZoomFrame`](../../izoomframe).

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | La diapositive référencée n'appartient pas à la présentation actuelle. |

### Exemples

Cet exemple démontre la création et l'insertion d'un objet Zoom à l'index spécifié d'une collection (supposons qu'il y ait au moins deux diapositives dans la présentation "Presentation.pptx"):

```csharp
[C#]
using (Presentation pres = new Presentation("Presentation.pptx"))
{
    IZoomFrame zoomFrame = pres.Slides[0].Shapes.InsertZoomFrame(2, 150, 20, 50, 50, pres.Slides[1]);
}
```

### Voir aussi

* interface [IZoomFrame](../../izoomframe)
* interface [ISlide](../../islide)
* interface [IShapeCollection](../../ishapecollection)
* namespace [Aspose.Slides](../../ishapecollection)
* assembly [Aspose.Slides](../../../)

---

## InsertZoomFrame(int, float, float, float, float, ISlide, IPPImage) {#insertzoomframe_1}

Crée un nouvel objet Zoom et l'insère dans une collection à l'index spécifié.

```csharp
public IZoomFrame InsertZoomFrame(int index, float x, float y, float width, float height, 
    ISlide slide, IPPImage image)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| index | Int32 | L'index basé sur zéro auquel le cadre Zoom doit être inséré. |
| x | Single | Coordonnée X d'un nouveau cadre Zoom Single. |
| y | Single | Coordonnée Y d'un nouveau cadre Zoom Single. |
| width | Single | Largeur d'un nouveau cadre Zoom Single. |
| height | Single | Hauteur d'un nouveau cadre Zoom Single. |
| slide | ISlide | L'objet diapositive référencé par le cadre Zoom [`ISlide`](../../islide). |
| image | IPPImage | L'image pour la diapositive référencée [`IPPImage`](../../ippimage) |

### Valeur de retour

Objet Zoom créé [`IZoomFrame`](../../izoomframe).

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | La diapositive référencée n'appartient pas à la présentation actuelle. |

### Exemples

Cet exemple démontre la création et l'insertion d'un objet Zoom à l'index spécifié d'une collection (supposons qu'il y ait au moins deux diapositives dans la présentation "Presentation.pptx"):

```csharp
[C#]
using (Presentation pres = new Presentation("Presentation.pptx"))
{
    IPPImage image = pres.Images.AddImage(Image.FromFile("image.png"));
    IZoomFrame zoomFrame = pres.Slides[0].Shapes.InsertZoomFrame(2, 150, 20, 50, 50, pres.Slides[1], image);
}
```

### Voir aussi

* interface [IZoomFrame](../../izoomframe)
* interface [ISlide](../../islide)
* interface [IPPImage](../../ippimage)
* interface [IShapeCollection](../../ishapecollection)
* namespace [Aspose.Slides](../../ishapecollection)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->