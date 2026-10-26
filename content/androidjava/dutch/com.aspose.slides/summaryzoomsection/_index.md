---
title: SummaryZoomSection
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een Summary Zoom Section-object voor in een Summary Zoom-frame.
type: docs
url: /nl/com.aspose.slides/summaryzoomsection/
---
**Erfelijkheid:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject), [com.aspose.slides.ZoomObject](../../com.aspose.slides/zoomobject), [com.aspose.slides.SectionZoomFrame](../../com.aspose.slides/sectionzoomframe)

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection)
```
public class SummaryZoomSection extends SectionZoomFrame implements ISummaryZoomSection
```

Stelt een Summary Zoom Section-object voor in een Summary Zoom-frame.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getTitle()](#getTitle--) | Retourneert de teksttitel van het Summary Zoom Section-object. |
| [setTitle(String value)](#setTitle-java.lang.String-) | Retourneert de teksttitel van het Summary Zoom Section-object. |
| [getDescription()](#getDescription--) | Retourneert de tekstbeschrijving van het Summary Zoom Section-object. |
| [setDescription(String value)](#setDescription-java.lang.String-) | Retourneert de tekstbeschrijving van het Summary Zoom Section-object. |
### getTitle() {#getTitle--}
```
public final String getTitle()
```


Retourneert de teksttitel van het Summary Zoom Section-object.

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setTitle("Title");
>  ```

**Retourneert:**
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public final void setTitle(String value)
```


Retourneert de teksttitel van het Summary Zoom Section-object.

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setTitle("Title");
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getDescription() {#getDescription--}
```
public final String getDescription()
```


Retourneert de tekstbeschrijving van het Summary Zoom Section-object.

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setDescription("Description");
> ```

**Retourneert:**
java.lang.String
### setDescription(String value) {#setDescription-java.lang.String-}
```
public final void setDescription(String value)
```


Retourneert de tekstbeschrijving van het Summary Zoom Section-object.

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setDescription("Description");
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |