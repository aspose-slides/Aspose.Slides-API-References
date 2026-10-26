---
title: SectionZoomFrame
second_title: Aspose.Slides για Android μέσω αναφοράς Java API
description: Αντιπροσωπεύει ένα αντικείμενο Section Zoom σε μια διαφάνεια.
type: docs
url: /el/com.aspose.slides/sectionzoomframe/
---
**Κληρονομιά:**  
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject), [com.aspose.slides.ZoomObject](../../com.aspose.slides/zoomobject)

**Όλες οι Υλοποιημένες Διεπαφές:**  
[com.aspose.slides.ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe)  
```
public class SectionZoomFrame extends ZoomObject implements ISectionZoomFrame
```

Αντιπροσωπεύει ένα αντικείμενο Section Zoom σε μια διαφάνεια.

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getTargetSection()](#getTargetSection--) | Αποκτά ή ορίζει το αντικείμενο ενότητας στο οποίο συνδέεται το αντικείμενο Section Zoom. |
| [setTargetSection(ISection value)](#setTargetSection-com.aspose.slides.ISection-) | Αποκτά ή ορίζει το αντικείμενο ενότητας στο οποίο συνδέεται το αντικείμενο Section Zoom. |

### getTargetSection() {#getTargetSection--}
```
public final ISection getTargetSection()
```

Αποκτά ή ορίζει το αντικείμενο ενότητας στο οποίο συνδέεται το αντικείμενο Section Zoom. Ανάγνωση/εγγραφή [ISection](../../com.aspose.slides/isection).

--------------------

> ```
> Next example demonstrates changing target section and creates new image for the section zoom object:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISectionZoomFrame sectionZoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1));
>      sectionZoomFrame.setTargetSection(pres.getSections().get_Item(2));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Επιστρέφει:**  
[ISection](../../com.aspose.slides/isection)

### setTargetSection(ISection value) {#setTargetSection-com.aspose.slides.ISection-}
```
public final void setTargetSection(ISection value)
```

Αποκτά ή ορίζει το αντικείμενο ενότητας στο οποίο συνδέεται το αντικείμενο Section Zoom. Ανάγνωση/εγγραφή [ISection](../../com.aspose.slides/isection).

--------------------

> ```
> Next example demonstrates changing target section and creates new image for the section zoom object:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISectionZoomFrame sectionZoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1));
>      sectionZoomFrame.setTargetSection(pres.getSections().get_Item(2));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [ISection](../../com.aspose.slides/isection) |  |