---
title: SummaryZoomSection
second_title: Aspose.Slides for Android via Java API Referansı
description: Summary Zoom çerçevesinde bir Summary Zoom Section nesnesini temsil eder.
type: docs
url: /tr/com.aspose.slides/summaryzoomsection/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject), [com.aspose.slides.ZoomObject](../../com.aspose.slides/zoomobject), [com.aspose.slides.SectionZoomFrame](../../com.aspose.slides/sectionzoomframe)

**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection)
```
public class SummaryZoomSection extends SectionZoomFrame implements ISummaryZoomSection
```

Summary Zoom Section nesnesini bir Summary Zoom çerçevesinde temsil eder.
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [getTitle()](#getTitle--) | Summary Zoom Section nesnesinin metin başlığını döndürür. |
| [setTitle(String value)](#setTitle-java.lang.String-) | Summary Zoom Section nesnesinin metin başlığını döndürür. |
| [getDescription()](#getDescription--) | Summary Zoom Section nesnesinin metin açıklamasını döndürür. |
| [setDescription(String value)](#setDescription-java.lang.String-) | Summary Zoom Section nesnesinin metin açıklamasını döndürür. |
### getTitle() {#getTitle--}
```
public final String getTitle()
```


Summary Zoom Section nesnesinin metin başlığını döndürür.

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setTitle("Title");
>  ```


**Döndürür:**
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public final void setTitle(String value)
```


Summary Zoom Section nesnesinin metin başlığını döndürür.

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setTitle("Title");
>  ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### getDescription() {#getDescription--}
```
public final String getDescription()
```


Summary Zoom Section nesnesinin metin açıklamasını döndürür.

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setDescription("Description");
> ```


**Döndürür:**
java.lang.String
### setDescription(String value) {#setDescription-java.lang.String-}
```
public final void setDescription(String value)
```


Summary Zoom Section nesnesinin metin açıklamasını döndürür.

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setDescription("Description");
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |