---
title: SetGeometryPath
second_title: Référence de l'API Aspose.Slides pour .NET
description: Met à jour la géométrie de la forme à partir de l'objet IGeometryPathaspose.slides/igeometrypath. Les coordonnées doivent être relatives au coin supérieur gauche de la forme. Change le type de la forme ShapeTypeaspose.slides/geometryshape/shapetype en Personnalisé.
type: docs
weight: 60
url: /fr/aspose.slides/geometryshape/setgeometrypath/
---

## GeometryShape.SetGeometryPath méthode

Met à jour la géométrie de la forme à partir de l'objet [`IGeometryPath`](../../igeometrypath). Les coordonnées doivent être relatives au coin supérieur gauche de la forme. Change le type de la forme ([`ShapeType`](../shapetype)) en Personnalisé.

```csharp
public void SetGeometryPath(IGeometryPath geometryPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| geometryPath | IGeometryPath | Chemin de géométrie |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Aucun chemin trouvé |
| ArgumentException | Chemin vide trouvé |

### Exemples

Exemple :

```csharp
[C#]
using (Presentation pres = new Presentation())
{
    GeometryShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 100, 100, 200, 100) as GeometryShape;

    GeometryPath geometryPath0 = new GeometryPath();
    geometryPath0.MoveTo(0, 0);
    geometryPath0.LineTo(shape.Width, 0);
    geometryPath0.LineTo(shape.Width, shape.Height/3);
    geometryPath0.LineTo(0, shape.Height / 3);
    geometryPath0.CloseFigure();

    GeometryPath geometryPath1 = new GeometryPath();
    geometryPath1.MoveTo(0, shape.Height/3 * 2);
    geometryPath1.LineTo(shape.Width, shape.Height / 3 * 2);
    geometryPath1.LineTo(shape.Width, shape.Height);
    geometryPath1.LineTo(0, shape.Height);
    geometryPath1.CloseFigure();

    shape.SetGeometryPaths(new GeometryPath[] { geometryPath0, geometryPath1});

    pres.Save("output.pptx", SaveFormat.Pptx);
}
```

### Voir aussi

* interface [IGeometryPath](../../igeometrypath)
* class [GeometryShape](../../geometryshape)
* namespace [Aspose.Slides](../../geometryshape)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->