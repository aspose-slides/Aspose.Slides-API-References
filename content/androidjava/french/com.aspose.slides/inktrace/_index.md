---
title: InkTrace
second_title: Aspose.Slides pour Android via la référence de l'API Java
description: Représente un objet Trace.
type: docs
url: /fr/com.aspose.slides/inktrace/
---
**Héritage:**
java.lang.Object

**Toutes les interfaces implémentées:**
[com.aspose.slides.IInkTrace](../../com.aspose.slides/iinktrace)
```
public class InkTrace implements IInkTrace
```

Représente un objet Trace. Un élément Trace est utilisé pour enregistrer les données capturées par le numériseur. Il contient une séquence de points encodés selon la spécification fournie par l'objet InkTraceFormat.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getBrush()](#getBrush--) | Obtient le Brush pour l'IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) Lecture seule. |
| [getPoints()](#getPoints--) | Obtient les points pour l'IInkLine android.graphics.PointF Lecture seule. |
### getBrush() {#getBrush--}
```
public final IInkBrush getBrush()
```


Obtient le Brush pour l'IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) Lecture seule.

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
public final PointF[] getPoints()

Gets points for the IInkLine android.graphics.PointF Read-only.

--------------------

Exemple :
 
 Presentation pres = new Presentation("pres.pptx");
 try {
     IInk ink = (IInk)pres.getSlides().get_Item(0).getShapes().get_Item(0);
     IInkTrace[] traces = ink.getTraces();
     android.graphics.PointF[] points = traces[0].getPoints();
 } finally {
     if (pres != null) pres.dispose();
 }

**Renvoie:**  
android.graphics.PointF[]