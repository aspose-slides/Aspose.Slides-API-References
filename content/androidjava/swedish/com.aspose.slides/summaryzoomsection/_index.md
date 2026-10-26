---
title: SummaryZoomSection
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar ett Summary Zoom Section-objekt i en Summary Zoom-ram.
type: docs
url: /sv/com.aspose.slides/summaryzoomsection/
---
**Arv:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject), [com.aspose.slides.ZoomObject](../../com.aspose.slides/zoomobject), [com.aspose.slides.SectionZoomFrame](../../com.aspose.slides/sectionzoomframe)

**Alla implementerade gränssnitt:**
[com.aspose.slides.ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection)
```
public class SummaryZoomSection extends SectionZoomFrame implements ISummaryZoomSection
```

Representerar ett Summary Zoom Section-objekt i en Summary Zoom frame.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getTitle()](#getTitle--) | Returnerar texttiteln för Summary Zoom Section-objektet. |
| [setTitle(String value)](#setTitle-java.lang.String-) | Returnerar texttiteln för Summary Zoom Section-objektet. |
| [getDescription()](#getDescription--) | Returnerar textbeskrivningen för Summary Zoom Section-objektet. |
| [setDescription(String value)](#setDescription-java.lang.String-) | Returnerar textbeskrivningen för Summary Zoom Section-objektet. |
### getTitle() {#getTitle--}
```
public final String getTitle()
```


Returnerar texttiteln för Summary Zoom Section-objektet.

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setTitle("Title");
> ```

**Returnerar:**
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public final void setTitle(String value)
```


Returnerar texttiteln för Summary Zoom Section-objektet.

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setTitle("Title");
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |

### getDescription() {#getDescription--}
```
public final String getDescription()
```


Returnerar textbeskrivningen för Summary Zoom Section-objektet.

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
public final void setDescription(String value)
```


Returnerar textbeskrivningen för Summary Zoom Section-objektet.

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setDescription("Description");
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |