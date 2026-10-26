---
title: IDataLabel
second_title: Aspose.Slides Android के लिये Java API संदर्भ
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

| विधि | विवरण |
| --- | --- |
| [isVisible()](#isVisible--) | False का अर्थ है कि डेटा लेबल दिखाई नहीं देता (और इसलिए सभी Show*-flags (ShowValue, ...) गलत हैं). |
| [hide()](#hide--) | सभी Show*-flags (ShowValue, ...) को false स्थिति में सेट करके डेटा लेबल को छिपाएँ। |
| [getDataLabelFormat()](#getDataLabelFormat--) | डेटा लेबल का प्रारूप वापस करता है। |
| [getValueFromCell()](#getValueFromCell--) | वर्कबुक डेटा सेल को प्राप्त करता है या सेट करता है। |
| [setValueFromCell(IChartDataCell value)](#setValueFromCell-com.aspose.slides.IChartDataCell-) | वर्कबुक डेटा सेल को प्राप्त करता है या सेट करता है। |
| [getActualLabelText()](#getActualLabelText--) | DataLabelFormat सेटिंग्स या TextFrameForOverriding.Text मान के आधार पर वास्तविक लेबल टेक्स्ट लौटाता है। |
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

False का अर्थ है कि डेटा लेबल दिखाई नहीं देता (और इसलिए सभी Show*-flags (ShowValue, ...) गलत हैं). केवल-पढ़ने योग्य बूलियन.

--------------------

यदि डेटा लेबल दिखाई दे रहा है तो आप इसे Hide() विधि से छिपा सकते हैं। लेकिन यदि डेटा लेबल दिखाई नहीं दे रहा है (IsVisible false है) तो आप Show*-flags (ShowValue, ...) को true स्थिति में सेट करके डेटा लेबल को दिखाई दे सकता है।

**वापसी:**
boolean
### hide() {#hide--}
```
public abstract void hide()
```

सभी Show*-flags (ShowValue, ...) को false स्थिति में सेट करके डेटा लेबल को छिपाएँ। इसके बाद IsVisible false होगा.

--------------------

यदि डेटा लेबल दिखाई नहीं दे रहा है (IsVisible false है) तो आप Show*-flags (ShowValue, ...) को true स्थिति में सेट करके डेटा लेबल को दिखाई दे सकता है।

### getDataLabelFormat() {#getDataLabelFormat--}
```
public abstract IDataLabelFormat getDataLabelFormat()
```

डेटा लेबल का प्रारूप वापस करता है। केवल-पढ़ने योग्य [IDataLabelFormat](../../com.aspose.slides/idatalabelformat)।

**वापसी:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getValueFromCell() {#getValueFromCell--}
```
public abstract IChartDataCell getValueFromCell()
```

वर्कबुक डेटा सेल को प्राप्त करता है या सेट करता है। यदि IDataLabelFormat.ShowLabelValueFromCell प्रॉपर्टी true हो तो लागू होता है।

**वापसी:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setValueFromCell(IChartDataCell value) {#setValueFromCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setValueFromCell(IChartDataCell value)
```

वर्कबुक डेटा सेल को प्राप्त करता है या सेट करता है। यदि IDataLabelFormat.ShowLabelValueFromCell प्रॉपर्टी true हो तो लागू होता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getActualLabelText() {#getActualLabelText--}
```
public abstract String getActualLabelText()
```

DataLabelFormat सेटिंग्स या TextFrameForOverriding.Text मान के आधार पर वास्तविक लेबल टेक्स्ट लौटाता है।

**वापसी:**
java.lang.String - वास्तविक लेबल टेक्स्ट स्ट्रिंग