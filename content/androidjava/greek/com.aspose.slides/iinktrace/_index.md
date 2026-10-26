---
title: IInkTrace
second_title: Aspose.Slides for Android via Java API Reference
description: Represents handwritten line in an Ink object.
type: docs
url: /el/com.aspose.slides/iinktrace/
---```
public interface IInkTrace
```

Αναπαριστά γραμμή χειρόγραφης σε αντικείμενο Ink.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getBrush()](#getBrush--) | Λαμβάνει το Brush για το IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) Μόνο για ανάγνωση. |
| [getPoints()](#getPoints--) | Λαμβάνει σημεία για το IInkLine android.graphics.PointF Μόνο για ανάγνωση. |
### getBrush() {#getBrush--}
```
public abstract IInkBrush getBrush()
```

Λαμβάνει το Brush για το IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) Μόνο για ανάγνωση.

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
public abstract PointF[] getPoints()
```

Λαμβάνει σημεία για το IInkLine android.graphics.PointF Μόνο για ανάγνωση.

--------------------

> ```
> Example:
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

**Επιστρέφει:**
android.graphics.PointF[]