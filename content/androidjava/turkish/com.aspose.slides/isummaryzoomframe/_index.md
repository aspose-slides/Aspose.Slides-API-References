---
title: ISummaryZoomFrame
second_title: Aspose.Slides for Android via Java API Referansı
description: Bir slaytta Summary Zoom çerçevesini temsil eder.
type: docs
url: /tr/com.aspose.slides/isummaryzoomframe/
---
**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface ISummaryZoomFrame extends IGraphicalObject
```

Bir slaytta Summary Zoom çerçevesini temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getLayout()](#getLayout--) | Çerçevedeki Summary Zoom Sections layout'ı alır. |
| [getSummaryZoomCollection()](#getSummaryZoomCollection--) | Summary Zoom Frame nesnesi için [ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection) alır. |
### getLayout() {#getLayout--}
```
public abstract int getLayout()
```

Çerçevedeki Summary Zoom Sections layout'ı alır. Varsayılan değer GridLayout'tir.

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

**Döndürür:**
int
### getSummaryZoomCollection() {#getSummaryZoomCollection--}
```
public abstract ISummaryZoomSectionCollection getSummaryZoomCollection()
```

Summary Zoom Frame nesnesi için [ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection) alır.

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

**Döndürür:**
[ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection)