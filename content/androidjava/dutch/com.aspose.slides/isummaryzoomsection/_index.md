---
title: ISummaryZoomSection
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een Summary Zoom Section-object voor in een Summary Zoom-frame.
type: docs
url: /nl/com.aspose.slides/isummaryzoomsection/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe)
```
public interface ISummaryZoomSection extends ISectionZoomFrame
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
public abstract String getTitle()
```

Retourneert de teksttitel van het Summary Zoom Section-object.

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setTitle("Title");
> ```

**Retour:**
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public abstract void setTitle(String value)
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
public abstract String getDescription()
```

Retourneert de tekstbeschrijving van het Summary Zoom Section-object.

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setDescription("Description");
> ```

**Retour:**
java.lang.String
### setDescription(String value) {#setDescription-java.lang.String-}
```
public abstract void setDescription(String value)
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