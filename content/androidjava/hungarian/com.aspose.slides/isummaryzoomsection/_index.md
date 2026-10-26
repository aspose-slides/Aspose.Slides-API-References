---
title: ISummaryZoomSection
second_title: Aspose.Slides Androidra Java API referencia
description: Egy Summary Zoom keretben a Summary Zoom Section objektumot reprezentálja.
type: docs
url: /hu/com.aspose.slides/isummaryzoomsection/
---
**Minden megvalósított interfész:**
[com.aspose.slides.ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe)
```
public interface ISummaryZoomSection extends ISectionZoomFrame
```

Egy Summary Zoom keretben a Summary Zoom Section objektumot reprezentálja.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getTitle()](#getTitle--) | Visszaadja a Summary Zoom Section objektum szövegcímét. |
| [setTitle(String value)](#setTitle-java.lang.String-) | Visszaadja a Summary Zoom Section objektum szövegcímét. |
| [getDescription()](#getDescription--) | Visszaadja a Summary Zoom Section objektum szöveges leírását. |
| [setDescription(String value)](#setDescription-java.lang.String-) | Visszaadja a Summary Zoom Section objektum szöveges leírását. |
### getTitle() {#getTitle--}
```
public abstract String getTitle()
```

Visszaadja a Summary Zoom Section objektum szövegcímét.

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setTitle("Title");
>  ```


**Visszatér:**  
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public abstract void setTitle(String value)
```

Visszaadja a Summary Zoom Section objektum szövegcímét.

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
public abstract String getDescription()
```

Visszaadja a Summary Zoom Section objektum szöveges leírását.

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setDescription("Description");
>  ```

**Visszatér:**  
java.lang.String
### setDescription(String value) {#setDescription-java.lang.String-}
```
public abstract void setDescription(String value)
```

Visszaadja a Summary Zoom Section objektum szöveges leírását.

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setDescription("Description");
>  ```

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |