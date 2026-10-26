---
title: InkTrace
second_title: مرجع API ل Aspose.Slides للـ Java
description: يمثل كائن Trace.
type: docs
url: /ar/com.aspose.slides/inktrace/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المطبقة:**
[com.aspose.slides.IInkTrace](../../com.aspose.slides/iinktrace)
```
public class InkTrace implements IInkTrace
```

يمثل كائن Trace. يُستخدم عنصر Trace لتسجيل البيانات التي يلتقطها المذبذب. يحتوي على تسلسل من النقاط المشفرة وفقًا للمواصفات التي يقدمها كائن InkTraceFormat.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getBrush()](#getBrush--) | يحصل على Brush لـ IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) قراءة فقط. |
| [getPoints()](#getPoints--) | يحصل على نقاط لـ IInkLine java.awt.geom.Point2D.Float قراءة فقط. |
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

**الإرجاع:**
[IInkBrush](../../com.aspose.slides/iinkbrush)
### getPoints() {#getPoints--}
```
public final Point2D.Float[] getPoints()
```


يحصل على نقاط لـ IInkLine java.awt.geom.Point2D.Float قراءة فقط.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IInk ink = (IInk)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IInkTrace[] traces = ink.getTraces();
>      Point2D.Float[] points = traces[0].getPoints();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**الإرجاع:**
java.awt.geom.Point2D.Float[]