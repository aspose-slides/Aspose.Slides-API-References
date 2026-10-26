---
title: InkTrace
second_title: Aspose.Slides لنظام Android عبر مرجع API جافا
description: يمثل كائن Trace.
type: docs
url: /ar/com.aspose.slides/inktrace/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IInkTrace](../../com.aspose.slides/iinktrace)
```
public class InkTrace implements IInkTrace
```

يمثل كائن Trace. يُستخدم عنصر Trace لتسجيل البيانات التي يلتقطها الممسح الضوئي. يحتوي على تسلسل من النقاط مُشفّرة وفقًا للمواصفات التي يحددها كائن InkTraceFormat.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getBrush()](#getBrush--) | يحصل على Brush لـ IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) قراءة فقط. |
| [getPoints()](#getPoints--) | يحصل على النقاط لـ IInkLine android.graphics.PointF قراءة فقط. |
### getBrush() {#getBrush--}
```
public final IInkBrush getBrush()
```

يحصل على Brush لـ IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) قراءة فقط.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IInk ink = (IInk)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IInkTrace[] traces = ink.getTraces();
>      IInkBrush brush = traces[0].getBrush();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**القيمة المرجعة:**
[IInkBrush](../../com.aspose.slides/iinkbrush)
### getPoints() {#getPoints--}
```
public final PointF[] getPoints()
```

يحصل على النقاط لـ IInkLine android.graphics.PointF قراءة فقط.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IInk ink = (IInk)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IInkTrace[] traces = ink.getTraces();
>      android.graphics.PointF[] points = traces[0].getPoints();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**القيمة المرجعة:**
android.graphics.PointF[]