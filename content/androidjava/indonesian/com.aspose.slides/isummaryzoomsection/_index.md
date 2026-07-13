---
title: ISummaryZoomSection
second_title: Aspose.Slides untuk Android via Referensi API Java
description: Mewakili objek Summary Zoom Section dalam sebuah frame Summary Zoom.
type: docs
url: /id/com.aspose.slides/isummaryzoomsection/
---
**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe)
```
public interface ISummaryZoomSection extends ISectionZoomFrame
```

Mewakili objek Summary Zoom Section dalam sebuah frame Summary Zoom.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getTitle()](#getTitle--) | Mengembalikan judul teks dari objek Summary Zoom Section. |
| [setTitle(String value)](#setTitle-java.lang.String-) | Mengembalikan judul teks dari objek Summary Zoom Section. |
| [getDescription()](#getDescription--) | Mengembalikan deskripsi teks dari objek Summary Zoom Section. |
| [setDescription(String value)](#setDescription-java.lang.String-) | Mengembalikan deskripsi teks dari objek Summary Zoom Section. |
### getTitle() {#getTitle--}
```
public abstract String getTitle()
```


Mengembalikan judul teks dari objek Summary Zoom Section.

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setTitle("Title");
>  ```

**Mengembalikan:**
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public abstract void setTitle(String value)
```


Mengembalikan judul teks dari objek Summary Zoom Section.

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setTitle("Title");
>  ```


**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |

### getDescription() {#getDescription--}
```
public abstract String getDescription()
```


Mengembalikan deskripsi teks dari objek Summary Zoom Section.

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setDescription("Description");
> ```

**Mengembalikan:**
java.lang.String
### setDescription(String value) {#setDescription-java.lang.String-}
```
public abstract void setDescription(String value)
```


Mengembalikan deskripsi teks dari objek Summary Zoom Section.

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setDescription("Description");
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |