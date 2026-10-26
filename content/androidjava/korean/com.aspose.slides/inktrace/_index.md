---
title: InkTrace
second_title: Java API 참조를 통한 Android용 Aspose.Slides
description: Trace 객체를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/inktrace/
---
**상속:**
java.lang.Object

**모든 구현된 인터페이스:**
[com.aspose.slides.IInkTrace](../../com.aspose.slides/iinktrace)
```
public class InkTrace implements IInkTrace
```

Trace 객체를 나타냅니다. Trace 요소는 디지털라이저가 캡처한 데이터를 기록하는 데 사용됩니다. 이는 InkTraceFormat 객체가 제공하는 사양에 따라 인코딩된 점들의 시퀀스를 포함합니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getBrush()](#getBrush--) | [IInkBrush](../../com.aspose.slides/iinkbrush) IInkLine에 대한 Brush를 가져옵니다. 읽기 전용. |
| [getPoints()](#getPoints--) | IInkLine android.graphics.PointF에 대한 점들을 가져옵니다. 읽기 전용. |
### getBrush() {#getBrush--}
```
public final IInkBrush getBrush()
```

[IInkBrush](../../com.aspose.slides/iinkbrush) IInkLine에 대한 Brush를 가져옵니다. 읽기 전용.

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
public final PointF[] getPoints()
```

IInkLine android.graphics.PointF에 대한 점들을 가져옵니다. 읽기 전용.

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


**반환:**
android.graphics.PointF[]