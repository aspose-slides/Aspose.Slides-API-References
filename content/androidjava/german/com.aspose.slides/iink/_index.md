---
title: IInk
second_title: Aspose.Slides für Android über die Java-API-Referenz
description: Stellt ein Tintenobjekt auf einer Folie dar.
type: docs
url: /de/com.aspose.slides/iink/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface IInk extends IGraphicalObject
```

Stellt ein Tintenobjekt auf einer Folie dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getTraces()](#getTraces--) | Ruft alle Spuren ab, die im IInk-Element [IInkTrace](../../com.aspose.slides/iinktrace) enthalten sind. |
### getTraces() {#getTraces--}
```
public abstract IInkTrace[] getTraces()
```

Ruft alle Spuren ab, die im IInk-Element [IInkTrace](../../com.aspose.slides/iinktrace) enthalten sind. Nur lesbar.

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

**Rückgabewert:**
com.aspose.slides.IInkTrace[]