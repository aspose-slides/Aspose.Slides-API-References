---
title: ChartPlotArea
second_title: Aspose.Slides for Java API संदर्भ
description: ऐसा आयत दर्शाता है जहाँ चार्ट प्लॉट किया जाना चाहिए।
type: docs
url: /hi/com.aspose.slides/chartplotarea/
---
**विरासत:**
java.lang.Object, com.aspose.slides.DomObject

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IChartPlotArea](../../com.aspose.slides/ichartplotarea)
```
public class ChartPlotArea extends DomObject<Chart> implements IChartPlotArea
```

चार्ट जहाँ प्लॉट किया जाना चाहिए, उसका आयत निरूपित करता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getFormat()](#getFormat--) | एक प्लॉट एरिया का स्वरूप लौटाता है। |
| [getX()](#getX--) | प्लॉट एरिया बाउंडिंग बॉक्स के ऊपरी बाएँ कोने के x निर्देशांक को चार्ट की चौड़ाई के भाग के रूप में (0 से 1 तक) लौटाता है या सेट करता है। |
| [setX(float value)](#setX-float-) | प्लॉट एरिया बाउंडिंग बॉक्स के ऊपरी बाएँ कोने के x निर्देशांक को चार्ट की चौड़ाई के भाग के रूप में (0 से 1 तक) लौटाता है या सेट करता है। |
| [getY()](#getY--) | प्लॉट एरिया बाउंडिंग बॉक्स के ऊपरी बाएँ कोने के y निर्देशांक को चार्ट की ऊँचाई के भाग के रूप में (0 से 1 तक) लौटाता है या सेट करता है। |
| [setY(float value)](#setY-float-) | प्लॉट एरिया बाउंडिंग बॉक्स के ऊपरी बाएँ कोने के y निर्देशांक को चार्ट की ऊँचाई के भाग के रूप में (0 से 1 तक) लौटाता है या सेट करता है। |
| [getWidth()](#getWidth--) | प्लॉट एरिया बाउंडिंग बॉक्स की चौड़ाई को चार्ट की चौड़ाई के भाग के रूप में (0 से 1 तक) लौटाता है या सेट करता है। |
| [setWidth(float value)](#setWidth-float-) | प्लॉट एरिया बाउंडिंग बॉक्स की चौड़ाई को चार्ट की चौड़ाई के भाग के रूप में (0 से 1 तक) लौटाता है या सेट करता है। |
| [getHeight()](#getHeight--) | प्लॉट एरिया बाउंडिंग बॉक्स की ऊँचाई को चार्ट की ऊँचाई के भाग के रूप में (0 से 1 तक) लौटाता है या सेट करता है। |
| [setHeight(float value)](#setHeight-float-) | प्लॉट एरिया बाउंडिंग बॉक्स की ऊँचाई को चार्ट की ऊँचाई के भाग के रूप में (0 से 1 तक) लौटाता है या सेट करता है। |
| [getRight()](#getRight--) | दाएँ। |
| [getBottom()](#getBottom--) | नीचे। |
| [getChart()](#getChart--) | चार्ट। |
| [isLocationAutocalculated()](#isLocationAutocalculated--) | निर्धारित करता है कि स्थान कैसे गणना किया जाना चाहिए: true \\u2013 स्वचालित रूप से गणना किया गया; X, Y, Width, Height गुणों द्वारा परिभाषित। |
| [getLayoutTargetType()](#getLayoutTargetType--) | यदि प्लॉट एरिया का लेआउट मैन्युअल रूप से परिभाषित किया गया है तो यह प्रॉपर्टी निर्धारित करती है कि प्लॉट एरिया को उसके अंदर (अक्ष और अक्ष लेबल को शामिल नहीं) या बाहर (अक्ष और अक्ष लेबल सहित) लेआउट किया जाए। |
| [setLayoutTargetType(int value)](#setLayoutTargetType-int-) | यदि प्लॉट एरिया का लेआउट मैन्युअल रूप से परिभाषित किया गया है तो यह प्रॉपर्टी निर्धारित करती है कि प्लॉट एरिया को उसके अंदर (अक्ष और अक्ष लेबल को शामिल नहीं) या बाहर (अक्ष और अक्ष लेबल सहित) लेआउट किया जाए। |
| [getActualX()](#getActualX--) | चार्ट तत्व के वास्तविक x स्थान (बाएँ) को चार्ट के बाएँ शीर्ष कोने के सापेक्ष निर्दिष्ट करता है। |
| [getActualY()](#getActualY--) | चार्ट तत्व के वास्तविक शीर्ष को चार्ट के बाएँ शीर्ष कोने के सापेक्ष निर्दिष्ट करता है। |
| [getActualWidth()](#getActualWidth--) | चार्ट तत्व की वास्तविक चौड़ाई को निर्दिष्ट करता है। |
| [getActualHeight()](#getActualHeight--) | चार्ट तत्व की वास्तविक ऊँचाई को निर्दिष्ट करता है। |
| [getSlide()](#getSlide--) | एक FillFormat की मूल स्लाइड लौटाता है। |
| [getPresentation()](#getPresentation--) | एक FillFormat की मूल प्रस्तुति लौटाता है। |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

एक प्लॉट एरिया का स्वरूप लौटाता है। केवल पढ़ने योग्य [IFormat](../../com.aspose.slides/iformat)।

**वापसी:**
[IFormat](../../com.aspose.slides/iformat)

### getX() {#getX--}
```
public final float getX()
```

प्लॉट एरिया बाउंडिंग बॉक्स के ऊपरी बाएँ कोने के x निर्देशांक को चार्ट की चौड़ाई के भाग के रूप में (0 से 1 तक) लौटाता है या सेट करता है। पढ़ें/लिखें float.

**वापसी:**
float

### setX(float value) {#setX-float-}
```
public final void setX(float value)
```

प्लॉट एरिया बाउंडिंग बॉक्स के ऊपरी बाएँ कोने के x निर्देशांक को चार्ट की चौड़ाई के भाग के रूप में (0 से 1 तक) लौटाता है या सेट करता है। पढ़ें/लिखें float.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### getY() {#getY--}
```
public final float getY()
```

प्लॉट एरिया बाउंडिंग बॉक्स के ऊपरी बाएँ कोने के y निर्देशांक को चार्ट की ऊँचाई के भाग के रूप में (0 से 1 तक) लौटाता है या सेट करता है। पढ़ें/लिखें float.

**वापसी:**
float

### setY(float value) {#setY-float-}
```
public final void setY(float value)
```

प्लॉट एरिया बाउंडिंग बॉक्स के ऊपरी बाएँ कोने के y निर्देशांक को चार्ट की ऊँचाई के भाग के रूप में (0 से 1 तक) लौटाता है या सेट करता है। पढ़ें/लिखें float.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### getWidth() {#getWidth--}
```
public final float getWidth()
```

प्लॉट एरिया बाउंडिंग बॉक्स की चौड़ाई को चार्ट की चौड़ाई के भाग के रूप में (0 से 1 तक) लौटाता है या सेट करता है। पढ़ें/लिखें float.

**वापसी:**
float

### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```

प्लॉट एरिया बाउंडिंग बॉक्स की चौड़ाई को चार्ट की चौड़ाई के भाग के रूप में (0 से 1 तक) लौटाता है या सेट करता है। पढ़ें/लिखें float.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### getHeight() {#getHeight--}
```
public final float getHeight()
```

प्लॉट एरिया बाउंडिंग बॉक्स की ऊँचाई को चार्ट की ऊँचाई के भाग के रूप में (0 से 1 तक) लौटाता है या सेट करता है। पढ़ें/लिखें float.

**वापसी:**
float

### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```

प्लॉट एरिया बाउंडिंग बॉक्स की ऊँचाई को चार्ट की ऊँचाई के भाग के रूप में (0 से 1 तक) लौटाता है या सेट करता है। पढ़ें/लिखें float.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### getRight() {#getRight--}
```
public final float getRight()
```

दाएँ। केवल पढ़ने योग्य float.

**वापसी:**
float

### getBottom() {#getBottom--}
```
public final float getBottom()
```

नीचे। केवल पढ़ने योग्य float.

**वापसी:**
float

### getChart() {#getChart--}
```
public final IChart getChart()
```

चार्ट। केवल पढ़ने योग्य [IChart](../../com.aspose.slides/ichart)।

**वापसी:**
[IChart](../../com.aspose.slides/ichart)

### isLocationAutocalculated() {#isLocationAutocalculated--}
```
public final boolean isLocationAutocalculated()
```

निर्धारित करता है कि स्थान कैसे गणना किया जाना चाहिए: true \\u2013 स्वचालित रूप से गणना किया गया; X, Y, Width, Height गुणों द्वारा परिभाषित। केवल पढ़ने योग्य boolean.

**वापसी:**
boolean

### getLayoutTargetType() {#getLayoutTargetType--}
```
public final int getLayoutTargetType()
```

यदि प्लॉट एरिया का लेआउट मैन्युअल रूप से परिभाषित किया गया है तो यह प्रॉपर्टी निर्धारित करती है कि प्लॉट एरिया को उसके अंदर (अक्ष और अक्ष लेबल को शामिल नहीं) या बाहर (अक्ष और अक्ष लेबल सहित) लेआउट किया जाए। पढ़ें/लिखें [LayoutTargetType](../../com.aspose.slides/layouttargettype)(\#getLayoutTargetType.getLayoutTargetType/\#setLayoutTargetType(int).setLayoutTargetType(int)).

--------------------

> ```
> Presentation presentation = new Presentation();
>   try
>   {
>       ISlide slide = presentation.getSlides().get_Item(0);
>       IChart chart = slide.getShapes().addChart(ChartType.ClusteredColumn, 20, 100, 600, 400);
>       chart.getPlotArea().setX(0.2f);
>       chart.getPlotArea().setY(0.2f);
>       chart.getPlotArea().setWidth(0.7f);
>       chart.getPlotArea().setHeight(0.7f);
>       chart.getPlotArea().setLayoutTargetType(LayoutTargetType.Inner);
>       ...
>   } finally {
>       if (presentation != null) presentation.dispose();
>   }
> ```

**वापसी:**
int

### setLayoutTargetType(int value) {#setLayoutTargetType-int-}
```
public final void setLayoutTargetType(int value)
```

यदि प्लॉट एरिया का लेआउट मैन्युअल रूप से परिभाषित किया गया है तो यह प्रॉपर्टी निर्धारित करती है कि प्लॉट एरिया को उसके अंदर (अक्ष और अक्ष लेबल को शामिल नहीं) या बाहर (अक्ष और अक्ष लेबल सहित) लेआउट किया जाए। पढ़ें/लिखें [LayoutTargetType](../../com.aspose.slides/layouttargettype)(\#getLayoutTargetType.getLayoutTargetType/\#setLayoutTargetType(int).setLayoutTargetType(int)).

--------------------

> ```
> Presentation presentation = new Presentation();
>   try
>   {
>       ISlide slide = presentation.getSlides().get_Item(0);
>       IChart chart = slide.getShapes().addChart(ChartType.ClusteredColumn, 20, 100, 600, 400);
>       chart.getPlotArea().setX(0.2f);
>       chart.getPlotArea().setY(0.2f);
>       chart.getPlotArea().setWidth(0.7f);
>       chart.getPlotArea().setHeight(0.7f);
>       chart.getPlotArea().setLayoutTargetType(LayoutTargetType.Inner);
>       ...
>   } finally {
>       if (presentation != null) presentation.dispose();
>   }
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getActualX() {#getActualX--}
```
public final float getActualX()
```

चार्ट तत्व के वास्तविक x स्थान (बाएँ) को चार्ट के बाएँ शीर्ष कोने के सापेक्ष निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए पहले IChart.ValidateChartLayout() मेथड को कॉल करें। पढ़ें float.

**वापसी:**
float

### getActualY() {#getActualY--}
```
public final float getActualY()
```

चार्ट तत्व के वास्तविक शीर्ष को चार्ट के बाएँ शीर्ष कोने के सापेक्ष निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए पहले IChart.ValidateChartLayout() मेथड को कॉल करें। पढ़ें float.

**वापसी:**
float

### getActualWidth() {#getActualWidth--}
```
public final float getActualWidth()
```

चार्ट तत्व की वास्तविक चौड़ाई को निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए पहले IChart.ValidateChartLayout() मेथड को कॉल करें। पढ़ें float.

**वापसी:**
float

### getActualHeight() {#getActualHeight--}
```
public final float getActualHeight()
```

चार्ट तत्व की वास्तविक ऊँचाई को निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए पहले IChart.ValidateChartLayout() मेथड को कॉल करें। पढ़ें float.

**वापसी:**
float

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

एक FillFormat की मूल स्लाइड लौटाता है। केवल पढ़ने योग्य [BaseSlide](../../com.aspose.slides/baseslide)।

**वापसी:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

एक FillFormat की मूल प्रस्तुति लौटाता है। केवल पढ़ने योग्य [IPresentation](../../com.aspose.slides/ipresentation)।

**वापसी:**
[IPresentation](../../com.aspose.slides/ipresentation)