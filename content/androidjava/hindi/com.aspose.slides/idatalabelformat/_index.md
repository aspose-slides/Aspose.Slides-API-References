---
title: IDataLabelFormat
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: DataLabel के लिए फॉर्मेटिंग विकल्प प्रस्तुत करता है।
type: docs
url: /hi/com.aspose.slides/idatalabelformat/
---
**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer)
```
public interface IDataLabelFormat extends IFormattedTextContainer
```

DataLabel के लिए फॉर्मेटिंग विकल्प प्रस्तुत करता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | पढ़ें/लिखें boolean। |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | पढ़ें/लिखें boolean। |
| [getNumberFormat()](#getNumberFormat--) | DataLabels ऑब्जेक्ट के लिए फ़ॉर्मेट स्ट्रिंग प्रस्तुत करता है। |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | DataLabels ऑब्जेक्ट के लिए फ़ॉर्मेट स्ट्रिंग प्रस्तुत करता है। |
| [getFormat()](#getFormat--) | डेटा लेबल के फ़ॉर्मेट को प्रस्तुत करता है। |
| [getPosition()](#getPosition--) | डेटा लेबल की स्थिति प्रस्तुत करता है। |
| [setPosition(int value)](#setPosition-int-) | डेटा लेबल की स्थिति प्रस्तुत करता है। |
| [getShowLegendKey()](#getShowLegendKey--) | निर्दिष्ट चार्ट के डेटा लेबल लेजेंड कुंजी प्रदर्शन व्यवहार को प्रस्तुत करता है। |
| [setShowLegendKey(boolean value)](#setShowLegendKey-boolean-) | निर्दिष्ट चार्ट के डेटा लेबल लेजेंड कुंजी प्रदर्शन व्यवहार को प्रस्तुत करता है। |
| [getShowValue()](#getShowValue--) | निर्दिष्ट चार्ट के डेटा लेबल प्रतिशत मान प्रदर्शन व्यवहार को प्रस्तुत करता है। |
| [setShowValue(boolean value)](#setShowValue-boolean-) | निर्दिष्ट चार्ट के डेटा लेबल प्रतिशत मान प्रदर्शन व्यवहार को प्रस्तुत करता है। |
| [getShowCategoryName()](#getShowCategoryName--) | निर्दिष्ट चार्ट के डेटा लेबल श्रेणी नाम प्रदर्शन व्यवहार को प्रस्तुत करता है। |
| [setShowCategoryName(boolean value)](#setShowCategoryName-boolean-) | निर्दिष्ट चार्ट के डेटा लेबल श्रेणी नाम प्रदर्शन व्यवहार को प्रस्तुत करता है। |
| [getShowSeriesName()](#getShowSeriesName--) | एक Boolean लौटाता या सेट करता है जो चार्ट पर डेटा लेबल के लिए श्रृंखला नाम प्रदर्शन व्यवहार को दर्शाता है। |
| [setShowSeriesName(boolean value)](#setShowSeriesName-boolean-) | एक Boolean लौटाता या सेट करता है जो चार्ट पर डेटा लेबल के लिए श्रृंखला नाम प्रदर्शन व्यवहार को दर्शाता है। |
| [getShowPercentage()](#getShowPercentage--) | निर्दिष्ट चार्ट के डेटा लेबल प्रतिशत मान प्रदर्शन व्यवहार को प्रस्तुत करता है। |
| [setShowPercentage(boolean value)](#setShowPercentage-boolean-) | निर्दिष्ट चार्ट के डेटा लेबल प्रतिशत मान प्रदर्शन व्यवहार को प्रस्तुत करता है। |
| [getShowBubbleSize()](#getShowBubbleSize--) | निर्दिष्ट चार्ट के डेटा लेबल बबल आकार मान प्रदर्शन व्यवहार को प्रस्तुत करता है। |
| [setShowBubbleSize(boolean value)](#setShowBubbleSize-boolean-) | निर्दिष्ट चार्ट के डेटा लेबल बबल आकार मान प्रदर्शन व्यवहार को प्रस्तुत करता है। |
| [getShowLeaderLines()](#getShowLeaderLines--) | निर्दिष्ट चार्ट के डेटा लेबल लीडर लाइन्स प्रदर्शन व्यवहार को प्रस्तुत करता है। |
| [setShowLeaderLines(boolean value)](#setShowLeaderLines-boolean-) | निर्दिष्ट चार्ट के डेटा लेबल लीडर लाइन्स प्रदर्शन व्यवहार को प्रस्तुत करता है। |
| [getShowLabelAsDataCallout()](#getShowLabelAsDataCallout--) | निर्धारित करता है कि निर्दिष्ट चार्ट का डेटा लेबल डेटा कॉलआउट के रूप में या डेटा लेबल के रूप में प्रदर्शित होगा। |
| [setShowLabelAsDataCallout(boolean value)](#setShowLabelAsDataCallout-boolean-) | निर्धारित करता है कि निर्दिष्ट चार्ट का डेटा लेबल डेटा कॉलआउट के रूप में या डेटा लेबल के रूप में प्रदर्शित होगा। |
| [getShowLabelValueFromCell()](#getShowLabelValueFromCell--) | निर्दिष्ट चार्ट के डेटा लेबल सेल मान प्रदर्शन व्यवहार को प्रस्तुत करता है। |
| [setShowLabelValueFromCell(boolean value)](#setShowLabelValueFromCell-boolean-) | निर्दिष्ट चार्ट के डेटा लेबल सेल मान प्रदर्शन व्यवहार को प्रस्तुत करता है। |
| [getSeparator()](#getSeparator--) | सेट करता या लौटाता है एक Variant जो चार्ट पर डेटा लेबल्स के लिए विभाजक दर्शाता है। |
| [setSeparator(String value)](#setSeparator-java.lang.String-) | सेट करता या लौटाता है एक Variant जो चार्ट पर डेटा लेबल्स के लिए विभाजक दर्शाता है। |

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public abstract boolean isNumberFormatLinkedToSource()
```

पढ़ें/लिखें boolean.

--------------------

यदि इस DataLabelFormat ऑब्जेक्ट का पैरेंट DataLabelCollection डेटा लेबल्स का संग्रह है तो यह प्रॉपर्टी DataLabelCollection संग्रह में नए डेटा लेबल्स के लिए IsNumberFormatLinkedToSource प्रॉपर्टी का डिफॉल्ट मान प्राप्त या सेट करती है। इस प्रॉपर्टी को मान के साथ सेट करने से यह मान सभी DataLabelCollection संग्रह में डेटा लेबल्स के लिए IsNumberFormatLinkedToSource प्रॉपर्टी में भी सेट हो जाता है (उदाहरण के लिए "DataLabels.getDefaultDataLabelFormat().setNumberFormatLinkedToSource(val);" जिससे सभी DataLabels.get_Item(i).isNumberFormatLinkedToSource() मान बराबर हो जाता है)।

**वापसी:**
boolean

### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public abstract void setNumberFormatLinkedToSource(boolean value)
```

पढ़ें/लिखें boolean.

--------------------

यदि इस DataLabelFormat ऑब्जेक्ट का पैरेंट DataLabelCollection डेटा लेबल्स का संग्रह है तो यह प्रॉपर्टी DataLabelCollection संग्रह में नए डेटा लेबल्स के लिए IsNumberFormatLinkedToSource प्रॉपर्टी का डिफॉल्ट मान प्राप्त या सेट करती है। इस प्रॉपर्टी को मान के साथ सेट करने से यह मान सभी DataLabelCollection संग्रह में डेटा लेबल्स के लिए IsNumberFormatLinkedToSource प्रॉपर्टी में भी सेट हो जाता है (उदाहरण के लिए "DataLabels.getDefaultDataLabelFormat().setNumberFormatLinkedToSource(val);" जिससे सभी DataLabels.get_Item(i).isNumberFormatLinkedToSource() मान बराबर हो जाता है)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public abstract String getNumberFormat()
```

DataLabels ऑब्जेक्ट के लिए फ़ॉर्मेट स्ट्रिंग प्रस्तुत करता है। पढ़ें/लिखें String।

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```


--------------------

यदि इस DataLabelFormat ऑब्जेक्ट का पैरेंट DataLabelCollection डेटा लेबल्स का संग्रह है तो यह प्रॉपर्टी DataLabelCollection संग्रह में नए डेटा लेबल्स के लिए NumberFormat प्रॉपर्टी का डिफॉल्ट मान प्राप्त या सेट करती है। जब इस प्रॉपर्टी को मान से सेट किया जाता है, तो वह मान सभी DataLabelCollection संग्रह में डेटा लेबल्स के लिए NumberFormat प्रॉपर्टी में भी सेट हो जाता है (उदाहरण के लिए "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" जिससे सभी DataLabels.get_Item(i).getNumberFormat() बराबर हो जाता है)।

**वापसी:**
java.lang.String

### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public abstract void setNumberFormat(String value)
```

DataLabels ऑब्जेक्ट के लिए फ़ॉर्मेट स्ट्रिंग प्रस्तुत करता है। पढ़ें/लिखें String।

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```


--------------------

यदि इस DataLabelFormat ऑब्जेक्ट का पैरेंट DataLabelCollection डेटा लेबल्स का संग्रह है तो यह प्रॉपर्टी DataLabelCollection संग्रह में नए डेटा लेबल्स के लिए NumberFormat प्रॉपर्टी का डिफॉल्ट मान प्राप्त या सेट करती है। जब इस प्रॉपर्टी को मान से सेट किया जाता है, तो वह मान सभी DataLabelCollection संग्रह में डेटा लेबल्स के लिए NumberFormat प्रॉपर्टी में भी सेट हो जाता है (उदाहरण के लिए "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" जिससे सभी DataLabels.get_Item(i).getNumberFormat() बराबर हो जाता है)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

डेटा लेबल के फ़ॉर्मेट को प्रस्तुत करता है। केवल पढ़ने योग्य [IFormat](../../com.aspose.slides/iformat)।

--------------------

यदि इस DataLabelFormat ऑब्जेक्ट का पैरेंट DataLabelCollection डेटा लेबल्स का संग्रह है तो यह प्रॉपर्टी नए डेटा लेबल्स के लिए डिफॉल्ट फ़ॉर्मेट का प्रतिनिधित्व करती है।

**वापसी:**
[IFormat](../../com.aspose.slides/iformat)

### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

डेटा लेबल की स्थिति को प्रस्तुत करता है। पढ़ें/लिखें [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition)।

--------------------

यदि इस DataLabelFormat ऑब्जेक्ट का पैरेंट DataLabelCollection डेटा लेबल्स का संग्रह है तो यह प्रॉपर्टी DataLabelCollection संग्रह में नए डेटा लेबल्स के लिए Position प्रॉपर्टी का डिफॉल्ट मान प्राप्त या सेट करती है। यह DataLabel ऑब्जेक्ट की स्थिति को दर्शाता है। इस प्रॉपर्टी को मान के साथ सेट करने से यह मान सभी DataLabelCollection संग्रह में डेटा लेबल्स के लिए Position प्रॉपर्टी में भी सेट हो जाता है (उदाहरण के लिए "DataLabels.getDefaultDataLabelFormat().setPosition(val)" जिससे सभी DataLabels.get_Item(i).getPosition() बराबर हो जाता है)।

**वापसी:**
int

### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

डेटा लेबल की स्थिति को प्रस्तुत करता है। पढ़ें/लिखें [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition)।

--------------------

यदि इस DataLabelFormat ऑब्जेक्ट का पैरेंट DataLabelCollection डेटा लेबल्स का संग्रह है तो यह प्रॉपर्टी DataLabelCollection संग्रह में नए डेटा लेबल्स के लिए Position प्रॉपर्टी का डिफॉल्ट मान प्राप्त या सेट करती है। यह DataLabel ऑब्जेक्ट की स्थिति को दर्शाता है। इस प्रॉपर्टी को मान के साथ सेट करने से यह मान सभी DataLabelCollection संग्रह में डेटा लेबल्स के लिए Position प्रॉपर्टी में भी सेट हो जाता है (उदाहरण के लिए "DataLabels.getDefaultDataLabelFormat().setPosition(val)" जिससे सभी DataLabels.get_Item(i).getPosition() बराबर हो जाता है)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getShowLegendKey() {#getShowLegendKey--}
```
public abstract boolean getShowLegendKey()
```

निर्दिष्ट चार्ट के डेटा लेबल लेजेंड कुंजी प्रदर्शन व्यवहार को प्रस्तुत करता है। यदि डेटा लेबल लेजेंड कुंजी दृश्यमान है तो true। पढ़ें/लिखें boolean।

--------------------

यदि इस DataLabelFormat ऑब्जेक्ट का पैरेंट DataLabelCollection डेटा लेबल्स का संग्रह है तो यह प्रॉपर्टी DataLabelCollection संग्रह में नए डेटा लेबल्स के लिए ShowLegendKey प्रॉपर्टी का डिफॉल्ट मान प्राप्त या सेट करती है। इस प्रॉपर्टी को मान के साथ सेट करने से यह मान सभी DataLabelCollection संग्रह में डेटा लेबल्स के लिए ShowLegendKey प्रॉपर्टी में भी सेट हो जाता है (उदाहरण के लिए "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" जिससे सभी DataLabels.get_Item(i).getShowLegendKey() बराबर हो जाता है)।

**वापसी:**
boolean

### setShowLegendKey(boolean value) {#setShowLegendKey-boolean-}
```
public abstract void setShowLegendKey(boolean value)
```

निर्दिष्ट चार्ट के डेटा लेबल लेजेंड कुंजी प्रदर्शन व्यवहार को प्रस्तुत करता है। यदि डेटा लेबल लेजेंड कुंजी दृश्यमान है तो true। पढ़ें/लिखें boolean।

--------------------

यदि इस DataLabelFormat ऑब्जेक्ट का पैरेंट DataLabelCollection डेटा लेबल्स का संग्रह है तो यह प्रॉपर्टी DataLabelCollection संग्रह में नए डेटा लेबल्स के लिए ShowLegendKey प्रॉपर्टी का डिफॉल्ट मान प्राप्त या सेट करती है। इस प्रॉपर्टी को मान के साथ सेट करने से यह मान सभी DataLabelCollection संग्रह में डेटा लेबल्स के लिए ShowLegendKey प्रॉपर्टी में भी सेट हो जाता है (उदाहरण के लिए "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" जिससे सभी DataLabels.get_Item(i).getShowLegendKey() बराबर हो जाता है)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getShowValue() {#getShowValue--}
```
public abstract boolean getShowValue()
```

निर्दिष्ट चार्ट के डेटा लेबल प्रतिशत मान प्रदर्शन व्यवहार को प्रस्तुत करता है। true प्रतिशत मान प्रदर्शित करता है। छिपाने के लिए false। पढ़ें/लिखें boolean।

--------------------

यदि इस DataLabelFormat ऑब्जेक्ट का पैरेंट DataLabelCollection डेटा लेबल्स का संग्रह है तो यह प्रॉपर्टी DataLabelCollection संग्रह में नए डेटा लेबल्स के लिए ShowValue प्रॉपर्टी का डिफॉल्ट मान प्राप्त या सेट करती है। इस प्रॉपर्टी को मान के साथ सेट करने से यह मान सभी DataLabelCollection संग्रह में डेटा लेबल्स के लिए ShowValue प्रॉपर्टी में भी सेट हो जाता है (उदाहरण के लिए "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" जिससे सभी DataLabels.get_Item(i).getShowValue() बराबर हो जाता है)।

**वापसी:**
boolean

### setShowValue(boolean value) {#setShowValue-boolean-}
```
public abstract void setShowValue(boolean value)
```

निर्दिष्ट चार्ट के डेटा लेबल प्रतिशत मान प्रदर्शन व्यवहार को प्रस्तुत करता है। true प्रतिशत मान प्रदर्शित करता है। छिपाने के लिए false। पढ़ें/लिखें boolean।

--------------------

यदि इस DataLabelFormat ऑब्जेक्ट का पैरेंट DataLabelCollection डेटा लेबल्स का संग्रह है तो यह प्रॉपर्टी DataLabelCollection संग्रह में नए डेटा लेबल्स के लिए ShowValue प्रॉपर्टी का डिफॉल्ट मान प्राप्त या सेट करती है। इस प्रॉपर्टी को मान के साथ सेट करने से यह मान सभी DataLabelCollection संग्रह में डेटा लेबल्स के लिए ShowValue प्रॉपर्टी में भी सेट हो जाता है (उदाहरण के लिए "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" जिससे सभी DataLabels.get_Item(i).getShowValue() बराबर हो जाता है)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getShowCategoryName() {#getShowCategoryName--}
```
public abstract boolean getShowCategoryName()
```

निर्दिष्ट चार्ट के डेटा लेबल श्रेणी नाम प्रदर्शन व्यवहार को प्रस्तुत करता है। चार्ट पर डेटा लेबल्स के लिए श्रेणी नाम प्रदर्शित करने हेतु true। छिपाने के लिए false। पढ़ें/लिखें boolean।

--------------------

यदि इस DataLabelFormat ऑब्जेक्ट का पैरेंट DataLabelCollection डेटा लेबल्स का संग्रह है तो यह प्रॉपर्टी DataLabelCollection संग्रह में नए डेटा लेबल्स के लिए ShowCategoryName प्रॉपर्टी का डिफॉल्ट मान प्राप्त या सेट करती है। इस प्रॉपर्टी को मान के साथ सेट करने से यह मान सभी DataLabelCollection संग्रह में डेटा लेबल्स के लिए ShowCategoryName प्रॉपर्टी में भी सेट हो जाता है (उदाहरण के लिए "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" जिससे सभी DataLabels.get_Item(i).getShowCategoryName() बराबर हो जाता है)।

**वापसी:**
boolean

### setShowCategoryName(boolean value) {#setShowCategoryName-boolean-}
```
public abstract void setShowCategoryName(boolean value)
```

निर्दिष्ट चार्ट के डेटा लेबल श्रेणी नाम प्रदर्शन व्यवहार को प्रस्तुत करता है। चार्ट पर डेटा लेबल्स के लिए श्रेणी नाम प्रदर्शित करने हेतु true। छिपाने के लिए false। पढ़ें/लिखें boolean।

--------------------

यदि इस DataLabelFormat ऑब्जेक्ट का पैरेंट DataLabelCollection डेटा लेबल्स का संग्रह है तो यह प्रॉपर्टी DataLabelCollection संग्रह में नए डेटा लेबल्स के लिए ShowCategoryName प्रॉपर्टी का डिफॉल्ट मान प्राप्त या सेट करती है। इस प्रॉपर्टी को मान के साथ सेट करने से यह मान सभी DataLabelCollection संग्रह में डेटा लेबल्स के लिए ShowCategoryName प्रॉपर्टी में भी सेट हो जाता है (उदाहरण के लिए "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" जिससे सभी DataLabels.get_Item(i).getShowCategoryName() बराबर हो जाता है)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getShowSeriesName() {#getShowSeriesName--}
```
public abstract boolean getShowSeriesName()
```

एक Boolean लौटाता या सेट करता है जो चार्ट पर डेटा लेबल्स के लिए श्रृंखला नाम प्रदर्शन व्यवहार को दर्शाता है। श्रृंखला नाम दिखाने हेतु true। छिपाने के लिए false। पढ़ें/लिखें boolean।

--------------------

यदि इस DataLabelFormat ऑब्जेक्ट का पैरेंट DataLabelCollection डेटा लेबल्स का संग्रह है तो यह प्रॉपर्टी DataLabelCollection संग्रह में नए डेटा लेबल्स के लिए ShowSeriesName प्रॉपर्टी का डिफॉल्ट मान प्राप्त या सेट करती है। इस प्रॉपर्टी को मान के साथ सेट करने से यह मान सभी DataLabelCollection संग्रह में डेटा लेबल्स के लिए ShowSeriesName प्रॉपर्टी में भी सेट हो जाता है (उदाहरण के लिए "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" जिससे सभी DataLabels.get_Item(i).getShowSeriesName() बराबर हो जाता है)।

**वापसी:**
boolean

### setShowSeriesName(boolean value) {#setShowSeriesName-boolean-}
```
public abstract void setShowSeriesName(boolean value)
```

एक Boolean लौटाता या सेट करता है जो चार्ट पर डेटा लेबल्स के लिए श्रृंखला नाम प्रदर्शन व्यवहार को दर्शाता है। श्रृंखला नाम दिखाने हेतु true। छिपाने के लिए false। पढ़ें/लिखें boolean।

--------------------

यदि इस DataLabelFormat ऑब्जेक्ट का पैरेंट DataLabelCollection डेटा लेबल्स का संग्रह है तो यह प्रॉपर्टी DataLabelCollection संग्रह में नए डेटा लेबल्स के लिए ShowSeriesName प्रॉपर्टी का डिफॉल्ट मान प्राप्त या सेट करती है। इस प्रॉपर्टी को मान के साथ सेट करने से यह मान सभी DataLabelCollection संग्रह में डेटा लेबल्स के लिए ShowSeriesName प्रॉपर्टी में भी सेट हो जाता है (उदाहरण के लिए "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" जिससे सभी DataLabels.get_Item(i).getShowSeriesName() बराबर हो जाता है)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getShowPercentage() {#getShowPercentage--}
```
public abstract boolean getShowPercentage()
```

निर्दिष्ट चार्ट के डेटा लेबल प्रतिशत मान प्रदर्शन व्यवहार को प्रस्तुत करता है। true प्रतिशत मान प्रदर्शित करता है। छिपाने के लिए false। पढ़ें/लिखें boolean।

--------------------

यदि इस DataLabelFormat ऑब्जेक्ट का पैरेंट DataLabelCollection डेटा लेबल्स का संग्रह है तो यह प्रॉपर्टी DataLabelCollection संग्रह में नए डेटा लेबल्स के लिए ShowPercentage प्रॉपर्टी का डिफॉल्ट मान प्राप्त या सेट करती है। इस प्रॉपर्टी को मान के साथ सेट करने से यह मान सभी DataLabelCollection संग्रह में डेटा लेबल्स के लिए ShowPercentage प्रॉपर्टी में भी सेट हो जाता है (उदाहरण के लिए "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" जिससे सभी DataLabels.get_Item(i).getShowPercentage() बराबर हो जाता है)।

**वापसी:**
boolean

### setShowPercentage(boolean value) {#setShowPercentage-boolean-}
```
public abstract void setShowPercentage(boolean value)
```

निर्दिष्ट चार्ट के डेटा लेबल प्रतिशत मान प्रदर्शन व्यवहार को प्रस्तुत करता है। true प्रतिशत मान प्रदर्शित करता है। छिपाने के लिए false। पढ़ें/लिखें boolean।

--------------------

यदि इस DataLabelFormat ऑब्जेक्ट का पैरेंट DataLabelCollection डेटा लेबल्स का संग्रह है तो यह प्रॉपर्टी DataLabelCollection संग्रह में नए डेटा लेबल्स के लिए ShowPercentage प्रॉपर्टी का डिफॉल्ट मान प्राप्त या सेट करती है। इस प्रॉपर्टी को मान के साथ सेट करने से यह मान सभी DataLabelCollection संग्रह में डेटा लेबल्स के लिए ShowPercentage प्रॉपर्टी में भी सेट हो जाता है (उदाहरण के लिए "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" जिससे सभी DataLabels.get_Item(i).getShowPercentage() बराबर हो जाता है)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getShowBubbleSize() {#getShowBubbleSize--}
```
public abstract boolean getShowBubbleSize()
```

निर्दिष्ट चार्ट के डेटा लेबल बबल आकार मान प्रदर्शन व्यवहार को प्रस्तुत करता है। true बबल आकार मान प्रदर्शित करता है। छिपाने के लिए false। पढ़ें/लिखें boolean।

--------------------

यदि इस DataLabelFormat ऑब्जेक्ट का पैरेंट DataLabelCollection डेटा लेबल्स का संग्रह है तो यह प्रॉपर्टी DataLabelCollection संग्रह में नए डेटा लेबल्स के लिए ShowBubbleSize प्रॉपर्टी का डिफॉल्ट मान प्राप्त या सेट करती है। इस प्रॉपर्टी को मान के साथ सेट करने से यह मान सभी DataLabelCollection संग्रह में डेटा लेबल्स के लिए ShowBubbleSize प्रॉपर्टी में भी सेट हो जाता है (उदाहरण के लिए "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" जिससे सभी DataLabels.get_Item(i).getShowBubbleSize() बराबर हो जाता है)।

**वापसी:**
boolean

### setShowBubbleSize(boolean value) {#setShowBubbleSize-boolean-}
```
public abstract void setShowBubbleSize(boolean value)
```

निर्दिष्ट चार्ट के डेटा लेबल बबल आकार मान प्रदर्शन व्यवहार को प्रस्तुत करता है। true बबल आकार मान प्रदर्शित करता है। छिपाने के लिए false। पढ़ें/लिखें boolean।

--------------------

यदि इस DataLabelFormat ऑब्जेक्ट का पैरेंट DataLabelCollection डेटा लेबल्स का संग्रह है तो यह प्रॉपर्टी DataLabelCollection संग्रह में नए डेटा लेबल्स के लिए ShowBubbleSize प्रॉपर्टी का डिफॉल्ट मान प्राप्त या सेट करती है। इस प्रॉपर्टी को मान के साथ सेट करने से यह मान सभी DataLabelCollection संग्रह में डेटा लेबल्स के लिए ShowBubbleSize प्रॉपर्टी में भी सेट हो जाता है (उदाहरण के लिए "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" जिससे सभी DataLabels.get_Item(i).getShowBubbleSize() बराबर हो जाता है)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getShowLeaderLines() {#getShowLeaderLines--}
```
public abstract boolean getShowLeaderLines()
```

निर्दिष्ट चार्ट के डेटा लेबल लीडर लाइन्स प्रदर्शन व्यवहार को प्रस्तुत करता है। true लीडर लाइन्स प्रदर्शित करता है। छिपाने के लिए false। पढ़ें/लिखें boolean।

--------------------

यदि इस DataLabelFormat ऑब्जेक्ट का पैरेंट DataLabelCollection डेटा लेबल्स का संग्रह है तो यह प्रॉपर्टी DataLabelCollection संग्रह में नए डेटा लेबल्स के लिए ShowLeaderLines प्रॉपर्टी का डिफॉल्ट मान प्राप्त या सेट करती है। इस प्रॉपर्टी को मान के साथ सेट करने से यह मान सभी DataLabelCollection संग्रह में डेटा लेबल्स के लिए ShowLeaderLines प्रॉपर्टी में भी सेट हो जाता है (उदाहरण के लिए "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" जिससे सभी DataLabels.get_Item(i).getShowLeaderLines() बराबर हो जाता है)।

**वापसी:**
boolean

### setShowLeaderLines(boolean value) {#setShowLeaderLines-boolean-}
```
public abstract void setShowLeaderLines(boolean value)
```

निर्दिष्ट चार्ट के डेटा लेबल लीडर लाइन्स प्रदर्शन व्यवहार को प्रस्तुत करता है। true लीडर लाइन्स प्रदर्शित करता है। छिपाने के लिए false। पढ़ें/लिखें boolean।

--------------------

यदि इस DataLabelFormat ऑब्जेक्ट का पैरेंट DataLabelCollection डेटा लेबल्स का संग्रह है तो यह प्रॉपर्टी DataLabelCollection संग्रह में नए डेटा लेबल्स के लिए ShowLeaderLines प्रॉपर्टी का डिफॉल्ट मान प्राप्त या सेट करती है। इस प्रॉपर्टी को मान के साथ सेट करने से यह मान सभी DataLabelCollection संग्रह में डेटा लेबल्स के लिए ShowLeaderLines प्रॉपर्टी में भी सेट हो जाता है (उदाहरण के लिए "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" जिससे सभी DataLabels.get_Item(i).getShowLeaderLines() बराबर हो जाता है)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelAsDataCallout() {#getShowLabelAsDataCallout--}
```
public abstract boolean getShowLabelAsDataCallout()
```

निर्धारित करता है कि निर्दिष्ट चार्ट का डेटा लेबल डेटा कॉलआउट के रूप में या डेटा लेबल के रूप में प्रदर्शित होगा।

--------------------

यदि इस DataLabelFormat ऑब्जेक्ट का पैरेंट DataLabelCollection डेटा लेबल्स का संग्रह है तो यह प्रॉपर्टी DataLabelCollection संग्रह में नए डेटा लेबल्स के लिए ShowLabelAsDataCallout प्रॉपर्टी का डिफॉल्ट मान प्राप्त या सेट करती है। इस प्रॉपर्टी को मान के साथ सेट करने से यह मान सभी DataLabelCollection संग्रह में डेटा लेबल्स के लिए ShowLabelAsDataCallout प्रॉपर्टी में भी सेट हो जाता है (उदाहरण के लिए "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" जिससे सभी DataLabels.get_Item(i).getShowLabelAsDataCallout() बराबर हो जाता है)।

**वापसी:**
boolean

### setShowLabelAsDataCallout(boolean value) {#setShowLabelAsDataCallout-boolean-}
```
public abstract void setShowLabelAsDataCallout(boolean value)
```

निर्धारित करता है कि निर्दिष्ट चार्ट का डेटा लेबल डेटा कॉलआउट के रूप में या डेटा लेबल के रूप में प्रदर्शित होगा।

--------------------

यदि इस DataLabelFormat ऑब्जेक्ट का पैरेंट DataLabelCollection डेटा लेबल्स का संग्रह है तो यह प्रॉपर्टी DataLabelCollection संग्रह में नए डेटा लेबल्स के लिए ShowLabelAsDataCallout प्रॉपर्टी का डिफॉल्ट मान प्राप्त या सेट करती है। इस प्रॉपर्टी को मान के साथ सेट करने से यह मान सभी DataLabelCollection संग्रह में डेटा लेबल्स के लिए ShowLabelAsDataCallout प्रॉपर्टी में भी सेट हो जाता है (उदाहरण के रूप में "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" जिससे सभी DataLabels.get_Item(i).getShowLabelAsDataCallout() बराबर हो जाता है)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelValueFromCell() {#getShowLabelValueFromCell--}
```
public abstract boolean getShowLabelValueFromCell()
```

निर्दिष्ट चार्ट के डेटा लेबल सेल मान प्रदर्शन व्यवहार को प्रस्तुत करता है। true सेल मान प्रदर्शित करता है। छिपाने के लिए false। पढ़ें/लिखें boolean।

--------------------

यदि इस DataLabelFormat ऑब्जेक्ट का पैरेंट DataLabelCollection डेटा लेबल्स का संग्रह है तो यह प्रॉपर्टी DataLabelCollection संग्रह में नए डेटा लेबल्स के लिए ShowLabelValueFromCell प्रॉपर्टी का डिफॉल्ट मान प्राप्त या सेट करती है। इस प्रॉपर्टी को मान के साथ सेट करने से यह मान सभी DataLabelCollection संग्रह में डेटा लेबल्स के लिए ShowLabelValueFromCell प्रॉपर्टी में भी सेट हो जाता है (उदाहरण के लिए "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" जिससे सभी DataLabels.get_Item(i).getShowLabelValueFromCell() बराबर हो जाता है)।

**वापसी:**
boolean

### setShowLabelValueFromCell(boolean value) {#setShowLabelValueFromCell-boolean-}
```
public abstract void setShowLabelValueFromCell(boolean value)
```

निर्दिष्ट चार्ट के डेटा लेबल सेल मान प्रदर्शन व्यवहार को प्रस्तुत करता है। true सेल मान प्रदर्शित करता है। छिपाने के लिए false। पढ़ें/लिखें boolean।

--------------------

यदि इस DataLabelFormat ऑब्जेक्ट का पैरेंट DataLabelCollection डेटा लेबल्स का संग्रह है तो यह प्रॉपर्टी DataLabelCollection संग्रह में नए डेटा लेबल्स के लिए ShowLabelValueFromCell प्रॉपर्टी का डिफॉल्ट मान प्राप्त या सेट करती है। इस प्रॉपर्टी को मान के साथ सेट करने से यह मान सभी DataLabelCollection संग्रह में डेटा लेबल्स के लिए ShowLabelValueFromCell प्रॉपर्टी में भी सेट हो जाता है (उदाहरण के लिए "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" जिससे सभी DataLabels.get_Item(i).getShowLabelValueFromCell() बराबर हो जाता है)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getSeparator() {#getSeparator--}
```
public abstract String getSeparator()
```

सेट करता या लौटाता है एक Variant जो चार्ट पर डेटा लेबल्स के लिए प्रयुक्त विभाजक को दर्शाता है। पढ़ें/लिखें String।

--------------------

यदि इस DataLabelFormat ऑब्जेक्ट का पैरेंट DataLabelCollection डेटा लेबल्स का संग्रह है तो यह प्रॉपर्टी DataLabelCollection संग्रह में नए डेटा लेबल्स के लिए Separator प्रॉपर्टी का डिफॉल्ट मान प्राप्त या सेट करती है। इस प्रॉपर्टी को मान के साथ सेट करने से यह मान सभी DataLabelCollection संग्रह में डेटा लेबल्स के लिए Separator प्रॉपर्टी में भी सेट हो जाता है (उदाहरण के लिए "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" जिससे सभी DataLabels.get_Item(i).getSeparator() बराबर हो जाता है)।

**वापसी:**
java.lang.String

### setSeparator(String value) {#setSeparator-java.lang.String-}
```
public abstract void setSeparator(String value)
```

सेट करता या लौटाता है एक Variant जो चार्ट पर डेटा लेबल्स के लिए प्रयुक्त विभाजक को दर्शाता है। पढ़ें/लिखें String।

--------------------

यदि इस DataLabelFormat ऑब्जेक्ट का पैरेंट DataLabelCollection डेटा लेबल्स का संग्रह है तो यह प्रॉपर्टी DataLabelCollection संग्रह में नए डेटा लेबल्स के लिए Separator प्रॉपर्टी का डिफॉल्ट मान प्राप्त या सेट करती है। इस प्रॉपर्टी को मान के साथ सेट करने से यह मान सभी DataLabelCollection संग्रह में डेटा लेबल्स के लिए Separator प्रॉपर्टी में भी सेट हो जाता है (उदाहरण के रूप में "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" जिससे सभी DataLabels.get_Item(i).getSeparator() बराबर हो जाता है)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |