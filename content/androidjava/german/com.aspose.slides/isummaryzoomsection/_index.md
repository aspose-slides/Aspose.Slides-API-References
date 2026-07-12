---
title: ISummaryZoomSection
second_title: Aspose.Slides für Android über Java API Referenz
description: Stellt ein Summary Zoom Section-Objekt in einem Summary Zoom Frame dar.
type: docs
url: /de/com.aspose.slides/isummaryzoomsection/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe)
```
public interface ISummaryZoomSection extends ISectionZoomFrame
```

Stellt ein Summary Zoom Section-Objekt in einem Summary Zoom Frame dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getTitle()](#getTitle--) | Gibt den Texttitel des Summary Zoom Section-Objekts zurück. |
| [setTitle(String value)](#setTitle-java.lang.String-) | Gibt den Texttitel des Summary Zoom Section-Objekts zurück. |
| [getDescription()](#getDescription--) | Gibt die Textbeschreibung des Summary Zoom Section-Objekts zurück. |
| [setDescription(String value)](#setDescription-java.lang.String-) | Gibt die Textbeschreibung des Summary Zoom Section-Objekts zurück. |
### getTitle() {#getTitle--}
```
public abstract String getTitle()
```


Gibt den Texttitel des Summary Zoom Section-Objekts zurück.

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setTitle("Title");
> ```

**Rückgabewert:**
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public abstract void setTitle(String value)
```


Gibt den Texttitel des Summary Zoom Section-Objekts zurück.

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setTitle("Title");
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |

### getDescription() {#getDescription--}
```
public abstract String getDescription()
```


Gibt die Textbeschreibung des Summary Zoom Section-Objekts zurück.

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setDescription("Description");
> ```

**Rückgabewert:**
java.lang.String
### setDescription(String value) {#setDescription-java.lang.String-}
```
public abstract void setDescription(String value)
```


Gibt die Textbeschreibung des Summary Zoom Section-Objekts zurück.

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setDescription("Description");
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |