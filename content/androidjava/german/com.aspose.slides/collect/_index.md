---
title: Collect
second_title: Aspose.Slides für Android über die Java API Referenz
description: Stellt eine Gruppe von Methoden dar, die dazu bestimmt sind, Modellobjekte verschiedener Typen aus . zu sammeln.
type: docs
url: /de/com.aspose.slides/collect/
---
**Vererbung:**
java.lang.Object
```
public class Collect
```

Stellt eine Gruppe von Methoden dar, die dazu bestimmt sind, Modellobjekte verschiedener Typen aus [Presentation](../../com.aspose.slides/presentation) zu sammeln.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      for (IShape shape : Collect.shapes(pres))
>      {
>          // ... Shape-Formatierung ändern oder andere Eigenschaften
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Collect()](#Collect--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [shapes(Presentation pres)](#shapes-com.aspose.slides.Presentation-) | Sammelt alle Instanzen von [Shape](../../com.aspose.slides/shape) im [Presentation](../../com.aspose.slides/presentation). |
### Collect() {#Collect--}
```
public Collect()
```


### shapes(Presentation pres) {#shapes-com.aspose.slides.Presentation-}
```
public static System.Collections.Generic.IGenericEnumerable<Shape> shapes(Presentation pres)
```


Sammelt alle Instanzen von [Shape](../../com.aspose.slides/shape) im [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      for (IShape shape : Collect.shapes(pres))
>      {
>          // wenn das Shape ein AutoShape ist, füge einen schwarzen Vollrahmen hinzu
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


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentation zum Sammeln von Shapes |

**Rückgabewert:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.Shape> - Sammlung aller Shapes, die in der Präsentation enthalten sind