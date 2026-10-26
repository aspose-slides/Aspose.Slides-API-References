---
title: ChartPlotArea
second_title: Aspose.Slides के लिए Android, Java API रेफ़रेंस के माध्यम से
description: चार्ट को प्लॉट करने के लिए जहाँ आयत हो, उसे दर्शाता है।
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

चार्ट जहाँ चित्रित किया जाना चाहिए, वह आयत दर्शाता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getFormat()](#getFormat--) | एक प्लॉट क्षेत्र का स्वरूप लौटाता है। |
| [getX()](#getX--) | चार्ट की चौड़ाई के अनुपात (0 से 1) में प्लॉट क्षेत्र बाउंडिंग बॉक्स के ऊपरी बाएँ कोने के X निर्देशांक को लौटाता या सेट करता है। |
| [setX(float value)](#setX-float-) | चार्ट की चौड़ाई के अनुपात (0 से 1) में प्लॉट क्षेत्र बाउंडिंग बॉक्स के ऊपरी बाएँ कोने के X निर्देशांक को लौटाता या सेट करता है। |
| [getY()](#getY--) | चार्ट की ऊँचाई के अनुपात (0 से 1) में प्लॉट क्षेत्र बाउंडिंग बॉक्स के ऊपरी बाएँ कोने के Y निर्देशांक को लौटाता या सेट करता है। |
| [setY(float value)](#setY-float-) | चार्ट की ऊँचाई के अनुपात (0 से 1) में प्लॉट क्षेत्र बाउंडिंग बॉक्स के ऊपरी बाएँ कोने के Y निर्देशांक को लौटाता या सेट करता है। |
| [getWidth()](#getWidth--) | प्लॉट क्षेत्र बाउंडिंग बॉक्स की चौड़ाई को चार्ट की चौड़ाई के अनुपात (0 से 1) में लौटाता या सेट करता है। |
| [setWidth(float value)](#setWidth-float-) | प्लॉट क्षेत्र बाउंडिंग बॉक्स की चौड़ाई को चार्ट की चौड़ाई के अनुपात (0 से 1) में लौटाता या सेट करता है। |
| [getHeight()](#getHeight--) | प्लॉट क्षेत्र बाउंडिंग बॉक्स की ऊँचाई को चार्ट की ऊँचाई के अनुपात (0 से 1) में लौटाता या सेट करता है। |
| [setHeight(float value)](#setHeight-float-) | प्लॉट क्षेत्र बाउंडिंग बॉक्स की ऊँचाई को चार्ट की ऊँचाई के अनुपात (0 से 1) में लौटाता या सेट करता है। |
| [getRight()](#getRight--) | दाएँ। |
| [getBottom()](#getBottom--) | नीचे। |
| [getChart()](#getChart--) | चार्ट। |
| [isLocationAutocalculated()](#isLocationAutocalculated--) | परिभाषित करता है कि स्थान कैसे गणना किया जाना चाहिए: true – स्वचालित रूप से गणना किया गया; X, Y, Width, Height गुणों द्वारा निर्धारित। |
| [getLayoutTargetType()](#getLayoutTargetType--) | यदि प्लॉट क्षेत्र की लेआउट मैन्युअल रूप से परिभाषित की गई है, तो यह गुण निर्धारित करता है कि प्लॉट क्षेत्र को उसके अंदर (अक्ष और अक्ष लेबल सहित नहीं) या बाहर (अक्ष और अक्ष लेबल सहित) लेआउट किया जाए। |
| [setLayoutTargetType(int value)](#setLayoutTargetType-int-) | यदि प्लॉट क्षेत्र की लेआउट मैन्युअल रूप से परिभाषित की गई है, तो यह गुण निर्धारित करता है कि प्लॉट क्षेत्र को उसके अंदर (अक्ष और अक्ष लेबल सहित नहीं) या बाहर (अक्ष और अक्ष लेबल सहित) लेआउट किया जाए। |
| [getActualX()](#getActualX--) | चार्ट के बाएँ शीर्ष कोने के सापेक्ष चार्ट तत्व के वास्तविक X स्थान (बाएँ) को निर्दिष्ट करता है। |
| [getActualY()](#getActualY--) | चार्ट के बाएँ शीर्ष कोने के सापेक्ष चार्ट तत्व के वास्तविक शीर्ष को निर्दिष्ट करता है। |
| [getActualWidth()](#getActualWidth--) | चार्ट तत्व की वास्तविक चौड़ाई को निर्दिष्ट करता है। |
| [getActualHeight()](#getActualHeight--) | चार्ट तत्व की वास्तविक ऊँचाई को निर्दिष्ट करता है। |
| [getSlide()](#getSlide--) | FillFormat का पैरेंट स्लाइड लौटाता है। |
| [getPresentation()](#getPresentation--) | FillFormat का पैरेंट प्रेजेंटेशन लौटाता है। |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

एक प्लॉट क्षेत्र का स्वरूप लौटाता है। केवल-पढ़ने योग्य [IFormat](../../com.aspose.slides/iformat)।

**रिटर्न:**  
[IFormat](../../com.aspose.slides/iformat)

### getX() {#getX--}
```
public final float getX()
```

चार्ट की चौड़ाई के अनुपात (0 से 1) में प्लॉट क्षेत्र बाउंडिंग बॉक्स के ऊपरी बाएँ कोने के X निर्देशांक को लौटाता या सेट करता है। पढ़ने/लिखने योग्य float।

**रिटर्न:**  
float

### setX(float value) {#setX-float-}
```
public final void setX(float value)
```

चार्ट की चौड़ाई के अनुपात (0 से 1) में प्लॉट क्षेत्र बाउंडिंग बॉक्स के ऊपरी बाएँ कोने के X निर्देशांक को लौटाता या सेट करता है। पढ़ने/लिखने योग्य float।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### getY() {#getY--}
```
public final float getY()
```

चार्ट की ऊँचाई के अनुपात (0 से 1) में प्लॉट क्षेत्र बाउंडिंग बॉक्स के ऊपरी बाएँ कोने के Y निर्देशांक को लौटाता या सेट करता है। पढ़ने/लिखने योग्य float।

**रिटर्न:**  
float

### setY(float value) {#setY-float-}
```
public final void setY(float value)
```

चार्ट की ऊँचाई के अनुपात (0 से 1) में प्लॉट क्षेत्र बाउंडिंग बॉक्स के ऊपरी बाएँ कोने के Y निर्देशांक को लौटाता या सेट करता है। पढ़ने/लिखने योग्य float।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### getWidth() {#getWidth--}
```
public final float getWidth()
```

प्लॉट क्षेत्र बाउंडिंग बॉक्स की चौड़ाई को चार्ट की चौड़ाई के अनुपात (0 से 1) में लौटाता या सेट करता है। पढ़ने/लिखने योग्य float।

**रिटर्न:**  
float

### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```

प्लॉट क्षेत्र बाउंडिंग बॉक्स की चौड़ाई को चार्ट की चौड़ाई के अनुपात (0 से 1) में लौटाता या सेट करता है। पढ़ने/लिखने योग्य float।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### getHeight() {#getHeight--}
```
public final float getHeight()
```

प्लॉट क्षेत्र बाउंडिंग बॉक्स की ऊँचाई को चार्ट की ऊँचाई के अनुपात (0 से 1) में लौटाता या सेट करता है। पढ़ने/लिखने योग्य float।

**रिटर्न:**  
float

### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```

प्लॉट क्षेत्र बाउंडिंग बॉक्स की ऊँचाई को चार्ट की ऊँचाई के अनुपात (0 से 1) में लौटाता या सेट करता है। पढ़ने/लिखने योग्य float।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### getRight() {#getRight--}
```
public final float getRight()
```

दाएँ। केवल-पढ़ने योग्य float।

**रिटर्न:**  
float

### getBottom() {#getBottom--}
```
public final float getBottom()
```

नीचे। केवल-पढ़ने योग्य float।

**रिटर्न:**  
float

### getChart() {#getChart--}
```
public final IChart getChart()
```

चार्ट। केवल-पढ़ने योग्य [IChart](../../com.aspose.slides/ichart)।

**रिटर्न:**  
[IChart](../../com.aspose.slides/ichart)

### isLocationAutocalculated() {#isLocationAutocalculated--}
```
public final boolean isLocationAutocalculated()
```

परिभाषित करता है कि स्थान कैसे गणना किया जाना चाहिए: true – स्वचालित रूप से गणना किया गया; X, Y, Width, Height गुणों द्वारा निर्धारित। केवल-पढ़ने योग्य boolean।

**रिटर्न:**  
boolean

### getLayoutTargetType() {#getLayoutTargetType--}
```
public final int getLayoutTargetType()
```

यदि प्लॉट क्षेत्र की लेआउट मैन्युअल रूप से परिभाषित की गई है, तो यह गुण निर्धारित करता है कि प्लॉट क्षेत्र को उसके अंदर (अक्ष और अक्ष लेबल सहित नहीं) या बाहर (अक्ष और अक्ष लेबल सहित) लेआउट किया जाए। पढ़ने/लिखने योग्य [LayoutTargetType](../../com.aspose.slides/layouttargettype)(\#getLayoutTargetType.getLayoutTargetType/\#setLayoutTargetType(int).setLayoutTargetType(int))।

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

**रिटर्न:**  
int

### setLayoutTargetType(int value) {#setLayoutTargetType-int-}
```
public final void setLayoutTargetType(int value)
```

यदि प्लॉट क्षेत्र की लेआउट मैन्युअल रूप से परिभाषित की गई है, तो यह गुण निर्धारित करता है कि प्लॉट क्षेत्र को उसके अंदर (अक्ष और अक्ष लेबल सहित नहीं) या बाहर (अक्ष और अक्ष लेबल सहित) लेआउट किया जाए। पढ़ने/लिखने योग्य [LayoutTargetType](../../com.aspose.slides/layouttargettype)(\#getLayoutTargetType.getLayoutTargetType/\#setLayoutTargetType(int).setLayoutTargetType(int))।

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

चार्ट के बाएँ शीर्ष कोने के सापेक्ष चार्ट तत्व के वास्तविक X स्थान (बाएँ) को निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए IChart.ValidateChartLayout() विधि को कॉल करें। पढ़ने योग्य float।

**रिटर्न:**  
float

### getActualY() {#getActualY--}
```
public final float getActualY()
```

चार्ट के बाएँ शीर्ष कोने के सापेक्ष चार्ट तत्व के वास्तविक शीर्ष को निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए IChart.ValidateChartLayout() विधि को कॉल करें। पढ़ने योग्य float।

**रिटर्न:**  
float

### getActualWidth() {#getActualWidth--}
```
public final float getActualWidth()
```

चार्ट तत्व की वास्तविक चौड़ाई को निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए IChart.ValidateChartLayout() विधि को कॉल करें। पढ़ने योग्य float।

**रिटर्न:**  
float

### getActualHeight() {#getActualHeight--}
```
public final float getActualHeight()
```

चार्ट तत्व की वास्तविक ऊँचाई को निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए IChart.ValidateChartLayout() विधि को कॉल करें। पढ़ने योग्य float।

**रिटर्न:**  
float

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

FillFormat का पैरेंट स्लाइड लौटाता है। केवल-पढ़ने योग्य [BaseSlide](../../com.aspose.slides/baseslide)।

**रिटर्न:**  
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

FillFormat का पैरेंट प्रेजेंटेशन लौटाता है। केवल-पढ़ने योग्य [IPresentation](../../com.aspose.slides/ipresentation)।

**रिटर्न:**  
[IPresentation](../../com.aspose.slides/ipresentation)