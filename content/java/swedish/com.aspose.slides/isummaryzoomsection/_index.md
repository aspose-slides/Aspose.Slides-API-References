---
title: ISummaryZoomSection
second_title: Aspose.Slides för Java API-referens
description: Representerar ett Summary Zoom Section-objekt i en Summary Zoom-ram.
type: docs
url: /sv/com.aspose.slides/isummaryzoomsection/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe)
```
public interface ISummaryZoomSection extends ISectionZoomFrame
```

Representerar ett Summary Zoom Section object i en Summary Zoom frame.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getTitle()](#getTitle--) | Returnerar texttiteln för Summary Zoom Section object. |
| [setTitle(String value)](#setTitle-java.lang.String-) | Returnerar texttiteln för Summary Zoom Section object. |
| [getDescription()](#getDescription--) | Returnerar textbeskrivningen för Summary Zoom Section object. |
| [setDescription(String value)](#setDescription-java.lang.String-) | Returnerar textbeskrivningen för Summary Zoom Section object. |
### getTitle() {#getTitle--}
```
public abstract String getTitle()
```


Returnerar texttiteln för Summary Zoom Section object.

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setTitle("Title");
>  ```

**Returnerar:**
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public abstract void setTitle(String value)
```


Returnerar texttiteln för Summary Zoom Section object.

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setTitle("Title");
>  ```


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |

### getDescription() {#getDescription--}
```
public abstract String getDescription()
```


Returnerar textbeskrivningen för Summary Zoom Section object.

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setDescription("Description");
> ```

**Returnerar:**
java.lang.String
### setDescription(String value) {#setDescription-java.lang.String-}
```
public abstract void setDescription(String value)
```


Returnerar textbeskrivningen för Summary Zoom Section object.

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setDescription("Description");
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | |
| value | java.lang.String |  |