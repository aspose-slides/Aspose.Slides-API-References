---
title: IInk
second_title: Aspose.Slides için Java API Referansı
description: Bir slayt üzerindeki mürekkep nesnesini temsil eder.
type: docs
url: /tr/com.aspose.slides/iink/
---
**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface IInk extends IGraphicalObject
```

Bir slayt üzerindeki mürekkep nesnesini temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getTraces()](#getTraces--) | IInk öğesinde bulunan tüm izleri alır [IInkTrace](../../com.aspose.slides/iinktrace). |
### getTraces() {#getTraces--}
```
public abstract IInkTrace[] getTraces()
```


IInk öğesinde bulunan tüm izleri alır [IInkTrace](../../com.aspose.slides/iinktrace). Salt okuma.

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