---
title: IInkTrace
second_title: Aspose.Slides Android के लिए Java API संदर्भ
description: Ink ऑब्जेक्ट में हस्तलिखित रेखा का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/iinktrace/
---```
public interface IInkTrace
```

Ink ऑब्जेक्ट में हस्तलिखित रेखा का प्रतिनिधित्व करता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getBrush()](#getBrush--) | IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) के लिए Brush प्राप्त करता है केवल-पढ़ने-योग्य। |
| [getPoints()](#getPoints--) | IInkLine android.graphics.PointF के लिए बिंदु प्राप्त करता है केवल-पढ़ने-योग्य। |

### getBrush() {#getBrush--}
```
public abstract IInkBrush getBrush()
```

IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) के लिए Brush प्राप्त करता है केवल-पढ़ने-योग्य।

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
public abstract PointF[] getPoints()
```

IInkLine android.graphics.PointF के लिए बिंदु प्राप्त करता है केवल-पढ़ने-योग्य।

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

**वापसी:**  
android.graphics.PointF[]