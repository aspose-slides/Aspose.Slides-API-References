---
title: SummaryZoomFrame
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa um objeto Summary Zoom em um slide.
type: docs
url: /pt/com.aspose.slides/summaryzoomframe/
---
**Herança:** java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**Todas as interfaces implementadas:**
[com.aspose.slides.ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe)
```
public class SummaryZoomFrame extends GraphicalObject implements ISummaryZoomFrame
```

Representa um objeto Summary Zoom em um slide.
## Métodos

| Método | Descrição |
| --- | --- |
| [getLayout()](#getLayout--) | Obtém o layout das Summary Zoom Sections no frame. |
| [getSummaryZoomCollection()](#getSummaryZoomCollection--) | Obtém [ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection) para o objeto Summary Zoom Frame. |
### getLayout() {#getLayout--}
```
public final int getLayout()
```


Obtém o layout das Summary Zoom Sections no frame. Valor padrão é GridLayout.

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


**Retorna:**
int
### getSummaryZoomCollection() {#getSummaryZoomCollection--}
```
public final ISummaryZoomSectionCollection getSummaryZoomCollection()
```


Obtém [ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection) para o objeto Summary Zoom Frame.

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


**Retorna:**
[ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection)