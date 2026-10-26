---
title: IZoomFrame
second_title: Αναφορά API Aspose.Slides για Java
description: Αναπαριστά ένα αντικείμενο Slide Zoom σε μια διαφάνεια.
type: docs
url: /el/com.aspose.slides/izoomframe/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IZoomObject](../../com.aspose.slides/izoomobject)
```
public interface IZoomFrame extends IZoomObject
```

Αναπαριστά ένα αντικείμενο Slide Zoom σε μια διαφάνεια.
## Μέθοδοι

| Method | Description |
| --- | --- |
| [getTargetSlide()](#getTargetSlide--) | Λαμβάνει ή ορίζει το αντικείμενο διαφάνειας στο οποίο συνδέεται το Slide Zoom object. |
| [setTargetSlide(ISlide value)](#setTargetSlide-com.aspose.slides.ISlide-) | Λαμβάνει ή ορίζει το αντικείμενο διαφάνειας στο οποίο συνδέεται το Slide Zoom object. |
### getTargetSlide() {#getTargetSlide--}
```
public abstract ISlide getTargetSlide()
```


Λαμβάνει ή ορίζει το αντικείμενο διαφάνειας στο οποίο συνδέεται το Slide Zoom object. Ανάγνωση/εγγραφή [ISlide](../../com.aspose.slides/islide).

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
public abstract void setTargetSlide(ISlide value)
```


Λαμβάνει ή ορίζει το αντικείμενο διαφάνειας στο οποίο συνδέεται το Slide Zoom object. Ανάγνωση/εγγραφή [ISlide](../../com.aspose.slides/islide).

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