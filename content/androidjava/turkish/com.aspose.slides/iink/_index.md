---
title: IInk
second_title: Aspose.Slides for Android için Java API Referansı
description: Bir slayttaki mürekkep nesnesini temsil eder.
type: docs
url: /tr/com.aspose.slides/iink/
---
**Tüm Uygulanan Arayüzler:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface IInk extends IGraphicalObject
```

Bir slayttaki mürekkep nesnesini temsil eder.
## Yöntemler

| Metod | Açıklama |
| --- | --- |
| [getTraces()](#getTraces--) | IInk öğesinde bulunan tüm izleri alır [IInkTrace](../../com.aspose.slides/iinktrace). |
### getTraces() {#getTraces--}
```
public abstract IInkTrace[] getTraces()
```

IInk öğesinde bulunan tüm izleri alır [IInkTrace](../../com.aspose.slides/iinktrace). Salt okunur.

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

**Döndürür:**
com.aspose.slides.IInkTrace[]