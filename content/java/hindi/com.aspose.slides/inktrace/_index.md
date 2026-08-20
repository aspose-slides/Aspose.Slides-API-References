---
title: InkTrace
second_title: Aspose.Slides जावा के लिए API संदर्भ
description: एक Trace ऑब्जेक्ट का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/inktrace/
---
**विरासत:**
java.lang.Object

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IInkTrace](../../com.aspose.slides/iinktrace)
```
public class InkTrace implements IInkTrace
```

एक Trace ऑब्जेक्ट का प्रतिनिधित्व करता है। एक Trace तत्व डिजिटलाइज़र द्वारा कैप्चर किए गए डेटा को रिकॉर्ड करने के लिए उपयोग किया जाता है। यह InkTraceFormat ऑब्जेक्ट द्वारा दी गई विशिष्टता के अनुसार एन्कोड किए गए बिंदुओं की श्रृंखला शामिल करता है।

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getBrush()](#getBrush--) | IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) के लिए Brush प्राप्त करता है केवल-पढ़ने योग्य। |
| [getPoints()](#getPoints--) | IInkLine java.awt.geom.Point2D.Float के लिए बिंदु प्राप्त करता है केवल-पढ़ने योग्य। |

### getBrush() {#getBrush--}
```
public final IInkBrush getBrush()
```

IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) के लिए Brush प्राप्त करता है केवल-पढ़ने योग्य।

--------------------

> ```
> उदाहरण:
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


**रिटर्न:**
[IInkBrush](../../com.aspose.slides/iinkbrush)

### getPoints() {#getPoints--}
```
public final Point2D.Float[] getPoints()
```

IInkLine java.awt.geom.Point2D.Float के लिए बिंदु प्राप्त करता है केवल-पढ़ने योग्य।

--------------------

> ```
> उदाहरण:
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


**रिटर्न:**
java.awt.geom.Point2D.Float[]