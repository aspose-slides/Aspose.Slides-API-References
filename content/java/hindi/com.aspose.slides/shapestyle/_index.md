---
title: ShapeStyle
second_title: Aspose.Slides के लिए Java API संदर्भ
description: आकारों की शैली संदर्भ का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/shapestyle/
---
**विरासत:**  
java.lang.Object, com.aspose.slides.DomObject

**सभी लागू इंटरफ़ेस:**  
[com.aspose.slides.IShapeStyle](../../com.aspose.slides/ishapestyle)  
```
public class ShapeStyle extends DomObject<Shape> implements IShapeStyle
```

shape के शैली संदर्भ का प्रतिनिधित्व करता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getLineColor()](#getLineColor--) | एक shape की outline color लौटाता है। |
| [getLineStyleIndex()](#getLineStyleIndex--) | line के column index को style matrix में लौटाता है या सेट करता है। |
| [setLineStyleIndex(int value)](#setLineStyleIndex-int-) | line के column index को style matrix में लौटाता है या सेट करता है। |
| [getFillColor()](#getFillColor--) | एक shape की fill color लौटाता है। |
| [getFillStyleIndex()](#getFillStyleIndex--) | shape के fill column index को style matrices में लौटाता है या सेट करता है। |
| [setFillStyleIndex(short value)](#setFillStyleIndex-short-) | shape के fill column index को style matrices में लौटाता है या सेट करता है। |
| [getEffectColor()](#getEffectColor--) | एक shape की effect color लौटाता है। |
| [getEffectStyleIndex()](#getEffectStyleIndex--) | shape के effect column index को style matrix में लौटाता है या सेट करता है। |
| [setEffectStyleIndex(long value)](#setEffectStyleIndex-long-) | shape के effect column index को style matrix में लौटाता है या सेट करता है। |
| [getFontColor()](#getFontColor--) | एक shape की font color लौटाता है। |
| [getFontCollectionIndex()](#getFontCollectionIndex--) | shape के font index को font collection में लौटाता है या सेट करता है। |
| [setFontCollectionIndex(byte value)](#setFontCollectionIndex-byte-) | shape के font index को font collection में लौटाता है या सेट करता है। |
### getLineColor() {#getLineColor--}
```
public final IColorFormat getLineColor()
```

एक shape की outline color लौटाता है। केवल पढ़ने योग्य [IColorFormat](../../com.aspose.slides/icolorformat)।

**वापसी:**  
[IColorFormat](../../com.aspose.slides/icolorformat)
### getLineStyleIndex() {#getLineStyleIndex--}
```
public final int getLineStyleIndex()
```

line के column index को style matrix में लौटाता है या सेट करता है। पढ़े/लिखे int।

**वापसी:**  
int
### setLineStyleIndex(int value) {#setLineStyleIndex-int-}
```
public final void setLineStyleIndex(int value)
```

line के column index को style matrix में लौटाता है या सेट करता है। पढ़े/लिखे int।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |
### getFillColor() {#getFillColor--}
```
public final IColorFormat getFillColor()
```

एक shape की fill color लौटाता है। केवल पढ़ने योग्य [IColorFormat](../../com.aspose.slides/icolorformat)।

**वापसी:**  
[IColorFormat](../../com.aspose.slides/icolorformat)
### getFillStyleIndex() {#getFillStyleIndex--}
```
public final short getFillStyleIndex()
```

shape के fill column index को style matrices में लौटाता है या सेट करता है। 0 का अर्थ कोई भराव नहीं, सकारात्मक मान - theme की fill styles में index, नकारात्मक मान - theme की background styles में index। पढ़े/लिखे short।

**वापसी:**  
short
### setFillStyleIndex(short value) {#setFillStyleIndex-short-}
```
public final void setFillStyleIndex(short value)
```

shape के fill column index को style matrices में लौटाता है या सेट करता है। 0 का अर्थ कोई भराव नहीं, सकारात्मक मान - theme की fill styles में index, नकारात्मक मान - theme की background styles में index। पढ़े/लिखे short।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | short |  |
### getEffectColor() {#getEffectColor--}
```
public final IColorFormat getEffectColor()
```

एक shape की effect color लौटाता है। केवल पढ़ने योग्य [IColorFormat](../../com.aspose.slides/icolorformat)।

**वापसी:**  
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffectStyleIndex() {#getEffectStyleIndex--}
```
public final long getEffectStyleIndex()
```

shape के effect column index को style matrix में लौटाता है या सेट करता है। पढ़े/लिखे long।

**वापसी:**  
long
### setEffectStyleIndex(long value) {#setEffectStyleIndex-long-}
```
public final void setEffectStyleIndex(long value)
```

shape के effect column index को style matrix में लौटाता है या सेट करता है। पढ़े/लिखे long।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | long |  |
### getFontColor() {#getFontColor--}
```
public final IColorFormat getFontColor()
```

एक shape की font color लौटाता है। केवल पढ़ने योग्य [IColorFormat](../../com.aspose.slides/icolorformat)।

**वापसी:**  
[IColorFormat](../../com.aspose.slides/icolorformat)
### getFontCollectionIndex() {#getFontCollectionIndex--}
```
public final byte getFontCollectionIndex()
```

shape के font index को font collection में लौटाता है या सेट करता है। पढ़े/लिखे [FontCollectionIndex](../../com.aspose.slides/fontcollectionindex)।

**वापसी:**  
byte
### setFontCollectionIndex(byte value) {#setFontCollectionIndex-byte-}
```
public final void setFontCollectionIndex(byte value)
```

shape के font index को font collection में लौटाता है या सेट करता है। पढ़े/लिखे [FontCollectionIndex](../../com.aspose.slides/fontcollectionindex)।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |