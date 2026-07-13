---
title: IInk
second_title: Aspose.Slides pro Android pomocí Java API Reference
description: Představuje objekt ink na snímku.
type: docs
url: /cs/com.aspose.slides/iink/
---
**Všechny implementované rozhraní:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface IInk extends IGraphicalObject
```

Představuje objekt ink na snímku.
## Metody

| Metoda | Popis |
| --- | --- |
| [getTraces()](#getTraces--) | Získá všechny stopy obsažené v prvku IInk [IInkTrace](../../com.aspose.slides/iinktrace). |
### getTraces() {#getTraces--}
```
public abstract IInkTrace[] getTraces()
```

Získá všechny stopy obsažené v prvku IInk [IInkTrace](../../com.aspose.slides/iinktrace). Pouze pro čtení.

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


**Vrací:**
com.aspose.slides.IInkTrace[]