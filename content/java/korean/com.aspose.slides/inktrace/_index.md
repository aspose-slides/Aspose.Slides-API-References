---
title: InkTrace
second_title: Aspose.Slides for Java API 레퍼런스
description: Trace 객체를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/inktrace/
---
**상속:**
java.lang.Object

**구현된 모든 인터페이스:**
[com.aspose.slides.IInkTrace](../../com.aspose.slides/iinktrace)
```
public class InkTrace implements IInkTrace
```

Trace 객체를 나타냅니다. Trace 요소는 디지타이저가 캡처한 데이터를 기록하는 데 사용됩니다. InkTraceFormat 객체가 제공하는 사양에 따라 인코딩된 일련의 포인트를 포함합니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getBrush()](#getBrush--) | IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush)에 대한 Brush를 가져옵니다(읽기 전용). |
| [getPoints()](#getPoints--) | IInkLine java.awt.geom.Point2D.Float에 대한 점을 가져옵니다(읽기 전용). |
### getBrush() {#getBrush--}
```
public final IInkBrush getBrush()
```

IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush)에 대한 Brush를 가져옵니다(읽기 전용).

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
public final Point2D.Float[] getPoints()
```

IInkLine java.awt.geom.Point2D.Float에 대한 점을 가져옵니다(읽기 전용).

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


**반환값:**
java.awt.geom.Point2D.Float[]