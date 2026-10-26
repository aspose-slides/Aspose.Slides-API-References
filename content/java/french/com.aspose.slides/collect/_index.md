---
title: Collect
second_title: Référence de l'API Aspose.Slides for Java
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

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Collect()](#Collect--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [shapes(Presentation pres)](#shapes-com.aspose.slides.Presentation-) | Collecte toutes les instances de [Shape](../../com.aspose.slides/shape) dans le [Presentation](../../com.aspose.slides/presentation). |
### Collect() {#Collect--}
```
public Collect()
```


### shapes(Presentation pres) {#shapes-com.aspose.slides.Presentation-}
```
public static System.Collections.Generic.IGenericEnumerable<Shape> shapes(Presentation pres)
```


Collecte toutes les instances de [Shape](../../com.aspose.slides/shape) dans le [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      for (IShape shape : Collect.shapes(pres))
>      {
>          // si la forme est AutoShape, ajoutez une bordure noire pleine
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

**Renvoie:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.Shape> - Collection de toutes les formes contenues dans la présentation