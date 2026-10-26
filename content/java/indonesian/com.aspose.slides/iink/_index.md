---
title: IInk
second_title: Referensi API Aspose.Slides untuk Java
description: Mewakili objek tinta pada slide.
type: docs
url: /id/com.aspose.slides/iink/
---
**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface IInk extends IGraphicalObject
```

Mewakili objek tinta pada slide.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getTraces()](#getTraces--) | Mengambil semua jejak yang terdapat dalam elemen IInk [IInkTrace](../../com.aspose.slides/iinktrace). |
### getTraces() {#getTraces--}
```
public abstract IInkTrace[] getTraces()
```

Mengambil semua jejak yang terdapat dalam elemen IInk [IInkTrace](../../com.aspose.slides/iinktrace). Baca-saja.

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


**Mengembalikan:**
com.aspose.slides.IInkTrace[]