---
title: InsertSectionZoomFrame
second_title: Référence de l'API Aspose.Slides pour .NET
description: Crée un nouvel objet Section Zoom et l'insère dans une collection à l'index spécifié.
type: docs
weight: 370
url: /fr/aspose.slides/shapecollection/insertsectionzoomframe/
---

## InsertSectionZoomFrame(int, float, float, float, float, ISection) {#insertsectionzoomframe}

Crée un nouvel objet Section Zoom et l'insère dans une collection à l'index spécifié.

```csharp
public ISectionZoomFrame InsertSectionZoomFrame(int index, float x, float y, float width, 
    float height, ISection section)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| index | Int32 | L'index basé sur zéro où le cadre Section Zoom doit être inséré. |
| x | Single | Coordonnée X d'un nouveau cadre Section Zoom Single. |
| y | Single | Coordonnée Y d'un nouveau cadre Section Zoom Single. |
| width | Single | Largeur d'un nouveau cadre Section Zoom Single. |
| height | Single | Hauteur d'un nouveau cadre Section Zoom Single. |
| section | ISection | L'objet diapositive référencé par le cadre Section Zoom [`ISection`](../../isection). |

### Valeur de retour

Objet Section Zoom créé [`ISectionZoomFrame`](../../isectionzoomframe).

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | La section référencée n'appartient pas à la présentation actuelle ou ne contient aucune diapositive. |

### Exemples

Cet exemple démontre la création et l'insertion d'un objet Section Zoom à l'index spécifié d'une collection (supposons qu'il y ait au moins deux sections dans la présentation "Presentation.pptx"):

```csharp
[C#]
using (Presentation pres = new Presentation("Presentation.pptx"))
{
    ISectionZoomFrame zoomFrame = pres.Slides[0].Shapes.InsertSectionZoomFrame(2, 150, 20, 50, 50, pres.Sections[1]);
}
```

### Voir aussi

* interface [ISectionZoomFrame](../../isectionzoomframe)
* interface [ISection](../../isection)
* class [ShapeCollection](../../shapecollection)
* namespace [Aspose.Slides](../../shapecollection)
* assembly [Aspose.Slides](../../../)

---

## InsertSectionZoomFrame(int, float, float, float, float, ISection, IPPImage) {#insertsectionzoomframe_1}

Crée un nouvel objet Section Zoom et l'insère dans une collection à l'index spécifié.

```csharp
public ISectionZoomFrame InsertSectionZoomFrame(int index, float x, float y, float width, 
    float height, ISection section, IPPImage image)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| index | Int32 | L'index basé sur zéro où le cadre Section Zoom doit être inséré. |
| x | Single | Coordonnée X d'un nouveau cadre Section Zoom Single. |
| y | Single | Coordonnée Y d'un nouveau cadre Section Zoom Single. |
| width | Single | Largeur d'un nouveau cadre Section Zoom Single. |
| height | Single | Hauteur d'un nouveau cadre Section Zoom Single. |
| section | ISection | L'objet diapositive référencé par le cadre Section Zoom [`ISection`](../../isection). |
| image | IPPImage | L'image pour la diapositive référencée [`IPPImage`](../../ippimage) |

### Valeur de retour

Objet Section Zoom créé [`ISectionZoomFrame`](../../isectionzoomframe).

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | La section référencée n'appartient pas à la présentation actuelle ou ne contient aucune diapositive. |

### Exemples

Cet exemple démontre la création et l'insertion d'un objet Section Zoom à l'index spécifié d'une collection (supposons qu'il y ait au moins deux sections dans la présentation "Presentation.pptx"):

```csharp
[C#]
using (Presentation pres = new Presentation("Presentation.pptx"))
{
    IPPImage image = pres.Images.AddImage(Image.FromFile("image.png"));
    ISectionZoomFrame zoomFrame = pres.Slides[0].Shapes.InsertSectionZoomFrame(2, 150, 20, 50, 50, pres.Sections[1], image);
}
```

### Voir aussi

* interface [ISectionZoomFrame](../../isectionzoomframe)
* interface [ISection](../../isection)
* interface [IPPImage](../../ippimage)
* class [ShapeCollection](../../shapecollection)
* namespace [Aspose.Slides](../../shapecollection)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->