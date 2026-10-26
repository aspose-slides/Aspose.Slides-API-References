---
title: ShapeStyle
second_title: Aspose.Slides for Android जावा API रेफ़रेंस
description: आकार शैली संदर्भ का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/shapestyle/
---
**विरासत:**
java.lang.Object, com.aspose.slides.DomObject

**सभी कार्यान्वित इंटरफ़ेस:**
[com.aspose.slides.IShapeStyle](../../com.aspose.slides/ishapestyle)
```
public class ShapeStyle extends DomObject<Shape> implements IShapeStyle
```

आकार की शैली संदर्भ का प्रतिनिधित्व करता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getLineColor()](#getLineColor--) | आकार की रूपरेखा रंग लौटाता है। |
| [getLineStyleIndex()](#getLineStyleIndex--) | लाइन का कॉलम सूचकांक शैली मैट्रिक्स में लौटाता है या सेट करता है। |
| [setLineStyleIndex(int value)](#setLineStyleIndex-int-) | लाइन का कॉलम सूचकांक शैली मैट्रिक्स में लौटाता है या सेट करता है। |
| [getFillColor()](#getFillColor--) | आकार का भराव रंग लौटाता है। |
| [getFillStyleIndex()](#getFillStyleIndex--) | आकार का भराव कॉलम सूचकांक शैली मैट्रिक्स में लौटाता है या सेट करता है। |
| [setFillStyleIndex(short value)](#setFillStyleIndex-short-) | आकार का भराव कॉलम सूचकांक शैली मैट्रिक्स में लौटाता है या सेट करता है। |
| [getEffectColor()](#getEffectColor--) | आकार का प्रभाव रंग लौटाता है। |
| [getEffectStyleIndex()](#getEffectStyleIndex--) | आकार का प्रभाव कॉलम सूचकांक शैली मैट्रिक्स में लौटाता है या सेट करता है। |
| [setEffectStyleIndex(long value)](#setEffectStyleIndex-long-) | आकार का प्रभाव कॉलम सूचकांक शैली मैट्रिक्स में लौटाता है या सेट करता है। |
| [getFontColor()](#getFontColor--) | आकार का फ़ॉन्ट रंग लौटाता है। |
| [getFontCollectionIndex()](#getFontCollectionIndex--) | आकार का फ़ॉन्ट सूचकांक फ़ॉन्ट संग्रह में लौटाता है या सेट करता है। |
| [setFontCollectionIndex(byte value)](#setFontCollectionIndex-byte-) | आकार का फ़ॉन्ट सूचकांक फ़ॉन्ट संग्रह में लौटाता है या सेट करता है। |
### getLineColor() {#getLineColor--}
```
public final IColorFormat getLineColor()
```

आकार की रूपरेखा रंग लौटाता है। केवल-पढ़ने योग्य [IColorFormat](../../com.aspose.slides/icolorformat)।

**रिटर्न:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getLineStyleIndex() {#getLineStyleIndex--}
```
public final int getLineStyleIndex()
```

लाइन का कॉलम सूचकांक शैली मैट्रिक्स में लौटाता है या सेट करता है। पढ़ने/लिखने योग्य int।

**रिटर्न:**
int
### setLineStyleIndex(int value) {#setLineStyleIndex-int-}
```
public final void setLineStyleIndex(int value)
```

लाइन का कॉलम सूचकांक शैली मैट्रिक्स में लौटाता है या सेट करता है। पढ़ने/लिखने योग्य int।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |
### getFillColor() {#getFillColor--}
```
public final IColorFormat getFillColor()
```

आकार का भराव रंग लौटाता है। केवल-पढ़ने योग्य [IColorFormat](../../com.aspose.slides/icolorformat)।

**रिटर्न:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getFillStyleIndex() {#getFillStyleIndex--}
```
public final short getFillStyleIndex()
```

आकार का भराव कॉलम सूचकांक शैली मैट्रिक्स में लौटाता है या सेट करता है। 0 का अर्थ कोई भराव नहीं, सकारात्मक मान – थीम के भराव शैलियों में सूचकांक, नकारात्मक मान – थीम के पृष्ठभूमि शैलियों में सूचकांक। पढ़ने/लिखने योग्य short।

**रिटर्न:**
short
### setFillStyleIndex(short value) {#setFillStyleIndex-short-}
```
public final void setFillStyleIndex(short value)
```

आकार का भराव कॉलम सूचकांक शैली मैट्रिक्स में लौटाता है या सेट करता है। 0 का अर्थ कोई भराव नहीं, सकारात्मक मान – थीम के भराव शैलियों में सूचकांक, नकारात्मक मान – थीम के पृष्ठभूमि शैलियों में सूचकांक। पढ़ने/लिखने योग्य short।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | short |  |
### getEffectColor() {#getEffectColor--}
```
public final IColorFormat getEffectColor()
```

आकार का प्रभाव रंग लौटाता है। केवल-पढ़ने योग्य [IColorFormat](../../com.aspose.slides/icolorformat)।

**रिटर्न:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffectStyleIndex() {#getEffectStyleIndex--}
```
public final long getEffectStyleIndex()
```

आकार का प्रभाव कॉलम सूचकांक शैली मैट्रिक्स में लौटाता है या सेट करता है। पढ़ने/लिखने योग्य long।

**रिटर्न:**
long
### setEffectStyleIndex(long value) {#setEffectStyleIndex-long-}
```
public final void setEffectStyleIndex(long value)
```

आकार का प्रभाव कॉलम सूचकांक शैली मैट्रिक्स में लौटाता है या सेट करता है। पढ़ने/लिखने योग्य long।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | long |  |
### getFontColor() {#getFontColor--}
```
public final IColorFormat getFontColor()
```

आकार का फ़ॉन्ट रंग लौटाता है। केवल-पढ़ने योग्य [IColorFormat](../../com.aspose.slides/icolorformat)।

**रिटर्न:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getFontCollectionIndex() {#getFontCollectionIndex--}
```
public final byte getFontCollectionIndex()
```

आकार का फ़ॉन्ट सूचकांक फ़ॉन्ट संग्रह में लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [FontCollectionIndex](../../com.aspose.slides/fontcollectionindex)।

**रिटर्न:**
byte
### setFontCollectionIndex(byte value) {#setFontCollectionIndex-byte-}
```
public final void setFontCollectionIndex(byte value)
```

आकार का फ़ॉन्ट सूचकांक फ़ॉन्ट संग्रह में लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [FontCollectionIndex](../../com.aspose.slides/fontcollectionindex)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |