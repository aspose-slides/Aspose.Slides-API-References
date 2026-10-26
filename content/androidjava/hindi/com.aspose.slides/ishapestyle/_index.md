---
title: IShapeStyle
second_title: Aspose.Slides for Android via Java API Reference
description: Represent shapes style reference.
type: docs
url: /hi/com.aspose.slides/ishapestyle/
---```
public interface IShapeStyle
```

आकार की शैली संदर्भ प्रस्तुत करता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getLineColor()](#getLineColor--) | एक आकार का आउटलाइन रंग लौटाता है। |
| [getLineStyleIndex()](#getLineStyleIndex--) | शैली मैट्रिक्स में लाइन के कॉलम इंडेक्स को लौटाता है या सेट करता है। |
| [setLineStyleIndex(int value)](#setLineStyleIndex-int-) | शैली मैट्रिक्स में लाइन के कॉलम इंडेक्स को लौटाता है या सेट करता है। |
| [getFillColor()](#getFillColor--) | एक आकार का फ़िल रंग लौटाता है। |
| [getFillStyleIndex()](#getFillStyleIndex--) | शैली मैट्रिक्स में आकार के फ़िल कॉलम इंडेक्स को लौटाता है या सेट करता है। |
| [setFillStyleIndex(short value)](#setFillStyleIndex-short-) | शैली मैट्रिक्स में आकार के फ़िल कॉलम इंडेक्स को लौटाता है या सेट करता है। |
| [getEffectColor()](#getEffectColor--) | एक आकार का इफ़ेक्ट रंग लौटाता है। |
| [getEffectStyleIndex()](#getEffectStyleIndex--) | शैली मैट्रिक्स में आकार के इफ़ेक्ट कॉलम इंडेक्स को लौटाता है या सेट करता है। |
| [setEffectStyleIndex(long value)](#setEffectStyleIndex-long-) | शैली मैट्रिक्स में आकार के इफ़ेक्ट कॉलम इंडेक्स को लौटाता है या सेट करता है। |
| [getFontColor()](#getFontColor--) | एक आकार का फ़ॉन्ट रंग लौटाता है। |
| [getFontCollectionIndex()](#getFontCollectionIndex--) | फ़ॉन्ट संग्रह में आकार के फ़ॉन्ट इंडेक्स को लौटाता है या सेट करता है। |
| [setFontCollectionIndex(byte value)](#setFontCollectionIndex-byte-) | फ़ॉन्ट संग्रह में आकार के फ़ॉन्ट इंडेक्स को लौटाता है या सेट करता है। |
### getLineColor() {#getLineColor--}
```
public abstract IColorFormat getLineColor()
```


एक आकार का आउटलाइन रंग लौटाता है। केवल-पढ़ने योग्य [IColorFormat](../../com.aspose.slides/icolorformat).

**रिटर्न:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getLineStyleIndex() {#getLineStyleIndex--}
```
public abstract int getLineStyleIndex()
```


शैली मैट्रिक्स में लाइन के कॉलम इंडेक्स को लौटाता है या सेट करता है। पढ़ने-और-लिखने योग्य int।

**रिटर्न:**
int
### setLineStyleIndex(int value) {#setLineStyleIndex-int-}
```
public abstract void setLineStyleIndex(int value)
```


शैली मैट्रिक्स में लाइन के कॉलम इंडेक्स को लौटाता है या सेट करता है। पढ़ने-और-लिखने योग्य int।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getFillColor() {#getFillColor--}
```
public abstract IColorFormat getFillColor()
```


एक आकार का फ़िल रंग लौटाता है। केवल-पढ़ने योग्य [IColorFormat](../../com.aspose.slides/icolorformat).

**रिटर्न:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getFillStyleIndex() {#getFillStyleIndex--}
```
public abstract short getFillStyleIndex()
```


शैली मैट्रिक्स में आकार के फ़िल कॉलम इंडेक्स को लौटाता है या सेट करता है। 0 का अर्थ कोई फ़िल नहीं, सकारात्मक मान – थीम के फ़िल शैलियों में इंडेक्स, नकारात्मक मान – थीम की बैकग्राउंड शैलियों में इंडेक्स। पढ़ने-और-लिखने योग्य short।

**रिटर्न:**
short
### setFillStyleIndex(short value) {#setFillStyleIndex-short-}
```
public abstract void setFillStyleIndex(short value)
```


शैली मैट्रिक्स में आकार के फ़िल कॉलम इंडेक्स को लौटाता है या सेट करता है। 0 का अर्थ कोई फ़िल नहीं, सकारात्मक मान – थीम के फ़िल शैलियों में इंडेक्स, नकारात्मक मान – थीम की बैकग्राउंड शैलियों में इंडेक्स। पढ़ने-और-लिखने योग्य short।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | short |  |

### getEffectColor() {#getEffectColor--}
```
public abstract IColorFormat getEffectColor()
```


एक आकार का इफ़ेक्ट रंग लौटाता है। केवल-पढ़ने योग्य [IColorFormat](../../com.aspose.slides/icolorformat).

**रिटर्न:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffectStyleIndex() {#getEffectStyleIndex--}
```
public abstract long getEffectStyleIndex()
```


शैली मैट्रिक्स में आकार के इफ़ेक्ट कॉलम इंडेक्स को लौटाता है या सेट करता है। पढ़ने-और-लिखने योग्य long।

**रिटर्न:**
long
### setEffectStyleIndex(long value) {#setEffectStyleIndex-long-}
```
public abstract void setEffectStyleIndex(long value)
```


शैली मैट्रिक्स में आकार के इफ़ेक्ट कॉलम इंडेक्स को लौटाता है या सेट करता है। पढ़ने-और-लिखने योग्य long।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | long |  |

### getFontColor() {#getFontColor--}
```
public abstract IColorFormat getFontColor()
```


एक आकार का फ़ॉन्ट रंग लौटाता है। केवल-पढ़ने योग्य [IColorFormat](../../com.aspose.slides/icolorformat).

**रिटर्न:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getFontCollectionIndex() {#getFontCollectionIndex--}
```
public abstract byte getFontCollectionIndex()
```


फ़ॉन्ट संग्रह में आकार के फ़ॉन्ट इंडेक्स को लौटाता है या सेट करता है। पढ़ने-और-लिखने योग्य [FontCollectionIndex](../../com.aspose.slides/fontcollectionindex)।

**रिटर्न:**
byte
### setFontCollectionIndex(byte value) {#setFontCollectionIndex-byte-}
```
public abstract void setFontCollectionIndex(byte value)
```


फ़ॉन्ट संग्रह में आकार के फ़ॉन्ट इंडेक्स को लौटाता है या सेट करता है। पढ़ने-और-लिखने योग्य [FontCollectionIndex](../../com.aspose.slides/fontcollectionindex)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |