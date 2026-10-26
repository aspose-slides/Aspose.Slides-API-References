---
title: SummaryZoomFrame
second_title: Aspose.Slides for Android via Java API Referansı
description: Bir slaytta Summary Zoom nesnesini temsil eder.
type: docs
url: /tr/com.aspose.slides/summaryzoomframe/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe)
```
public class SummaryZoomFrame extends GraphicalObject implements ISummaryZoomFrame
```

Bir slaytta Summary Zoom nesnesini temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getLayout()](#getLayout--) | Çerçevedeki Summary Zoom Bölümlerinin düzenini alır. |
| [getSummaryZoomCollection()](#getSummaryZoomCollection--) | Summary Zoom Frame nesnesi için [ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection) alır. |
### getLayout() {#getLayout--}
```
public final int getLayout()
```


Çerçevedeki Summary Zoom Bölümlerinin düzenini alır. Varsayılan değer GridLayout'tir.

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


**Döndürür:**
int
### getSummaryZoomCollection() {#getSummaryZoomCollection--}
```
public final ISummaryZoomSectionCollection getSummaryZoomCollection()
```


Summary Zoom Frame nesnesi için [ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection) alır.

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


**Döndürür:**
[ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection)