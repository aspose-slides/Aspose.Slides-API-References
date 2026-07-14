---
title: IParagraphFormat
second_title: Aspose.Slides for Android via Java API Reference
description: यह क्लास पैराग्राफ फ़ॉर्मेटिंग प्रॉपर्टीज़ रखती है।
type: docs
url: /hi/com.aspose.slides/iparagraphformat/
---```
public interface IParagraphFormat
```

यह क्लास पैराग्राफ फ़ॉर्मेटिंग प्रॉपर्टीज़ रखती है। [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) के विपरीत, इस क्लास की सभी प्रॉपर्टीज़ लिखने योग्य हैं।

--------------------

यह क्लास किसी विशिष्ट पैराग्राफ के लिए परिभाषित पैराग्राफ फ़ॉर्मेटिंग प्रॉपर्टीज़ को लौटाने और संशोधित करने के लिए उपयोग की जाती है। इसका अर्थ है कि मान प्राप्त करने पर कोई विरासत लागू नहीं होती, इसलिए अधिकांश मामलों में आपको "undefined" दर्शाने वाले मान मिलेंगे।

विरासत सहित प्रभावी फ़ॉर्मेटिंग पैरामीटर मान प्राप्त करने के लिए आपको [getEffective](../../com.aspose.slides/iparagraphformat\#getEffective) मेथड का उपयोग करना होगा जो एक [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) इंस्टेंस लौटाता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getBullet()](#getBullet--) | पैराग्राफ के बुलेट फ़ॉर्मेट को लौटाता है। |
| [getDepth()](#getDepth--) | पैराग्राफ की गहराई को लौटाता या सेट करता है। |
| [setDepth(short value)](#setDepth-short-) | पैराग्राफ की गहराई को लौटाता या सेट करता है। |
| [getAlignment()](#getAlignment--) | पैराग्राफ में बिना विरासत के टेक्स्ट संरेखण को लौटाता या सेट करता है। |
| [setAlignment(int value)](#setAlignment-int-) | पैराग्राफ में बिना विरासत के टेक्स्ट संरेखण को लौटाता या सेट करता है। |
| [getSpaceWithin()](#getSpaceWithin--) | पैराग्राफ में आधार रेखाओं के बीच अंतराल की मात्रा को लौटाता या सेट करता है। |
| [setSpaceWithin(float value)](#setSpaceWithin-float-) | पैराग्राफ में आधार रेखाओं के बीच अंतराल की मात्रा को लौटाता या सेट करता है। |
| [getSpaceBefore()](#getSpaceBefore--) | बिना विरासत के पैराग्राफ की पहली पंक्ति से पहले की जगह की मात्रा को लौटाता या सेट करता है। |
| [setSpaceBefore(float value)](#setSpaceBefore-float-) | बिना विरासत के पैराग्राफ की पहली पंक्ति से पहले की जगह की मात्रा को लौटाता या सेट करता है। |
| [getSpaceAfter()](#getSpaceAfter--) | बिना विरासत के पैराग्राफ की अंतिम पंक्ति के बाद की जगह की मात्रा को लौटाता या सेट करता है। |
| [setSpaceAfter(float value)](#setSpaceAfter-float-) | बिना विरासत के पैराग्राफ की अंतिम पंक्ति के बाद की जगह की मात्रा को लौटाता या सेट करता है। |
| [getEastAsianLineBreak()](#getEastAsianLineBreak--) | निर्‍णय करता है कि पैराग्राफ में ईस्ट एशियन लाइन ब्रेक उपयोग किया जाता है या नहीं। |
| [setEastAsianLineBreak(byte value)](#setEastAsianLineBreak-byte-) | निर्‍णय करता है कि पैराग्राफ में ईस्ट एशियन लाइन ब्रेक उपयोग किया जाता है या नहीं। |
| [getRightToLeft()](#getRightToLeft--) | निर्धारित करता है कि पैराग्राफ में दाएँ-से-बाएँ लेखन प्रयोग किया जाता है या नहीं। |
| [setRightToLeft(byte value)](#setRightToLeft-byte-) | निर्धारित करता है कि पैराग्राफ में दाएँ-से-बाएँ लेखन प्रयोग किया जाता है या नहीं। |
| [getLatinLineBreak()](#getLatinLineBreak--) | निर्धारित करता है कि पैराग्राफ में लैटिन लाइन ब्रेक प्रयोग किया जाता है या नहीं। |
| [setLatinLineBreak(byte value)](#setLatinLineBreak-byte-) | निर्धारित करता है कि पैराग्राफ में लैटिन लाइन ब्रेक प्रयोग किया जाता है या नहीं। |
| [getHangingPunctuation()](#getHangingPunctuation--) | निर्धारित करता है कि पैराग्राफ में हैंगिंग पंचुएशन प्रयोग किया जाता है या नहीं। |
| [setHangingPunctuation(byte value)](#setHangingPunctuation-byte-) | निर्धारित करता है कि पैराग्राफ में हैंगिंग पंचुएशन प्रयोग किया जाता है या नहीं। |
| [getMarginLeft()](#getMarginLeft--) | बिना विरासत के पैराग्राफ में बाएँ मार्जिन को लौटाता या सेट करता है। |
| [setMarginLeft(float value)](#setMarginLeft-float-) | बिना विरासत के पैराग्राफ में बाएँ मार्जिन को लौटाता या सेट करता है। |
| [getMarginRight()](#getMarginRight--) | बिना विरासत के पैराग्राफ में दाएँ मार्जिन को लौटाता या सेट करता है। |
| [setMarginRight(float value)](#setMarginRight-float-) | बिना विरासत के पैराग्राफ में दाएँ मार्जिन को लौटाता या सेट करता है। |
| [getIndent()](#getIndent--) | बिना विरासत के पैराग्राफ की पहली पंक्ति इंडेंट/हैंगिंग इंडेंट को लौटाता या सेट करता है। |
| [setIndent(float value)](#setIndent-float-) | बिना विरासत के पैराग्राफ की पहली पंक्ति इंडेंट/हैंगिंग इंडेंट को लौटाता या सेट करता है। |
| [getDefaultTabSize()](#getDefaultTabSize--) | बिना विरासत के डिफ़ॉल्ट टैबुलेशन आकार को लौटाता या सेट करता है। |
| [setDefaultTabSize(float value)](#setDefaultTabSize-float-) | बिना विरासत के डिफ़ॉल्ट टैबुलेशन आकार को लौटाता या सेट करता है। |
| [getTabs()](#getTabs--) | पैराग्राफ की टैबुलेशन को लौटाता है। |
| [getFontAlignment()](#getFontAlignment--) | बिना विरासत के पैराग्राफ में फ़ॉन्ट संरेखण को लौटाता या सेट करता है। |
| [setFontAlignment(int value)](#setFontAlignment-int-) | बिना विरासत के पैराग्राफ में फ़ॉन्ट संरेखण को लौटाता या सेट करता है। |
| [getDefaultPortionFormat()](#getDefaultPortionFormat--) | पैराग्राफ का डिफ़ॉल्ट पोर्शन फ़ॉर्मेट लौटाता है। |
| [getEffective()](#getEffective--) | विरासत लागू होते हुए प्रभावी पैराग्राफ फ़ॉर्मेटिंग डेटा प्राप्त करता है। |

### getBullet() {#getBullet--}
```
public abstract IBulletFormat getBullet()
```

पैराग्राफ के बुलेट फ़ॉर्मेट को लौटाता है। केवल-पढ़ने योग्य [IBulletFormat](../../com.aspose.slides/ibulletformat).

**रिटर्न:**
[IBulletFormat](../../com.aspose.slides/ibulletformat)

### getDepth() {#getDepth--}
```
public abstract short getDepth()
```

पैराग्राफ की गहराई को लौटाता या सेट करता है। मान 0 अपरिभाषित मान को दर्शाता है। पढ़ने/लिखने योग्य शॉर्ट।

**रिटर्न:**
short

### setDepth(short value) {#setDepth-short-}
```
public abstract void setDepth(short value)
```

पैराग्राफ की गहराई को लौटाता या सेट करता है। मान 0 अपरिभाषित मान को दर्शाता है। पढ़ने/लिखने योग्य शॉर्ट।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | short |  |

### getAlignment() {#getAlignment--}
```
public abstract int getAlignment()
```

बिना विरासत के पैराग्राफ में टेक्स्ट संरेखण को लौटाता या सेट करता है। पढ़ने/लिखने योग्य [TextAlignment](../../com.aspose.slides/textalignment)।

**रिटर्न:**
int

### setAlignment(int value) {#setAlignment-int-}
```
public abstract void setAlignment(int value)
```

बिना विरासत के पैराग्राफ में टेक्स्ट संरेखण को लौटाता या सेट करता है। पढ़ने/लिखने योग्य [TextAlignment](../../com.aspose.slides/textalignment)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getSpaceWithin() {#getSpaceWithin--}
```
public abstract float getSpaceWithin()
```

बिना विरासत के पैराग्राफ में आधार रेखाओं के बीच अंतराल की मात्रा को लौटाता या सेट करता है। सकारात्मक मान प्रतिशत दर्शाता है, नकारात्मक मान बिंदु में आकार। पढ़ने/लिखने योग्य फ़्लोट।

**रिटर्न:**
float

### setSpaceWithin(float value) {#setSpaceWithin-float-}
```
public abstract void setSpaceWithin(float value)
```

बिना विरासत के पैराग्राफ में आधार रेखाओं के बीच अंतराल की मात्रा को लौटाता या सेट करता है। सकारात्मक मान प्रतिशत दर्शाता है, नकारात्मक मान बिंदु में आकार। पढ़ने/लिखने योग्य फ़्लोट।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### getSpaceBefore() {#getSpaceBefore--}
```
public abstract float getSpaceBefore()
```

बिना विरासत के पैराग्राफ की पहली पंक्ति से पहले की जगह की मात्रा को लौटाता या सेट करता है। सकारात्मक मान फ़ॉन्ट आकार के प्रतिशत को दर्शाता है, नकारात्मक मान बिंदु में आकार। पढ़ने/लिखने योग्य फ़्लोट।

**रिटर्न:**
float

### setSpaceBefore(float value) {#setSpaceBefore-float-}
```
public abstract void setSpaceBefore(float value)
```

बिना विरासत के पैराग्राफ की पहली पंक्ति से पहले की जगह की मात्रा को लौटाता या सेट करता है। सकारात्मक मान फ़ॉन्ट आकार के प्रतिशत को दर्शाता है, नकारात्मक मान बिंदु में आकार। पढ़ने/लिखने योग्य फ़्लोट।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### getSpaceAfter() {#getSpaceAfter--}
```
public abstract float getSpaceAfter()
```

बिना विरासत के पैराग्राफ की अंतिम पंक्ति के बाद की जगह की मात्रा को लौटाता या सेट करता है। सकारात्मक मान फ़ॉन्ट आकार के प्रतिशत को दर्शाता है, नकारात्मक मान बिंदु में आकार। पढ़ने/लिखने योग्य फ़्लोट।

**रिटर्न:**
float

### setSpaceAfter(float value) {#setSpaceAfter-float-}
```
public abstract void setSpaceAfter(float value)
```

बिना विरासत के पैराग्राफ की अंतिम पंक्ति के बाद की जगह की मात्रा को लौटाता या सेट करता है। सकारात्मक मान फ़ॉन्ट आकार के प्रतिशत को दर्शाता है, नकारात्मक मान बिंदु में आकार। पढ़ने/लिखने योग्य फ़्लोट।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### getEastAsianLineBreak() {#getEastAsianLineBreak--}
```
public abstract byte getEastAsianLineBreak()
```

निर्धारित करता है कि पैराग्राफ में ईस्ट एशियन लाइन ब्रेक उपयोग किया जाता है या नहीं। कोई विरासत लागू नहीं। पढ़ने/लिखने योग्य [NullableBool](../../com.aspose.slides/nullablebool)।

**रिटर्न:**
byte

### setEastAsianLineBreak(byte value) {#setEastAsianLineBreak-byte-}
```
public abstract void setEastAsianLineBreak(byte value)
```

निर्धारित करता है कि पैराग्राफ में ईस्ट एशियन लाइन ब्रेक उपयोग किया जाता है या नहीं। कोई विरासत लागू नहीं। पढ़ने/लिखने योग्य [NullableBool](../../com.aspose.slides/nullablebool)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |

### getRightToLeft() {#getRightToLeft--}
```
public abstract byte getRightToLeft()
```

निर्धारित करता है कि पैराग्राफ में दाएँ-से-बाएँ लेखन प्रयोग किया जाता है या नहीं। कोई विरासत लागू नहीं। पढ़ने/लिखने योग्य [NullableBool](../../com.aspose.slides/nullablebool)।

**रिटर्न:**
byte

### setRightToLeft(byte value) {#setRightToLeft-byte-}
```
public abstract void setRightToLeft(byte value)
```

निर्धारित करता है कि पैराग्राफ में दाएँ-से-बाएँ लेखन प्रयोग किया जाता है या नहीं। कोई विरासत लागू नहीं। पढ़ने/लिखने योग्य [NullableBool](../../com.aspose.slides/nullablebool)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |

### getLatinLineBreak() {#getLatinLineBreak--}
```
public abstract byte getLatinLineBreak()
```

निर्धारित करता है कि पैराग्राफ में लैटिन लाइन ब्रेक प्रयोग किया जाता है या नहीं। कोई विरासत लागू नहीं। पढ़ने/लिखने योग्य [NullableBool](../../com.aspose.slides/nullablebool)।

**रिटर्न:**
byte

### setLatinLineBreak(byte value) {#setLatinLineBreak-byte-}
```
public abstract void setLatinLineBreak(byte value)
```

निर्धारित करता है कि पैराग्राफ में लैटिन लाइन ब्रेक प्रयोग किया जाता है या नहीं। कोई विरासत लागू नहीं। पढ़ने/लिखने योग्य [NullableBool](../../com.aspose.slides/nullablebool)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |

### getHangingPunctuation() {#getHangingPunctuation--}
```
public abstract byte getHangingPunctuation()
```

निर्धारित करता है कि पैराग्राफ में हैंगिंग पंचुएशन प्रयोग किया जाता है या नहीं। कोई विरासत लागू नहीं। पढ़ने/लिखने योग्य [NullableBool](../../com.aspose.slides/nullablebool)।

**रिटर्न:**
byte

### setHangingPunctuation(byte value) {#setHangingPunctuation-byte-}
```
public abstract void setHangingPunctuation(byte value)
```

निर्धारित करता है कि पैराग्राफ में हैंगिंग पंचुएशन प्रयोग किया जाता है या नहीं। कोई विरासत लागू नहीं। पढ़ने/लिखने योग्य [NullableBool](../../com.aspose.slides/nullablebool)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |

### getMarginLeft() {#getMarginLeft--}
```
public abstract float getMarginLeft()
```

बिना विरासत के पैराग्राफ में बाएँ मार्जिन को लौटाता या सेट करता है। पढ़ने/लिखने योग्य फ़्लोट।

**रिटर्न:**
float

### setMarginLeft(float value) {#setMarginLeft-float-}
```
public abstract void setMarginLeft(float value)
```

बिना विरासत के पैराग्राफ में बाएँ मार्जिन को लौटाता या सेट करता है। पढ़ने/लिखने योग्य फ़्लोट।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### getMarginRight() {#getMarginRight--}
```
public abstract float getMarginRight()
```

बिना विरासत के पैराग्राफ में दाएँ मार्जिन को लौटाता या सेट करता है। पढ़ने/लिखने योग्य फ़्लोट।

**रिटर्न:**
float

### setMarginRight(float value) {#setMarginRight-float-}
```
public abstract void setMarginRight(float value)
```

बिना विरासत के पैराग्राफ में दाएँ मार्जिन को लौटाता या सेट करता है। पढ़ने/लिखने योग्य फ़्लोट।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### getIndent() {#getIndent--}
```
public abstract float getIndent()
```

बिना विरासत के पैराग्राफ की पहली पंक्ति इंडेंट/हैंगिंग इंडेंट को लौटाता या सेट करता है। हैंगिंग इंडेंट नकारात्मक मानों से परिभाषित किया जा सकता है। पढ़ने/लिखने योग्य फ़्लोट।

**रिटर्न:**
float

### setIndent(float value) {#setIndent-float-}
```
public abstract void setIndent(float value)
```

बिना विरासत के पैराग्राफ की पहली पंक्ति इंडेंट/हैंगिंग इंडेंट को लौटाता या सेट करता है। हैंगिंग इंडेंट नकारात्मक मानों से परिभाषित किया जा सकता है। पढ़ने/लिखने योग्य फ़्लोट।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### getDefaultTabSize() {#getDefaultTabSize--}
```
public abstract float getDefaultTabSize()
```

बिना विरासत के डिफ़ॉल्ट टैबुलेशन आकार को लौटाता या सेट करता है। पढ़ने/लिखने योग्य फ़्लोट।

**रिटर्न:**
float

### setDefaultTabSize(float value) {#setDefaultTabSize-float-}
```
public abstract void setDefaultTabSize(float value)
```

बिना विरासत के डिफ़ॉल्ट टैबुलेशन आकार को लौटाता या सेट करता है। पढ़ने/लिखने योग्य फ़्लोट।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### getTabs() {#getTabs--}
```
public abstract ITabCollection getTabs()
```

पैराग्राफ की टैबुलेशन को लौटाता है। कोई विरासत लागू नहीं। केवल-पढ़ने योग्य [ITabCollection](../../com.aspose.slides/itabcollection)।

**रिटर्न:**
[ITabCollection](../../com.aspose.slides/itabcollection)

### getFontAlignment() {#getFontAlignment--}
```
public abstract int getFontAlignment()
```

बिना विरासत के पैराग्राफ में फ़ॉन्ट संरेखण को लौटाता या सेट करता है। पढ़ने/लिखने योग्य [FontAlignment](../../com.aspose.slides/fontalignment)।

**रिटर्न:**
int

### setFontAlignment(int value) {#setFontAlignment-int-}
```
public abstract void setFontAlignment(int value)
```

बिना विरासत के पैराग्राफ में फ़ॉन्ट संरेखण को लौटाता या सेट करता है। पढ़ने/लिखने योग्य [FontAlignment](../../com.aspose.slides/fontalignment)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getDefaultPortionFormat() {#getDefaultPortionFormat--}
```
public abstract IPortionFormat getDefaultPortionFormat()
```

डिफ़ॉल्ट पोर्शन फ़ॉर्मेट को लौटाता है। कोई विरासत लागू नहीं। केवल-पढ़ने योग्य [IPortionFormat](../../com.aspose.slides/iportionformat)।

**रिटर्न:**
[IPortionFormat](../../com.aspose.slides/iportionformat)

### getEffective() {#getEffective--}
```
public abstract IParagraphFormatEffectiveData getEffective()
```

विरासत लागू होते हुए प्रभावी पैराग्राफ फ़ॉर्मेटिंग डेटा प्राप्त करता है।

**रिटर्न:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) - A [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).