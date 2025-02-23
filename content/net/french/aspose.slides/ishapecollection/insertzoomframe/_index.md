---
title: InsertZoomFrame
second_title: Référence de l'API Aspose.Slides pour .NET
description: Crée un nouvel objet Zoom et linsère dans une collection à lindex spécifié.
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

| Paramètre | Taper | La description |
| --- | --- | --- |
| index | Int32 | Index de base zéro auquel le cadre Zoom doit être inséré. |
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

Cet exemple illustre la création et l'insertion d'un objet Zoom à l'index spécifié d'une collection (en supposant qu'il y a au moins deux diapositives dans la présentation "Presentation.pptx") :

```csharp
[C#]
using (Presentation pres = new Presentation("Presentation.pptx"))
{
    IZoomFrame zoomFrame = pres.Slides[0].Shapes.InsertZoomFrame(2, 150, 20, 50, 50, pres.Slides[1]);
}
```

### Voir également

* interface [IZoomFrame](../../izoomframe)
* interface [ISlide](../../islide)
* interface [IShapeCollection](../../ishapecollection)
* espace de noms [Aspose.Slides](../../ishapecollection)
* Assemblée [Aspose.Slides](../../../)

---

## InsertZoomFrame(int, float, float, float, float, ISlide, IPPImage) {#insertzoomframe_1}

Crée un nouvel objet Zoom et l'insère dans une collection à l'index spécifié.

```csharp
public IZoomFrame InsertZoomFrame(int index, float x, float y, float width, float height, 
    ISlide slide, IPPImage image)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| index | Int32 | Index de base zéro auquel le cadre Zoom doit être inséré. |
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

Cet exemple illustre la création et l'insertion d'un objet Zoom à l'index spécifié d'une collection (en supposant qu'il y a au moins deux diapositives dans la présentation "Presentation.pptx") :

```csharp
[C#]
using (Presentation pres = new Presentation("Presentation.pptx"))
{
    IPPImage image = pres.Images.AddImage(Image.FromFile("image.png"));
    IZoomFrame zoomFrame = pres.Slides[0].Shapes.InsertZoomFrame(2, 150, 20, 50, 50, pres.Slides[1], image);
}
```

### Voir également

* interface [IZoomFrame](../../izoomframe)
* interface [ISlide](../../islide)
* interface [IPPImage](../../ippimage)
* interface [IShapeCollection](../../ishapecollection)
* espace de noms [Aspose.Slides](../../ishapecollection)
* Assemblée [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
