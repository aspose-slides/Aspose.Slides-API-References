---
title: IInkTrace
second_title: Aspose.Slides for Java API Reference
description: يمثل خطًا مكتوبًا يدويًا في كائن Ink.
type: docs
url: /ar/com.aspose.slides/iinktrace/
---```
public interface IInkTrace
```

يمثل خطًا مكتوبًا يدويًا في كائن Ink.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getBrush()](#getBrush--) | يحصل على Brush للـ IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) للقراءة فقط. |
| [getPoints()](#getPoints--) | يحصل على نقاط للـ IInkLine java.awt.geom.Point2D.Float للقراءة فقط. |
### getBrush() {#getBrush--}
```
public abstract IInkBrush getBrush()
```


يحصل على Brush للـ IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) للقراءة فقط.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>      IInk ink = (IInk)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IInkTrace[] traces = ink.getTraces();
>      IInkBrush brush = traces[0].getBrush();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**إرجاع:**  
[IInkBrush](../../com.aspose.slides/iinkbrush)
### getPoints() {#getPoints--}
```
public abstract Point2D.Float[] getPoints()
```


يحصل على نقاط للـ IInkLine java.awt.geom.Point2D.Float للقراءة فقط.

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

**إرجاع:**  
java.awt.geom.Point2D.Float[]