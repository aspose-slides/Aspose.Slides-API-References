---
title: IInk
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar ett bläckobjekt på en bild.
type: docs
url: /sv/com.aspose.slides/iink/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface IInk extends IGraphicalObject
```

Representerar ett bläckobjekt på en bild.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getTraces()](#getTraces--) | Hämtar alla spår som finns i IInk-elementet [IInkTrace](../../com.aspose.slides/iinktrace). |
### getTraces() {#getTraces--}
```
public abstract IInkTrace[] getTraces()
```


Hämtar alla spår som finns i IInk-elementet [IInkTrace](../../com.aspose.slides/iinktrace). Skrivskyddad.

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

**Returnerar:**
com.aspose.slides.IInkTrace[]