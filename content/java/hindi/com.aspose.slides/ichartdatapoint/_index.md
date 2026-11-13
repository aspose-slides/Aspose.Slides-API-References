---
title: IChartDataPoint
second_title: Aspose.Slides for Java API संदर्भ
description: सीरीज डेटा पॉइंट का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/ichartdatapoint/
---
**All Implemented Interfaces:**
[com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IChartDataPoint extends IActualLayout
```

सीरीज डेटा पॉइंट का प्रतिनिधित्व करता है।
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getXValue()](#getXValue--) | एक चार्ट डेटा पॉइंट का x मान प्राप्त करता है। |
| [getYValue()](#getYValue--) | एक चार्ट डेटा पॉइंट का y मान प्राप्त करता है। |
| [getBubbleSize()](#getBubbleSize--) | एक चार्ट डेटा पॉइंट का बबल आकार प्राप्त करता है। |
| [getValue()](#getValue--) | एक चार्ट डेटा पॉइंट का मान प्राप्त करता है। |
| [getCachedXValue()](#getCachedXValue--) | एक चार्ट डेटा पॉइंट का cached X मान प्राप्त करता है। |
| [getCachedYValue()](#getCachedYValue--) | एक चार्ट डेटा पॉइंट का cached Y मान प्राप्त करता है। |
| [getCachedValue()](#getCachedValue--) | एक चार्ट डेटा पॉइंट का cached मान प्राप्त करता है। |
| [getCachedBubbleSize()](#getCachedBubbleSize--) | एक चार्ट डेटा पॉइंट का cached बबल आकार प्राप्त करता है। |
| [getSizeValue()](#getSizeValue--) | एक चार्ट डेटा पॉइंट का आकार मान प्राप्त करता है। |
| [getColorValue()](#getColorValue--) | एक चार्ट डेटा पॉइंट का रंग मान प्राप्त करता है। |
| [getErrorBarsCustomValues()](#getErrorBarsCustomValues--) | कस्टम वैल्यू टाइप के मामले में सीरीज एरर बार वैल्यू को दर्शाता है। |
| [getLabel()](#getLabel--) | चार्ट डेटा पॉइंट का लेबल दर्शाता है। |
| [isBubble3D()](#isBubble3D--) | यह निर्दिष्ट करता है कि बब्बल्स पर 3-D इफ़ेक्ट लागू है। |
| [setBubble3D(boolean value)](#setBubble3D-boolean-) | यह निर्दिष्ट करता है कि बब्बल्स पर 3-D इफ़ेक्ट लागू है। |
| [getExplosion()](#getExplosion--) | पाई के केन्द्र से डेटा पॉइंट को कितनी दूरी पर ले जाया जाना चाहिए, यह निर्धारित करता है। |
| [setExplosion(int value)](#setExplosion-int-) | पाई के केन्द्र से डेटा पॉइंट को कितनी दूरी पर ले जाया जाना चाहिए, यह निर्धारित करता है। |
| [getFormat()](#getFormat--) | फॉर्मेटिंग प्रॉपर्टीज़ को दर्शाता है। |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | फॉर्मेटिंग प्रॉपर्टीज़ को दर्शाता है। |
| [getMarker()](#getMarker--) | एक डेटा मार्कर निर्दिष्ट करता है। |
| [remove()](#remove--) | चार्ट सीरीज़ से DataPoint को हटाता है। |
| [getAutomaticDataPointColor()](#getAutomaticDataPointColor--) | सीरीज़ इंडेक्स, डेटा पॉइंट इंडेक्स, ParentSeriesGroup.IsColorVaried प्रॉपर्टी और चार्ट स्टाइल के आधार पर डेटा पॉइंट का स्वचालित रंग लौटाता है। |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | निम्न चार्ट प्रकारों में संबंधित लीजेंड एंट्री की प्रॉपर्टीज़: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie। |
| [getSetAsTotal()](#getSetAsTotal--) | डेटा पॉइंट को कुल (total) के रूप में सेट करता है। |
| [setSetAsTotal(boolean value)](#setSetAsTotal-boolean-) | डेटा पॉइंट को कुल (total) के रूप में सेट करता है। |
| [getInvertIfNegative()](#getInvertIfNegative--) | यदि मान नकारात्मक हो तो डेटा पॉइंट को उसके रंग उलटने के लिए निर्दिष्ट करता है। |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | यदि मान नकारात्मक हो तो डेटा पॉइंट को उसके रंग उलटने के लिए निर्दिष्ट करता है। |
| [getDataPointLevels()](#getDataPointLevels--) | डेटा पॉइंट लेवल्स का कंटेनर लौटाता है। |
| [getIndex()](#getIndex--) | यह निर्धारित करता है कि इस डेटा पॉइंट को पैरेंट की किस बच्चों की कलेक्शन में लागू किया गया है। |
### getXValue() {#getXValue--}
```
public abstract IStringOrDoubleChartValue getXValue()
```

एक चार्ट डेटा पॉइंट का x मान प्राप्त करता है। केवल-पढ़ने योग्य [IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)।

**वापसी:**
[IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)
### getYValue() {#getYValue--}
```
public abstract IDoubleChartValue getYValue()
```

एक चार्ट डेटा पॉइंट का y मान प्राप्त करता है। केवल-पढ़ने योग्य [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)।

**वापसी:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getBubbleSize() {#getBubbleSize--}
```
public abstract IDoubleChartValue getBubbleSize()
```

एक चार्ट डेटा पॉइंट का बबल आकार प्राप्त करता है। केवल-पढ़ने योग्य [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)।

**वापसी:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getValue() {#getValue--}
```
public abstract IDoubleChartValue getValue()
```

एक चार्ट डेटा पॉइंट का मान प्राप्त करता है। केवल-पढ़ने योग्य [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)।

**वापसी:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getCachedXValue() {#getCachedXValue--}
```
public abstract ICachedChartValue getCachedXValue()
```

एक चार्ट डेटा पॉइंट का cached X मान प्राप्त करता है। केवल-पढ़ने योग्य [ICachedChartValue](../../com.aspose.slides/icachedchartvalue)।

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // चार्ट सीरीज़ के सभी cached X मान प्रिंट करें।
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedXValue().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**वापसी:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
### getCachedYValue() {#getCachedYValue--}
```
public abstract ICachedChartValue getCachedYValue()
```

एक चार्ट डेटा पॉइंट का cached Y मान प्राप्त करता है। केवल-पढ़ने योग्य [ICachedChartValue](../../com.aspose.slides/icachedchartvalue)।

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // चार्ट सीरीज़ के सभी cached Y मान प्रिंट करें।
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedYValue().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**वापसी:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
### getCachedValue() {#getCachedValue--}
```
public abstract ICachedChartValue getCachedValue()
```

एक चार्ट डेटा पॉइंट का cached मान प्राप्त करता है। केवल-पढ़ने योग्य [ICachedChartValue](../../com.aspose.slides/icachedchartvalue)।

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // चार्ट सीरीज़ के सभी cached मान प्रिंट करें।
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedValue().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**वापसी:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
### getCachedBubbleSize() {#getCachedBubbleSize--}
```
public abstract ICachedChartValue getCachedBubbleSize()
```

एक चार्ट डेटा पॉइंट का cached बबल आकार प्राप्त करता है। केवल-पढ़ने योग्य [ICachedChartValue](../../com.aspose.slides/icachedchartvalue)।

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // चार्ट सीरीज़ के सभी cached बबल आकार मान प्रिंट करें।
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedBubbleSize().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**वापसी:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
### getSizeValue() {#getSizeValue--}
```
public abstract IDoubleChartValue getSizeValue()
```

एक चार्ट डेटा पॉइंट का आकार मान प्राप्त करता है। Treemap और Sunburst चार्ट्स में उपयोग किया जाता है। केवल-पढ़ने योग्य [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)।

**वापसी:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getColorValue() {#getColorValue--}
```
public abstract IDoubleChartValue getColorValue()
```

एक चार्ट डेटा पॉइंट का रंग मान प्राप्त करता है। Map चार्ट्स में उपयोग किया जाता है। केवल-पढ़ने योग्य [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)।

**वापसी:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getErrorBarsCustomValues() {#getErrorBarsCustomValues--}
```
public abstract IErrorBarsCustomValues getErrorBarsCustomValues()
```

कस्टम वैल्यू टाइप के मामले में सीरीज एरर बार वैल्यू को दर्शाता है। केवल-पढ़ने योग्य [IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues)।

**वापसी:**
[IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues)
### getLabel() {#getLabel--}
```
public abstract IDataLabel getLabel()
```

चार्ट डेटा पॉइंट का लेबल दर्शाता है। केवल-पढ़ने योग्य [IDataLabel](../../com.aspose.slides/idatalabel)।

**वापसी:**
[IDataLabel](../../com.aspose.slides/idatalabel)
### isBubble3D() {#isBubble3D--}
```
public abstract boolean isBubble3D()
```

यह निर्दिष्ट करता है कि बब्बल्स पर 3-D इफ़ेक्ट लागू है। पढ़ने/लिखने योग्य बूलियन।

**वापसी:**
boolean
### setBubble3D(boolean value) {#setBubble3D-boolean-}
```
public abstract void setBubble3D(boolean value)
```

यह निर्दिष्ट करता है कि बब्बल्स पर 3-D इफ़ेक्ट लागू है। पढ़ने/लिखने योग्य बूलियन।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getExplosion() {#getExplosion--}
```
public abstract int getExplosion()
```

पाई के केन्द्र से डेटा पॉइंट को कितनी दूरी पर ले जाया जाना चाहिए, यह निर्धारित करता है। पढ़ने/लिखने योग्य int।

**वापसी:**
int
### setExplosion(int value) {#setExplosion-int-}
```
public abstract void setExplosion(int value)
```

पाई के केन्द्र से डेटा पॉइंट को कितनी दूरी पर ले जाया जाना चाहिए, यह निर्धारित करता है। पढ़ने/लिखने योग्य int।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

फॉर्मेटिंग प्रॉपर्टीज़ को दर्शाता है। पढ़ने/लिखने योग्य [IFormat](../../com.aspose.slides/iformat)।

**वापसी:**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public abstract void setFormat(IFormat value)
```

फॉर्मेटिंग प्रॉपर्टीज़ को दर्शाता है। पढ़ने/लिखने योग्य [IFormat](../../com.aspose.slides/iformat)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |
### getMarker() {#getMarker--}
```
public abstract IMarker getMarker()
```

एक डेटा मार्कर निर्दिष्ट करता है। केवल-पढ़ने योग्य [IMarker](../../com.aspose.slides/imarker)।

**वापसी:**
[IMarker](../../com.aspose.slides/imarker)
### remove() {#remove--}
```
public abstract void remove()
```

चार्ट सीरीज़ से DataPoint को हटाता है।

### getAutomaticDataPointColor() {#getAutomaticDataPointColor--}
```
public abstract Color getAutomaticDataPointColor()
```

सीरीज़ इंडेक्स, डेटा पॉइंट इंडेक्स, ParentSeriesGroup.IsColorVaried प्रॉपर्टी और चार्ट स्टाइल के आधार पर डेटा पॉइंट का स्वचालित रंग लौटाता है। यदि FillType NotDefined के बराबर है तो यह रंग डिफ़ॉल्ट रूप से उपयोग किया जाता है।

**वापसी:**
java.awt.Color - Automatic color of data point java.awt.Color
### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```

निम्न चार्ट प्रकारों में संबंधित लीजेंड एंट्री की प्रॉपर्टीज़: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie। केवल-पढ़ने योग्य [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)।

**वापसी:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### getSetAsTotal() {#getSetAsTotal--}
```
public abstract boolean getSetAsTotal()
```

डेटा पॉइंट को कुल (total) के रूप में सेट करता है। केवल Waterfall सीरीज़ प्रकार के लिए लागू।

**वापसी:**
boolean
### setSetAsTotal(boolean value) {#setSetAsTotal-boolean-}
```
public abstract void setSetAsTotal(boolean value)
```

डेटा पॉइंट को कुल (total) के रूप में सेट करता है। केवल Waterfall सीरीज़ प्रकार के लिए लागू।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getInvertIfNegative() {#getInvertIfNegative--}
```
public abstract boolean getInvertIfNegative()
```

यदि मान नकारात्मक हो तो डेटा पॉइंट को उसके रंग उलटने के लिए निर्दिष्ट करता है। पढ़ने/लिखने योग्य बूलियन।

**वापसी:**
boolean
### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public abstract void setInvertIfNegative(boolean value)
```

यदि मान नकारात्मक हो तो डेटा पॉइंट को उसके रंग उलटने के लिए निर्दिष्ट करता है। पढ़ने/लिखने योग्य बूलियन।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getDataPointLevels() {#getDataPointLevels--}
```
public abstract IChartDataPointLevelsManager getDataPointLevels()
```

डेटा पॉइंट लेवल्स का कंटेनर लौटाता है। Treeamp और Sunburst सीरीज़ के लिए लागू। डेटा पॉइंट लेवल्स की इंडेक्सिंग शून्य-आधारित है।

**वापसी:**
[IChartDataPointLevelsManager](../../com.aspose.slides/ichartdatapointlevelsmanager)
### getIndex() {#getIndex--}
```
public abstract long getIndex()
```

निर्धारित करता है कि इस डेटा पॉइंट को पैरेंट के बच्चों की किस कलेक्शन में लागू किया गया है। पढ़ने long।

**वापसी:**
long