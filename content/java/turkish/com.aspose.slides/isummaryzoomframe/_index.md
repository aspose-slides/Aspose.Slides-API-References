---
title: ISummaryZoomFrame
second_title: Aspose.Slides for Java API Referansı
description: Bir slaytta Summary Zoom çerçevesini temsil eder.
type: docs
url: /tr/com.aspose.slides/isummaryzoomframe/
---
**Tüm Gerçekleştirilen Arayüzler:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface ISummaryZoomFrame extends IGraphicalObject
```

Bir slaytta Summary Zoom çerçevesini temsil eder.
## Metotlar

| Metod | Açıklama |
| --- | --- |
| [getLayout()](#getLayout--) | Çerçevedeki Summary Zoom Sections düzenini alır. |
| [getSummaryZoomCollection()](#getSummaryZoomCollection--) | [ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection)'yi Summary Zoom Frame nesnesi için alır. |
### getLayout() {#getLayout--}
```
public abstract int getLayout()
```


Çerçevedeki Summary Zoom Sections düzenini alır. Varsayılan değer GridLayout'tir.

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


[ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection)'yi Summary Zoom Frame nesnesi için alır.

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