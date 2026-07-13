---
title: ISummaryZoomSection
second_title: Aspose.Slides pro Android pomocí Java API Reference
description: Představuje objekt sekce souhrnného zoomu ve snímku souhrnného zoomu.
type: docs
url: /cs/com.aspose.slides/isummaryzoomsection/
---
**Všechny implementované rozhraní:**
[com.aspose.slides.ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe)
```
public interface ISummaryZoomSection extends ISectionZoomFrame
```

Představuje objekt sekce souhrnného zoomu ve snímku souhrnného zoomu.
## Metody

| Metoda | Popis |
| --- | --- |
| [getTitle()](#getTitle--) | Vrací textový název objektu sekce souhrnného zoomu. |
| [setTitle(String value)](#setTitle-java.lang.String-) | Vrací textový název objektu sekce souhrnného zoomu. |
| [getDescription()](#getDescription--) | Vrací textový popis objektu sekce souhrnného zoomu. |
| [setDescription(String value)](#setDescription-java.lang.String-) | Vrací textový popis objektu sekce souhrnného zoomu. |
### getTitle() {#getTitle--}
```
public abstract String getTitle()
```


Vrací textový název objektu sekce souhrnného zoomu.

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setTitle("Title");
>  ```


**Vrací:**
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public abstract void setTitle(String value)
```


Vrací textový název objektu sekce souhrnného zoomu.

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setTitle("Title");
>  ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |

### getDescription() {#getDescription--}
```
public abstract String getDescription()
```


Vrací textový popis objektu sekce souhrnného zoomu.

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setDescription("Description");
> ```


**Vrací:**
java.lang.String
### setDescription(String value) {#setDescription-java.lang.String-}
```
public abstract void setDescription(String value)
```


Vrací textový popis objektu sekce souhrnného zoomu.

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setDescription("Description");
> ```


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |