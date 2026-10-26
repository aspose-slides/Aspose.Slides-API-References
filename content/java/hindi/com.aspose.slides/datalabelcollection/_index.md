---
title: DataLabelCollection
second_title: Aspose.Slides के लिए Java API संदर्भ
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
| [getChart()](#getChart--) | पैरेंट चार्ट को लौटाता है। |
| [iterator()](#iterator--) | एक इंटरेटर लौटाता है जो संग्रह के माध्यम से इटरेट करता है। |
| [iteratorJava()](#iteratorJava--) | पूरे संग्रह के लिए एक जावा इटरेटर लौटाता है। |
| [isVisible()](#isVisible--) | फ़ॉल्स का अर्थ है कि डेटा लेबल डिफ़ॉल्ट रूप से दिखाई नहीं देता (और इसलिए DefaultDataLabelFormat प्रॉपर्टी के सभी Show*-फ़्लैग (ShowValue, ...) फ़ॉल्स होते हैं)। |
| [hide()](#hide--) | सभी Show*-फ़्लैग (ShowValue, ...) को false सेट करके डेटा लेबल को डिफ़ॉल्ट रूप से छिपा दें। |
| [getCountOfVisibleDataLabels()](#getCountOfVisibleDataLabels--) | संग्रह में दृश्यमान डेटा लेबल की संख्या प्राप्त करता है। |
| [getCount()](#getCount--) | संग्रह में सभी डेटा लेबल की संख्या प्राप्त करता है। |
| [getDefaultDataLabelFormat()](#getDefaultDataLabelFormat--) | डिफ़ॉल्ट डेटा लेबल फ़ॉर्मेट को प्राप्त करता है। |
| [getLeaderLinesFormat()](#getLeaderLinesFormat--) | डेटा लेबल लीडर लाइन्स फ़ॉर्मेट का प्रतिनिधित्व करता है। |
| [getParentSeries()](#getParentSeries--) | पैरेंट श्रृंखला को प्राप्त करता है। |
| [indexOf(IDataLabel value)](#indexOf-com.aspose.slides.IDataLabel-) | संग्रह में निर्दिष्ट DataLabel का अनुक्रमांक लौटाता है। |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट अनुक्रमांक वाले डेटा पॉइंट के लिए डेटा लेबल को प्राप्त करता है। |
| [getSlide()](#getSlide--) | FillFormat का पैरेंट स्लाइड लौटाता है। |
| [getPresentation()](#getPresentation--) | FillFormat की पैरेंट प्रस्तुति लौटाता है। |

### getChart() {#getChart--}
```
public final IChart getChart()
```

पैरेंट चार्ट को लौटाता है। केवल पढ़ने योग्य [IChart](../../com.aspose.slides/ichart)।

**वापसी:**
[IChart](../../com.aspose.slides/ichart)

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IDataLabel> iterator()
```

एक इंटरेटर लौटाता है जो संग्रह के माध्यम से इटरेट करता है।

**वापसी:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDataLabel> - एक IGenericEnumerator जो संग्रह के माध्यम से इटरेट करने के लिए उपयोग किया जा सकता है।

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IDataLabel> iteratorJava()
```

पूरे संग्रह के लिए एक जावा इटरेटर लौटाता है।

**वापसी:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDataLabel> - एक java.util.Iterator पूरे संग्रह के लिए।

### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

फ़ॉल्स का अर्थ है कि डेटा लेबल डिफ़ॉल्ट रूप से दिखाई नहीं देता (और इसलिए DefaultDataLabelFormat प्रॉपर्टी के सभी Show*-फ़्लैग (ShowValue, ...) फ़ॉल्स होते हैं)। केवल पढ़ने योग्य boolean।

---
यदि डेटा लेबल डिफ़ॉल्ट रूप से दिखाई देता है तो आप इसे Hide() मेथड के साथ डिफ़ॉल्ट रूप से छिपा सकते हैं। लेकिन यदि डेटा लेबल डिफ़ॉल्ट रूप से दिखाई नहीं देता (IsVisible फ़ॉल्स है) तो आप Show*-फ़्लैग (ShowValue, ...) को true सेट करके डेटा लेबल को "डिफ़ॉल्ट रूप से दृश्यमान" बना सकते हैं।

**वापसी:**
boolean

### hide() {#hide--}
```
public final void hide()
```

सभी Show*-फ़्लैग (ShowValue, ...) को false सेट करके डेटा लेबल को डिफ़ॉल्ट रूप से छिपा दें। इसके बाद IsVisible फ़ॉल्स होगा।

---
यदि डेटा लेबल डिफ़ॉल्ट रूप से दिखाई नहीं देता (IsVisible फ़ॉल्स है) तो आप Show*-फ़्लैग (ShowValue, ...) को true सेट करके डेटा लेबल को "डिफ़ॉल्ट रूप से दृश्यमान" बना सकते हैं।

### getCountOfVisibleDataLabels() {#getCountOfVisibleDataLabels--}
```
public final int getCountOfVisibleDataLabels()
```

संग्रह में दृश्यमान डेटा लेबल की संख्या प्राप्त करता है। केवल पढ़ने योग्य int।

**वापसी:**
int

### getCount() {#getCount--}
```
public final int getCount()
```

संग्रह में सभी डेटा लेबल की संख्या प्राप्त करता है। केवल पढ़ने योग्य int।

**वापसी:**
int

### getDefaultDataLabelFormat() {#getDefaultDataLabelFormat--}
```
public final IDataLabelFormat getDefaultDataLabelFormat()
```

डिफ़ॉल्ट डेटा लेबल फ़ॉर्मेट को प्राप्त करता है। केवल पढ़ने योग्य [IDataLabelFormat](../../com.aspose.slides/idatalabelformat)।

**वापसी:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)

### getLeaderLinesFormat() {#getLeaderLinesFormat--}
```
public final IChartLinesFormat getLeaderLinesFormat()
```

डेटा लेबल लीडर लाइन्स फ़ॉर्मेट का प्रतिनिधित्व करता है। केवल पढ़ने योग्य [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)।

---
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

**वापसी:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getParentSeries() {#getParentSeries--}
```
public final IChartSeries getParentSeries()
```

पैरेंट श्रृंखला को प्राप्त करता है। केवल पढ़ने योग्य [IChartSeries](../../com.aspose.slides/ichartseries)।

**वापसी:**
[IChartSeries](../../com.aspose.slides/ichartseries)

### indexOf(IDataLabel value) {#indexOf-com.aspose.slides.IDataLabel-}
```
public final int indexOf(IDataLabel value)
```

संग्रह में निर्दिष्ट DataLabel का अनुक्रमांक लौटाता है।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IDataLabel](../../com.aspose.slides/idatalabel) | DataLabel को खोजने के लिए। |

**वापसी:**
int - एक DataLabel का अनुक्रमांक या -1 यदि DataLabel इस संग्रह से नहीं है।

### get_Item(int index) {#get-Item-int-}
```
public final IDataLabel get_Item(int index)
```

निर्दिष्ट अनुक्रमांक वाले डेटा पॉइंट के लिए डेटा लेबल को प्राप्त करता है।

---
डेटा लेबल तक पहुँचने का वैकल्पिक तरीका है: - series.getDataPoints().get_Item(i).getLabel() - लेबल गुणों को प्रबंधित करें।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int |  |

**वापसी:**
[IDataLabel](../../com.aspose.slides/idatalabel)

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

FillFormat का पैरेंट स्लाइड लौटाता है। केवल पढ़ने योग्य [BaseSlide](../../com.aspose.slides/baseslide)।

**वापसी:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

FillFormat की पैरेंट प्रस्तुति लौटाता है। केवल पढ़ने योग्य [IPresentation](../../com.aspose.slides/ipresentation)।

**वापसी:**
[IPresentation](../../com.aspose.slides/ipresentation)