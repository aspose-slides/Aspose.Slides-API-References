---
title: ISummaryZoomFrame
second_title: Référence de l'API Aspose.Slides pour Android via Java
description: Représente un cadre Summary Zoom dans une diapositive.
type: docs
url: /fr/com.aspose.slides/isummaryzoomframe/
---
**Toutes les interfaces implémentées :**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface ISummaryZoomFrame extends IGraphicalObject
```

Représente un cadre Summary Zoom dans une diapositive.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getLayout()](#getLayout--) | Obtient la disposition des sections Summary Zoom dans le cadre. |
| [getSummaryZoomCollection()](#getSummaryZoomCollection--) | Obtient [ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection) pour l'objet Summary Zoom Frame. |
### getLayout() {#getLayout--}
```
public abstract int getLayout()
```


Obtient la disposition des sections Summary Zoom dans le cadre. La valeur par défaut est GridLayout.

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

**Returns:**
int
### getSummaryZoomCollection() {#getSummaryZoomCollection--}
```
public abstract ISummaryZoomSectionCollection getSummaryZoomCollection()


Obtient [ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection) pour l'objet Summary Zoom Frame.

--------------------

> ```
> L'exemple montre comment obtenir l'élément Summary Zoom Section par indice :
>  
>  Presentation pres = new Presentation();
>  try {
>       ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame)pres.getSlides().get_Item(1).getShapes().get_Item(0);
>       ISummaryZoomSectionCollection collection = zoomFrame.getSummaryZoomCollection();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Renvoie :**
[ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection)