---
title: InkTrace
second_title: Référence de l'API Aspose.Slides pour Java
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

Représente un objet Trace. Un élément Trace est utilisé pour enregistrer les données capturées par le numériseur. Il contient une séquence de points encodés selon la spécification fournie par l’objet InkTraceFormat.

## Méthodes

| Méthode | Description |
| --- | --- |
| [getBrush()](#getBrush--) | Obtient Brush pour le IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) Lecture seule. |
| [getPoints()](#getPoints--) | Obtient les points pour le IInkLine java.awt.geom.Point2D.Float Lecture seule. |

### getBrush() {#getBrush--}
```
public final IInkBrush getBrush()
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


**Retour:**  
[IInkBrush](../../com.aspose.slides/iinkbrush)

### getPoints() {#getPoints--}
```
public final Point2D.Float[] getPoints()
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


**Retour:**  
java.awt.geom.Point2D.Float[]