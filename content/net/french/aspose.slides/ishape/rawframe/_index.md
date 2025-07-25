---
title: RawFrame
second_title: Aspose.Sildes pour la référence API .NET
description: Renvoie ou définit les propriétés des cadres de forme bruts. Lecture/écriture IShapeFrameaspose.slides/ishapeframe.
type: docs
weight: 210
url: /fr/aspose.slides/ishape/rawframe/
---

## IShape.RawFrame propriété

Renvoie ou définit les propriétés du cadre de forme brut. Lecture/écriture [`IShapeFrame`](../../ishapeframe).

```csharp
public IShapeFrame RawFrame { get; set; }
```

### Exemples

Le code qui tente d'assigner un cadre indéfini à IShape.Frame n'a pas de sens dans le cas général (particulièrement lorsque le GroupShape parent est imbriqué plusieurs fois dans d'autres GroupShape-s). Par exemple :

```csharp
IShape shape = ...;
shape.Frame = new ShapeFrame(float.NaN, float.NaN, float.NaN, float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, float.NaN);
```

ou

```csharp
slide.Shapes.AddAutoShape(ShapeType.RoundCornerRectangle, float.NaN, float.NaN, float.NaN, float.NaN);
```

Un tel code peut conduire à des situations floues. Des restrictions ont donc été ajoutées pour utiliser des valeurs indéfinies pour IShape.Frame. Les valeurs de x, y, width, height, flipH, flipV et rotationAngle doivent être définies (pas float.NaN ou NullableBool.NotDefined). Le code d'exemple ci-dessus lance maintenant une exception ArgumentException. Cela s'applique à ces cas d'utilisation :

```csharp
IShape shape = ...;
shape.Frame = ...; // ne peut pas être indéfini

IShapeCollection shapes = ...;
// les paramètres x, y, width, height ne peuvent pas être float.NaN :
{
    shapes.AddAudioFrameCD(...);
    shapes.AddAudioFrameEmbedded(...);
    shapes.AddAudioFrameLinked(...);
    shapes.AddAutoShape(...);
    shapes.AddChart(...);
    shapes.AddConnector(...);
    shapes.AddOleObjectFrame(...);
    shapes.AddPictureFrame(...);
    shapes.AddSmartArt(...);
    shapes.AddTable(...);
    shapes.AddVideoFrame(...);
    shapes.InsertAudioFrameEmbedded(...);
    shapes.InsertAudioFrameLinked(...);
    shapes.InsertAutoShape(...);
    shapes.InsertChart(...);
    shapes.InsertConnector(...);
    shapes.InsertOleObjectFrame(...);
    shapes.InsertPictureFrame(...);
    shapes.InsertTable(...);
    shapes.InsertVideoFrame(...);
}
```

Mais les propriétés du cadre IShape.RawFrame peuvent être indéfinies. Cela a du sens lorsque la forme est liée à un espace réservé. Dans ce cas, les valeurs de cadre de forme indéfinies sont remplacées par celles de la forme d'espace réservé parent. S'il n'y a pas de forme d'espace réservé parent pour cette forme, alors cette forme utilise des valeurs par défaut lorsqu'elle évalue le cadre effectif basé sur son IShape.RawFrame. Les valeurs par défaut sont 0 et NullableBool.False pour x, y, width, height, flipH, flipV et rotationAngle. Par exemple :

```csharp
IShape shape = ...; // la forme est liée à un espace réservé
shape.RawFrame = new ShapeFrame(float.NaN, float.NaN, 100, float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0); // maintenant, la forme hérite des valeurs x, y, height, flipH, flipV de l'espace réservé et remplace width=100 et rotationAngle=0.
```

### Voir aussi

* interface [IShapeFrame](../../ishapeframe)
* interface [IShape](../../ishape)
* namespace [Aspose.Slides](../../ishape)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->