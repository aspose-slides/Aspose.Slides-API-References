---
title: ZoomFrame
second_title: Aspose.Slides για Android μέσω αναφοράς API Java
description: Αντιπροσωπεύει ένα αντικείμενο Slide Zoom σε μια διαφάνεια.
type: docs
url: /el/com.aspose.slides/zoomframe/
---
**Κληρονομία:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject), [com.aspose.slides.ZoomObject](../../com.aspose.slides/zoomobject)

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IZoomFrame](../../com.aspose.slides/izoomframe)
```
public class ZoomFrame extends ZoomObject implements IZoomFrame
```

Αντιπροσωπεύει ένα αντικείμενο Slide Zoom σε μια διαφάνεια.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getTargetSlide()](#getTargetSlide--) | Ανακτά ή ορίζει το αντικείμενο διαφάνειας στο οποίο συνδέεται το αντικείμενο Slide Zoom. |
| [setTargetSlide(ISlide value)](#setTargetSlide-com.aspose.slides.ISlide-) | Ανακτά ή ορίζει το αντικείμενο διαφάνειας στο οποίο συνδέεται το αντικείμενο Slide Zoom. |
### getTargetSlide() {#getTargetSlide--}
```
public final ISlide getTargetSlide()
```


Ανακτά ή ορίζει το αντικείμενο διαφάνειας στο οποίο συνδέεται το αντικείμενο Slide Zoom. Ανάγνωση/Εγγραφή [ISlide](../../com.aspose.slides/islide).

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


Ανακτά ή ορίζει το αντικείμενο διαφάνειας στο οποίο συνδέεται το αντικείμενο Slide Zoom. Ανάγνωση/Εγγραφή [ISlide](../../com.aspose.slides/islide).

--------------------

> ```
> Next example demonstrates changing target slide and creates new image for the Slide Zoom object:
>  
>  IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>  zoomFrame.setTargetSlide(pres.getSlides().get_Item(2));
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [ISlide](../../com.aspose.slides/islide) |  |