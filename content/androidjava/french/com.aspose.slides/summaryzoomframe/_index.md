---
title: SummaryZoomFrame
second_title: Aspose.Slides pour Android via la référence API Java
description: Représente un objet Summary Zoom dans une diapositive.
type: docs
url: /fr/com.aspose.slides/summaryzoomframe/
---
**Héritage :**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**Toutes les interfaces implémentées :**
[com.aspose.slides.ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe)
```
public class SummaryZoomFrame extends GraphicalObject implements ISummaryZoomFrame
```

Représente un objet Summary Zoom dans une diapositive.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getLayout()](#getLayout--) | Obtient la disposition des sections Summary Zoom dans le cadre. |
| [getSummaryZoomCollection()](#getSummaryZoomCollection--) | Obtient [ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection) pour l'objet Summary Zoom Frame. |
### getLayout() {#getLayout--}
```
public final int getLayout()
```

Obtient la disposition des sections Summary Zoom dans le cadre. La valeur par défaut est GridLayout.

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

**Returns:**
int
### getSummaryZoomCollection() {#getSummaryZoomCollection--}
```
public final ISummaryZoomSectionCollection getSummaryZoomCollection()

Obtient [ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection) pour l'objet Summary Zoom Frame.

--------------------

> ```
> L'exemple montre comment obtenir l'élément de section Summary Zoom par index :
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame)pres.getSlides().get_Item(1).getShapes().get_Item(0);
>      ISummaryZoomSectionCollection collection = zoomFrame.getSummaryZoomCollection();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Retourne :**
[ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection)