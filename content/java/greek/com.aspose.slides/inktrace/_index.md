---
title: InkTrace
second_title: Αναφορά API του Aspose.Slides για Java
description: Αντιπροσωπεύει ένα αντικείμενο Trace.
type: docs
url: /el/com.aspose.slides/inktrace/
---
**Κληρονομικότητα:**
java.lang.Object

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IInkTrace](../../com.aspose.slides/iinktrace)
```
public class InkTrace implements IInkTrace
```

Αντιπροσωπεύει ένα αντικείμενο Trace. Ένα στοιχείο Trace χρησιμοποιείται για την καταγραφή των δεδομένων που καταγράφει ο ψηφιοποιητής. Περιέχει μια ακολουθία σημείων κωδικοποιημένων σύμφωνα με την προδιαγραφή που παρέχεται από το αντικείμενο InkTraceFormat.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getBrush()](#getBrush--) | Λαμβάνει Brush για το IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) Μόνο για ανάγνωση. |
| [getPoints()](#getPoints--) | Λαμβάνει σημεία για το IInkLine java.awt.geom.Point2D.Float Μόνο για ανάγνωση. |
### getBrush() {#getBrush--}
```
public final IInkBrush getBrush()
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
public final Point2D.Float[] getPoints()
```


Λαμβάνει σημεία για το IInkLine java.awt.geom.Point2D.Float Μόνο για ανάγνωση.

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