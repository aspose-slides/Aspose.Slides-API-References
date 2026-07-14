---
title: InkTrace
second_title: Aspose.Slides Android के लिए Java API संदर्भ के माध्यम से
description: एक Trace ऑब्जेक्ट का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/inktrace/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IInkTrace](../../com.aspose.slides/iinktrace)
```
public class InkTrace implements IInkTrace
```

एक Trace ऑब्जेक्ट का प्रतिनिधित्व करता है। एक Trace एलिमेंट का उपयोग डिज़िटाइज़र द्वारा कैप्चर किए गए डेटा को रिकॉर्ड करने के लिए किया जाता है। यह InkTraceFormat ऑब्जेक्ट द्वारा दी गई विशिष्टता के अनुसार एन्कोड किए गए बिंदुओं की एक अनुक्रम रखता है।

## विधियां

| विधि | विवरण |
| --- | --- |
| [getBrush()](#getBrush--) | IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) के लिए Brush प्राप्त करता है। केवल पढ़ने योग्य। |
| [getPoints()](#getPoints--) | IInkLine android.graphics.PointF के लिए बिंदु प्राप्त करता है। केवल पढ़ने योग्य। |
### getBrush() {#getBrush--}
```
public final IInkBrush getBrush()
```


IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) के लिए Brush प्राप्त करता है। केवल पढ़ने योग्य।

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


**रिटर्न:**
[IInkBrush](../../com.aspose.slides/iinkbrush)
### getPoints() {#getPoints--}
```
public final PointF[] getPoints()
```


IInkLine android.graphics.PointF के लिए बिंदु प्राप्त करता है। केवल पढ़ने योग्य।

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


**रिटर्न:**
android.graphics.PointF[]