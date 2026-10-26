---
title: InkTrace
second_title: Aspose.Slides για Android μέσω αναφοράς του Java API
description: Αναπαριστά ένα αντικείμενο Trace.
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

Αναπαριστά ένα αντικείμενο Trace. Ένα στοιχείο Trace χρησιμοποιείται για την καταγραφή των δεδομένων που συλλάβει ο ψηφιοποιητής. Περιέχει μια ακολουθία σημείων κωδικοποιημένων σύμφωνα με την προδιαγραφή που δίνει το αντικείμενο InkTraceFormat.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getBrush()](#getBrush--) | Λαμβάνει Brush για το IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) Μόνο για ανάγνωση. |
| [getPoints()](#getPoints--) | Λαμβάνει σημεία για το IInkLine android.graphics.PointF Μόνο για ανάγνωση. |
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
public final PointF[] getPoints()
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