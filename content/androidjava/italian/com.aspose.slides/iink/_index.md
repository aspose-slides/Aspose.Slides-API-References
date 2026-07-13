---
title: IInk
second_title: Aspose.Slides per Android via Riferimento API Java
description: Rappresenta un oggetto inchiostro su una diapositiva.
type: docs
url: /it/com.aspose.slides/iink/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface IInk extends IGraphicalObject
```

Rappresenta un oggetto inchiostro su una diapositiva.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getTraces()](#getTraces--) | Recupera tutte le tracce contenute nell'elemento IInk [IInkTrace](../../com.aspose.slides/iinktrace). |
### getTraces() {#getTraces--}
```
public abstract IInkTrace[] getTraces()
```


Recupera tutte le tracce contenute nell'elemento IInk [IInkTrace](../../com.aspose.slides/iinktrace). Sola lettura.

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

**Restituisce:**
com.aspose.slides.IInkTrace[]