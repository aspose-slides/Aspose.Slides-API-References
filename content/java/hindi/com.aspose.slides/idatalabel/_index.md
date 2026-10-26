---
title: IDataLabel
second_title: Aspose.Slides जावा API संदर्भ
description: एक श्रृंखला लेबल का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/idatalabel/
---
**सभी लागू इंटरफ़ेस:**  
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IOverridableText](../../com.aspose.slides/ioverridabletext), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IDataLabel extends ILayoutable, IOverridableText, IActualLayout
```

एक श्रृंखला लेबल का प्रतिनिधित्व करता है।

## विधियाँ

| मेथड | विवरण |
| --- | --- |
| [isVisible()](#isVisible--) | False का अर्थ है कि डेटा लेबल दृश्यमान नहीं है (और इसलिए सभी Show*-flags (ShowValue, ...) false हैं). |
| [hide()](#hide--) | सभी Show*-flags (ShowValue, ...) को false स्थिति में सेट करके डेटा लेबल को छिपाएँ. |
| [getDataLabelFormat()](#getDataLabelFormat--) | डेटा लेबल का फ़ॉर्मेट लौटाता है. |
| [getValueFromCell()](#getValueFromCell--) | वर्कबुक डेटा सेल को प्राप्त करता है या सेट करता है. |
| [setValueFromCell(IChartDataCell value)](#setValueFromCell-com.aspose.slides.IChartDataCell-) | वर्कबुक डेटा सेल को प्राप्त करता है या सेट करता है. |
| [getActualLabelText()](#getActualLabelText--) | DataLabelFormat सेटिंग्स या TextFrameForOverriding.Text मान के आधार पर वास्तविक लेबल टेक्स्ट लौटाता है. |

### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

False का अर्थ है कि डेटा लेबल दृश्यमान नहीं है (और इसलिए सभी Show*-flags (ShowValue, ...) false हैं). केवल पढ़ने योग्य बूलियन.

--------------------

यदि डेटा लेबल दृश्यमान है तो आप Hide() मेथड से इसे छिपा सकते हैं. लेकिन यदि डेटा लेबल दृश्यमान नहीं है (IsVisible false है) तो आप Show*-flags (ShowValue, ...) को true स्थिति में सेट करके डेटा लेबल को फिर से दृश्यमान बना सकते हैं.

**रिटर्न:**  
boolean

### hide() {#hide--}
```
public abstract void hide()
```

सभी Show*-flags (ShowValue, ...) को false स्थिति में सेट करके डेटा लेबल को छिपाएँ. इस कार्रवाई के बाद IsVisible false रहेगा.

--------------------

यदि डेटा लेबल दृश्यमान नहीं है (IsVisible false है) तो आप Show*-flags (ShowValue, ...) को true स्थिति में सेट करके डेटा लेबल को दृश्यमान बना सकते हैं.

### getDataLabelFormat() {#getDataLabelFormat--}
```
public abstract IDataLabelFormat getDataLabelFormat()
```

डेटा लेबल का फ़ॉर्मेट लौटाता है. केवल पढ़ने योग्य [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**रिटर्न:**  
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)

### getValueFromCell() {#getValueFromCell--}
```
public abstract IChartDataCell getValueFromCell()
```

वर्कबुक डेटा सेल को प्राप्त करता है या सेट करता है. यह तब लागू होता है जब IDataLabelFormat.ShowLabelValueFromCell प्रॉपर्टी true हो.

**रिटर्न:**  
[IChartDataCell](../../com.aspose.slides/ichartdatacell)

### setValueFromCell(IChartDataCell value) {#setValueFromCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setValueFromCell(IChartDataCell value)
```

वर्कबुक डेटा सेल को प्राप्त करता है या सेट करता है. यह तब लागू होता है जब IDataLabelFormat.ShowLabelValueFromCell प्रॉपर्टी true हो.

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getActualLabelText() {#getActualLabelText--}
```
public abstract String getActualLabelText()
```

DataLabelFormat सेटिंग्स या TextFrameForOverriding.Text मान के आधार पर वास्तविक लेबल टेक्स्ट लौटाता है.

**रिटर्न:**  
java.lang.String - Actual label text String