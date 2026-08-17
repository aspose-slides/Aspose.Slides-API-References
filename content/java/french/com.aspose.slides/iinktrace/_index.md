---
title: IInkTrace
second_title: Aspose.Slides for Java API Reference
description: Représente une ligne manuscrite dans un objet Ink.
type: docs
url: /fr/com.aspose.slides/iinktrace/
---```
public interface IInkTrace
```

Représente une ligne manuscrite dans un objet Ink.
## Méthodes

| Method | Description |
| --- | --- |
| [getBrush()](#getBrush--) | Obtient Brush pour le IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) Lecture seule. |
| [getPoints()](#getPoints--) | Obtient les points pour le IInkLine java.awt.geom.Point2D.Float Lecture seule. |
### getBrush() {#getBrush--}
```
public abstract IInkBrush getBrush()
```


Obtient Brush pour le IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) Lecture seule.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IInk ink = (IInk)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IInkTrace[] traces = ink.getTraces();
>      IInkBrush brush = traces[0].getBrush();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Renvoie:**  
[IInkBrush](../../com.aspose.slides/iinkbrush)
### getPoints() {#getPoints--}
```
public abstract Point2D.Float[] getPoints()
```


Obtient les points pour le IInkLine java.awt.geom.Point2D.Float Lecture seule.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IInk ink = (IInk)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IInkTrace[] traces = ink.getTraces();
>      Point2D.Float[] points = traces[0].getPoints();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Renvoie:**  
java.awt.geom.Point2D.Float[]