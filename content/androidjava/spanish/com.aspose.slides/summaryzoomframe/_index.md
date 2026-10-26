---
title: SummaryZoomFrame
second_title: Aspose.Slides para Android a través de la referencia de API Java
description: Representa un objeto Summary Zoom en una diapositiva.
type: docs
url: /es/com.aspose.slides/summaryzoomframe/
---
**Herencia:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**Todas las interfaces implementadas:**
[com.aspose.slides.ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe)
```
public class SummaryZoomFrame extends GraphicalObject implements ISummaryZoomFrame
```

Representa un objeto Summary Zoom en una diapositiva.
## Métodos

| Método | Descripción |
| --- | --- |
| [getLayout()](#getLayout--) | Obtiene el diseño de las secciones Summary Zoom en el marco. |
| [getSummaryZoomCollection()](#getSummaryZoomCollection--) | Obtiene [ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection) para el objeto Summary Zoom Frame. |
### getLayout() {#getLayout--}
```
public final int getLayout()
```


Obtiene el diseño de las secciones Summary Zoom en el marco. El valor predeterminado es GridLayout.

--------------------

> ```
> The example demonstrates getting Summary Zoom Section element by index:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame)pres.getSlides().get_Item(1).getShapes().get_Item(0);
>      int layout = zoomFrame.getLayout();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Devuelve:**
int
### getSummaryZoomCollection() {#getSummaryZoomCollection--}
```
public final ISummaryZoomSectionCollection getSummaryZoomCollection()
```


Obtiene [ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection) para el objeto Summary Zoom Frame.

--------------------

> ```
> The example demonstrates getting Summary Zoom Section element by index:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame)pres.getSlides().get_Item(1).getShapes().get_Item(0);
>      ISummaryZoomSectionCollection collection = zoomFrame.getSummaryZoomCollection();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Devuelve:**
[ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection)