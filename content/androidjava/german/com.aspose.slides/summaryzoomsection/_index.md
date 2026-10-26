---
title: SummaryZoomSection
second_title: Aspose.Slides für Android über die Java-API-Referenz
description: Stellt ein Summary Zoom Section-Objekt in einem Summary Zoom-Frame dar.
type: docs
url: /de/com.aspose.slides/summaryzoomsection/
---
**Vererbung:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject), [com.aspose.slides.ZoomObject](../../com.aspose.slides/zoomobject), [com.aspose.slides.SectionZoomFrame](../../com.aspose.slides/sectionzoomframe)

**Alle implementierten Schnittstellen:**
[com.aspose.slides.ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection)
```
public class SummaryZoomSection extends SectionZoomFrame implements ISummaryZoomSection
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
public final String getTitle()
```


Gibt den Texttitel des Summary Zoom Section-Objekts zurück.

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setTitle("Title");
>  ```

**Rückgabe:**
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public final void setTitle(String value)
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
public final String getDescription()
```


Gibt die Textbeschreibung des Summary Zoom Section-Objekts zurück.

--------------------

> ```
> Beispiel:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setDescription("Description");
> ```


**Rückgabe:**
java.lang.String
### setDescription(String value) {#setDescription-java.lang.String-}
```
public final void setDescription(String value)
```


Gibt die Textbeschreibung des Summary Zoom Section-Objekts zurück.

--------------------

> ```
> Beispiel:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setDescription("Description");
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |