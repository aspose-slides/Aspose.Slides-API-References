---
title: IInk
second_title: Aspose.Slides dla Androida poprzez odwołanie API Java
description: Reprezentuje obiekt tuszu na slajdzie.
type: docs
url: /pl/com.aspose.slides/iink/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface IInk extends IGraphicalObject
```

Reprezentuje obiekt tuszu na slajdzie.
## Metody

| Metoda | Opis |
| --- | --- |
| [getTraces()](#getTraces--) | Pobiera wszystkie ślady zawarte w elemencie IInk [IInkTrace](../../com.aspose.slides/iinktrace). |
### getTraces() {#getTraces--}
```
public abstract IInkTrace[] getTraces()
```

Pobiera wszystkie ślady zawarte w elemencie IInk [IInkTrace](../../com.aspose.slides/iinktrace). Tylko do odczytu.

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

**Zwraca:**
com.aspose.slides.IInkTrace[]