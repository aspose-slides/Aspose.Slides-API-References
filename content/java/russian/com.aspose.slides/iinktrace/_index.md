---
title: IInkTrace
second_title: Aspose.Slides for Java API Reference
description: Представляет рукописную линию в объекте Ink.
type: docs
url: /ru/com.aspose.slides/iinktrace/
---```
public interface IInkTrace
```

Представляет рукописную линию в объекте Ink.
## Методы

| Метод | Описание |
| --- | --- |
| [getBrush()](#getBrush--) | Возвращает Brush для IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) Только для чтения. |
| [getPoints()](#getPoints--) | Возвращает точки для IInkLine java.awt.geom.Point2D.Float Только для чтения. |
### getBrush() {#getBrush--}
```
public abstract IInkBrush getBrush()
```


Возвращает Brush для IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) Только для чтения.

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
public abstract Point2D.Float[] getPoints()
```


Возвращает точки для IInkLine java.awt.geom.Point2D.Float Только для чтения.

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

**Возвращает:**
java.awt.geom.Point2D.Float[]