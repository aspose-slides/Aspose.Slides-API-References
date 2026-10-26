---
title: IInk
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایانگر یک شیء جوهر بر روی اسلاید است.
type: docs
url: /fa/com.aspose.slides/iink/
---
**تمام اینترفیس‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface IInk extends IGraphicalObject
```

نمایانگر یک شیء جوهر بر روی اسلاید است.
## متدها

| متد | توضیح |
| --- | --- |
| [getTraces()](#getTraces--) | تمام ردیاب‌های موجود در عنصر IInk [IInkTrace](../../com.aspose.slides/iinktrace) را دریافت می‌کند. |
### getTraces() {#getTraces--}
```
public abstract IInkTrace[] getTraces()
```

تمام ردیاب‌های موجود در عنصر IInk [IInkTrace](../../com.aspose.slides/iinktrace) را دریافت می‌کند. فقط‌خواندنی.

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

**بازمی‌گرداند:**
com.aspose.slides.IInkTrace[]