---
title: IInkTrace
second_title: Aspose.Slides for Android via Java API Reference
description: Represents handwritten line in an Ink object.
type: docs
url: /ar/com.aspose.slides/iinktrace/
---```
public interface IInkTrace
```

يمثل خطًا مكتوبًا يدويًا في كائن Ink.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getBrush()](#getBrush--) | يحصل على فرشاة للـ IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) للقراءة فقط. |
| [getPoints()](#getPoints--) | يحصل على نقاط للـ IInkLine android.graphics.PointF للقراءة فقط. |
### getBrush() {#getBrush--}
```
public abstract IInkBrush getBrush()
```


يحصل على فرشاة للـ IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) للقراءة فقط.

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
public abstract PointF[] getPoints()
```


يحصل على نقاط للـ IInkLine android.graphics.PointF للقراءة فقط.

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

**الإرجاع:**
android.graphics.PointF[]