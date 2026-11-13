---
title: ChartDataPoint
second_title: Aspose.Slides for Java API संदर्भ
description: सीरीज़ डेटा पॉइंट का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/chartdatapoint/
---
**विरासत:**  
java.lang.Object

**सभी लागू इंटरफ़ेस:**  
[com.aspose.slides.IChartDataPoint](../../com.aspose.slides/ichartdatapoint), com.aspose.slides.IDOMObject  
```
public class ChartDataPoint implements IChartDataPoint, IDOMObject
```

सीरीज़ डेटा पॉइंट का प्रतिनिधित्व करता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getXValue()](#getXValue--) | XValue. |
| [getYValue()](#getYValue--) | YValue. |
| [getBubbleSize()](#getBubbleSize--) | BubbleSize. |
| [getValue()](#getValue--) | Value. |
| [getSizeValue()](#getSizeValue--) | चार्ट डेटा पॉइंट का आकार मान लौटाता है। |
| [getColorValue()](#getColorValue--) | चार्ट डेटा पॉइंट का रंग मान लौटाता है। |
| [getErrorBarsCustomValues()](#getErrorBarsCustomValues--) | कस्टम मान प्रकार के मामले में श्रृंखला त्रुटि बार मानों का प्रतिनिधित्व करता है। |
| [getLabel()](#getLabel--) | Label. |
| [isBubble3D()](#isBubble3D--) | निर्दिष्ट करता है कि बुलबुले पर 3-D प्रभाव लागू किया गया है। |
| [setBubble3D(boolean value)](#setBubble3D-boolean-) | निर्दिष्ट करता है कि बुलबुले पर 3-D प्रभाव लागू किया गया है। |
| [getExplosion()](#getExplosion--) | डेटा पॉइंट को पाई के केंद्र से कितना दूरी पर ले जाया जाएगा, यह निर्दिष्ट करता है। |
| [setExplosion(int value)](#setExplosion-int-) | डेटा पॉइंट को पाई के केंद्र से कितना दूरी पर ले जाया जाएगा, यह निर्दिष्ट करता है। |
| [getFormat()](#getFormat--) | फ़ॉर्मेटिंग गुणों का प्रतिनिधित्व करता है। |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | फ़ॉर्मेटिंग गुणों का प्रतिनिधित्व करता है। |
| [getMarker()](#getMarker--) | डेटा मार्कर निर्दिष्ट करता है। |
| [getSetAsTotal()](#getSetAsTotal--) | डेटा पॉइंट को कुल के रूप में सेट करता है। |
| [setSetAsTotal(boolean value)](#setSetAsTotal-boolean-) | डेटा पॉइंट को कुल के रूप में सेट करता है। |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | संबंधित लेजेंड प्रविष्टि के गुण, इस सूची में से चार्ट प्रकार के मामले में: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie। |
| [remove()](#remove--) | DataPoint को चार्ट श्रृंखला से हटाता है। |
| [getDataPointLevels()](#getDataPointLevels--) | डेटा पॉइंट स्तरों का कंटेनर लौटाता है। |
| [getIndex()](#getIndex--) |  |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getAutomaticDataPointColor()](#getAutomaticDataPointColor--) | सीरीज़ इंडेक्स, डेटा पॉइंट इंडेक्स, ParentSeriesGroup.IsColorVaried प्रॉपर्टी और चार्ट शैली के आधार पर डेटा पॉइंट का स्वतः रंग लौटाता है। |
| [getInvertIfNegative()](#getInvertIfNegative--) | यदि मान नकारात्मक है तो डेटा पॉइंट के रंग उलटे जाएंगे, यह निर्दिष्ट करता है। |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | यदि मान नकारात्मक है तो डेटा पॉइंट के रंग उलटे जाएंगे, यह निर्दिष्ट करता है। |
| [getCachedValue()](#getCachedValue--) | चार्ट डेटा पॉइंट का कैश किया हुआ मान प्राप्त करता है। |
| [getCachedXValue()](#getCachedXValue--) | चार्ट डेटा पॉइंट का कैश किया हुआ X मान प्राप्त करता है। |
| [getCachedYValue()](#getCachedYValue--) | चार्ट डेटा पॉइंट का कैश किया हुआ Y मान प्राप्त करता है। |
| [getCachedBubbleSize()](#getCachedBubbleSize--) | चार्ट डेटा पॉइंट का कैश किया हुआ बुलबुले आकार प्राप्त करता है। |
| [getActualX()](#getActualX--) | चार्ट तत्व का वास्तविक X स्थान (बाएँ) चार्ट के बाएँ ऊपर कोने के सापेक्ष निर्दिष्ट करता है। |
| [getActualY()](#getActualY--) | चार्ट तत्व का वास्तविक शीर्ष चार्ट के बाएँ ऊपर कोने के सापेक्ष निर्दिष्ट करता है। |
| [getActualWidth()](#getActualWidth--) | चार्ट तत्व की वास्तविक चौड़ाई निर्दिष्ट करता है। |
| [getActualHeight()](#getActualHeight--) | चार्ट तत्व की वास्तविक ऊँचाई निर्दिष्ट करता है। |

### getXValue() {#getXValue--}
```
public final IStringOrDoubleChartValue getXValue()
```

XValue. केवल-पढ़ने योग्य [IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)।

**वापसी:**  
[IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)

### getYValue() {#getYValue--}
```
public final IDoubleChartValue getYValue()
```

YValue. केवल-पढ़ने योग्य [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)।

**वापसी:**  
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getBubbleSize() {#getBubbleSize--}
```
public final IDoubleChartValue getBubbleSize()
```

BubbleSize. केवल-पढ़ने योग्य [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)।

**वापसी:**  
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getValue() {#getValue--}
```
public final IDoubleChartValue getValue()
```

Value. केवल-पढ़ने योग्य [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)।

**वापसी:**  
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getSizeValue() {#getSizeValue--}
```
public final IDoubleChartValue getSizeValue()
```

चार्ट डेटा पॉइंट का आकार मान लौटाता है। Treemap और Sunburst चार्ट के साथ उपयोग किया जाता है। केवल-पढ़ने योग्य [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)।

**वापसी:**  
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getColorValue() {#getColorValue--}
```
public final IDoubleChartValue getColorValue()
```

चार्ट डेटा पॉइंट का रंग मान लौटाता है। मानचित्र चार्ट के साथ उपयोग किया जाता है। केवल-पढ़ने योग्य [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)।

**वापसी:**  
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getErrorBarsCustomValues() {#getErrorBarsCustomValues--}
```
public final IErrorBarsCustomValues getErrorBarsCustomValues()
```

कस्टम मान प्रकार के मामले में श्रृंखला त्रुटि बार मानों का प्रतिनिधित्व करता है। केवल-पढ़ने योग्य [IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues)।

**वापसी:**  
[IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues)

### getLabel() {#getLabel--}
```
public final IDataLabel getLabel()
```

Label. केवल-पढ़ने योग्य [IDataLabel](../../com.aspose.slides/idatalabel)।

**वापसी:**  
[IDataLabel](../../com.aspose.slides/idatalabel)

### isBubble3D() {#isBubble3D--}
```
public final boolean isBubble3D()
```

निर्दिष्ट करता है कि बुलबुले पर 3-D प्रभाव लागू किया गया है। पढ़ने/लिखने योग्य boolean।

**वापसी:**  
boolean

### setBubble3D(boolean value) {#setBubble3D-boolean-}
```
public final void setBubble3D(boolean value)
```

निर्दिष्ट करता है कि बुलबुले पर 3-D प्रभाव लागू किया गया है। पढ़ने/लिखने योग्य boolean।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getExplosion() {#getExplosion--}
```
public final int getExplosion()
```

डेटा पॉइंट को पाई के केंद्र से कितना दूरी पर ले जाया जाएगा, यह निर्दिष्ट करता है। पढ़ने/लिखने योग्य int।

**वापसी:**  
int

### setExplosion(int value) {#setExplosion-int-}
```
public final void setExplosion(int value)
```

डेटा पॉइंट को पाई के केंद्र से कितना दूरी पर ले जाया जाएगा, यह निर्दिष्ट करता है। पढ़ने/लिखने योग्य int।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

फ़ॉर्मेटिंग गुणों का प्रतिनिधित्व करता है। पढ़ने/लिखने योग्य [IFormat](../../com.aspose.slides/iformat)।

**वापसी:**  
[IFormat](../../com.aspose.slides/iformat)

### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public final void setFormat(IFormat value)
```

फ़ॉर्मेटिंग गुणों का प्रतिनिधित्व करता है। पढ़ने/लिखने योग्य [IFormat](../../com.aspose.slides/iformat)।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### getMarker() {#getMarker--}
```
public final IMarker getMarker()
```

डेटा मार्कर निर्दिष्ट करता है। केवल-पढ़ने योग्य [IMarker](../../com.aspose.slides/imarker)।

**वापसी:**  
[IMarker](../../com.aspose.slides/imarker)

### getSetAsTotal() {#getSetAsTotal--}
```
public final boolean getSetAsTotal()
```

डेटा पॉइंट को कुल के रूप में सेट करता है। केवल Waterfall श्रृंखला प्रकार के लिए लागू।

**वापसी:**  
boolean

### setSetAsTotal(boolean value) {#setSetAsTotal-boolean-}
```
public final void setSetAsTotal(boolean value)
```

डेटा पॉइंट को कुल के रूप में सेट करता है। केवल Waterfall श्रृंखला प्रकार के लिए लागू।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public final ILegendEntryProperties getRelatedLegendEntry()
```

संबंधित लेजेंड प्रविष्टि के गुण, इस सूची में से चार्ट प्रकार के मामले में: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie। केवल-पढ़ने योग्य [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)।

**वापसी:**  
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)

### remove() {#remove--}
```
public final void remove()
```

DataPoint को चार्ट श्रृंखला से हटाता है।

### getDataPointLevels() {#getDataPointLevels--}
```
public final IChartDataPointLevelsManager getDataPointLevels()
```

डेटा पॉइंट स्तरों का कंटेनर लौटाता है। Treeamp और Sunburst श्रृंखला के लिए लागू। डेटा पॉइंट स्तरों की अनुक्रमण शून्य-आधारित है।

**वापसी:**  
[IChartDataPointLevelsManager](../../com.aspose.slides/ichartdatapointlevelsmanager)

### getIndex() {#getIndex--}
```
public final long getIndex()
```

**वापसी:**  
long

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate ऑब्जेक्ट लौटाता है। केवल-पढ़ने योग्य IDOMObject।

**वापसी:**  
com.aspose.slides.IDOMObject

### getAutomaticDataPointColor() {#getAutomaticDataPointColor--}
```
public final Color getAutomaticDataPointColor()
```

सीरीज़ इंडेक्स, डेटा पॉइंट इंडेक्स, ParentSeriesGroup.IsColorVaried प्रॉपर्टी और चार्ट शैली के आधार पर डेटा पॉइंट का स्वतः रंग लौटाता है। यदि FillType NotDefined के बराबर है तो यह रंग डिफ़ॉल्ट रूप से उपयोग किया जाता है।

**वापसी:**  
java.awt.Color

### getInvertIfNegative() {#getInvertIfNegative--}
```
public final boolean getInvertIfNegative()
```

यदि मान नकारात्मक है तो डेटा पॉइंट के रंग उलटे जाएंगे, यह निर्दिष्ट करता है। पढ़ने/लिखने योग्य boolean।

**वापसी:**  
boolean

### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public final void setInvertIfNegative(boolean value)
```

यदि मान नकारात्मक है तो डेटा पॉइंट के रंग उलटे जाएंगे, यह निर्दिष्ट करता है। पढ़ने/लिखने योग्य boolean।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getCachedValue() {#getCachedValue--}
```
public final ICachedChartValue getCachedValue()
```

चार्ट डेटा पॉइंट का कैश किया हुआ मान प्राप्त करता है। केवल-पढ़ने योग्य [ICachedChartValue](../../com.aspose.slides/icachedchartvalue)।

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // चार्ट श्रृंखला के सभी कैश किए गए मानों को प्रिंट करें।
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedValue().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**वापसी:**  
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)

### getCachedXValue() {#getCachedXValue--}
```
public final ICachedChartValue getCachedXValue()
```

चार्ट डेटा पॉइंट का कैश किया हुआ X मान प्राप्त करता है। केवल-पढ़ने योग्य [ICachedChartValue](../../com.aspose.slides/icachedchartvalue)।

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // चार्ट श्रृंखला के सभी कैश किए गए X मानों को प्रिंट करें।
>          for (IChartDataPoint point : series.getDataPoints())
>              System::println(point.getCachedXValue().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**वापसी:**  
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)

### getCachedYValue() {#getCachedYValue--}
```
public final ICachedChartValue getCachedYValue()
```

चार्ट डेटा पॉइंट का कैश किया हुआ Y मान प्राप्त करता है। केवल-पढ़ने योग्य [ICachedChartValue](../../com.aspose.slides/icachedchartvalue)।

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // चार्ट श्रृंखला के सभी कैश किए गए Y मानों को प्रिंट करें।
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedYValue().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**वापसी:**  
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)

### getCachedBubbleSize() {#getCachedBubbleSize--}
```
public final ICachedChartValue getCachedBubbleSize()
```

चार्ट डेटा पॉइंट का कैश किया हुआ बुलबुले आकार प्राप्त करता है। केवल-पढ़ने योग्य [ICachedChartValue](../../com.aspose.slides/icachedchartvalue)।

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // चार्ट श्रृंखला के सभी कैश किए गए बुलबुला आकार मानों को प्रिंट करें।
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedBubbleSize().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**वапसी:**  
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)

### getActualX() {#getActualX--}
```
public final float getActualX()
```

चार्ट तत्व का वास्तविक X स्थान (बाएँ) चार्ट के बाएँ ऊपर कोने के सापेक्ष निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए पहले IChart.ValidateChartLayout() को कॉल करें। पढ़ें float।

**वापसी:**  
float

### getActualY() {#getActualY--}
```
public final float getActualY()
```

चार्ट तत्व का वास्तविक शीर्ष चार्ट के बाएँ ऊपर कोने के सापेक्ष निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए पहले IChart.ValidateChartLayout() को कॉल करें। पढ़ें float।

**वापसी:**  
float

### getActualWidth() {#getActualWidth--}
```
public final float getActualWidth()
```

चार्ट तत्व की वास्तविक चौड़ाई निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए पहले IChart.ValidateChartLayout() को कॉल करें। पढ़ें float।

**वापसी:**  
float

### getActualHeight() {#getActualHeight--}
```
public final float getActualHeight()
```

चार्ट तत्व की वास्तविक ऊँचाई निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए पहले IChart.ValidateChartLayout() को कॉल करें। पढ़ें float।

**वापसी:**  
float