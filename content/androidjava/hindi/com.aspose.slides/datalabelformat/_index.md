---
title: DataLabelFormat
second_title: Java API संदर्भ के माध्यम से Aspose.Slides for Android
description: DataLabel के लिए स्वरूप विकल्पों का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/datalabelformat/
---
**विरासत:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
```
public final class DataLabelFormat extends PVIObject implements IDataLabelFormat
```

DataLabel के लिए स्वरूपण विकल्पों का प्रतिनिधित्व करता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | पढ़ें/लिखें boolean। |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | पढ़ें/लिखें boolean। |
| [getNumberFormat()](#getNumberFormat--) | DataLabels ऑब्जेक्ट के लिए फ़ॉर्मेट स्ट्रिंग का प्रतिनिधित्व करता है। |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | DataLabels ऑब्जेक्ट के लिए फ़ॉर्मेट स्ट्रिंग का प्रतिनिधित्व करता है। |
| [getFormat()](#getFormat--) | डेटा लेबल के स्वरूप का प्रतिनिधित्व करता है। |
| [getPosition()](#getPosition--) | डेटा लेबल की स्थिति का प्रतिनिधित्व करता है। |
| [setPosition(int value)](#setPosition-int-) | डेटा लेबल की स्थिति का प्रतिनिधित्व करता है। |
| [getShowLegendKey()](#getShowLegendKey--) | निर्दिष्ट चार्ट के डेटा लेबल लेजेंड कुंजी प्रदर्शन व्यवहार का प्रतिनिधित्व करता है। |
| [setShowLegendKey(boolean value)](#setShowLegendKey-boolean-) | निर्दिष्ट चार्ट के डेटा लेबल लेजेंड कुंजी प्रदर्शन व्यवहार का प्रतिनिधित्व करता है। |
| [getShowValue()](#getShowValue--) | निर्दिष्ट चार्ट के डेटा लेबल प्रतिशत मान प्रदर्शन व्यवहार का प्रतिनिधित्व करता है। |
| [setShowValue(boolean value)](#setShowValue-boolean-) | निर्दिष्ट चार्ट के डेटा लेबल प्रतिशत मान प्रदर्शन व्यवहार का प्रतिनिधित्व करता है। |
| [getShowCategoryName()](#getShowCategoryName--) | निर्दिष्ट चार्ट के डेटा लेबल वर्ग नाम प्रदर्शन व्यवहार का प्रतिनिधित्व करता है। |
| [setShowCategoryName(boolean value)](#setShowCategoryName-boolean-) | निर्दिष्ट चार्ट के डेटा लेबल वर्ग नाम प्रदर्शन व्यवहार का प्रतिनिधित्व करता है। |
| [getShowSeriesName()](#getShowSeriesName--) | डेटा लेबल पर चार्ट में सीरीज़ नाम प्रदर्शन व्यवहार को इंगित करने के लिए Boolean को लौटाता है या सेट करता है। |
| [setShowSeriesName(boolean value)](#setShowSeriesName-boolean-) | डेटा लेबल पर चार्ट में सीरीज़ नाम प्रदर्शन व्यवहार को इंगित करने के लिए Boolean को लौटाता है या सेट करता है। |
| [getShowPercentage()](#getShowPercentage--) | निर्दिष्ट चार्ट के डेटा लेबल प्रतिशत मान प्रदर्शन व्यवहार का प्रतिनिधित्व करता है। |
| [setShowPercentage(boolean value)](#setShowPercentage-boolean-) | निर्दिष्ट चार्ट के डेटा लेबल प्रतिशत मान प्रदर्शन व्यवहार का प्रतिनिधित्व करता है। |
| [getShowBubbleSize()](#getShowBubbleSize--) | निर्दिष्ट चार्ट के डेटा लेबल बबल आकार मान प्रदर्शन व्यवहार का प्रतिनिधित्व करता है। |
| [setShowBubbleSize(boolean value)](#setShowBubbleSize-boolean-) | निर्दिष्ट चार्ट के डेटा लेबल बबल आकार मान प्रदर्शन व्यवहार का प्रतिनिधित्व करता है। |
| [getShowLeaderLines()](#getShowLeaderLines--) | निर्दिष्ट चार्ट के डेटा लेबल लीडर लाइन्स प्रदर्शन व्यवहार का प्रतिनिधित्व करता है। |
| [setShowLeaderLines(boolean value)](#setShowLeaderLines-boolean-) | निर्दिष्ट चार्ट के डेटा लेबल लीडर लाइन्स प्रदर्शन व्यवहार का प्रतिनिधित्व करता है। |
| [getShowLabelValueFromCell()](#getShowLabelValueFromCell--) | निर्दिष्ट चार्ट के डेटा लेबल सेल मान प्रदर्शन व्यवहार का प्रतिनिधित्व करता है। |
| [setShowLabelValueFromCell(boolean value)](#setShowLabelValueFromCell-boolean-) | निर्दिष्ट चार्ट के डेटा लेबल सेल मान प्रदर्शन व्यवहार का प्रतिनिधित्व करता है। |
| [getShowLabelAsDataCallout()](#getShowLabelAsDataCallout--) | निर्धारित करता है कि निर्दिष्ट चार्ट का डेटा लेबल डेटा कॉलआउट के रूप में या डेटा लेबल के रूप में प्रदर्शित होगा। |
| [setShowLabelAsDataCallout(boolean value)](#setShowLabelAsDataCallout-boolean-) | निर्धारित करता है कि निर्दिष्ट चार्ट का डेटा लेबल डेटा कॉलआउट के रूप में या डेटा लेबल के रूप में प्रदर्शित होगा। |
| [getSeparator()](#getSeparator--) | डेटा लेबल पर चार्ट में प्रयुक्त विभाजक को दर्शाने वाले Variant को सेट करता है या लौटाता है। |
| [setSeparator(String value)](#setSeparator-java.lang.String-) | डेटा लेबल पर चार्ट में प्रयुक्त विभाजक को दर्शाने वाले Variant को सेट करता है या लौटाता है। |
| [getTextFormat()](#getTextFormat--) | चार्ट टेक्स्ट फ़ॉर्मेट लौटाता है। |
| [getChart()](#getChart--) | चार्ट लौटाता है। |

### getVersion() {#getVersion--}
```
public long getVersion()
```

संस्करण। केवल-पढ़ने योग्य long।

**वापसी:**  
long

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public final boolean isNumberFormatLinkedToSource()
```

पढ़ें/लिखें boolean।

--------------------

यदि इस DataLabelFormat वस्तु का पैरेंट डेटा लेबल्स का DataLabelCollection संग्रह है, तो यह संपत्ति DataLabelCollection संग्रह में नए डेटा लेबल्स के लिए IsNumberFormatLinkedToSource संपत्ति का डिफ़ॉल्ट मान प्राप्त करती है या सेट करती है। इस संपत्ति को मान के साथ सेट करने से यह मान सभी डेटा लेबल्स में IsNumberFormatLinkedToSource संपत्ति के लिए भी सेट हो जाता है (उदाहरण के लिए "DataLabels.getDefaultDataLabelFormat().isNumberFormatLinkedToSource(val);" सभी DataLabels.get_Item(i).isNumberFormatLinkedToSource() को val के बराबर बनाता है)।

**वापसी:**  
boolean

### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public final void setNumberFormatLinkedToSource(boolean value)
```

पढ़ें/लिखें boolean।

--------------------

यदि इस DataLabelFormat वस्तु का पैरेंट डेटा लेबल्स का DataLabelCollection संग्रह है, तो यह संपत्ति DataLabelCollection संग्रह में नए डेटा लेबल्स के लिए IsNumberFormatLinkedToSource संपत्ति का डिफ़ॉल्ट मान प्राप्त करती है या सेट करती है। इस संपत्ति को मान के साथ सेट करने से यह मान सभी डेटा लेबल्स में IsNumberFormatLinkedToSource संपत्ति के लिए भी सेट हो जाता है (उदाहरण के लिए "DataLabels.getDefaultDataLabelFormat().isNumberFormatLinkedToSource(val);" सभी DataLabels.get_Item(i).isNumberFormatLinkedToSource() को val के बराबर बनाता है)।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public final String getNumberFormat()
```

DataLabels ऑब्जेक्ट के लिए फ़ॉर्मेट स्ट्रिंग का प्रतिनिधित्व करता है। पढ़ें/लिखें String।

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```

--------------------

यदि इस DataLabelFormat वस्तु का पैरेंट डेटा लेबल्स का DataLabelCollection संग्रह है, तो यह संपत्ति DataLabelCollection संग्रह में नए डेटा लेबल्स के लिए NumberFormat संपत्ति का डिफ़ॉल्ट मान प्राप्त करती है या सेट करती है। इस संपत्ति को मान के साथ सेट करने से यह मान सभी डेटा लेबल्स में NumberFormat संपत्ति के लिए भी सेट हो जाता है (उदाहरण के लिए "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" सभी DataLabels.get_Item(i).getNumberFormat() को val के बराबर बनाता है)।

**वापसी:**  
java.lang.String

### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public final void setNumberFormat(String value)
```

DataLabels ऑब्जेक्ट के लिए फ़ॉर्मेट स्ट्रिंग का प्रतिनिधित्व करता है। पढ़ें/लिखें String।

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```

--------------------

यदि इस DataLabelFormat वस्तु का पैरेंट डेटा लेबल्स का DataLabelCollection संग्रह है, तो यह संपत्ति DataLabelCollection संग्रह में नए डेटा लेबल्स के लिए NumberFormat संपत्ति का डिफ़ॉल्ट मान प्राप्त करती है या सेट करती है। इस संपत्ति को मान के साथ सेट करने से यह मान सभी डेटा लेबल्स में NumberFormat संपत्ति के लिए भी सेट हो जाता है (उदाहरण के लिए "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" सभी DataLabels.get_Item(i).getNumberFormat() को val के बराबर बनाता है)।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

डेटा लेबल के स्वरूप का प्रतिनिधित्व करता है। केवल-पढ़ने योग्य [IFormat](../../com.aspose.slides/iformat)।

--------------------

यदि इस DataLabelFormat वस्तु का पैरेंट डेटा लेबल्स का DataLabelCollection संग्रह है, तो यह संपत्ति नए डेटा लेबल्स के लिए डिफ़ॉल्ट स्वरूप का प्रतिनिधित्व करती है।

**वापसी:**  
[IFormat](../../com.aspose.slides/iformat)

### getPosition() {#getPosition--}
```
public final int getPosition()
```

डेटा लेबल की स्थिति का प्रतिनिधित्व करता है। पढ़ें/लिखें [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition)।

--------------------

यदि इस DataLabelFormat वस्तु का पैरेंट डेटा लेबल्स का DataLabelCollection संग्रह है, तो यह संपत्ति DataLabelCollection संग्रह में नए डेटा लेबल्स के लिए Position संपत्ति का डिफ़ॉल्ट मान प्राप्त करती है या सेट करती है। यह DataLabel ऑब्जेक्ट की स्थिति को दर्शाता है। इस संपत्ति को मान के साथ सेट करने से यह मान सभी डेटा लेबल्स में Position संपत्ति के लिए भी सेट हो जाता है (उदाहरण के लिए "DataLabels.getDefaultDataLabelFormat().setPosition(val);" सभी DataLabels.get_Item(i).getPosition() को val के बराबर बनाता है)।

**वापसी:**  
int

### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```

डेटा लेबल की स्थिति का प्रतिनिधित्व करता है। पढ़ें/लिखें [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition)।

--------------------

यदि इस DataLabelFormat वस्तु का पैरेंट डेटा लेबल्स का DataLabelCollection संग्रह है, तो यह संपत्ति DataLabelCollection संग्रह में नए डेटा लेबल्स के लिए Position संपत्ति का डिफ़ॉल्ट मान प्राप्त करती है या सेट करती है। यह DataLabel ऑब्जेक्ट की स्थिति को दर्शाता है। इस संपत्ति को मान के साथ सेट करने से यह मान सभी डेटा लेबल्स में Position संपत्ति के लिए भी सेट हो जाता है (उदाहरण के लिए "DataLabels.getDefaultDataLabelFormat().setPosition(val);" सभी DataLabels.get_Item(i).getPosition() को val के बराबर बनाता है)।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getShowLegendKey() {#getShowLegendKey--}
```
public final boolean getShowLegendKey()
```

निर्दिष्ट चार्ट के डेटा लेबल लेजेंड कुंजी प्रदर्शन व्यवहार का प्रतिनिधित्व करता है। यदि डेटा लेबल लेजेंड कुंजी प्रदर्शित है तो True। पढ़ें/लिखें boolean।

--------------------

यदि इस DataLabelFormat वस्तु का पैरेंट डेटा लेबल्स का DataLabelCollection संग्रह है, तो यह संपत्ति DataLabelCollection संग्रह में नए डेटा लेबल्स के लिए ShowLegendKey संपत्ति का डिफ़ॉल्ट मान प्राप्त करती है या सेट करती है। इस संपत्ति को मान के साथ सेट करने से यह मान सभी डेटा लेबल्स में ShowLegendKey संपत्ति के लिए भी सेट हो जाता है (उदाहरण के लिए "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" सभी DataLabels.get_Item(i).getShowLegendKey() को val के बराबर बनाता है)।

**वापसी:**  
boolean

### setShowLegendKey(boolean value) {#setShowLegendKey-boolean-}
```
public final void setShowLegendKey(boolean value)
```

निर्दिष्ट चार्ट के डेटा लेबल लेजेंड कुंजी प्रदर्शन व्यवहार का प्रतिनिधित्व करता है। यदि डेटा लेबल लेजेंड कुंजी प्रदर्शित है तो True। पढ़ें/लिखें boolean।

--------------------

यदि इस DataLabelFormat वस्तु का पैरेंट डेटा लेबल्स का DataLabelCollection संग्रह है, तो यह संपत्ति DataLabelCollection संग्रह में नए डेटा लेबल्स के लिए ShowLegendKey संपत्ति का डिफ़ॉल्ट मान प्राप्त करती है या सेट करती है। इस संपत्ति को मान के साथ सेट करने से यह मान सभी डेटा लेबल्स में ShowLegendKey संपत्ति के लिए भी सेट हो जाता है (उदाहरण के लिए "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" सभी DataLabels.get_Item(i).getShowLegendKey() को val के बराबर बनाता है)।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getShowValue() {#getShowValue--}
```
public final boolean getShowValue()
```

निर्दिष्ट चार्ट के डेटा लेबल प्रतिशत मान प्रदर्शन व्यवहार का प्रतिनिधित्व करता है। True प्रतिशत मान दर्शाता है। False छिपाने के लिए। पढ़ें/लिखें boolean।

--------------------

यदि इस DataLabelFormat वस्तु का पैरेंट डेटा लेबल्स का DataLabelCollection संग्रह है, तो यह संपत्ति DataLabelCollection संग्रह में नए डेटा लेबल्स के लिए ShowValue संपत्ति का डिफ़ॉल्ट मान प्राप्त करती है या सेट करती है। इस संपत्ति को मान के साथ सेट करने से यह मान सभी डेटा लेबल्स में ShowValue संपत्ति के लिए भी सेट हो जाता है (उदाहरण के लिए "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" सभी DataLabels.get_Item(i).getShowValue() को val के बराबर बनाता है)।

**वापसी:**  
boolean

### setShowValue(boolean value) {#setShowValue-boolean-}
```
public final void setShowValue(boolean value)
```

निर्दिष्ट चार्ट के डेटा लेबल प्रतिशत मान प्रदर्शन व्यवहार का प्रतिनिधित्व करता है। True प्रतिशत मान दर्शाता है। False छिपाने के लिए। पढ़ें/लिखें boolean।

--------------------

यदि इस DataLabelFormat वस्तु का पैरेंट डेटा लेबल्स का DataLabelCollection संग्रह है, तो यह संपत्ति DataLabelCollection संग्रह में नए डेटा लेबल्स के लिए ShowValue संपत्ति का डिफ़ॉल्ट मान प्राप्त करती है या सेट करती है। इस संपत्ति को मान के साथ सेट करने से यह मान सभी डेटा लेबल्स में ShowValue संपत्ति के लिए भी सेट हो जाता है (उदाहरण के लिए "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" सभी DataLabels.get_Item(i).getShowValue() को val के बराबर बनाता है)।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getShowCategoryName() {#getShowCategoryName--}
```
public final boolean getShowCategoryName()
```

निर्दिष्ट चार्ट के डेटा लेबल वर्ग नाम प्रदर्शन व्यवहार का प्रतिनिधित्व करता है। True डेटा लेबल्स पर वर्ग नाम दिखाता है। False छिपाने के लिए। पढ़ें/लिखें boolean।

--------------------

यदि इस DataLabelFormat वस्तु का पैरेंट डेटा लेबल्स का DataLabelCollection संग्रह है, तो यह संपत्ति DataLabelCollection संग्रह में नए डेटा लेबल्स के लिए ShowCategoryName संपत्ति का डिफ़ॉल्ट मान प्राप्त करती है या सेट करती है। इस संपत्ति को मान के साथ सेट करने से यह मान सभी डेटा लेबल्स में ShowCategoryName संपत्ति के लिए भी सेट हो जाता है (उदाहरण के लिए "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" सभी DataLabels.get_Item(i).getShowCategoryName() को val के बराबर बनाता है)।

**वापसी:**  
boolean

### setShowCategoryName(boolean value) {#setShowCategoryName-boolean-}
```
public final void setShowCategoryName(boolean value)
```

निर्दिष्ट चार्ट के डेटा लेबल वर्ग नाम प्रदर्शन व्यवहार का प्रतिनिधित्व करता है। True डेटा लेबल्स पर वर्ग नाम दिखाता है। False छिपाने के लिए। पढ़ें/लिखें boolean।

--------------------

यदि इस DataLabelFormat वस्तु का पैरेंट डेटा लेबल्स का DataLabelCollection संग्रह है, तो यह संपत्ति DataLabelCollection संग्रह में नए डेटा लेबल्स के लिए ShowCategoryName संपत्ति का डिफ़ॉल्ट मान प्राप्त करती है या सेट करती है। इस संपत्ति को मान के साथ सेट करने से यह मान सभी डेटा लेबल्स में ShowCategoryName संपत्ति के लिए भी सेट हो जाता है (उदाहरण के लिए "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" सभी DataLabels.get_Item(i).getShowCategoryName() को val के बराबर बनाता है)।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getShowSeriesName() {#getShowSeriesName--}
```
public final boolean getShowSeriesName()
```

डेटा लेबल्स पर चार्ट में सीरीज़ नाम प्रदर्शन व्यवहार को इंगित करने के लिए Boolean को लौटाता है या सेट करता है। True सीरीज़ नाम दिखाने के लिए। False छिपाने के लिए। पढ़ें/लिखें boolean।

--------------------

यदि इस DataLabelFormat वस्तु का पैरेंट डेटा लेबल्स का DataLabelCollection संग्रह है, तो यह संपत्ति DataLabelCollection संग्रह में नए डेटा लेबल्स के लिए ShowSeriesName संपत्ति का डिफ़ॉल्ट मान प्राप्त करती है या सेट करती है। इस संपत्ति को मान के साथ सेट करने से यह मान सभी डेटा लेबल्स में ShowSeriesName संपत्ति के लिए भी सेट हो जाता है (उदाहरण के लिए "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" सभी DataLabels.get_Item(i).getShowSeriesName() को val के बराबर बनाता है)।

**वापसी:**  
boolean

### setShowSeriesName(boolean value) {#setShowSeriesName-boolean-}
```
public final void setShowSeriesName(boolean value)
```

डेटा लेबल्स पर चार्ट में सीरीज़ नाम प्रदर्शन व्यवहार को इंगित करने के लिए Boolean को लौटाता है या सेट करता है। True सीरीज़ नाम दिखाने के लिए। False छिपाने के लिए। पढ़ें/लिखें boolean।

--------------------

यदि इस DataLabelFormat वस्तु का पैरेंट डेटा लेबल्स का DataLabelCollection संग्रह है, तो यह संपत्ति DataLabelCollection संग्रह में नए डेटा लेबल्स के लिए ShowSeriesName संपत्ति का डिफ़ॉल्ट मान प्राप्त करती है या सेट करती है। इस संपत्ति को मान के साथ सेट करने से यह मान सभी डेटा लेबल्स में ShowSeriesName संपत्ति के लिए भी सेट हो जाता है (उदाहरण के लिए "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" सभी DataLabels.get_Item(i).getShowSeriesName() को val के बराबर बनाता है)।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getShowPercentage() {#getShowPercentage--}
```
public final boolean getShowPercentage()
```

निर्दिष्ट चार्ट के डेटा लेबल प्रतिशत मान प्रदर्शन व्यवहार का प्रतिनिधित्व करता है। True प्रतिशत मान दर्शाता है। False छिपाने के लिए। पढ़ें/लिखें boolean।

--------------------

यदि इस DataLabelFormat वस्तु का पैरेंट डेटा लेबल्स का DataLabelCollection संग्रह है, तो यह संपत्ति DataLabelCollection संग्रह में नए डेटा लेबल्स के लिए ShowPercentage संपत्ति का डिफ़ॉल्ट मान प्राप्त करती है या सेट करती है। इस संपत्ति को मान के साथ सेट करने से यह मान सभी डेटा लेबल्स में ShowPercentage संपत्ति के लिए भी सेट हो जाता है (उदाहरण के लिए "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" सभी DataLabels.get_Item(i).getShowPercentage() को val के बराबर बनाता है)।

**वापसी:**  
boolean

### setShowPercentage(boolean value) {#setShowPercentage-boolean-}
```
public final void setShowPercentage(boolean value)
```

निर्दिष्ट चार्ट के डेटा लेबल प्रतिशत मान प्रदर्शन व्यवहार का प्रतिनिधित्व करता है। True प्रतिशत मान दर्शाता है। False छिपाने के लिए। पढ़ें/लिखें boolean।

--------------------

यदि इस DataLabelFormat वस्तु का पैरेंट डेटा लेबल्स का DataLabelCollection संग्रह है, तो यह संपत्ति DataLabelCollection संग्रह में नए डेटा लेबल्स के लिए ShowPercentage संपत्ति का डिफ़ॉल्ट मान प्राप्त करती है या सेट करती है। इस संपत्ति को मान के साथ सेट करने से यह मान सभी डेटा लेबल्स में ShowPercentage संपत्ति के लिए भी सेट हो जाता है (उदाहरण के लिए "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" सभी DataLabels.get_Item(i).getShowPercentage() को val के बराबर बनाता है)।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getShowBubbleSize() {#getShowBubbleSize--}
```
public final boolean getShowBubbleSize()
```

निर्दिष्ट चार्ट के डेटा लेबल बबल आकार मान प्रदर्शन व्यवहार का प्रतिनिधित्व करता है। True बबल आकार मान दर्शाता है। False छिपाने के लिए। पढ़ें/लिखें boolean।

--------------------

यदि इस DataLabelFormat वस्तु का पैरेंट डेटा लेबल्स का DataLabelCollection संग्रह है, तो यह संपत्ति DataLabelCollection संग्रह में नए डेटा लेबल्स के लिए ShowBubbleSize संपत्ति का डिफ़ॉल्ट मान प्राप्त करती है या सेट करती है। इस संपत्ति को मान के साथ सेट करने से यह मान सभी डेटा लेबल्स में ShowBubbleSize संपत्ति के लिए भी सेट हो जाता है (उदाहरण के लिए "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" सभी DataLabels.get_Item(i).getShowBubbleSize() को val के बराबर बनाता है)।

**वापसी:**  
boolean

### setShowBubbleSize(boolean value) {#setShowBubbleSize-boolean-}
```
public final void setShowBubbleSize(boolean value)
```

निर्दिष्ट चार्ट के डेटा लेबल बबल आकार मान प्रदर्शन व्यवहार का प्रतिनिधित्व करता है। True बबल आकार मान दर्शाता है। False छिपाने के लिए। पढ़ें/लिखें boolean।

--------------------

यदि इस DataLabelFormat वस्तु का पैरेंट डेटा लेबल्स का DataLabelCollection संग्रह है, तो यह संपत्ति DataLabelCollection संग्रह में नए डेटा लेबल्स के लिए ShowBubbleSize संपत्ति का डिफ़ॉल्ट मान प्राप्त करती है या सेट करती है। इस संपत्ति को मान के साथ सेट करने से यह मान सभी डेटा लेबल्स में ShowBubbleSize संपत्ति के लिए भी सेट हो जाता है (उदाहरण के लिए "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" सभी DataLabels.get_Item(i).getShowBubbleSize() को val के बराबर बनाता है)।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getShowLeaderLines() {#getShowLeaderLines--}
```
public final boolean getShowLeaderLines()
```

निर्दिष्ट चार्ट के डेटा लेबल लीडर लाइन्स प्रदर्शन व्यवहार का प्रतिनिधित्व करता है। True लीडर लाइन्स दर्शाता है। False छिपाने के लिए। पढ़ें/लिखें boolean।

--------------------

यदि इस DataLabelFormat वस्तु का पैरेंट डेटा लेबल्स का DataLabelCollection संग्रह है, तो यह संपत्ति DataLabelCollection संग्रह में नए डेटा लेबल्स के लिए ShowLeaderLines संपत्ति का डिफ़ॉल्ट मान प्राप्त करती है या सेट करती है। इस संपत्ति को मान के साथ सेट करने से यह मान सभी डेटा लेबल्स में ShowLeaderLines संपत्ति के लिए भी सेट हो जाता है (उदाहरण के लिए "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" सभी DataLabels.get_Item(i).getShowLeaderLines() को val के बराबर बनाता है)।

**वापसी:**  
boolean

### setShowLeaderLines(boolean value) {#setShowLeaderLines-boolean-}
```
public final void setShowLeaderLines(boolean value)
```

निर्दिष्ट चार्ट के डेटा लेबल लीडर लाइन्स प्रदर्शन व्यवहार का प्रतिनिधित्व करता है। True लीडर लाइन्स दर्शाता है। False छिपाने के लिए। पढ़ें/लिखें boolean।

--------------------

यदि इस DataLabelFormat वस्तु का पैरेंट डेटा लेबल्स का DataLabelCollection संग्रह है, तो यह संपत्ति DataLabelCollection संग्रह में नए डेटा लेबल्स के लिए ShowLeaderLines संपत्ति का डिफ़ॉल्ट मान प्राप्त करती है या सेट करती है। इस संपत्ति को मान के साथ सेट करने से यह मान सभी डेटा लेबल्स में ShowLeaderLines संपत्ति के लिए भी सेट हो जाता है (उदाहरण के लिए "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" सभी DataLabels.get_Item(i).getShowLeaderLines() को val के बराबर बनाता है)।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelValueFromCell() {#getShowLabelValueFromCell--}
```
public final boolean getShowLabelValueFromCell()
```

निर्दिष्ट चार्ट के डेटा लेबल सेल मान प्रदर्शन व्यवहार का प्रतिनिधित्व करता है। True सेल मान दर्शाता है। False छिपाने के लिए। पढ़ें/लिखें boolean।

--------------------

यदि इस DataLabelFormat वस्तु का पैरेंट डेटा लेबल्स का DataLabelCollection संग्रह है, तो यह संपत्ति DataLabelCollection संग्रह में नए डेटा लेबल्स के लिए ShowLabelValueFromCell संपत्ति का डिफ़ॉल्ट मान प्राप्त करती है या सेट करती है। इस संपत्ति को मान के साथ सेट करने से यह मान सभी डेटा लेबल्स में ShowLabelValueFromCell संपत्ति के लिए भी सेट हो जाता है (उदाहरण के लिए "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" सभी DataLabels.get_Item(i).getShowLabelValueFromCell() को val के बराबर बनाता है)।

**वापसी:**  
boolean

### setShowLabelValueFromCell(boolean value) {#setShowLabelValueFromCell-boolean-}
```
public final void setShowLabelValueFromCell(boolean value)
```

निर्दिष्ट चार्ट के डेटा लेबल सेल मान प्रदर्शन व्यवहार का प्रतिनिधित्व करता है। True सेल मान दर्शाता है। False छिपाने के लिए। पढ़ें/लिखें boolean।

--------------------

यदि इस DataLabelFormat वस्तु का पैरेंट डेटा लेबल्स का DataLabelCollection संग्रह है, तो यह संपत्ति DataLabelCollection संग्रह में नए डेटा लेबल्स के लिए ShowLabelValueFromCell संपत्ति का डिफ़ॉल्ट मान प्राप्त करती है या सेट करती है। इस संपत्ति को मान के साथ सेट करने से यह मान सभी डेटा लेबल्स में ShowLabelValueFromCell संपत्ति के लिए भी सेट हो जाता है (उदाहरण के लिए "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" सभी DataLabels.get_Item(i).getShowLabelValueFromCell() को val के बराबर बनाता है)।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelAsDataCallout() {#getShowLabelAsDataCallout--}
```
public final boolean getShowLabelAsDataCallout()
```

निर्धारित करता है कि निर्दिष्ट चार्ट का डेटा लेबल डेटा कॉलआउट के रूप में या डेटा लेबल के रूप में प्रदर्शित होगा।

--------------------

यदि इस DataLabelFormat वस्तु का पैरेंट डेटा लेबल्स का DataLabelCollection संग्रह है, तो यह संपत्ति DataLabelCollection संग्रह में नए डेटा लेबल्स के लिए ShowLabelAsDataCallout संपत्ति का डिफ़ॉल्ट मान प्राप्त करती है या सेट करती है। इस संपत्ति को मान के साथ सेट करने से यह मान सभी डेटा लेबल्स में ShowLabelAsDataCallout संपत्ति के लिए भी सेट हो जाता है (उदाहरण के लिए "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" सभी DataLabels.get_Item(i).getShowLabelAsDataCallout() को val के बराबर बनाता है)।

**वापसी:**  
boolean

### setShowLabelAsDataCallout(boolean value) {#setShowLabelAsDataCallout-boolean-}
```
public final void setShowLabelAsDataCallout(boolean value)
```

निर्धारित करता है कि निर्दिष्ट चार्ट का डेटा लेबल डेटा कॉलआउट के रूप में या डेटा लेबल के रूप में प्रदर्शित होगा।

--------------------

यदि इस DataLabelFormat वस्तु का पैरेंट डेटा लेबल्स का DataLabelCollection संग्रह है, तो यह संपत्ति DataLabelCollection संग्रह में नए डेटा लेबल्स के लिए ShowLabelAsDataCallout संपत्ति का डिफ़ॉल्ट मान प्राप्त करती है या सेट करती है। इस संपत्ति को मान के साथ सेट करने से यह मान सभी डेटा लेबल्स में ShowLabelAsDataCallout संपत्ति के लिए भी सेट हो जाता है (उदाहरण के लिए "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" सभी DataLabels.get_Item(i).getShowLabelAsDataCallout() को val के बराबर बनाता है)।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getSeparator() {#getSeparator--}
```
public final String getSeparator()
```

डेटा लेबल पर चार्ट में प्रयुक्त विभाजक को दर्शाने वाले Variant को सेट करता है या लौटाता है। पढ़ें/लिखें String।

--------------------

यदि इस DataLabelFormat वस्तु का पैरेंट डेटा लेबल्स का DataLabelCollection संग्रह है, तो यह संपत्ति DataLabelCollection संग्रह में नए डेटा लेबल्स के लिए Separator संपत्ति का डिफ़ॉल्ट मान प्राप्त करती है या सेट करती है। इस संपत्ति को मान के साथ सेट करने से यह मान सभी डेटा लेबल्स में Separator संपत्ति के लिए भी सेट हो जाता है (उदाहरण के लिए "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" सभी DataLabels.get_Item(i).getSeparator() को val के बराबर बनाता है)।

**वापसी:**  
java.lang.String

### setSeparator(String value) {#setSeparator-java.lang.String-}
```
public final void setSeparator(String value)
```

डेटा लेबल पर चार्ट में प्रयुक्त विभाजक को दर्शाने वाले Variant को सेट करता है या लौटाता है। पढ़ें/लिखें String।

--------------------

यदि इस DataLabelFormat वस्तु का पैरेंट डेटा लेबल्स का DataLabelCollection संग्रह है, तो यह संपत्ति DataLabelCollection संग्रह में नए डेटा लेबल्स के लिए Separator संपत्ति का डिफ़ॉल्ट मान प्राप्त करती है या सेट करती है। इस संपत्ति को मान के साथ सेट करने से यह मान सभी डेटा लेबल्स में Separator संपत्ति के लिए भी सेट हो जाता है (उदाहरण के लिए "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" सभी DataLabels.get_Item(i).getSeparator() को val के बराबर बनाता है)।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

चार्ट टेक्स्ट फ़ॉर्मेट लौटाता है। केवल-पढ़ने योग्य [IChartTextFormat](../../com.aspose.slides/icharttextformat)।

**वापसी:**  
[IChartTextFormat](../../com.aspose.slides/icharttextformat)

### getChart() {#getChart--}
```
public final IChart getChart()
```

चार्ट लौटाता है। केवल-पढ़ने योग्य [IChart](../../com.aspose.slides/ichart)।

**वापसी:**  
[IChart](../../com.aspose.slides/ichart)