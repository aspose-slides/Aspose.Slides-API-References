---
title: ISummaryZoomFrame
second_title: Referência da API Aspose.Slides para Java
description: Representa um quadro Summary Zoom em um slide.
type: docs
url: /pt/com.aspose.slides/isummaryzoomframe/
---
**Todas as Interfaces Implementadas:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface ISummaryZoomFrame extends IGraphicalObject
```

Representa um quadro Summary Zoom em um slide.

## Métodos

| Método | Descrição |
| --- | --- |
| [getLayout()](#getLayout--) | Obtém o layout das Summary Zoom Sections no quadro. |
| [getSummaryZoomCollection()](#getSummaryZoomCollection--) | Obtém [ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection) para o objeto Summary Zoom Frame. |

### getLayout() {#getLayout--}
```
public abstract int getLayout()
```

Obtém o layout das Summary Zoom Sections no quadro. O valor padrão é GridLayout.

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

**Retorna:**
int

### getSummaryZoomCollection() {#getSummaryZoomCollection--}
```
public abstract ISummaryZoomSectionCollection getSummaryZoomCollection()
```

Obtém [ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection) para o objeto Summary Zoom Frame.

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

**Retorna:**
[ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection)