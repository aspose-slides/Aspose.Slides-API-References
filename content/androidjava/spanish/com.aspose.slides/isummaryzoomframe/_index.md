---
title: ISummaryZoomFrame
second_title: Aspose.Slides para Android mediante la referencia de la API Java
description: Representa un marco Summary Zoom en una diapositiva.
type: docs
url: /es/com.aspose.slides/isummaryzoomframe/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface ISummaryZoomFrame extends IGraphicalObject
```

Representa un marco Summary Zoom en una diapositiva.
## Métodos

| Método | Descripción |
| --- | --- |
| [getLayout()](#getLayout--) | Obtiene el diseño de las secciones Summary Zoom en el marco. |
| [getSummaryZoomCollection()](#getSummaryZoomCollection--) | Obtiene [ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection) para el objeto Summary Zoom Frame. |
### getLayout() {#getLayout--}
```
public abstract int getLayout()
```

Obtiene el diseño de las secciones Summary Zoom en el marco. El valor predeterminado es GridLayout.

--------------------

> ```
> The example demonstrates getting Summary Zoom Section element by index:
>  
>  Presentation pres = new Presentation();
>  try {
>       ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame)pres.getSlides().get_Item(1).getShapes().get_Item(0);
>       int layout = zoomFrame.getLayout();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Devuelve:**
int
### getSummaryZoomCollection() {#getSummaryZoomCollection--}
```
public abstract ISummaryZoomSectionCollection getSummaryZoomCollection()
```

Obtiene [ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection) para el objeto Summary Zoom Frame.

--------------------

> ```
> The example demonstrates getting Summary Zoom Section element by index:
>  
>  Presentation pres = new Presentation();
>  try {
>       ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame)pres.getSlides().get_Item(1).getShapes().get_Item(0);
>       ISummaryZoomSectionCollection collection = zoomFrame.getSummaryZoomCollection();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Devuelve:**
[ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection)