---
title: IInk
second_title: Aspose.Slides for Android Java API hivatkozás
description: Egy tintát tartalmazó objektumot ábrázol egy dián.
type: docs
url: /hu/com.aspose.slides/iink/
---
**Minden megvalósított interfész:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface IInk extends IGraphicalObject
```

Egy tintát tartalmazó objektumot ábrázol egy dián.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getTraces()](#getTraces--) | Az IInk elemben lévő összes nyomot adja vissza [IInkTrace](../../com.aspose.slides/iinktrace). |
### getTraces() {#getTraces--}
```
public abstract IInkTrace[] getTraces()
```


Az IInk elemben lévő összes nyomot adja vissza [IInkTrace](../../com.aspose.slides/iinktrace). Csak olvasható.

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


**Visszatérési érték:**
com.aspose.slides.IInkTrace[]