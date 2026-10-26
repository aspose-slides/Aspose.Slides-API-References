---
title: ISummaryZoomSection
second_title: Aspose.Slides for Android için Java API Referansı
description: Summary Zoom çerçevesinde bir Summary Zoom Section nesnesini temsil eder.
type: docs
url: /tr/com.aspose.slides/isummaryzoomsection/
---
**Tüm Uygulanan Arayüzler:**
[com.aspose.slides.ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe)
```
public interface ISummaryZoomSection extends ISectionZoomFrame
```

Summary Zoom çerçevesinde bir Summary Zoom Section nesnesini temsil eder.
## Yöntemler

| Metot | Açıklama |
| --- | --- |
| [getTitle()](#getTitle--) | Summary Zoom Section nesnesinin metin başlığını döndürür. |
| [setTitle(String value)](#setTitle-java.lang.String-) | Summary Zoom Section nesnesinin metin başlığını döndürür. |
| [getDescription()](#getDescription--) | Summary Zoom Section nesnesinin metin açıklamasını döndürür. |
| [setDescription(String value)](#setDescription-java.lang.String-) | Summary Zoom Section nesnesinin metin açıklamasını döndürür. |
### getTitle() {#getTitle--}
```
public abstract String getTitle()
```


Summary Zoom Section nesnesinin metin başlığını döndürür.

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setTitle("Title");
> ```

**Döndürür:**
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public abstract void setTitle(String value)
```


Summary Zoom Section nesnesinin metin başlığını döndürür.

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setTitle("Title");
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### getDescription() {#getDescription--}
```
public abstract String getDescription()
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
public abstract void setDescription(String value)
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