---
title: IDataLabelCollection
second_title: Aspose.Slides जावा के लिए API संदर्भ
description: एक श्रृंखला लेबल का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/idatalabelcollection/
---
**सभी लागू इंटरफ़ेस:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable, [com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IDataLabelCollection extends System.Collections.Generic.IGenericEnumerable<IDataLabel>, IChartComponent
```

एक श्रृंखला लेबल का प्रतिनिधित्व करता है।
## विधियां

| मेथड | विवरण |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट अनुक्रमांक वाले डेटा बिंदु के लिए डेटा लेबल प्राप्त करता है। |
| [getDefaultDataLabelFormat()](#getDefaultDataLabelFormat--) | संग्रह में सभी डेटा लेबलों का डिफ़ॉल्ट फ़ॉर्मेट लौटाता है। |
| [getLeaderLinesFormat()](#getLeaderLinesFormat--) | डेटा लेबलों की लीडर लाइन्स फ़ॉर्मेट का प्रतिनिधित्व करता है। |
| [isVisible()](#isVisible--) | फ़ॉल्स का अर्थ है कि डेटा लेबल डिफ़ॉल्ट रूप से दृश्यमान नहीं है (और इसलिए DefaultDataLabelFormat संपत्ति के सभी Show*-flags (ShowValue, ...) फ़ॉल्स होते हैं)। |
| [hide()](#hide--) | डिफ़ॉल्ट रूप से डेटा लेबल को छुपाने के लिए DefaultDataLabelFormat संपत्ति के सभी Show*-flags (ShowValue, ...) को फ़ॉल्स स्थिति में सेट करें। |
| [getCountOfVisibleDataLabels()](#getCountOfVisibleDataLabels--) | संग्रह में दृश्यमान डेटा लेबलों की संख्या प्राप्त करता है। |
| [getCount()](#getCount--) | संग्रह में सभी डेटा लेबलों की संख्या प्राप्त करता है। |
| [getParentSeries()](#getParentSeries--) | पैरेंट चार्ट श्रृंखला लौटाता है। |
| [indexOf(IDataLabel value)](#indexOf-com.aspose.slides.IDataLabel-) | संग्रह में निर्दिष्ट DataLabel का अनुक्रमांक लौटाता है। |
| [getDefaultLabelShapeType()](#getDefaultLabelShapeType--) | डेटा लेबलों के लिए डिफ़ॉल्ट आकार प्रकार प्राप्त करता या सेट करता है। |
| [setDefaultLabelShapeType(int value)](#setDefaultLabelShapeType-int-) | डेटा लेबलों के लिए डिफ़ॉल्ट आकार प्रकार प्राप्त करता या सेट करता है। |
### get_Item(int index) {#get-Item-int-}
```
public abstract IDataLabel get_Item(int index)
```

डेटा बिंदु के लिए निर्दिष्ट अनुक्रमांक वाला डेटा लेबल प्राप्त करता है।

--------------------

डेटा लेबल तक पहुँचने का वैकल्पिक तरीका है: - getSeries().getDataPoints().get_Item(i).getLabel() - लेबल गुणों का प्रबंधन करें।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int |  |

**रिटर्न:**
[IDataLabel](../../com.aspose.slides/idatalabel)
### getDefaultDataLabelFormat() {#getDefaultDataLabelFormat--}
```
public abstract IDataLabelFormat getDefaultDataLabelFormat()
```

संग्रह में सभी डेटा लेबलों का डिफ़ॉल्ट फ़ॉर्मेट लौटाता है। केवल पढ़ने योग्य [IDataLabelFormat](../../com.aspose.slides/idatalabelformat)।

**रिटर्न:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getLeaderLinesFormat() {#getLeaderLinesFormat--}
```
public abstract IChartLinesFormat getLeaderLinesFormat()
```

डेटा लेबलों की लीडर लाइन्स फ़ॉर्मेट का प्रतिनिधित्व करता है। केवल पढ़ने योग्य [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)।

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
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

फ़ॉल्स का अर्थ है कि डेटा लेबल डिफ़ॉल्ट रूप से दृश्यमान नहीं है (और इसलिए DefaultDataLabelFormat संपत्ति के सभी Show*-flags (ShowValue, ...) फ़ॉल्स होते हैं)। केवल पढ़ने योग्य boolean .

--------------------

यदि डेटा लेबल डिफ़ॉल्ट रूप से दृश्यमान है, तो आप Hide() मेथड से उसे डिफ़ॉल्ट रूप से छुपा सकते हैं। लेकिन यदि डेटा लेबल डिफ़ॉल्ट रूप से दृश्यमान नहीं है (IsVisible फ़ॉल्स है) तो आप Show*-flags (ShowValue, ...) को true स्थिति में सेट करके डेटा लेबल को "डिफ़ॉल्ट रूप से दृश्यमान" बना सकते हैं।

**रिटर्न:**
boolean
### hide() {#hide--}
```
public abstract void hide()
```

डिफ़ॉल्ट रूप से डेटा लेबल को छुपाने के लिए DefaultDataLabelFormat संपत्ति के सभी Show*-flags (ShowValue, ...) को फ़ॉल्स स्थिति में सेट करें। IsVisible इसके बाद फ़ॉल्स होगा।

--------------------

यदि डेटा लेबल डिफ़ॉल्ट रूप से दृश्यमान नहीं है (IsVisible फ़ॉल्स है) तो आप Show*-flags (ShowValue, ...) को true स्थिति में सेट करके डेटा लेबल को "डिफ़ॉल्ट रूप से दृश्यमान" बना सकते हैं।

### getCountOfVisibleDataLabels() {#getCountOfVisibleDataLabels--}
```
public abstract int getCountOfVisibleDataLabels()
```

संग्रह में दृश्यमान डेटा लेबलों की संख्या प्राप्त करता है। केवल पढ़ने योग्य int .

**रिटर्न:**
int
### getCount() {#getCount--}
```
public abstract int getCount()
```

संग्रह में सभी डेटा लेबलों की संख्या प्राप्त करता है। केवल पढ़ने योग्य int .

**रिटर्न:**
int
### getParentSeries() {#getParentSeries--}
```
public abstract IChartSeries getParentSeries()
```

पैरेंट चार्ट श्रृंखला लौटाता है। केवल पढ़ने योग्य [IChartSeries](../../com.aspose.slides/ichartseries)।

**रिटर्न:**
[IChartSeries](../../com.aspose.slides/ichartseries)
### indexOf(IDataLabel value) {#indexOf-com.aspose.slides.IDataLabel-}
```
public abstract int indexOf(IDataLabel value)
```

संग्रह में निर्दिष्ट DataLabel का अनुक्रमांक लौटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IDataLabel](../../com.aspose.slides/idatalabel) | खोजने के लिए DataLabel। |

**रिटर्न:**
int - एक DataLabel का अनुक्रमांक या -1 यदि DataLabel इस संग्रह में नहीं है।
### getDefaultLabelShapeType() {#getDefaultLabelShapeType--}
```
public abstract int getDefaultLabelShapeType()
```

डेटा लेबलों के लिए डिफ़ॉल्ट आकार प्रकार प्राप्त करता या सेट करता है। यदि कोई आकार परिभाषित नहीं है तो [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) लौटाता है।

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // पहले श्रृंखला में सभी डेटा लेबल्स के आकार प्रकार को Ellipse सेट करें।
>      firstSeries.getLabels().setDefaultLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabels.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

इस संपत्ति को सेट करने से सभी डेटा लेबलों के IDataLabel.LabelShapeType ([IDataLabel.getLabelShapeType](../../com.aspose.slides/idatalabel\#getLabelShapeType)/[IDataLabel.setLabelShapeType(int)](../../com.aspose.slides/idatalabel\#setLabelShapeType-int-)) संपत्ति भी समान मान पर सेट हो जाती है।

**रिटर्न:**
int
### setDefaultLabelShapeType(int value) {#setDefaultLabelShapeType-int-}
```
public abstract void setDefaultLabelShapeType(int value)
```

डेटा लेबलों के लिए डिफ़ॉल्ट आकार प्रकार प्राप्त करता या सेट करता है। यदि कोई आकार परिभाषित नहीं है तो [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) लौटाता है।

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // पहले श्रृंखला में सभी डेटा लेबल्स के आकार प्रकार को Ellipse सेट करें।
>      firstSeries.getLabels().setDefaultLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabels.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

इस संपत्ति को सेट करने से सभी डेटा लेबलों के IDataLabel.LabelShapeType ([IDataLabel.getLabelShapeType](../../com.aspose.slides/idatalabel\#getLabelShapeType)/[IDataLabel.setLabelShapeType(int)](../../com.aspose.slides/idatalabel\#setLabelShapeType-int-)) संपत्ति भी समान मान पर सेट हो जाती है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |