---
title: IInk
second_title: مرجع API Aspose.Slides برای Java
description: یک شیء جوهر را بر روی اسلاید نشان می‌دهد.
type: docs
url: /fa/com.aspose.slides/iink/
---
**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface IInk extends IGraphicalObject
```

یک شیء جوهر را بر روی اسلاید نشان می‌دهد.
## متدها

| متد | توضیح |
| --- | --- |
| [getTraces()](#getTraces--) | تمام ردیابی‌های موجود در عنصر IInk [IInkTrace](../../com.aspose.slides/iinktrace) را دریافت می‌کند. |
### getTraces() {#getTraces--}
```
public abstract IInkTrace[] getTraces()
```

تمام ردیابی‌های موجود در عنصر IInk [IInkTrace](../../com.aspose.slides/iinktrace) را دریافت می‌کند. فقط خواندنی.

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


**برگشت:**
com.aspose.slides.IInkTrace[]