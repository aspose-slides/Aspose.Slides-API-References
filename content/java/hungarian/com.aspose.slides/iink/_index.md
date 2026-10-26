---
title: IInk
second_title: Aspose.Slides Java API referencia
description: Egy tintát (ink) objektumot ábrázol a dián.
type: docs
url: /hu/com.aspose.slides/iink/
---
**Összes megvalósított interfész:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface IInk extends IGraphicalObject
```

Egy tintát (ink) objektumot ábrázol a dián.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getTraces()](#getTraces--) | Megkapja az IInk elemben lévő összes nyomot [IInkTrace](../../com.aspose.slides/iinktrace). |
### getTraces() {#getTraces--}
```
public abstract IInkTrace[] getTraces()
```


Megkapja az IInk elemben lévő összes nyomot [IInkTrace](../../com.aspose.slides/iinktrace). Csak olvasható.

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


**Visszatér:**
com.aspose.slides.IInkTrace[]