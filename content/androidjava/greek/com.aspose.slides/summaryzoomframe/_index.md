---
title: SummaryZoomFrame
second_title: Aspose.Slides για Android μέσω αναφοράς Java API
description: Αναπαριστά ένα αντικείμενο Summary Zoom σε μια διαφράση.
type: docs
url: /el/com.aspose.slides/summaryzoomframe/
---
**Κληρονομιά:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe)
```
public class SummaryZoomFrame extends GraphicalObject implements ISummaryZoomFrame
```

Αναπαριστά ένα αντικείμενο Summary Zoom σε μια διαφράση.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getLayout()](#getLayout--) | Λαμβάνει τη διάταξη των τμημάτων Summary Zoom στο πλαίσιο. |
| [getSummaryZoomCollection()](#getSummaryZoomCollection--) | Λαμβάνει [ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection) για το αντικείμενο Summary Zoom Frame. |
### getLayout() {#getLayout--}
```
public final int getLayout()
```


Λαμβάνει τη διάταξη των τμημάτων Summary Zoom στο πλαίσιο. Η προεπιλεγμένη τιμή είναι GridLayout.

--------------------

> ```
> The example demonstrates getting Summary Zoom Section element by index:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame)pres.getSlides().get_Item(1).getShapes().get_Item(0);
>      int layout = zoomFrame.getLayout();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Επιστρέφει:**
int
### getSummaryZoomCollection() {#getSummaryZoomCollection--}
```
public final ISummaryZoomSectionCollection getSummaryZoomCollection()
```


Λαμβάνει [ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection) για το αντικείμενο Summary Zoom Frame.

--------------------

> ```
> The example demonstrates getting Summary Zoom Section element by index:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame)pres.getSlides().get_Item(1).getShapes().get_Item(0);
>      ISummaryZoomSectionCollection collection = zoomFrame.getSummaryZoomCollection();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Επιστρέφει:**
[ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection)