---
title: SummaryZoomFrame
second_title: Aspose.Slides untuk Android melalui Referensi API Java
description: Mewakili objek Summary Zoom dalam slide.
type: docs
url: /id/com.aspose.slides/summaryzoomframe/
---
**Pewarisan:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe)
```
public class SummaryZoomFrame extends GraphicalObject implements ISummaryZoomFrame
```

Mewakili objek Summary Zoom dalam slide.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getLayout()](#getLayout--) | Mendapatkan layout Summary Zoom Sections dalam frame. |
| [getSummaryZoomCollection()](#getSummaryZoomCollection--) | Mendapatkan [ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection) untuk objek Summary Zoom Frame. |
### getLayout() {#getLayout--}
```
public final int getLayout()
```


Mendapatkan layout Summary Zoom Sections dalam frame. Nilai default adalah GridLayout.

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

**Mengembalikan:**
int
### getSummaryZoomCollection() {#getSummaryZoomCollection--}
```
public final ISummaryZoomSectionCollection getSummaryZoomCollection()
```


Mendapatkan [ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection) untuk objek Summary Zoom Frame.

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

**Mengembalikan:**
[ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection)