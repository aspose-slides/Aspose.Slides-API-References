---
title: IInk
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een inktobject op een dia voor.
type: docs
url: /nl/com.aspose.slides/iink/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface IInk extends IGraphicalObject
```

Stelt een inktobject op een dia voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getTraces()](#getTraces--) | Haalt alle sporen op die zich in het IInk-element [IInkTrace](../../com.aspose.slides/iinktrace) bevinden. |
### getTraces() {#getTraces--}
```
public abstract IInkTrace[] getTraces()
```


Haalt alle sporen op die zich in het IInk-element [IInkTrace](../../com.aspose.slides/iinktrace) bevinden. Alleen-lezen.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>      IInk ink = (IInk)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IInkTrace[] traces = ink.getTraces();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Retour:**
com.aspose.slides.IInkTrace[]