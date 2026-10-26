---
title: ISectionZoomFrame
second_title: Aspose.Slides για Android μέσω Java API Αναφορά
description: Αναπαριστά ένα αντικείμενο Section Zoom σε μια διαφάνεια.
type: docs
url: /el/com.aspose.slides/isectionzoomframe/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IZoomObject](../../com.aspose.slides/izoomobject)
```
public interface ISectionZoomFrame extends IZoomObject
```

Αναπαριστά ένα αντικείμενο Section Zoom σε μια διαφάνεια.
## Μεθόδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getTargetSection()](#getTargetSection--) | Λαμβάνει ή ορίζει το αντικείμενο ενότητας στο οποίο συνδέεται το αντικείμενο Section Zoom. |
| [setTargetSection(ISection value)](#setTargetSection-com.aspose.slides.ISection-) | Λαμβάνει ή ορίζει το αντικείμενο ενότητας στο οποίο συνδέεται το αντικείμενο Section Zoom. |
### getTargetSection() {#getTargetSection--}
```
public abstract ISection getTargetSection()
```


Λαμβάνει ή ορίζει το αντικείμενο ενότητας στο οποίο συνδέεται το αντικείμενο Section Zoom. Ανάγνωση/εγγραφή [ISection](../../com.aspose.slides/isection).

--------------------

> ```
> This example demonstrates changing target section and creates a new image for the section zoom object:
>  
>  Presentation pres = new Presentation();
>  try {
>       ISectionZoomFrame sectionZoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1));
>       sectionZoomFrame.setTargetSection(pres.getSections().get_Item(2));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Επιστρέφει:**
[ISection](../../com.aspose.slides/isection)
### setTargetSection(ISection value) {#setTargetSection-com.aspose.slides.ISection-}
```
public abstract void setTargetSection(ISection value)
```


Λαμβάνει ή ορίζει το αντικείμενο ενότητας στο οποίο συνδέεται το αντικείμενο Section Zoom. Ανάγνωση/εγγραφή [ISection](../../com.aspose.slides/isection).

--------------------

> ```
> This example demonstrates changing target section and creates a new image for the section zoom object:
>  
>  Presentation pres = new Presentation();
>  try {
>       ISectionZoomFrame sectionZoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1));
>       sectionZoomFrame.setTargetSection(pres.getSections().get_Item(2));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [ISection](../../com.aspose.slides/isection) |  