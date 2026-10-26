---
title: SummaryZoomFrame
second_title: Riferimento API Java per Aspose.Slides per Android
description: Rappresenta un oggetto Summary Zoom in una diapositiva.
type: docs
url: /it/com.aspose.slides/summaryzoomframe/
---
**Ereditarietà:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**Tutte le Interfacce Implementate:**
[com.aspose.slides.ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe)
```
public class SummaryZoomFrame extends GraphicalObject implements ISummaryZoomFrame
```

Rappresenta un oggetto Summary Zoom in una diapositiva.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getLayout()](#getLayout--) | Ottiene il layout delle Sezioni Summary Zoom nel frame. |
| [getSummaryZoomCollection()](#getSummaryZoomCollection--) | Ottiene [ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection) per l'oggetto Summary Zoom Frame. |
### getLayout() {#getLayout--}
```
public final int getLayout()
```

Ottiene il layout delle Sezioni Summary Zoom nel frame. Il valore predefinito è GridLayout.

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

**Restituisce:**
int
### getSummaryZoomCollection() {#getSummaryZoomCollection--}
```
public final ISummaryZoomSectionCollection getSummaryZoomCollection()
```

Ottiene [ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection) per l'oggetto Summary Zoom Frame.

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

**Restituisce:**
[ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection)