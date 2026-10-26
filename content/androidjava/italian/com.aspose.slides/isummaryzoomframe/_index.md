---
title: ISummaryZoomFrame
second_title: Riferimento API Java di Aspose.Slides per Android
description: Rappresenta un frame di riepilogo Zoom in una diapositiva.
type: docs
url: /it/com.aspose.slides/isummaryzoomframe/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface ISummaryZoomFrame extends IGraphicalObject
```

Rappresenta un frame di riepilogo Zoom in una diapositiva.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getLayout()](#getLayout--) | Ottiene il layout delle sezioni di riepilogo Zoom nel frame. |
| [getSummaryZoomCollection()](#getSummaryZoomCollection--) | Ottiene [ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection) per l'oggetto Summary Zoom Frame. |
### getLayout() {#getLayout--}
```
public abstract int getLayout()
```


Ottiene il layout delle sezioni di riepilogo Zoom nel frame. Il valore predefinito è GridLayout.

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


**Restituisce:**
int
### getSummaryZoomCollection() {#getSummaryZoomCollection--}
```
public abstract ISummaryZoomSectionCollection getSummaryZoomCollection()
```


Ottiene [ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection) per l'oggetto Summary Zoom Frame.

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

**Restituisce:**
[ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection)