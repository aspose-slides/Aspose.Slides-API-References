---
title: IInk
second_title: Aspose.Slides لمرجع API جافا
description: يمثل كائن حبر على شريحة.
type: docs
url: /ar/com.aspose.slides/iink/
---
**جميع الواجهات المُطبقة:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface IInk extends IGraphicalObject
```

يمثل كائن حبر على الشريحة.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getTraces()](#getTraces--) | يحصل على جميع الآثار الموجودة في عنصر IInk [IInkTrace](../../com.aspose.slides/iinktrace). |
### getTraces() {#getTraces--}
```
public abstract IInkTrace[] getTraces()
```


يحصل على جميع الآثار الموجودة في عنصر IInk [IInkTrace](../../com.aspose.slides/iinktrace). قراءة فقط.

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

**القيمة المرجعة:**
com.aspose.slides.IInkTrace[]