---
title: IInk
second_title: Aspose.Slides pour Android via la référence API Java
description: Représente un objet d'encre sur une diapositive.
type: docs
url: /fr/com.aspose.slides/iink/
---
**Toutes les interfaces implémentées :**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface IInk extends IGraphicalObject
```

Représente un objet d'encre sur une diapositive.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getTraces()](#getTraces--) | Obtient toutes les traces contenues dans l'élément IInk [IInkTrace](../../com.aspose.slides/iinktrace). |
### getTraces() {#getTraces--}
```
public abstract IInkTrace[] getTraces()
```

Obtient toutes les traces contenues dans l'élément IInk [IInkTrace](../../com.aspose.slides/iinktrace). Lecture seule.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IInk ink = (IInk)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IInkTrace[] traces = ink.getTraces();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Renvoie :**
com.aspose.slides.IInkTrace[]