---
title: DataLabel
second_title: Aspose.Slides for Android के लिए जावा API संदर्भ
description: एक श्रृंखला लेबल का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/datalabel/
---
**उत्पत्ति:**
java.lang.Object

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IDataLabel](../../com.aspose.slides/idatalabel), com.aspose.slides.IDOMObject
```
public class DataLabel implements IDataLabel, IDOMObject
```

एक श्रृंखला लेबल का प्रतिनिधित्व करता है।

## निर्माता

| निर्माता | विवरण |
| --- | --- |
| [DataLabel(IChartDataPoint parentImmediate)](#DataLabel-com.aspose.slides.IChartDataPoint-) | DataLabel class की नई उदाहरण बनाता है। |

## विधियां

| विधि | विवरण |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | पैरेंट chart लौटाता है। |
| [isVisible()](#isVisible--) | False का अर्थ है कि डेटा लेबल दृश्यमान नहीं है (और सभी Show\*-flags (ShowValue, ...) झूठे होते हैं)। |
| [hide()](#hide--) | सभी Show\*-flags (ShowValue, ...) को false स्थिति में सेट करके डेटा लेबल को छिपा दें। |
| [getActualLabelText()](#getActualLabelText--) | DataLabelFormat सेटिंग्स या TextFrameForOverriding.Text मान के आधार पर वास्तविक लेबल टेक्स्ट लौटाता है। |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | पैरामीटर "text" के टेक्स्ट से TextFrameForOverriding को प्रारंभ करें। |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | रिच फॉर्मेटेड टेक्स्ट शामिल कर सकता है। |
| [getTextFormat()](#getTextFormat--) | टेक्स्ट फ़ॉर्मेट लौटाता है। |
| [getX()](#getX--) | चार्ट की चौड़ाई के अनुपात में शीर्षक का x निर्देशांक लौटाता है या सेट करता है। |
| [setX(float value)](#setX-float-) | चार्ट की चौड़ाई के अनुपात में शीर्षक का x निर्देशांक लौटाता है या सेट करता है। |
| [getY()](#getY--) | चार्ट की ऊँचाई के अनुपात में शीर्षक का y निर्देशांक लौटाता है या सेट करता है। |
| [setY(float value)](#setY-float-) | चार्ट की ऊँचाई के अनुपात में शीर्षक का y निर्देशांक लौटाता है या सेट करता है। |
| [getWidth()](#getWidth--) | चार्ट की चौड़ाई के अनुपात में शीर्षक की चौड़ाई लौटाता है या सेट करता है। |
| [setWidth(float value)](#setWidth-float-) | चार्ट की चौड़ाई के अनुपात में शीर्षक की चौड़ाई लौटाता है या सेट करता है। |
| [getHeight()](#getHeight--) | चार्ट की ऊँचाई के अनुपात में शीर्षक की ऊँचाई लौटाता है या सेट करता है। |
| [setHeight(float value)](#setHeight-float-) | चार्ट की ऊँचाई के अनुपात में शीर्षक की ऊँचाई लौटाता है या सेट करता है। |
| [getRight()](#getRight--) | दायां। |
| [getBottom()](#getBottom--) | नीचे। |
| [getDataLabelFormat()](#getDataLabelFormat--) | डेटा लेबल फ़ॉर्मेट लौटाता है। |
| [getValueFromCell()](#getValueFromCell--) | वर्कबुक डेटा सेल प्राप्त करता है या सेट करता है। |
| [setValueFromCell(IChartDataCell value)](#setValueFromCell-com.aspose.slides.IChartDataCell-) | वर्कबुक डेटा सेल प्राप्त करता है या सेट करता है। |
| [getActualX()](#getActualX--) | चार्ट तत्व की वास्तविक x स्थिति (बाएँ) को चार्ट के बाएँ शीर्ष कोने के सापेक्ष निर्दिष्ट करता है। |
| [getActualY()](#getActualY--) | चार्ट तत्व के वास्तविक शीर्ष को चार्ट के बाएँ शीर्ष कोने के सापेक्ष निर्दिष्ट करता है। |
| [getActualWidth()](#getActualWidth--) | चार्ट तत्व की वास्तविक चौड़ाई निर्दिष्ट करता है। |
| [getActualHeight()](#getActualHeight--) | चार्ट तत्व की वास्तविक ऊँचाई निर्दिष्ट करता है। |
| [getSlide()](#getSlide--) | FillFormat का पैरेंट स्लाइड लौटाता है। |
| [getPresentation()](#getPresentation--) | FillFormat की पैरेंट प्रेजेंटेशन लौटाता है। |

### DataLabel(IChartDataPoint parentImmediate) {#DataLabel-com.aspose.slides.IChartDataPoint-}
```
public DataLabel(IChartDataPoint parentImmediate)
```

DataLabel class की नई उदाहरण बनाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| parentImmediate | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | पैरेंट ChartDataPoint। |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate ऑब्जेक्ट लौटाता है। केवल-पढ़ने योग्य IDOMObject।

**रिटर्न:**
com.aspose.slides.IDOMObject

### getChart() {#getChart--}
```
public final IChart getChart()
```

पैरेंट chart लौटाता है। केवल-पढ़ने योग्य [IChart](../../com.aspose.slides/ichart)।

**रिटर्न:**
[IChart](../../com.aspose.slides/ichart)

### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

False का अर्थ है कि डेटा लेबल दृश्यमान नहीं है (और सभी Show\*-flags (ShowValue, ...) झूठे होते हैं)। केवल-पढ़ने योग्य boolean।

---

यदि डेटा लेबल दृश्यमान है तो आप इसे Hide() मेथड से छिपा सकते हैं। लेकिन यदि डेटा लेबल दृश्यमान नहीं है (IsVisible false है) तो आप Show\*-flags (ShowValue, ...) को true स्थिति में सेट करके इसे दृश्यमान बना सकते हैं।

**रिटर्न:**
boolean

### hide() {#hide--}
```
public final void hide()
```

सभी Show\*-flags (ShowValue, ...) को false स्थिति में सेट करके डेटा लेबल को छिपा दें। इसके बाद IsVisible false होगा।

---

यदि डेटा लेबल दृश्यमान नहीं है (IsVisible false) तो आप Show\*-flags (ShowValue, ...) को true स्थिति में सेट करके इसे दृश्यमान बना सकते हैं।

### getActualLabelText() {#getActualLabelText--}
```
public final String getActualLabelText()
```

DataLabelFormat सेटिंग्स या TextFrameForOverriding.Text मान के आधार पर वास्तविक लेबल टेक्स्ट लौटाता है।

**रिटर्न:**
java.lang.String - java.lang.String ऑब्जेक्ट।

### addTextFrameForOverriding(String text) {#addTextFrameForOverriding-java.lang.String-}
```
public final ITextFrame addTextFrameForOverriding(String text)
```

पैरामीटर "text" के टेक्स्ट से TextFrameForOverriding को प्रारंभ करें। यदि TextFrameForOverriding पहले से प्रारंभ है तो केवल उसका टेक्स्ट बदलें।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| text | java.lang.String | नए TextFrameForOverriding के लिए टेक्स्ट। |

**रिटर्न:**
[ITextFrame](../../com.aspose.slides/itextframe)

### getTextFrameForOverriding() {#getTextFrameForOverriding--}
```
public final ITextFrame getTextFrameForOverriding()
```

रिच फॉर्मेटेड टेक्स्ट शामिल कर सकता है। यदि यह प्रॉपर्टी null नहीं है तो यह फॉर्मेटेड टेक्स्ट मान डेटा लेबल के स्वतः-जनरेटेड टेक्स्ट को ओवरराइड करता है। डेटा लेबल का स्वतः-जनरेटेड टेक्स्ट वह टेक्स्ट है जो ShowSeriesName, ShowValue, ... प्रॉपर्टी द्वारा प्रबंधित होता है और TextFormatManager.TextFormat प्रॉपर्टी से फॉर्मेट किया जाता है। केवल-पढ़ने योग्य [ITextFrame](../../com.aspose.slides/itextframe)।

**रिटर्न:**
[ITextFrame](../../com.aspose.slides/itextframe)

### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

टेक्स्ट फ़ॉर्मेट लौटाता है। केवल-पढ़ने योग्य [IChartTextFormat](../../com.aspose.slides/icharttextformat)।

**रिटर्न:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)

### getX() {#getX--}
```
public final float getX()
```

चार्ट की चौड़ाई के अनुपात में शीर्षक का x निर्देशांक लौटाता है या सेट करता है। पढ़ने/लिखने योग्य float।

**रिटर्न:**
float

### setX(float value) {#setX-float-}
```
public final void setX(float value)
```

चार्ट की चौड़ाई के अनुपात में शीर्षक का x निर्देशांक लौटाता है या सेट करता है। पढ़ने/लिखने योग्य float।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### getY() {#getY--}
```
public final float getY()
```

चार्ट की ऊँचाई के अनुपात में शीर्षक का y निर्देशांक लौटाता है या सेट करता है। पढ़ने/लिखने योग्य float।

**रिटर्न:**
float

### setY(float value) {#setY-float-}
```
public final void setY(float value)
```

चार्ट की ऊँचाई के अनुपात में शीर्षक का y निर्देशांक लौटाता है या सेट करता है। पढ़ने/लिखने योग्य float।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### getWidth() {#getWidth--}
```
public final float getWidth()
```

चार्ट की चौड़ाई के अनुपात में शीर्षक की चौड़ाई लौटाता है या सेट करता है। पढ़ने/लिखने योग्य float।

**रिटर्न:**
float

### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```

चार्ट की चौड़ाई के अनुपात में शीर्षक की चौड़ाई लौटाता है या सेट करता है। पढ़ने/लिखने योग्य float।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### getHeight() {#getHeight--}
```
public final float getHeight()
```

चार्ट की ऊँचाई के अनुपात में शीर्षक की ऊँचाई लौटाता है या सेट करता है। पढ़ने/लिखने योग्य float।

**रिटर्न:**
float

### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```

चार्ट की ऊँचाई के अनुपात में शीर्षक की ऊँचाई लौटाता है या सेट करता है। पढ़ने/लिखने योग्य float।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### getRight() {#getRight--}
```
public final float getRight()
```

दायां। केवल-पढ़ने योग्य float।

**रिटर्न:**
float

### getBottom() {#getBottom--}
```
public final float getBottom()
```

नीचा। केवल-पढ़ने योग्य float।

**रिटर्न:**
float

### getDataLabelFormat() {#getDataLabelFormat--}
```
public final IDataLabelFormat getDataLabelFormat()
```

डेटा लेबल फ़ॉर्मेट लौटाता है। केवल-पढ़ने योग्य [IDataLabelFormat](../../com.aspose.slides/idatalabelformat)।

**रिटर्न:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)

### getValueFromCell() {#getValueFromCell--}
```
public final IChartDataCell getValueFromCell()
```

वर्कबुक डेटा सेल प्राप्त करता है या सेट करता है। यदि IDataLabelFormat.ShowLabelValueFromCell प्रॉपर्टी true है तो लागू होता है।

**रिटर्न:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)

### setValueFromCell(IChartDataCell value) {#setValueFromCell-com.aspose.slides.IChartDataCell-}
```
public final void setValueFromCell(IChartDataCell value)
```

वर्कबुक डेटा सेल प्राप्त करता है या सेट करता है। यदि IDataLabelFormat.ShowLabelValueFromCell प्रॉपर्टी true है तो लागू होता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getActualX() {#getActualX--}
```
public final float getActualX()
```

चार्ट के बाएँ शीर्ष कोने के सापेक्ष चार्ट तत्व की वास्तविक x स्थिति (बाएँ) निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए पहले IChart.ValidateChartLayout() मेथड को कॉल करें। पढ़ने योग्य float।

**रिटर्न:**
float

### getActualY() {#getActualY--}
```
public final float getActualY()
```

चार्ट के बाएँ शीर्ष कोने के सापेक्ष चार्ट तत्व की वास्तविक y स्थिति (ऊपर) निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए पहले IChart.ValidateChartLayout() मेथड को कॉल करें। पढ़ने योग्य float।

**रिटर्न:**
float

### getActualWidth() {#getActualWidth--}
```
public final float getActualWidth()
```

चार्ट तत्व की वास्तविक चौड़ाई निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए पहले IChart.ValidateChartLayout() मेथड को कॉल करें। पढ़ने योग्य float।

**रिटर्न:**
float

### getActualHeight() {#getActualHeight--}
```
public final float getActualHeight()
```

चार्ट तत्व की वास्तविक ऊँचाई निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए पहले IChart.ValidateChartLayout() मेथड को कॉल करें। पढ़ने योग्य float।

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

FillFormat की पैरेंट प्रेजेंटेशन लौटाता है। केवल-पढ़ने योग्य [IPresentation](../../com.aspose.slides/ipresentation)।

**रिटर्न:**
[IPresentation](../../com.aspose.slides/ipresentation)