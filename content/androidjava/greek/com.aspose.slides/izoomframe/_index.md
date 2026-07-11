---
title: IZoomFrame
second_title: Aspose.Slides για Android μέσω αναφοράς Java API
description: Αντιπροσωπεύει ένα αντικείμενο Slide Zoom σε μια διαφάνεια.
type: docs
url: /el/com.aspose.slides/izoomframe/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IZoomObject](../../com.aspose.slides/izoomobject)
```
public interface IZoomFrame extends IZoomObject
```

Αντιπροσωπεύει ένα αντικείμενο Slide Zoom σε μια Slide.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getTargetSlide()](#getTargetSlide--) | Λαμβάνει ή ορίζει το αντικείμενο slide που το αντικείμενο Slide Zoom συνδέει. |
| [setTargetSlide(ISlide value)](#setTargetSlide-com.aspose.slides.ISlide-) | Λαμβάνει ή ορίζει το αντικείμενο slide που το αντικείμενο Slide Zoom συνδέει. |
### getTargetSlide() {#getTargetSlide--}
```
public abstract ISlide getTargetSlide()
```


Λαμβάνει ή ορίζει το αντικείμενο slide που το αντικείμενο Slide Zoom συνδέει. Ανάγνωση/εγγραφή [ISlide](../../com.aspose.slides/islide).

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


Λαμβάνει ή ορίζει το αντικείμενο slide που το αντικείμενο Slide Zoom συνδέει. Ανάγνωση/εγγραφή [ISlide](../../com.aspose.slides/islide).

--------------------

> ```
> Το επόμενο παράδειγμα δείχνει την αλλαγή της διαφάνειας-στόχου και δημιουργεί μια νέα εικόνα για το αντικείμενο Slide Zoom:
>  
>  IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>  zoomFrame.setTargetSlide(pres.getSlides().get_Item(2));
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [ISlide](../../com.aspose.slides/islide) |  |