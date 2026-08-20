---
title: IInkTrace
second_title: Aspose.Slides Java API 레퍼런스
description: Ink 개체에 손으로 그린 선을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/iinktrace/
---```
public interface IInkTrace
```

Ink 개체에 손으로 그린 선을 나타냅니다.
## 메서드

| Method | Description |
| --- | --- |
| [getBrush()](#getBrush--) | IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush)에 대한 Brush를 가져옵니다. 읽기 전용. |
| [getPoints()](#getPoints--) | IInkLine java.awt.geom.Point2D.Float에 대한 포인트를 가져옵니다. 읽기 전용. |
### getBrush() {#getBrush--}
```
public abstract IInkBrush getBrush()
```


IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush)에 대한 Brush를 가져옵니다. 읽기 전용.

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


**반환:**
[IInkBrush](../../com.aspose.slides/iinkbrush)
### getPoints() {#getPoints--}
```
public abstract Point2D.Float[] getPoints()
```


IInkLine java.awt.geom.Point2D.Float에 대한 포인트를 가져옵니다. 읽기 전용.

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

**반환:**
java.awt.geom.Point2D.Float[]