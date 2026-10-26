---
title: IInkTrace
second_title: Aspose.Slides for Android via Java API Reference
description: Represents handwritten line in an Ink object.
type: docs
url: /fr/com.aspose.slides/iinktrace/
---```
public interface IInkTrace
```

Représente une ligne manuscrite dans un objet Ink.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getBrush()](#getBrush--) | Obtient le Brush pour le IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) Lecture seule. |
| [getPoints()](#getPoints--) | Obtient les points pour le IInkLine android.graphics.PointF Lecture seule. |
### getBrush() {#getBrush--}
```
public abstract IInkBrush getBrush()
```


Obtient le Brush pour le IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) Lecture seule.

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

**Returns:**
[IInkBrush](../../com.aspose.slides/iinkbrush)
### getPoints() {#getPoints--}
```
public abstract PointF[] getPoints()


Obtient les points pour le IInkLine android.graphics.PointF Lecture seule.

--------------------

> ```
> Exemple:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IInk ink = (IInk)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IInkTrace[] traces = ink.getTraces();
>      android.graphics.PointF[] points = traces[0].getPoints();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Renvoie :**
android.graphics.PointF[]