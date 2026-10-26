---
title: DataLabel
second_title: Aspose.Slides for Java API संदर्भ
description: एक श्रृंखला लेबल्स का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/datalabel/
---
**विरासत:**
java.lang.Object

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IDataLabel](../../com.aspose.slides/idatalabel), com.aspose.slides.IDOMObject
```
public class DataLabel implements IDataLabel, IDOMObject
```

एक श्रृंखला लेबल्स का प्रतिनिधित्व करता है।
## निर्माताएँ

| निर्माता | वर्णन |
| --- | --- |
| [DataLabel(IChartDataPoint parentImmediate)](#DataLabel-com.aspose.slides.IChartDataPoint-) | DataLabel वर्ग का एक नया उदाहरण बनाता है। |
## विधियाँ

| विधि | वर्णन |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | पैरेंट चार्ट लौटाता है। |
| [isVisible()](#isVisible--) | False का मतलब है कि डेटा लेबल दिखाई नहीं देता (और सभी Show*-flags (ShowValue, ...) झूठे होते हैं)। |
| [hide()](#hide--) | सभी Show*-flags (ShowValue, ...) को false स्थिति में सेट करके डेटा लेबल को छुपा दें। |
| [getActualLabelText()](#getActualLabelText--) | DataLabelFormat सेटिंग्स या TextFrameForOverriding.Text मान के आधार पर वास्तविक लेबल टेक्स्ट लौटाता है। |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | पैरामीटर "text" में टेक्स्ट के साथ TextFrameForOverriding को प्रारंभ करें। |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | रिच फॉर्मेटेड टेक्स्ट रख सकता है। |
| [getTextFormat()](#getTextFormat--) | टेक्स्ट फॉर्मेट लौटाता है। |
| [getX()](#getX--) | चार्ट की चौड़ाई के अनुपात में शीर्षक का x निर्देशांक लौटाता या सेट करता है। |
| [setX(float value)](#setX-float-) | चार्ट की चौड़ाई के अनुपात में शीर्षक का x निर्देशांक लौटाता या सेट करता है। |
| [getY()](#getY--) | चार्ट की ऊँचाई के अनुपात में शीर्षक का y निर्देशांक लौटाता या सेट करता है। |
| [setY(float value)](#setY-float-) | चार्ट की ऊँचाई के अनुपात में शीर्षक का y निर्देशांक लौटाता या सेट करता है। |
| [getWidth()](#getWidth--) | चार्ट की चौड़ाई के अनुपात में शीर्षक की चौड़ाई लौटाता या सेट करता है। |
| [setWidth(float value)](#setWidth-float-) | चार्ट की चौड़ाई के अनुपात में शीर्षक की चौड़ाई लौटाता या सेट करता है। |
| [getHeight()](#getHeight--) | चार्ट की ऊँचाई के अनुपात में शीर्षक की ऊँचाई लौटाता या सेट करता है। |
| [setHeight(float value)](#setHeight-float-) | चार्ट की ऊँचाई के अनुपात में शीर्षक की ऊँचाई लौटाता या सेट करता है। |
| [getRight()](#getRight--) | दायाँ। |
| [getBottom()](#getBottom--) | निचला। |
| [getDataLabelFormat()](#getDataLabelFormat--) | डेटा लेबल फॉर्मेट लौटाता है। |
| [getValueFromCell()](#getValueFromCell--) | वर्कबुक डेटा सेल प्राप्त करता या सेट करता है। |
| [setValueFromCell(IChartDataCell value)](#setValueFromCell-com.aspose.slides.IChartDataCell-) | वर्कबुक डेटा सेल प्राप्त करता या सेट करता है। |
| [getActualX()](#getActualX--) | चार्ट के बाएँ ऊपर कोने के सापेक्ष चार्ट तत्व का वास्तविक x स्थान (बाएँ) निर्दिष्ट करता है। |
| [getActualY()](#getActualY--) | चार्ट के बाएँ ऊपर कोने के सापेक्ष चार्ट तत्व का वास्तविक शीर्ष निर्दिष्ट करता है। |
| [getActualWidth()](#getActualWidth--) | चार्ट तत्व की वास्तविक चौड़ाई निर्दिष्ट करता है। |
| [getActualHeight()](#getActualHeight--) | चार्ट तत्व की वास्तविक ऊँचाई निर्दिष्ट करता है। |
| [getSlide()](#getSlide--) | FillFormat का पैरेंट स्लाइड लौटाता है। |
| [getPresentation()](#getPresentation--) | FillFormat की पैरेंट प्रस्तुति लौटाता है। |
### DataLabel(IChartDataPoint parentImmediate) {#DataLabel-com.aspose.slides.IChartDataPoint-}
```
public DataLabel(IChartDataPoint parentImmediate)
```

DataLabel वर्ग का एक नया उदाहरण बनाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| parentImmediate | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | पैरेंट ChartDataPoint। |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate ऑब्जेक्ट लौटाता है। केवल-पढ़ने योग्य IDOMObject।

**वापसी:**
com.aspose.slides.IDOMObject
### getChart() {#getChart--}
```
public final IChart getChart()
```

पैरेंट चार्ट लौटाता है। केवल-पढ़ने योग्य [IChart](../../com.aspose.slides/ichart)।

**वापसी:**
[IChart](../../com.aspose.slides/ichart)
### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

False का मतलब है कि डेटा लेबल दृश्य नहीं है (और सभी Show*-flags (ShowValue, ...) झूठे हैं)। केवल-पढ़ने योग्य boolean।

--------------------

यदि डेटा लेबल दृश्य है तो आप इसे Hide() मेथड से छुपा सकते हैं। लेकिन यदि डेटा लेबल दृश्य नहीं है (IsVisible false है) तो आप Show*-flags (ShowValue, ...) को true स्थिति में सेट करके डेटा लेबल को दृश्य बना सकते हैं।

**वापसी:**
boolean
### hide() {#hide--}
```
public final void hide()
```

सभी Show*-flags (ShowValue, ...) को false स्थिति में सेट करके डेटा लेबल को छुपा दें। इसके बाद IsVisible false रहेगा।

--------------------

यदि डेटा लेबल दृश्य नहीं है (IsVisible false है) तो आप Show*-flags (ShowValue, ...) को true स्थिति में सेट करके डेटा लेबल को दृश्य बना सकते हैं।

### getActualLabelText() {#getActualLabelText--}
```
public final String getActualLabelText()
```

DataLabelFormat सेटिंग्स या TextFrameForOverriding.Text मान के आधार पर वास्तविक लेबल टेक्स्ट लौटाता है।

**वापसी:**
java.lang.String - java.lang.String ऑब्जेक्ट।
### addTextFrameForOverriding(String text) {#addTextFrameForOverriding-java.lang.String-}
```
public final ITextFrame addTextFrameForOverriding(String text)
```

पैरामीटर "text" में टेक्स्ट के साथ TextFrameForOverriding को प्रारंभ करें। यदि TextFrameForOverriding पहले से प्रारंभ है तो केवल उसका टेक्स्ट बदलें।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| text | java.lang.String | नए TextFrameForOverriding के लिए टेक्स्ट। |

**वापसी:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTextFrameForOverriding() {#getTextFrameForOverriding--}
```
public final ITextFrame getTextFrameForOverriding()
```

रिच फ़ॉर्मेटेड टेक्स्ट रख सकता है। यदि यह प्रॉपर्टी null नहीं है तो यह फ़ॉर्मेटेड टेक्स्ट मान डेटा लेबल के स्वतः-जनरेटेड टेक्स्ट को ओवरराइड करता है। डेटा लेबल का स्वतः जनरेटेड टेक्स्ट वह टेक्स्ट है जिसे ShowSeriesName, ShowValue, ... प्रॉपर्टी द्वारा प्रबंधित किया जाता है और TextFormatManager.TextFormat प्रॉपर्टी से फ़ॉर्मेट किया जाता है। केवल-पढ़ने योग्य [ITextFrame](../../com.aspose.slides/itextframe)।

**वापसी:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

टेक्स्ट फॉर्मेट लौटाता है। केवल-पढ़ने योग्य [IChartTextFormat](../../com.aspose.slides/icharttextformat)।

**वापसी:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### getX() {#getX--}
```
public final float getX()
```

चार्ट की चौड़ाई के अनुपात में शीर्षक का x निर्देशांक लौटाता या सेट करता है। पढ़ने/लिखने योग्य float।

**वापसी:**
float
### setX(float value) {#setX-float-}
```
public final void setX(float value)
```

चार्ट की चौड़ाई के अनुपात में शीर्षक का x निर्देशांक लौटाता या सेट करता है। पढ़ने/लिखने योग्य float।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |
### getY() {#getY--}
```
public final float getY()
```

चार्ट की ऊँचाई के अनुपात में शीर्षक का y निर्देशांक लौटाता या सेट करता है। पढ़ने/लिखने योग्य float।

**वापसी:**
float
### setY(float value) {#setY-float-}
```
public final void setY(float value)
```

चार्ट की ऊँचाई के अनुपात में शीर्षक का y निर्देशांक लौटाता या सेट करता है। पढ़ने/लिखने योग्य float।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |
### getWidth() {#getWidth--}
```
public final float getWidth()
```

चार्ट की चौड़ाई के अनुपात में शीर्षक की चौड़ाई लौटाता या सेट करता है। पढ़ने/लिखने योग्य float।

**वापसी:**
float
### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```

चार्ट की चौड़ाई के अनुपात में शीर्षक की चौड़ाई लौटाता या सेट करता है। पढ़ने/लिखने योग्य float।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |
### getHeight() {#getHeight--}
```
public final float getHeight()
```

चार्ट की ऊँचाई के अनुपात में शीर्षक की ऊँचाई लौटाता या सेट करता है। पढ़ने/लिखने योग्य float।

**वापसी:**
float
### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```

चार्ट की ऊँचाई के अनुपात में शीर्षक की ऊँचाई लौटाता या सेट करता है। पढ़ने/लिखने योग्य float।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |
### getRight() {#getRight--}
```
public final float getRight()
```

दायाँ। केवल-पढ़ने योग्य float।

**वापसी:**
float
### getBottom() {#getBottom--}
```
public final float getBottom()
```

निचला। केवल-पढ़ने योग्य float।

**वापसी:**
float
### getDataLabelFormat() {#getDataLabelFormat--}
```
public final IDataLabelFormat getDataLabelFormat()
```

डेटा लेबल फॉर्मेट लौटाता है। केवल-पढ़ने योग्य [IDataLabelFormat](../../com.aspose.slides/idatalabelformat)।

**वापसी:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getValueFromCell() {#getValueFromCell--}
```
public final IChartDataCell getValueFromCell()
```

वर्कबुक डेटा सेल प्राप्त करता या सेट करता है। यदि IDataLabelFormat.ShowLabelValueFromCell प्रॉपर्टी true है तो लागू होता है।

**वापसी:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setValueFromCell(IChartDataCell value) {#setValueFromCell-com.aspose.slides.IChartDataCell-}
```
public final void setValueFromCell(IChartDataCell value)
```

वर्कबुक डेटा सेल प्राप्त करता या सेट करता है। यदि IDataLabelFormat.ShowLabelValueFromCell प्रॉपर्टी true है तो लागू होता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |
### getActualX() {#getActualX--}
```
public final float getActualX()
```

चार्ट के बाएँ ऊपर कोने के सापेक्ष चार्ट तत्व का वास्तविक x स्थान (बाएँ) निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए IChart.ValidateChartLayout() मेथड को पहले कॉल करें। पढ़ें float।

**वापसी:**
float
### getActualY() {#getActualY--}
```
public final float getActualY()
```

चार्ट के बाएँ ऊपर कोने के सापेक्ष चार्ट तत्व का वास्तविक शीर्ष निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए IChart.ValidateChartLayout() मेथड को पहले कॉल करें। पढ़ें float।

**वापसी:**
float
### getActualWidth() {#getActualWidth--}
```
public final float getActualWidth()
```

चार्ट तत्व की वास्तविक चौड़ाई निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए IChart.ValidateChartLayout() मेथड को पहले कॉल करें। पढ़ें float।

**वापसी:**
float
### getActualHeight() {#getActualHeight--}
```
public final float getActualHeight()
```

चार्ट तत्व की वास्तविक ऊँचाई निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए IChart.ValidateChartLayout() मेथड को पहले कॉल करें। पढ़ें float।

**वापसी:**
float
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

FillFormat का पैरेंट स्लाइड लौटाता है। केवल-पढ़ने योग्य [BaseSlide](../../com.aspose.slides/baseslide)।

**वापसी:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

FillFormat की पैरेंट प्रस्तुति लौटाता है। केवल-पढ़ने योग्य [IPresentation](../../com.aspose.slides/ipresentation)।

**वापसी:**
[IPresentation](../../com.aspose.slides/ipresentation)