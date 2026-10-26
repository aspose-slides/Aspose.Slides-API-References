---
title: IInk
second_title: Aspose.Slides para Android mediante la API de Java
description: Representa un objeto de tinta en una diapositiva.
type: docs
url: /es/com.aspose.slides/iink/
---
**Todas las Interfaces Implementadas:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface IInk extends IGraphicalObject
```

Representa un objeto de tinta en una diapositiva.
## Métodos

| Método | Descripción |
| --- | --- |
| [getTraces()](#getTraces--) | Obtiene todas las trazas contenidas en el elemento IInk [IInkTrace](../../com.aspose.slides/iinktrace). |
### getTraces() {#getTraces--}
```
public abstract IInkTrace[] getTraces()
```

Obtiene todas las trazas contenidas en el elemento IInk [IInkTrace](../../com.aspose.slides/iinktrace). Solo lectura.

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

**Devuelve:**
com.aspose.slides.IInkTrace[]