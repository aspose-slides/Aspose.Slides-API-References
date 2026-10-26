---
title: ISummaryZoomSection
second_title: Aspose.Slides para Android mediante la referencia de API de Java
description: Representa un objeto Summary Zoom Section en un marco Summary Zoom.
type: docs
url: /es/com.aspose.slides/isummaryzoomsection/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe)
```
public interface ISummaryZoomSection extends ISectionZoomFrame
```

Representa un objeto Summary Zoom Section en un marco Summary Zoom.
## Métodos

| Método | Descripción |
| --- | --- |
| [getTitle()](#getTitle--) | Devuelve el título de texto del objeto Summary Zoom Section. |
| [setTitle(String value)](#setTitle-java.lang.String-) | Devuelve el título de texto del objeto Summary Zoom Section. |
| [getDescription()](#getDescription--) | Devuelve la descripción de texto del objeto Summary Zoom Section. |
| [setDescription(String value)](#setDescription-java.lang.String-) | Devuelve la descripción de texto del objeto Summary Zoom Section. |
### getTitle() {#getTitle--}
```
public abstract String getTitle()
```

Devuelve el título de texto del objeto Summary Zoom Section.

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setTitle("Title");
>  ```


**Devuelve:**
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public abstract void setTitle(String value)
```

Devuelve el título de texto del objeto Summary Zoom Section.

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setTitle("Title");
> ```


**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |

### getDescription() {#getDescription--}
```
public abstract String getDescription()
```

Devuelve la descripción de texto del objeto Summary Zoom Section.

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setDescription("Description");
> ```


**Devuelve:**
java.lang.String
### setDescription(String value) {#setDescription-java.lang.String-}
```
public abstract void setDescription(String value)
```

Devuelve la descripción de texto del objeto Summary Zoom Section.

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setDescription("Description");
> ```


**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |