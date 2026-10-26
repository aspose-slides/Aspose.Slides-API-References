---
title: SummaryZoomSection
second_title: Aspose.Slides for Android Java API-referencia
description: Egy Summary Zoom Section objektumot reprezentál egy Summary Zoom keretben.
type: docs
url: /hu/com.aspose.slides/summaryzoomsection/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject), [com.aspose.slides.ZoomObject](../../com.aspose.slides/zoomobject), [com.aspose.slides.SectionZoomFrame](../../com.aspose.slides/sectionzoomframe)

**Minden megvalósított interfész:**
[com.aspose.slides.ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection)
```
public class SummaryZoomSection extends SectionZoomFrame implements ISummaryZoomSection
```

A Summary Zoom Section objektumot egy Summary Zoom keretben reprezentálja.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getTitle()](#getTitle--) | Visszaadja a Summary Zoom Section objektum szöveges címét. |
| [setTitle(String value)](#setTitle-java.lang.String-) | Visszaadja a Summary Zoom Section objektum szöveges címét. |
| [getDescription()](#getDescription--) | Visszaadja a Summary Zoom Section objektum szöveges leírását. |
| [setDescription(String value)](#setDescription-java.lang.String-) | Visszaadja a Summary Zoom Section objektum szöveges leírását. |
### getTitle() {#getTitle--}
```
public final String getTitle()
```


Visszaadja a Summary Zoom Section objektum szöveges címét.

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setTitle("Title");
>  ```

**Visszatérési érték:**
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public final void setTitle(String value)
```


Visszaadja a Summary Zoom Section objektum szöveges címét.

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setTitle("Title");
>  ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getDescription() {#getDescription--}
```
public final String getDescription()
```


Visszaadja a Summary Zoom Section objektum szöveges leírását.

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setDescription("Description");
> ```

**Visszatérési érték:**
java.lang.String
### setDescription(String value) {#setDescription-java.lang.String-}
```
public final void setDescription(String value)
```


Visszaadja a Summary Zoom Section objektum szöveges leírását.

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setDescription("Description");
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |