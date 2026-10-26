---
title: IInkTrace
second_title: Aspose.Slides for Java API Reference
description: Ink ऑब्जेक्ट में हाथ से लिखी गई लाइन का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/iinktrace/
---```
public interface IInkTrace
```

Ink ऑब्जेक्ट में हाथ से लिखी गई लाइन का प्रतिनिधित्व करता है।
## विधियां

| विधि | विवरण |
| --- | --- |
| [getBrush()](#getBrush--) | Brush को IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) के लिये प्राप्त करता है केवल-पढ़ने-योग्य। |
| [getPoints()](#getPoints--) | IInkLine के लिये बिंदु java.awt.geom.Point2D.Float प्राप्त करता है केवल-पढ़ने-योग्य। |
### getBrush() {#getBrush--}
```
public abstract IInkBrush getBrush()
```


Brush को IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) के लिये प्राप्त करता है केवल-पढ़ने-योग्य।

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

**वापसी:**
[IInkBrush](../../com.aspose.slides/iinkbrush)
### getPoints() {#getPoints--}
```
public abstract Point2D.Float[] getPoints()
```


IInkLine के लिये बिंदु java.awt.geom.Point2D.Float प्राप्त करता है केवल-पढ़ने-योग्य।

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

**वापसी:**
java.awt.geom.Point2D.Float[]