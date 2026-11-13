---
title: DataLabelCollection
second_title: Aspose.Slides जावा API संदर्भ
description: एक श्रृंखला लेबल का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/datalabelcollection/
---
**विरासत:**
java.lang.Object, com.aspose.slides.DomObject

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)
```
public class DataLabelCollection extends DomObject<ChartSeries> implements IDataLabelCollection
```

एक श्रृंखला लेबल का प्रतिनिधित्व करता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getChart()](#getChart--) | पेरेंट चार्ट लौटाता है। |
| [iterator()](#iterator--) | संग्रह के माध्यम से इटरिटेट करने वाला एन्यूमरेटर लौटाता है। |
| [iteratorJava()](#iteratorJava--) | पूरे संग्रह के लिए जावा इटरेटर लौटाता है। |
| [isVisible()](#isVisible--) | False का मतलब है कि डेटा लेबल डिफ़ॉल्ट रूप से दृश्य नहीं है (और इसलिए DefaultDataLabelFormat प्रॉपर्टी के सभी Show*-फ्लैग (ShowValue, ...) false होते हैं)। |
| [hide()](#hide--) | सभी Show*-फ़्लैग (ShowValue, ...) को false स्थिति में सेट करके डेटा लेबल को डिफ़ॉल्ट रूप से छुपा दें। |
| [getCountOfVisibleDataLabels()](#getCountOfVisibleDataLabels--) | संग्रह में दृश्यमान डेटा लेबल की संख्या प्राप्त करता है। |
| [getCount()](#getCount--) | संग्रह में सभी डेटा लेबल की संख्या प्राप्त करता है। |
| [getDefaultDataLabelFormat()](#getDefaultDataLabelFormat--) | डिफ़ॉल्ट डेटा लेबल फ़ॉर्मेट प्राप्त करता है। |
| [getLeaderLinesFormat()](#getLeaderLinesFormat--) | डेटा लेबल लीडर लाइन्स फ़ॉर्मेट का प्रतिनिधित्व करता है। |
| [getParentSeries()](#getParentSeries--) | पेरेंट सीरीज़ प्राप्त करता है। |
| [indexOf(IDataLabel value)](#indexOf-com.aspose.slides.IDataLabel-) | संग्रह में निर्दिष्ट DataLabel का इंडेक्स लौटाता है। |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट इंडेक्स वाले डेटा पॉइंट के लिए डेटा लेबल प्राप्त करता है। |
| [getDefaultLabelShapeType()](#getDefaultLabelShapeType--) | डेटा लेबल के लिए डिफ़ॉल्ट शेप टाइप प्राप्त करता है या सेट करता है। |
| [setDefaultLabelShapeType(int value)](#setDefaultLabelShapeType-int-) | डेटा लेबल के लिए डिफ़ॉल्ट शेप टाइप प्राप्त करता है या सेट करता है। |
| [getSlide()](#getSlide--) | FillFormat का पेरेंट स्लाइड लौटाता है। |
| [getPresentation()](#getPresentation--) | FillFormat का पेरेंट प्रेज़ेंटेशन लौटाता है। |
### getChart() {#getChart--}
```
public final IChart getChart()
```

पेरेंट चार्ट लौटाता है। केवल-पढ़ने योग्य [IChart](../../com.aspose.slides/ichart)।

**रिटर्न:**
[IChart](../../com.aspose.slides/ichart)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IDataLabel> iterator()
```

संग्रह के माध्यम से इटरिटेट करने वाला एन्यूमरेटर लौटाता है।

**रिटर्न:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDataLabel> - एक IGenericEnumerator जो संग्रह के माध्यम से इटरिटेट करने के लिए उपयोग किया जा सकता है।
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IDataLabel> iteratorJava()
```

पूरे संग्रह के लिए जावा इटरेटर लौटाता है।

**रिटर्न:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDataLabel> - एक java.util.Iterator जो पूरे संग्रह के लिए है।
### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

False का मतलब है कि डेटा लेबल डिफ़ॉल्ट रूप से दृश्य नहीं है (और इसलिए DefaultDataLabelFormat प्रॉपर्टी के सभी Show*-फ़्लैग (ShowValue, ...) false होते हैं)। केवल-पढ़ने योग्य बूलियन।

--------------------

यदि डेटा लेबल डिफ़ॉल्ट रूप से दृश्यमान है तो आप Hide() मेथड से इसे डिफ़ॉल्ट रूप से छुपा सकते हैं। लेकिन यदि डेटा लेबल डिफ़ॉल्ट रूप से दृश्य नहीं है (IsVisible false है) तो आप Show*-फ़्लैग (ShowValue, ...) को true स्थिति में सेट करके इसे डिफ़ॉल्ट रूप से “दृश्यमान” बना सकते हैं।

**रिटर्न:**
boolean
### hide() {#hide--}
```
public final void hide()
```

डेटा लेबल को डिफ़ॉल्ट रूप से छुपा दें सभी Show*-फ़्लैग (ShowValue, ...) को false स्थिति में सेट करके। इस कार्रवाई के बाद IsVisible false होगा।

--------------------

यदि डेटा लेबल डिफ़ॉल्ट रूप से दृश्य नहीं है (IsVisible false है) तो आप Show*-फ़्लैग (ShowValue, ...) को true स्थिति में सेट करके इसे डिफ़ॉल्ट रूप से “दृश्यमान” बना सकते हैं।

### getCountOfVisibleDataLabels() {#getCountOfVisibleDataLabels--}
```
public final int getCountOfVisibleDataLabels()
```

संग्रह में दृश्यमान डेटा लेबल की संख्या प्राप्त करता है। केवल-पढ़ने योग्य int।

**रिटर्न:**
int
### getCount() {#getCount--}
```
public final int getCount()
```

संग्रह में सभी डेटा लेबल की संख्या प्राप्त करता है। केवल-पढ़ने योग्य int।

**रिटर्न:**
int
### getDefaultDataLabelFormat() {#getDefaultDataLabelFormat--}
```
public final IDataLabelFormat getDefaultDataLabelFormat()
```

डिफ़ॉल्ट डेटा लेबल फ़ॉर्मेट प्राप्त करता है। केवल-पढ़ने योग्य [IDataLabelFormat](../../com.aspose.slides/idatalabelformat)।

**रिटर्न:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getLeaderLinesFormat() {#getLeaderLinesFormat--}
```
public final IChartLinesFormat getLeaderLinesFormat()
```

डेटा लेबल लीडर लाइन्स फ़ॉर्मेट का प्रतिनिधित्व करता है। केवल-पढ़ने योग्य [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)।

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IChart chart = (IChart) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      IDataLabelCollection labels = series.get_Item(0).getLabels();
>      labels.getLeaderLinesFormat().getLine().getFillFormat().setFillType(FillType.Solid);
>      labels.getLeaderLinesFormat().getLine().getFillFormat().getSolidFillColor().setColor(new java.awt.Color(255, 0, 0, 255));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**रिटर्न:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### getParentSeries() {#getParentSeries--}
```
public final IChartSeries getParentSeries()
```

पेरेंट सीरीज़ प्राप्त करता है। केवल-पढ़ने योग्य [IChartSeries](../../com.aspose.slides/ichartseries)।

**रिटर्न:**
[IChartSeries](../../com.aspose.slides/ichartseries)
### indexOf(IDataLabel value) {#indexOf-com.aspose.slides.IDataLabel-}
```
public final int indexOf(IDataLabel value)
```

संग्रह में निर्दिष्ट DataLabel का इंडेक्स लौटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IDataLabel](../../com.aspose.slides/idatalabel) | खोजने के लिए DataLabel। |

**रिटर्न:**
int - DataLabel का इंडेक्स या -1 यदि DataLabel इस संग्रह से नहीं है।
### get_Item(int index) {#get-Item-int-}
```
public final IDataLabel get_Item(int index)
```

निर्दिष्ट इंडेक्स वाले डेटा पॉइंट के लिए डेटा लेबल प्राप्त करता है।

--------------------

डेटा लेबल तक पहुँचने का वैकल्पिक तरीका है: - series.getDataPoints().get_Item(i).getLabel() - लेबल प्रॉपर्टीज़ प्रबंधित करें।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int |  |

**रिटर्न:**
[IDataLabel](../../com.aspose.slides/idatalabel)
### getDefaultLabelShapeType() {#getDefaultLabelShapeType--}
```
public final int getDefaultLabelShapeType()
```

डेटा लेबल के लिए डिफ़ॉल्ट शेप टाइप प्राप्त करता है या सेट करता है। यदि कोई शेप निर्धारित नहीं है तो [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) लौटाता है।

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // पहली श्रृंखला में सभी डेटा लेबल के आकार प्रकार को Ellipse पर सेट करें।
>      firstSeries.getLabels().setDefaultLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabels.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

इस प्रॉपर्टी को सेट करने से सभी डेटा लेबल के IDataLabel.LabelShapeType ([IDataLabel.getLabelShapeType](../../com.aspose.slides/idatalabel\#getLabelShapeType)/[IDataLabel.setLabelShapeType(int)](../../com.aspose.slides/idatalabel\#setLabelShapeType-int-)) प्रॉपर्टी भी समान मान पर सेट हो जाती है।

**रिटर्न:**
int
### setDefaultLabelShapeType(int value) {#setDefaultLabelShapeType-int-}
```
public final void setDefaultLabelShapeType(int value)
```

डेटा लेबल के लिए डिफ़ॉल्ट शेप टाइप प्राप्त करता है या सेट करता है। यदि कोई शेप निर्धारित नहीं है तो [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) लौटाता है।

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // पहली श्रृंखला में सभी डेटा लेबल के आकार प्रकार को Ellipse पर सेट करें।
>      firstSeries.getLabels().setDefaultLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabels.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

इस प्रॉपर्टी को सेट करने से सभी डेटा लेबल के IDataLabel.LabelShapeType ([IDataLabel.getLabelShapeType](../../com.aspose.slides/idatalabel\#getLabelShapeType)/[IDataLabel.setLabelShapeType(int)](../../com.aspose.slides/idatalabel\#setLabelShapeType-int-)) प्रॉपर्टी भी समान मान पर सेट हो जाती है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

FillFormat का पेरेंट स्लाइड लौटाता है। केवल-पढ़ने योग्य [BaseSlide](../../com.aspose.slides/baseslide)।

**रिटर्न:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

FillFormat का पेरेंट प्रेज़ेंटेशन लौटाता है। केवल-पढ़ने योग्य [IPresentation](../../com.aspose.slides/ipresentation)।

**रिटर्न:**
[IPresentation](../../com.aspose.slides/ipresentation)