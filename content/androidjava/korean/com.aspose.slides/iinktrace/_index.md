---
title: IInkTrace
second_title: Aspose.Slides Android용 Java API 참조
description: Ink 개체의 손글씨 선을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/iinktrace/
---```
public interface IInkTrace
```

Ink 개체의 손글씨 선을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getBrush()](#getBrush--) | IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush)에 대한 Brush를 가져옵니다. 읽기 전용. |
| [getPoints()](#getPoints--) | IInkLine android.graphics.PointF에 대한 포인트를 가져옵니다. 읽기 전용. |
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

**반환값:**
[IInkBrush](../../com.aspose.slides/iinkbrush)
### getPoints() {#getPoints--}
```
public abstract PointF[] getPoints()
```


IInkLine android.graphics.PointF에 대한 포인트를 가져옵니다. 읽기 전용.

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

**반환값:**
android.graphics.PointF[]