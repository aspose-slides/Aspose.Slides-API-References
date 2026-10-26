---
title: IDataLabelFormat
second_title: Java के लिए Aspose.Slides API संदर्भ
description: DataLabel के लिए फ़ॉर्मेटिंग विकल्पों का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/idatalabelformat/
---
**सभी लागू इंटरफ़ेसेस:**
[com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer)
```
public interface IDataLabelFormat extends IFormattedTextContainer
```

DataLabel के लिए फ़ॉर्मेटिंग विकल्प दर्शाता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | पढ़ें/लिखें बूलियन। |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | पढ़ें/लिखें बूलियन। |
| [getNumberFormat()](#getNumberFormat--) | DataLabels वस्तु के लिए फ़ॉर्मेट स्ट्रिंग दर्शाता है। |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | DataLabels वस्तु के लिए फ़ॉर्मेट स्ट्रिंग दर्शाता है। |
| [getFormat()](#getFormat--) | डेटा लेबल का फ़ॉर्मेट दर्शाता है। |
| [getPosition()](#getPosition--) | डेटा लेबल की स्थिति दर्शाता है। |
| [setPosition(int value)](#setPosition-int-) | डेटा लेबल की स्थिति दर्शाता है। |
| [getShowLegendKey()](#getShowLegendKey--) | निर्दिष्ट चार्ट के डेटा लेबल लेजेंड कुंजी प्रदर्शन व्यवहार को दर्शाता है। |
| [setShowLegendKey(boolean value)](#setShowLegendKey-boolean-) | निर्दिष्ट चार्ट के डेटा लेबल लेजेंड कुंजी प्रदर्शन व्यवहार को दर्शाता है। |
| [getShowValue()](#getShowValue--) | निर्दिष्ट चार्ट के डेटा लेबल प्रतिशत मान प्रदर्शन व्यवहार को दर्शाता है। |
| [setShowValue(boolean value)](#setShowValue-boolean-) | निर्दिष्ट चार्ट के डेटा लेबल प्रतिशत मान प्रदर्शन व्यवहार को दर्शाता है। |
| [getShowCategoryName()](#getShowCategoryName--) | निर्दिष्ट चार्ट के डेटा लेबल श्रेणी नाम प्रदर्शन व्यवहार को दर्शाता है। |
| [setShowCategoryName(boolean value)](#setShowCategoryName-boolean-) | निर्दिष्ट चार्ट के डेटा लेबल श्रेणी नाम प्रदर्शन व्यवहार को दर्शाता है। |
| [getShowSeriesName()](#getShowSeriesName--) | एक बूलियन लौटाता या सेट करता है जो चार्ट पर डेटा लेबल के लिए श्रृंखला नाम प्रदर्शन व्यवहार को दर्शाता है। |
| [setShowSeriesName(boolean value)](#setShowSeriesName-boolean-) | एक बूलियन लौटाता या सेट करता है जो चार्ट पर डेटा लेबल के लिए श्रृंखला नाम प्रदर्शन व्यवहार को दर्शाता है। |
| [getShowPercentage()](#getShowPercentage--) | निर्दिष्ट चार्ट के डेटा लेबल प्रतिशत मान प्रदर्शन व्यवहार को दर्शाता है। |
| [setShowPercentage(boolean value)](#setShowPercentage-boolean-) | निर्दिष्ट चार्ट के डेटा लेबल प्रतिशत मान प्रदर्शन व्यवहार को दर्शाता है। |
| [getShowBubbleSize()](#getShowBubbleSize--) | निर्दिष्ट चार्ट के डेटा लेबल बबल आकार मान प्रदर्शन व्यवहार को दर्शाता है। |
| [setShowBubbleSize(boolean value)](#setShowBubbleSize-boolean-) | निर्दिष्ट चार्ट के डेटा लेबल बबल आकार मान प्रदर्शन व्यवहार को दर्शाता है। |
| [getShowLeaderLines()](#getShowLeaderLines--) | निर्दिष्ट चार्ट के डेटा लेबल लीडर लाइन्स प्रदर्शन व्यवहार को दर्शाता है। |
| [setShowLeaderLines(boolean value)](#setShowLeaderLines-boolean-) | निर्दिष्ट चार्ट के डेटा लेबल लीडर लाइन्स प्रदर्शन व्यवहार को दर्शाता है। |
| [getShowLabelAsDataCallout()](#getShowLabelAsDataCallout--) | निर्धारित करता है कि निर्दिष्ट चार्ट का डेटा लेबल डेटा कॉलआउट के रूप में या डेटा लेबल के रूप में दिखाया जाएगा। |
| [setShowLabelAsDataCallout(boolean value)](#setShowLabelAsDataCallout-boolean-) | निर्धारित करता है कि निर्दिष्ट चार्ट का डेटा लेबल डेटा कॉलआउट के रूप में या डेटा लेबल के रूप में दिखाया जाएगा। |
| [getShowLabelValueFromCell()](#getShowLabelValueFromCell--) | निर्दिष्ट चार्ट के डेटा लेबल सेल मान प्रदर्शन व्यवहार को दर्शाता है। |
| [setShowLabelValueFromCell(boolean value)](#setShowLabelValueFromCell-boolean-) | निर्दिष्ट चार्ट के डेटा लेबल सेल मान प्रदर्शन व्यवहार को दर्शाता है। |
| [getSeparator()](#getSeparator--) | चार्ट पर डेटा लेबल के लिए उपयोग किए जाने वाले विभाजक को दर्शाने वाला एक वैरिएंट सेट या लौटाता है। |
| [setSeparator(String value)](#setSeparator-java.lang.String-) | चार्ट पर डेटा लेबल के लिए उपयोग किए जाने वाले विभाजक को दर्शाने वाला एक वैरिएंट सेट या लौटाता है। |

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public abstract boolean isNumberFormatLinkedToSource()
```

पढ़ें/लिखें बूलियन।

--------------------

यदि इस DataLabelFormat वस्तु का पैरेंट एक DataLabelCollection डेटा लेबलों का संग्रह है, तो यह प्रॉपर्टी DataLabelCollection संग्रह में नए डेटा लेबलों के लिए IsNumberFormatLinkedToSource प्रॉपर्टी के डिफ़ॉल्ट मान को प्राप्त या सेट करती है। इस प्रॉपर्टी को मान के साथ सेट करने पर यह मान DataLabelCollection संग्रह में सभी डेटा लेबलों के लिए IsNumberFormatLinkedToSource प्रॉपर्टी में भी सेट हो जाता है (उदाहरण के लिए "DataLabels.getDefaultDataLabelFormat().setNumberFormatLinkedToSource(val);" सभी DataLabels.get_Item(i).isNumberFormatLinkedToSource() को val के बराबर बनाता है)।

**वापसी:**
boolean

### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public abstract void setNumberFormatLinkedToSource(boolean value)
```

पढ़ें/लिखें बूलियन।

--------------------

यदि इस DataLabelFormat वस्तु का पैरेंट एक DataLabelCollection डेटा लेबलों का संग्रह है, तो यह प्रॉपर्टी DataLabelCollection संग्रह में नए डेटा लेबलों के लिए IsNumberFormatLinkedToSource प्रॉपर्टी के डिफ़ॉल्ट मान को प्राप्त या सेट करती है। इस प्रॉपर्टी को मान के साथ सेट करने पर यह मान DataLabelCollection संग्रह में सभी डेटा लेबलों के लिए IsNumberFormatLinkedToSource प्रॉपर्टी में भी सेट हो जाता है (उदाहरण के लिए "DataLabels.getDefaultDataLabelFormat().setNumberFormatLinkedToSource(val);" सभी DataLabels.get_Item(i).isNumberFormatLinkedToSource() को val के बराबर बनाता है)।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public abstract String getNumberFormat()
```

DataLabels वस्तु के लिए फ़ॉर्मेट स्ट्रिंग दर्शाता है। पढ़ें/लिखें स्ट्रिंग।

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```

--------------------

यदि इस DataLabelFormat वस्तु का पैरेंट एक DataLabelCollection डेटा लेबलों का संग्रह है, तो यह प्रॉपर्टी DataLabelCollection संग्रह में नए डेटा लेबलों के लिए NumberFormat प्रॉपर्टी के डिफ़ॉल्ट मान को प्राप्त या सेट करती है। जब इस प्रॉपर्टी को मान से सेट किया जाता है, तो वह मान DataLabelCollection संग्रह में सभी डेटा लेबलों के लिए NumberFormat प्रॉपर्टी में भी सेट हो जाता है (उदाहरण के लिए "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" सभी DataLabels.get_Item(i).getNumberFormat() को val के बराबर बनाता है)।

**वापसी:**
java.lang.String

### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public abstract void setNumberFormat(String value)
```

DataLabels वस्तु के लिए फ़ॉर्मेट स्ट्रिंग दर्शाता है। पढ़ें/लिखें स्ट्रिंग।

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```

--------------------

यदि इस DataLabelFormat वस्तु का पैरेंट एक DataLabelCollection डेटा लेबलों का संग्रह है, तो यह प्रॉपर्टी DataLabelCollection संग्रह में नए डेटा लेबलों के लिए NumberFormat प्रॉपर्टी के डिफ़ॉल्ट मान को प्राप्त या सेट करती है। जब इस प्रॉपर्टी को मान से सेट किया जाता है, तो वह मान DataLabelCollection संग्रह में सभी डेटा लेबलों के लिए NumberFormat प्रॉपर्टी में भी सेट हो जाता है (उदाहरण के लिए "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" सभी DataLabels.get_Item(i).getNumberFormat() को val के बराबर बनाता है)।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

डेटा लेबल का फ़ॉर्मेट दर्शाता है। केवल-पढ़ने योग्य [IFormat](../../com.aspose.slides/iformat)।

--------------------

यदि इस DataLabelFormat वस्तु का पैरेंट एक DataLabelCollection डेटा लेबलों का संग्रह है, तो यह प्रॉपर्टी नए डेटा लेबलों के लिए डिफ़ॉल्ट फ़ॉर्मेट दर्शाती है।

**वापसी:**
[IFormat](../../com.aspose.slides/iformat)

### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

डेटा लेबल की स्थिति दर्शाता है। पढ़ें/लिखें [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition)।

--------------------

यदि इस DataLabelFormat वस्तु का पैरेंट एक DataLabelCollection डेटा लेबलों का संग्रह है, तो यह प्रॉपर्टी DataLabelCollection संग्रह में नए डेटा लेबलों के लिए Position प्रॉपर्टी के डिफ़ॉल्ट मान को प्राप्त या सेट करती है। DataLabel वस्तुओं के लिए स्थिति दर्शाता है। इस प्रॉपर्टी को मान के साथ सेट करने पर यह मान सभी डेटा लेबलों के लिए Position प्रॉपर्टी में भी सेट हो जाता है (उदाहरण के लिए "DataLabels.getDefaultDataLabelFormat().setPosition(val)" सभी DataLabels.get_Item(i).getPosition() को val के बराबर बनाता है)।

**वापसी:**
int

### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

डेटा लेबल की स्थिति दर्शाता है। पढ़ें/लिखें [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition)।

--------------------

यदि इस DataLabelFormat वस्तु का पैरेंट एक DataLabelCollection डेटा लेबलों का संग्रह है, तो यह प्रॉपर्टी DataLabelCollection संग्रह में नए डेटा लेबलों के लिए Position प्रॉपर्टी के डिफ़ॉल्ट मान को प्राप्त या सेट करती है। DataLabel वस्तुओं के लिए स्थिति दर्शाता है। इस प्रॉपर्टी को मान के साथ सेट करने पर यह मान सभी डेटा लेबलों के लिए Position प्रॉपर्टी में भी सेट हो जाता है (उदाहरण के लिए "DataLabels.getDefaultDataLabelFormat().setPosition(val)" सभी DataLabels.get_Item(i).getPosition() को val के बराबर बनाता है)।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getShowLegendKey() {#getShowLegendKey--}
```
public abstract boolean getShowLegendKey()
```

निर्दिष्ट चार्ट के डेटा लेबल लेजेंड कुंजी प्रदर्शन व्यवहार को दर्शाता है। यदि लेजेंड कुंजी दिखाई देती है तो सत्य। पढ़ें/लिखें बूलियन।

--------------------

यदि इस DataLabelFormat वस्तु का पैरेंट एक DataLabelCollection डेटा लेबलों का संग्रह है, तो यह प्रॉपर्टी DataLabelCollection संग्रह में नए डेटा लेबलों के लिए ShowLegendKey प्रॉपर्टी के डिफ़ॉल्ट मान को प्राप्त या सेट करती है। इस प्रॉपर्टी को मान के साथ सेट करने पर यह मान सभी डेटा लेबलों के लिए ShowLegendKey प्रॉपर्टी में भी सेट हो जाता है (उदाहरण के लिए "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" सभी DataLabels.get_Item(i).getShowLegendKey() को val के बराबर बनाता है)।

**वापसी:**
boolean

### setShowLegendKey(boolean value) {#setShowLegendKey-boolean-}
```
public abstract void setShowLegendKey(boolean value)
```

निर्दिष्ट चार्ट के डेटा लेबल लेजेंड कुंजी प्रदर्शन व्यवहार को दर्शाता है। यदि लेजेंड कुंजी दिखाई देती है तो सत्य। पढ़ें/लिखें बूलियन।

--------------------

यदि इस DataLabelFormat वस्तु का पैरेंट एक DataLabelCollection डेटा लेबलों का संग्रह है, तो यह प्रॉपर्टी DataLabelCollection संग्रह में नए डेटा लेबलों के लिए ShowLegendKey प्रॉपर्टी के डिफ़ॉल्ट मान को प्राप्त या सेट करती है। इस प्रॉपर्टी को मान के साथ सेट करने पर यह मान सभी डेटा लेबलों के लिए ShowLegendKey प्रॉपर्टी में भी सेट हो जाता है (उदाहरण के लिए "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" सभी DataLabels.get_Item(i).getShowLegendKey() को val के बराबर बनाता है)।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getShowValue() {#getShowValue--}
```
public abstract boolean getShowValue()
```

निर्दिष्ट चार्ट के डेटा लेबल प्रतिशत मान प्रदर्शन व्यवहार को दर्शाता है। सत्य होने पर प्रतिशत मान दिखाया जाता है। फ़ॉल्स होने पर छिपाया जाता है। पढ़ें/लिखें बूलियन।

--------------------

यदि इस DataLabelFormat वस्तु का पैरेंट एक DataLabelCollection डेटा लेबलों का संग्रह है, तो यह प्रॉपर्टी DataLabelCollection संग्रह में नए डेटा लेबलों के लिए ShowValue प्रॉपर्टी के डिफ़ॉल्ट मान को प्राप्त या सेट करती है। इस प्रॉपर्टी को मान के साथ सेट करने पर यह मान सभी डेटा लेबलों के लिए ShowValue प्रॉपर्टी में भी सेट हो जाता है (उदाहरण के लिए "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" सभी DataLabels.get_Item(i).getShowValue() को val के बराबर बनाता है)।

**वापसी:**
boolean

### setShowValue(boolean value) {#setShowValue-boolean-}
```
public abstract void setShowValue(boolean value)
```

निर्दिष्ट चार्ट के डेटा लेबल प्रतिशत मान प्रदर्शन व्यवहार को दर्शाता है। सत्य होने पर प्रतिशत मान दिखाया जाता है। फ़ॉल्स होने पर छिपाया जाता है। पढ़ें/लिखें बूलियन।

--------------------

यदि इस DataLabelFormat वस्तु का पैरेंट एक DataLabelCollection डेटा लेबलों का संग्रह है, तो यह प्रॉपर्टी DataLabelCollection संग्रह में नए डेटा लेबलों के लिए ShowValue प्रॉपर्टी के डिफ़ॉल्ट मान को प्राप्त या सेट करती है। इस प्रॉपर्टी को मान के साथ सेट करने पर यह मान सभी डेटा लेबलों के लिए ShowValue प्रॉपर्टी में भी सेट हो जाता है (उदाहरण के लिए "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" सभी DataLabels.get_Item(i).getShowValue() को val के बराबर बनाता है)।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getShowCategoryName() {#getShowCategoryName--}
```
public abstract boolean getShowCategoryName()
```

निर्दिष्ट चार्ट के डेटा लेबल श्रेणी नाम प्रदर्शन व्यवहार को दर्शाता है। चार्ट पर डेटा लेबल के लिए श्रेणी नाम दिखाने के लिए सत्य। छिपाने के लिए फ़ॉल्स। पढ़ें/लिखें बूलियन।

--------------------

यदि इस DataLabelFormat वस्तु का पैरेंट एक DataLabelCollection डेटा लेबलों का संग्रह है, तो यह प्रॉपर्टी DataLabelCollection संग्रह में नए डेटा लेबलों के लिए ShowCategoryName प्रॉपर्टी के डिफ़ॉल्ट मान को प्राप्त या सेट करती है। इस प्रॉपर्टी को मान के साथ सेट करने पर यह मान सभी डेटा लेबलों के लिए ShowCategoryName प्रॉपर्टी में भी सेट हो जाता है (उदाहरण के लिए "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" सभी DataLabels.get_Item(i).getShowCategoryName() को val के बराबर बनाता है)।

**वापसी:**
boolean

### setShowCategoryName(boolean value) {#setShowCategoryName-boolean-}
```
public abstract void setShowCategoryName(boolean value)
```

निर्दिष्ट चार्ट के डेटा लेबल श्रेणी नाम प्रदर्शन व्यवहार को दर्शाता है। चार्ट पर डेटा लेबल के लिए श्रेणी नाम दिखाने के लिए सत्य। छिपाने के लिए फ़ॉल्स। पढ़ें/लिखें बूलियन।

--------------------
यदि इस DataLabelFormat वस्तु का मूल DataLabelCollection डेटा लेबल संग्रह है, तो यह गुण DataLabelCollection संग्रह में नए डेटा लेबल्स के लिए ShowCategoryName गुण का डिफ़ॉल्ट मान प्राप्त करता है या सेट करता है। इस गुण को मान के साथ सेट करने से यह मान सभी डेटा लेबल्स के ShowCategoryName गुण पर भी सेट हो जाता है (उदाहरण के लिए "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" जिससे सभी DataLabels.get_Item(i).getShowCategoryName() का मान val के बराबर हो जाता है)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getShowSeriesName() {#getShowSeriesName--}
```
public abstract boolean getShowSeriesName()
```

एक Boolean लौटाता है या सेट करता है ताकि चार्ट पर डेटा लेबल्स के लिए श्रृंखला नाम प्रदर्शित होने का व्यवहार दर्शाया जा सके। श्रृंखला नाम दिखाने के लिए True, छिपाने के लिए False। पढ़ें/लिखें Boolean।

--------------------

यदि इस DataLabelFormat वस्तु का मूल DataLabelCollection डेटा लेबल संग्रह है, तो यह गुण DataLabelCollection संग्रह में नए डेटा लेबल्स के लिए ShowSeriesName गुण का डिफ़ॉल्ट मान प्राप्त करता है या सेट करता है। इस गुण को मान के साथ सेट करने से यह मान सभी डेटा लेबल्स के ShowSeriesName गुण पर भी सेट हो जाता है (उदाहरण के लिए "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" जिससे सभी DataLabels.get_Item(i).getShowSeriesName() का मान val के बराबर हो जाता है)।

**रिटर्न:**
boolean
### setShowSeriesName(boolean value) {#setShowSeriesName-boolean-}
```
public abstract void setShowSeriesName(boolean value)
```

एक Boolean लौटाता है या सेट करता है ताकि चार्ट पर डेटा लेबल्स के लिए श्रृंखला नाम प्रदर्शित होने का व्यवहार दर्शाया जा सके। श्रृंखला नाम दिखाने के लिए True, छिपाने के लिए False। पढ़ें/लिखें Boolean।

--------------------

यदि इस DataLabelFormat वस्तु का मूल DataLabelCollection डेटा लेबल संग्रह है, तो यह गुण DataLabelCollection संग्रह में नए डेटा लेबल्स के लिए ShowSeriesName गुण का डिफ़ॉल्ट मान प्राप्त करता है या सेट करता है। इस गुण को मान के साथ सेट करने से यह मान सभी डेटा लेबल्स के ShowSeriesName गुण पर भी सेट हो जाता है (उदाहरण के लिए "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" जिससे सभी DataLabels.get_Item(i).getShowSeriesName() का मान val के बराबर हो जाता है)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getShowPercentage() {#getShowPercentage--}
```
public abstract boolean getShowPercentage()
```

एक Boolean लौटाता है या सेट करता है ताकि निर्दिष्ट चार्ट के डेटा लेबल प्रतिशत मूल्य प्रदर्शित होने का व्यवहार दर्शाया जा सके। प्रतिशत मूल्य दिखाने के लिए True, छिपाने के लिए False। पढ़ें/लिखें Boolean।

--------------------

यदि इस DataLabelFormat वस्तु का मूल DataLabelCollection डेटा लेबल संग्रह है, तो यह गुण DataLabelCollection संग्रह में नए डेटा लेबल्स के लिए ShowPercentage गुण का डिफ़ॉल्ट मान प्राप्त करता है या सेट करता है। इस गुण को मान के साथ सेट करने से यह मान सभी डेटा लेबल्स के ShowPercentage गुण पर भी सेट हो जाता है (उदाहरण के लिए "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" जिससे सभी DataLabels.get_Item(i).getShowPercentage() का मान val के बराबर हो जाता है)।

**रिटर्न:**
boolean
### setShowPercentage(boolean value) {#setShowPercentage-boolean-}
```
public abstract void setShowPercentage(boolean value)
```

एक Boolean लौटाता है या सेट करता है ताकि निर्दिष्ट चार्ट के डेटा लेबल प्रतिशत मूल्य प्रदर्शित होने का व्यवहार दर्शाया जा सके। प्रतिशत मूल्य दिखाने के लिए True, छिपाने के लिए False। पढ़ें/लिखें Boolean।

--------------------

यदि इस DataLabelFormat वस्तु का मूल DataLabelCollection डेटा लेबल संग्रह है, तो यह गुण DataLabelCollection संग्रह में नए डेटा लेबल्स के लिए ShowPercentage गुण का डिफ़ॉल्ट मान प्राप्त करता है या सेट करता है। इस गुण को मान के साथ सेट करने से यह मान सभी डेटा लेबल्स के ShowPercentage गुण पर भी सेट हो जाता है (उदाहरण के लिए "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" जिससे सभी DataLabels.get_Item(i).getShowPercentage() का मान val के बराबर हो जाता है)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getShowBubbleSize() {#getShowBubbleSize--}
```
public abstract boolean getShowBubbleSize()
```

एक Boolean लौटाता है या सेट करता है ताकि निर्दिष्ट चार्ट के डेटा लेबल बबल आकार मूल्य प्रदर्शित होने का व्यवहार दर्शाया जा सके। बबल आकार दिखाने के लिए True, छिपाने के लिए False। पढ़ें/लिखें Boolean।

--------------------

यदि इस DataLabelFormat वस्तु का मूल DataLabelCollection डेटा लेबल संग्रह है, तो यह गुण DataLabelCollection संग्रह में नए डेटा लेबल्स के लिए ShowBubbleSize गुण का डिफ़ॉल्ट मान प्राप्त करता है या सेट करता है। इस गुण को मान के साथ सेट करने से यह मान सभी डेटा लेबल्स के ShowBubbleSize गुण पर भी सेट हो जाता है (उदाहरण के लिए "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" जिससे सभी DataLabels.get_Item(i).getShowBubbleSize() का मान val के बराबर हो जाता है)।

**रिटर्न:**
boolean
### setShowBubbleSize(boolean value) {#setShowBubbleSize-boolean-}
```
public abstract void setShowBubbleSize(boolean value)
```

एक Boolean लौटाता है या सेट करता है ताकि निर्दिष्ट चार्ट के डेटा लेबल बबल आकार मूल्य प्रदर्शित होने का व्यवहार दर्शाया जा सके। बबल आकार दिखाने के लिए True, छिपाने के लिए False। पढ़ें/लिखें Boolean।

--------------------

यदि इस DataLabelFormat वस्तु का मूल DataLabelCollection डेटा लेबल संग्रह है, तो यह गुण DataLabelCollection संग्रह में नए डेटा लेबल्स के लिए ShowBubbleSize गुण का डिफ़ॉल्ट मान प्राप्त करता है या सेट करता है। इस गुण को मान के साथ सेट करने से यह मान सभी डेटा लेबल्स के ShowBubbleSize गुण पर भी सेट हो जाता है (उदाहरण के लिए "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" जिससे सभी DataLabels.get_Item(i).getShowBubbleSize() का मान val के बराबर हो जाता है)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getShowLeaderLines() {#getShowLeaderLines--}
```
public abstract boolean getShowLeaderLines()
```

एक Boolean लौटाता है या सेट करता है ताकि निर्दिष्ट चार्ट के डेटा लेबल लीडर लाइन्स प्रदर्शित होने का व्यवहार दर्शाया जा सके। लीडर लाइन्स दिखाने के लिए True, छिपाने के लिए False। पढ़ें/लिखें Boolean।

--------------------

यदि इस DataLabelFormat वस्तु का मूल DataLabelCollection डेटा लेबल संग्रह है, तो यह गुण DataLabelCollection संग्रह में नए डेटा लेबल्स के लिए ShowLeaderLines गुण का डिफ़ॉल्ट मान प्राप्त करता है या सेट करता है। इस गुण को मान के साथ सेट करने से यह मान सभी डेटा लेबल्स के ShowLeaderLines गुण पर भी सेट हो जाता है (उदाहरण के लिए "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" जिससे सभी DataLabels.get_Item(i).getShowLeaderLines() का मान val के बराबर हो जाता है)।

**रिटर्न:**
boolean
### setShowLeaderLines(boolean value) {#setShowLeaderLines-boolean-}
```
public abstract void setShowLeaderLines(boolean value)
```

एक Boolean लौटाता है या सेट करता है ताकि निर्दिष्ट चार्ट के डेटा लेबल लीडर लाइन्स प्रदर्शित होने का व्यवहार दर्शाया जा सके। लीडर लाइन्स दिखाने के लिए True, छिपाने के लिए False। पढ़ें/लिखें Boolean।

--------------------

यदि इस DataLabelFormat वस्तु का मूल DataLabelCollection डेटा लेबल संग्रह है, तो यह गुण DataLabelCollection संग्रह में नए डेटा लेबल्स के लिए ShowLeaderLines गुण का डिफ़ॉल्ट मान प्राप्त करता है या सेट करता है। इस गुण को मान के साथ सेट करने से यह मान सभी डेटा लेबल्स के ShowLeaderLines गुण पर भी सेट हो जाता है (उदाहरण के लिए "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" जिससे सभी DataLabels.get_Item(i).getShowLeaderLines() का मान val के बराबर हो जाता है)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelAsDataCallout() {#getShowLabelAsDataCallout--}
```
public abstract boolean getShowLabelAsDataCallout()
```

निर्दिष्ट चार्ट के डेटा लेबल को डेटा कॉलआउट या डेटा लेबल के रूप में प्रदर्शित करने का निर्धारण करता है।

--------------------

यदि इस DataLabelFormat वस्तु का मूल DataLabelCollection डेटा लेबल संग्रह है, तो यह गुण DataLabelCollection संग्रह में नए डेटा लेबल्स के लिए ShowLabelAsDataCallout गुण का डिफ़ॉल्ट मान प्राप्त करता है या सेट करता है। इस गुण को मान के साथ सेट करने से यह मान सभी डेटा लेबल्स के ShowLabelAsDataCallout गुण पर भी सेट हो जाता है (उदाहरण के लिए "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" जिससे सभी DataLabels.get_Item(i).getShowLabelAsDataCallout() का मान val के बराबर हो जाता है)।

**रिटर्न:**
boolean
### setShowLabelAsDataCallout(boolean value) {#setShowLabelAsDataCallout-boolean-}
```
public abstract void setShowLabelAsDataCallout(boolean value)
```

निर्दिष्ट चार्ट के डेटा लेबल को डेटा कॉलआउट या डेटा लेबल के रूप में प्रदर्शित करने का निर्धारण करता है।

--------------------

यदि इस DataLabelFormat वस्तु का मूल DataLabelCollection डेटा लेबल संग्रह है, तो यह गुण DataLabelCollection संग्रह में नए डेटा लेबल्स के लिए ShowLabelAsDataCallout गुण का डिफ़ॉल्ट मान प्राप्त करता है या सेट करता है। इस गुण को मान के साथ सेट करने से यह मान सभी डेटा लेबल्स के ShowLabelAsDataCallout गुण पर भी सेट हो जाता है (उदाहरण के लिए "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" जिससे सभी DataLabels.get_Item(i).getShowLabelAsDataCallout() का मान val के बराबर हो जाता है)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelValueFromCell() {#getShowLabelValueFromCell--}
```
public abstract boolean getShowLabelValueFromCell()
```

एक Boolean लौटाता है या सेट करता है ताकि निर्दिष्ट चार्ट के डेटा लेबल सेल मूल्य प्रदर्शित होने का व्यवहार दर्शाया जा सके। सेल मूल्य दिखाने के लिए True, छिपाने के लिए False। पढ़ें/लिखें Boolean।

--------------------

यदि इस DataLabelFormat वस्तु का मूल DataLabelCollection डेटा लेबल संग्रह है, तो यह गुण DataLabelCollection संग्रह में नए डेटा लेबल्स के लिए ShowLabelValueFromCell गुण का डिफ़ॉल्ट मान प्राप्त करता है या सेट करता है। इस गुण को मान के साथ सेट करने से यह मान सभी डेटा लेबल्स के ShowLabelValueFromCell गुण पर भी सेट हो जाता है (उदाहरण के लिए "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" जिससे सभी DataLabels.get_Item(i).getShowLabelValueFromCell() का मान val के बराबर हो जाता है)।

**रिटर्न:**
boolean
### setShowLabelValueFromCell(boolean value) {#setShowLabelValueFromCell-boolean-}
```
public abstract void setShowLabelValueFromCell(boolean value)
```

एक Boolean लौटाता है या सेट करता है ताकि निर्दिष्ट चार्ट के डेटा लेबल सेल मूल्य प्रदर्शित होने का व्यवहार दर्शाया जा सके। सेल मूल्य दिखाने के लिए True, छिपाने के लिए False। पढ़ें/लिखें Boolean।

--------------------

यदि इस DataLabelFormat वस्तु का मूल DataLabelCollection डेटा लेबल संग्रह है, तो यह गुण DataLabelCollection संग्रह में नए डेटा लेबल्स के लिए ShowLabelValueFromCell गुण का डिफ़ॉल्ट मान प्राप्त करता है या सेट करता है। इस गुण को मान के साथ सेट करने से यह मान सभी डेटा लेबल्स के ShowLabelValueFromCell गुण पर भी सेट हो जाता है (उदाहरण के लिए "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" जिससे सभी DataLabels.get_Item(i).getShowLabelValueFromCell() का मान val के बराबर हो जाता है)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getSeparator() {#getSeparator--}
```
public abstract String getSeparator()
```

एक Variant सेट करता है या लौटाता है जो चार्ट पर डेटा लेबल्स के लिए प्रयुक्त विभाजक को दर्शाता है। पढ़ें/लिखें String।

--------------------

यदि इस DataLabelFormat वस्तु का मूल DataLabelCollection डेटा लेबल संग्रह है, तो यह गुण DataLabelCollection संग्रह में नए डेटा लेबल्स के लिए Separator गुण का डिफ़ॉल्ट मान प्राप्त करता है या सेट करता है। इस गुण को मान के साथ सेट करने से यह मान सभी डेटा लेबल्स के Separator गुण पर भी सेट हो जाता है (उदाहरण के लिए "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" जिससे सभी DataLabels.get_Item(i).getSeparator() का मान val के बराबर हो जाता है)।

**रिटर्न:**
java.lang.String
### setSeparator(String value) {#setSeparator-java.lang.String-}
```
public abstract void setSeparator(String value)
```

एक Variant सेट करता है या लौटाता है जो चार्ट पर डेटा लेबल्स के लिए प्रयुक्त विभाजक को दर्शाता है। पढ़ें/लिखें String।

--------------------

यदि इस DataLabelFormat वस्तु का मूल DataLabelCollection डेटा लेबल संग्रह है, तो यह गुण DataLabelCollection संग्रह में नए डेटा लेबल्स के लिए Separator गुण का डिफ़ॉल्ट मान प्राप्त करता है या सेट करता है। इस गुण को मान के साथ सेट करने से यह मान सभी डेटा लेबल्स के Separator गुण पर भी सेट हो जाता है (उदाहरण के लिए "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" जिससे सभी DataLabels.get_Item(i).getSeparator() का मान val के बराबर हो जाता है)।
**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |