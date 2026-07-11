---
title: ISummaryZoomFrame
second_title: Aspose.Slides για Android μέσω Java API Αναφορά
description: Αντιπροσωπεύει ένα πλαίσιο Summary Zoom σε μια διαφάνεια.
type: docs
url: /el/com.aspose.slides/isummaryzoomframe/
---
**Όλες οι υλοποιημένες διεπαφές:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface ISummaryZoomFrame extends IGraphicalObject
```

Αντιπροσωπεύει ένα πλαίσιο Summary Zoom σε μια διαφάνεια.
## Μεθόδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getLayout()](#getLayout--) | Αποκτά τη διάταξη των Summary Zoom Sections στο πλαίσιο. |
| [getSummaryZoomCollection()](#getSummaryZoomCollection--) | Αποκτά [ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection) για το αντικείμενο Summary Zoom Frame. |
### getLayout() {#getLayout--}
```
public abstract int getLayout()
```


Αποκτά τη διάταξη των Summary Zoom Sections στο πλαίσιο. Η προεπιλεγμένη τιμή είναι GridLayout.

--------------------

> ```
> The example demonstrates getting Summary Zoom Section element by index:
>  
>  Presentation pres = new Presentation();
>  try {
>       ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame)pres.getSlides().get_Item(1).getShapes().get_Item(0);
>       int layout = zoomFrame.getLayout();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Επιστρέφει:**
int
### getSummaryZoomCollection() {#getSummaryZoomCollection--}
```
public abstract ISummaryZoomSectionCollection getSummaryZoomCollection()
```


Αποκτά [ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection) για το αντικείμενο Summary Zoom Frame.

--------------------

> ```
> The example demonstrates getting Summary Zoom Section element by index:
>  
>  Presentation pres = new Presentation();
>  try {
>       ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame)pres.getSlides().get_Item(1).getShapes().get_Item(0);
>       ISummaryZoomSectionCollection collection = zoomFrame.getSummaryZoomCollection();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Επιστρέφει:**
[ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection)