---
title: IDataLabelCollection
second_title: Aspose.Slides के लिए जावा API संदर्भ
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

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट इंडेक्स वाले डेटा पॉइंट के लिए डेटा लेबल प्राप्त करता है। |
| [getDefaultDataLabelFormat()](#getDefaultDataLabelFormat--) | संग्रह में सभी डेटा लेबल्स के डिफॉल्ट फ़ॉर्मेट को लौटाता है। |
| [getLeaderLinesFormat()](#getLeaderLinesFormat--) | डेटा लेबल्स के लीडर लाइन्स फ़ॉर्मेट का प्रतिनिधित्व करता है। |
| [isVisible()](#isVisible--) | फ़ॉल्स का अर्थ है कि डेटा लेबल डिफॉल्ट रूप से दृश्यमान नहीं है (और इसलिए DefaultDataLabelFormat प्रॉपर्टी के सभी Show*-फ़्लैग (ShowValue, ...) फ़ॉल्स होते हैं)। |
| [hide()](#hide--) | सभी Show*-flags (ShowValue, ...) को false स्थिति पर सेट करके डेटा लेबल को डिफॉल्ट रूप से छिपा दें। |
| [getCountOfVisibleDataLabels()](#getCountOfVisibleDataLabels--) | संग्रह में दृश्यमान डेटा लेबल्स की संख्या प्राप्त करता है। |
| [getCount()](#getCount--) | संग्रह में सभी डेटा लेबल्स की संख्या प्राप्त करता है। |
| [getParentSeries()](#getParentSeries--) | पैरेंट चार्ट सीरीज़ लौटाता है। |
| [indexOf(IDataLabel value)](#indexOf-com.aspose.slides.IDataLabel-) | संग्रह में निर्दिष्ट DataLabel का इंडेक्स लौटाता है। |

### get_Item(int index) {#get-Item-int-}
```
public abstract IDataLabel get_Item(int index)
```

निर्दिष्ट इंडेक्स वाले डेटा पॉइंट के लिए डेटा लेबल प्राप्त करता है।

--------------------

डेटा लेबल तक पहुंचने का वैकल्पिक तरीका है: - getSeries().getDataPoints().get_Item(i).getLabel() - लेबल प्रॉपर्टीज़ को प्रबंधित करें।

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

संग्रह में सभी डेटा लेबल्स के डिफॉल्ट फ़ॉर्मेट को लौटाता है। केवल पढ़ने योग्य [IDataLabelFormat](../../com.aspose.slides/idatalabelformat)।

**रिटर्न:**  
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)

### getLeaderLinesFormat() {#getLeaderLinesFormat--}
```
public abstract IChartLinesFormat getLeaderLinesFormat()
```

डेटा लेबल्स के लीडर लाइन्स फ़ॉर्मेट का प्रतिनिधित्व करता है। केवल पढ़ने योग्य [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)।

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

फ़ॉल्स का अर्थ है कि डेटा लेबल डिफॉल्ट रूप से दृश्यमान नहीं है (और इसलिए DefaultDataLabelFormat प्रॉपर्टी के सभी Show*-फ़्लैग (ShowValue, ...) फ़ॉल्स होते हैं)。 केवल पढ़ने योग्य boolean .

--------------------

यदि डेटा लेबल डिफॉल्ट रूप से दृश्यमान है तो आप इसे Hide() मेथड से डिफॉल्ट रूप से छिपा सकते हैं। लेकिन यदि डेटा लेबल डिफॉल्ट रूप से दृश्यमान नहीं है (IsVisible फ़ॉल्स है) तो आप Show*-फ़्लैग (ShowValue, ...) को true स्थिति में सेट करके डेटा लेबल को "डिफॉल्ट रूप से दृश्यमान" बना सकते हैं।

**रिटर्न:**  
boolean

### hide() {#hide--}
```
public abstract void hide()
```

सभी Show*-flags (ShowValue, ...) को false स्थिति पर सेट करके डेटा लेबल को डिफॉल्ट रूप से छिपा दें। इसके बाद IsVisible फ़ॉल्स होगा।

--------------------

यदि डेटा लेबल डिफॉल्ट रूप से दृश्यमान नहीं है (IsVisible फ़ॉल्स है) तो आप Show*-flags (ShowValue, ...) को true स्थिति में सेट करके डेटा लेबल को "डिफॉल्ट रूप से दृश्यमान" बना सकते हैं।

### getCountOfVisibleDataLabels() {#getCountOfVisibleDataLabels--}
```
public abstract int getCountOfVisibleDataLabels()
```

संग्रह में दृश्यमान डेटा लेबल्स की संख्या प्राप्त करता है। केवल पढ़ने योग्य int .

**रिटर्न:**  
int

### getCount() {#getCount--}
```
public abstract int getCount()
```

संग्रह में सभी डेटा लेबल्स की संख्या प्राप्त करता है। केवल पढ़ने योग्य int .

**रिटर्न:**  
int

### getParentSeries() {#getParentSeries--}
```
public abstract IChartSeries getParentSeries()
```

पैरेंट चार्ट सीरीज़ लौटाता है। केवल पढ़ने योग्य [IChartSeries](../../com.aspose.slides/ichartseries)।

**रिटर्न:**  
[IChartSeries](../../com.aspose.slides/ichartseries)

### indexOf(IDataLabel value) {#indexOf-com.aspose.slides.IDataLabel-}
```
public abstract int indexOf(IDataLabel value)
```

संग्रह में निर्दिष्ट DataLabel का इंडेक्स लौटाता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IDataLabel](../../com.aspose.slides/idatalabel) | खोजने के लिए DataLabel। |

**रिटर्न:**  
int - DataLabel का इंडेक्स या -1 यदि DataLabel इस संग्रह का नहीं है।