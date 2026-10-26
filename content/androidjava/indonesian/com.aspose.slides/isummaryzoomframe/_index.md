---
title: ISummaryZoomFrame
second_title: Referensi API Java untuk Aspose.Slides pada Android
description: Mewakili frame Summary Zoom dalam sebuah slide.
type: docs
url: /id/com.aspose.slides/isummaryzoomframe/
---
**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface ISummaryZoomFrame extends IGraphicalObject
```

Mewakili frame Summary Zoom dalam sebuah slide.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getLayout()](#getLayout--) | Mendapatkan tata letak Summary Zoom Sections dalam frame. |
| [getSummaryZoomCollection()](#getSummaryZoomCollection--) | Mendapatkan [ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection) untuk objek Summary Zoom Frame. |
### getLayout() {#getLayout--}
```
public abstract int getLayout()
```


Mendapatkan tata letak Summary Zoom Sections dalam frame. Nilai default adalah GridLayout.

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

**Mengembalikan:**
int
### getSummaryZoomCollection() {#getSummaryZoomCollection--}
```
public abstract ISummaryZoomSectionCollection getSummaryZoomCollection()
```


Mendapatkan [ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection) untuk objek Summary Zoom Frame.

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

**Mengembalikan:**
[ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection)