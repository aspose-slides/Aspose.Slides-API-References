---
title: IShapeStyle
second_title: Aspose.Slides for Java API Reference
description: आकार शैली संदर्भ का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/ishapestyle/
---```
public interface IShapeStyle
```

आकार शैली संदर्भ को दर्शाता है।
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getLineColor()](#getLineColor--) | एक आकार की रूपरेखा रंग वापस करता है। |
| [getLineStyleIndex()](#getLineStyleIndex--) | स्टाइल मैट्रिक्स में लाइन के कॉलम इंडेक्स को वापस करता है या सेट करता है। |
| [setLineStyleIndex(int value)](#setLineStyleIndex-int-) | स्टाइल मैट्रिक्स में लाइन के कॉलम इंडेक्स को वापस करता है या सेट करता है। |
| [getFillColor()](#getFillColor--) | एक आकार का भरने का रंग वापस करता है। |
| [getFillStyleIndex()](#getFillStyleIndex--) | स्टाइल मैट्रिक्स में आकार के भरने के कॉलम इंडेक्स को वापस करता है या सेट करता है। |
| [setFillStyleIndex(short value)](#setFillStyleIndex-short-) | स्टाइल मैट्रिक्स में आकार के भरने के कॉलम इंडेक्स को वापस करता है या सेट करता है। |
| [getEffectColor()](#getEffectColor--) | एक आकार का प्रभाव रंग वापस करता है। |
| [getEffectStyleIndex()](#getEffectStyleIndex--) | स्टाइल मैट्रिक्स में आकार के प्रभाव कॉलम इंडेक्स को वापस करता है या सेट करता है। |
| [setEffectStyleIndex(long value)](#setEffectStyleIndex-long-) | स्टाइल मैट्रिक्स में आकार के प्रभाव कॉलम इंडेक्स को वापस करता है या सेट करता है। |
| [getFontColor()](#getFontColor--) | एक आकार का फ़ॉन्ट रंग वापस करता है। |
| [getFontCollectionIndex()](#getFontCollectionIndex--) | फ़ॉन्ट संग्रह में आकार के फ़ॉन्ट इंडेक्स को वापस करता है या सेट करता है। |
| [setFontCollectionIndex(byte value)](#setFontCollectionIndex-byte-) | फ़ॉन्ट संग्रह में आकार के फ़ॉन्ट इंडेक्स को वापस करता है या सेट करता है। |
### getLineColor() {#getLineColor--}
```
public abstract IColorFormat getLineColor()
```

एक आकार की रूपरेखा रंग वापस करता है। केवल पढ़ने योग्य [IColorFormat](../../com.aspose.slides/icolorformat).

**वापसी:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getLineStyleIndex() {#getLineStyleIndex--}
```
public abstract int getLineStyleIndex()
```

स्टाइल मैट्रिक्स में लाइन के कॉलम इंडेक्स को वापस करता है या सेट करता है। पढ़ने/लिखने योग्य int.

**वापसी:**
int
### setLineStyleIndex(int value) {#setLineStyleIndex-int-}
```
public abstract void setLineStyleIndex(int value)
```

स्टाइल मैट्रिक्स में लाइन के कॉलम इंडेक्स को वापस करता है या सेट करता है। पढ़ने/लिखने योग्य int.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |
### getFillColor() {#getFillColor--}
```
public abstract IColorFormat getFillColor()
```

एक आकार का भरने का रंग वापस करता है। केवल पढ़ने योग्य [IColorFormat](../../com.aspose.slides/icolorformat).

**वापसी:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getFillStyleIndex() {#getFillStyleIndex--}
```
public abstract short getFillStyleIndex()
```

स्टाइल मैट्रिक्स में आकार के भरने के कॉलम इंडेक्स को वापस करता है या सेट करता है। 0 का अर्थ कोई भरना नहीं, सकारात्मक मान - थीम के भरने शैलियों में इंडेक्स, नकारात्मक मान - थीम के पृष्ठभूमि शैलियों में इंडेक्स। पढ़ने/लिखने योग्य short.

**वापसी:**
short
### setFillStyleIndex(short value) {#setFillStyleIndex-short-}
```
public abstract void setFillStyleIndex(short value)
```

स्टाइल मैट्रिक्स में आकार के भरने के कॉलम इंडेक्स को वापस करता है या सेट करता है। 0 का अर्थ कोई भरना नहीं, सकारात्मक मान - थीम के भरने शैलियों में इंडेक्स, नकारात्मक मान - थीम के पृष्ठभूमि शैलियों में इंडेक्स। पढ़ने/लिखने योग्य short.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | short |  |
### getEffectColor() {#getEffectColor--}
```
public abstract IColorFormat getEffectColor()
```

एक आकार का प्रभाव रंग वापस करता है। केवल पढ़ने योग्य [IColorFormat](../../com.aspose.slides/icolorformat).

**वापसी:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffectStyleIndex() {#getEffectStyleIndex--}
```
public abstract long getEffectStyleIndex()
```

स्टाइल मैट्रिक्स में आकार के प्रभाव कॉलम इंडेक्स को वापस करता है या सेट करता है। पढ़ने/लिखने योग्य long.

**वापसी:**
long
### setEffectStyleIndex(long value) {#setEffectStyleIndex-long-}
```
public abstract void setEffectStyleIndex(long value)
```

स्टाइल मैट्रिक्स में आकार के प्रभाव कॉलम इंडेक्स को वापस करता है या सेट करता है। पढ़ने/लिखने योग्य long.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | long |  |
### getFontColor() {#getFontColor--}
```
public abstract IColorFormat getFontColor()
```

एक आकार का फ़ॉन्ट रंग वापस करता है। केवल पढ़ने योग्य [IColorFormat](../../com.aspose.slides/icolorformat).

**वापसी:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getFontCollectionIndex() {#getFontCollectionIndex--}
```
public abstract byte getFontCollectionIndex()
```

फ़ॉन्ट संग्रह में आकार के फ़ॉन्ट इंडेक्स को वापस करता है या सेट करता है। पढ़ने/लिखने योग्य [FontCollectionIndex](../../com.aspose.slides/fontcollectionindex).

**वापसी:**
byte
### setFontCollectionIndex(byte value) {#setFontCollectionIndex-byte-}
```
public abstract void setFontCollectionIndex(byte value)
```

फ़ॉन्ट संग्रह में आकार के फ़ॉन्ट इंडेक्स को वापस करता है या सेट करता है। पढ़ने/लिखने योग्य [FontCollectionIndex](../../com.aspose.slides/fontcollectionindex).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |