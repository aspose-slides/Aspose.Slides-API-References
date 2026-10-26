---
title: IInkTrace
second_title: Aspose.Slides for Java API Reference
description: Αναπαριστά γραμμή χειρόγραφου σε ένα αντικείμενο Ink.
type: docs
url: /el/com.aspose.slides/iinktrace/
---```
public interface IInkTrace
```

Αναπαριστά γραμμή χειρόγραφου σε ένα αντικείμενο Ink.
## Μεθόδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getBrush()](#getBrush--) | Λαμβάνει Brush για το IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) Μόνο για ανάγνωση. |
| [getPoints()](#getPoints--) | Λαμβάνει points για το IInkLine java.awt.geom.Point2D.Float Μόνο για ανάγνωση. |
### getBrush() {#getBrush--}
```
public abstract IInkBrush getBrush()
```


Λαμβάνει Brush για το IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) Μόνο για ανάγνωση.

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

**Επιστρέφει:**
[IInkBrush](../../com.aspose.slides/iinkbrush)
### getPoints() {#getPoints--}
```
public abstract Point2D.Float[] getPoints()
```


Λαμβάνει points για το IInkLine java.awt.geom.Point2D.Float Μόνο για ανάγνωση.

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

**Επιστρέφει:**
java.awt.geom.Point2D.Float[]