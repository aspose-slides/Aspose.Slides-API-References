---
title: IInkTrace
second_title: Aspose.Slides for Android via Java API Reference
description: Represents handwritten line in an Ink object.
type: docs
url: /ru/com.aspose.slides/iinktrace/
---```
public interface IInkTrace
```

Представляет рукописную линию в объекте Ink.

## Методы

| Метод | Описание |
| --- | --- |
| [getBrush()](#getBrush--) | Получает Brush для IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) Только для чтения. |
| [getPoints()](#getPoints--) | Получает точки для IInkLine android.graphics.PointF Только для чтения. |

### getBrush() {#getBrush--}
```
public abstract IInkBrush getBrush()
```

Получает Brush для IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) Только для чтения.

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

**Возвращает:**
[IInkBrush](../../com.aspose.slides/iinkbrush)

### getPoints() {#getPoints--}
```
public abstract PointF[] getPoints()
```

Получает точки для IInkLine android.graphics.PointF Только для чтения.

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

**Возвращает:**
android.graphics.PointF[]