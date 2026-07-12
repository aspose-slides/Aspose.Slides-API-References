---
title: IInk
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa um objeto de tinta em um slide.
type: docs
url: /pt/com.aspose.slides/iink/
---
**Todas as Interfaces Implementadas:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface IInk extends IGraphicalObject
```

Representa um objeto de tinta em um slide.
## Métodos

| Método | Descrição |
| --- | --- |
| [getTraces()](#getTraces--) | Obtém todos os traços contidos no elemento IInk [IInkTrace](../../com.aspose.slides/iinktrace). |
### getTraces() {#getTraces--}
```
public abstract IInkTrace[] getTraces()
```


Obtém todos os traços contidos no elemento IInk [IInkTrace](../../com.aspose.slides/iinktrace). Somente leitura.

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

**Retorna:**
com.aspose.slides.IInkTrace[]