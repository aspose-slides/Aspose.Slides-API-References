---
title: ZoomFrame
second_title: Aspose.Slides για την Αναφορά API Java
description: Αναπαριστά ένα αντικείμενο Slide Zoom σε μια διαφάνεια.
type: docs
url: /el/com.aspose.slides/zoomframe/
---
**Κληρονομικότητα:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject), [com.aspose.slides.ZoomObject](../../com.aspose.slides/zoomobject)

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IZoomFrame](../../com.aspose.slides/izoomframe)
```
public class ZoomFrame extends ZoomObject implements IZoomFrame
```

Αναπαριστά ένα αντικείμενο Slide Zoom σε μια διαφάνεια.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getTargetSlide()](#getTargetSlide--) | Λαμβάνει ή ορίζει το αντικείμενο διαφάνειας στο οποίο συνδέεται το Slide Zoom. |
| [setTargetSlide(ISlide value)](#setTargetSlide-com.aspose.slides.ISlide-) | Λαμβάνει ή ορίζει το αντικείμενο διαφάνειας στο οποίο συνδέεται το Slide Zoom. |
### getTargetSlide() {#getTargetSlide--}
```
public final ISlide getTargetSlide()
```


Λαμβάνει ή ορίζει το αντικείμενο διαφάνειας στο οποίο συνδέεται το Slide Zoom. Ανάγνωση/εγγραφή [ISlide](../../com.aspose.slides/islide).

--------------------

> ```
> Next example demonstrates changing target slide and creates new image for the Slide Zoom object:
>  
>  IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>  zoomFrame.setTargetSlide(pres.getSlides().get_Item(2));
> ```

**Επιστρέφει:**
[ISlide](../../com.aspose.slides/islide)
### setTargetSlide(ISlide value) {#setTargetSlide-com.aspose.slides.ISlide-}
```
public final void setTargetSlide(ISlide value)
```


Λαμβάνει ή ορίζει το αντικείμενο διαφάνειας στο οποίο συνδέεται το Slide Zoom. Ανάγνωση/εγγραφή [ISlide](../../com.aspose.slides/islide).

--------------------

> ```
> Το επόμενο παράδειγμα δείχνει την αλλαγή της διαφάνειας προορισμού και δημιουργεί νέα εικόνα για το αντικείμενο Slide Zoom:
>  
>  IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>  zoomFrame.setTargetSlide(pres.getSlides().get_Item(2));
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [ISlide](../../com.aspose.slides/islide) |  |