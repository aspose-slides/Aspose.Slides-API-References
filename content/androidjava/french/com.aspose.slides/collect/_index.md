---
title: Collect
second_title: Référence de l'API Java Aspose.Slides pour Android
description: Représente un groupe de méthodes destiné à collecter des objets modèle de différents types depuis .
type: docs
url: /fr/com.aspose.slides/collect/
---
**Héritage:**
java.lang.Object
```
public class Collect
```

Représente un groupe de méthodes destiné à collecter des objets modèle de différents types depuis [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      for (IShape shape : Collect.shapes(pres))
>      {
>          // ... modifier le format de la forme ou d'autres propriétés
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Constructors

| Constructor | Description |
| --- | --- |
| [Collect()](#Collect--) |  |
## Methods

| Method | Description |
| --- | --- |
| [shapes(Presentation pres)](#shapes-com.aspose.slides.Presentation-) | Collects all instances of [Shape](../../com.aspose.slides/shape) in the [Presentation](../../com.aspose.slides/presentation). |
### Collect() {#Collect--}
```
public Collect()
```

### shapes(Presentation pres) {#shapes-com.aspose.slides.Presentation-}
```
public static System.Collections.Generic.IGenericEnumerable<Shape> shapes(Presentation pres)

Collects all instances of [Shape](../../com.aspose.slides/shape) in the [Presentation](../../com.aspose.slides/presentation).


--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      for (IShape shape : Collect.shapes(pres))
>      {
>          // if the shape is AutoShape, add a black solid border
>          if (shape instanceof AutoShape)
>          {
>              AutoShape autoShape = (AutoShape)shape;
>              autoShape.getLineFormat().setStyle(LineStyle.Single);
>              autoShape.getLineFormat().setWidth(10f);
>              autoShape.getLineFormat().getFillFormat().setFillType(FillType.Solid);
>              autoShape.getLineFormat().getFillFormat().getSolidFillColor().setColor(Color.black);
>          }
>      }
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Présentation pour collecter les formes |

**Retour:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.Shape> - Collection de toutes les formes contenues dans la présentation