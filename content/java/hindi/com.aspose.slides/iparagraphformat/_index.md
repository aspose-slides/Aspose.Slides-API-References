---
title: IParagraphFormat
second_title: Aspose.Slides for Java API Reference
description: यह वर्ग पैराग्राफ़ फ़ॉर्मेटिंग गुणधर्मों को सम्मिलित करता है।
type: docs
url: /hi/com.aspose.slides/iparagraphformat/
---```
public interface IParagraphFormat
```

यह वर्ग पैराग्राफ़ फ़ॉर्मेटिंग गुणधर्मों को सम्मिलित करता है। [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) के विपरीत, इस वर्ग की सभी गुणधर्म लिखने योग्य हैं।

--------------------

यह वर्ग किसी विशिष्ट पैराग्राफ़ के लिए परिभाषित पैराग्राफ़ फ़ॉर्मेटिंग गुणधर्मों को लौटाने और हेर-फ़ेर करने के लिये उपयोग किया जाता है। इसका अर्थ है कि मान प्राप्त करते समय कोई विरासत लागू नहीं होती, इसलिए अधिकांश मामलों में आपको "अपरिभाषित" मान प्राप्त होंगे।

विरासतित सहित प्रभावी फ़ॉर्मेटिंग पैरामीटर मान प्राप्त करने के लिये आपको [getEffective](../../com.aspose.slides/iparagraphformat\#getEffective) मेथड का प्रयोग करना होगा जो एक [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) इंस्टेंस वापस करता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getBullet()](#getBullet--) | पैराग्राफ़ का बुलेट फ़ॉर्मेट लौटाता है। |
| [getDepth()](#getDepth--) | पैराग्राफ़ की गहराई लौटाता है या सेट करता है। |
| [setDepth(short value)](#setDepth-short-) | पैराग्राफ़ की गहराई लौटाता है या सेट करता है। |
| [getAlignment()](#getAlignment--) | पैराग्राफ़ में टेक्स्ट संरेखण लौटाता है या सेट करता है (कोई विरासत नहीं)। |
| [setAlignment(int value)](#setAlignment-int-) | पैराग्राफ़ में टेक्स्ट संरेखण लौटाता है या सेट करता है (कोई विरासत नहीं)। |
| [getSpaceWithin()](#getSpaceWithin--) | पैराग्राफ़ में बेस लाइनों के बीच स्थान लौटाता है या सेट करता है। |
| [setSpaceWithin(float value)](#setSpaceWithin-float-) | पैराग्राफ़ में बेस लाइनों के बीच स्थान लौटाता है या सेट करता है। |
| [getSpaceBefore()](#getSpaceBefore--) | पैराग्राफ़ में पहली लाइन से पहले स्थान लौटाता है या सेट करता है (कोई विरासत नहीं)। |
| [setSpaceBefore(float value)](#setSpaceBefore-float-) | पैराग्राफ़ में पहली लाइन से पहले स्थान लौटाता है या सेट करता है (कोई विरासत नहीं)। |
| [getSpaceAfter()](#getSpaceAfter--) | पैराग्राफ़ में अंतिम लाइन के बाद स्थान लौटाता है या सेट करता है (कोई विरासत नहीं)। |
| [setSpaceAfter(float value)](#setSpaceAfter-float-) | पैराग्राफ़ में अंतिम लाइन के बाद स्थान लौटाता है या सेट करता है (कोई विरासत नहीं)। |
| [getEastAsianLineBreak()](#getEastAsianLineBreak--) | निर्धारित करता है कि पैराग्राफ़ में ईस्ट एशियन लाइन ब्रेक प्रयोग किया जाता है या नहीं। |
| [setEastAsianLineBreak(byte value)](#setEastAsianLineBreak-byte-) | निर्धारित करता है कि पैराग्राफ़ में ईस्ट एशियन लाइन ब्रेक प्रयोग किया जाता है या नहीं। |
| [getRightToLeft()](#getRightToLeft--) | निर्धारित करता है कि पैराग्राफ़ में राइट-टू-लेफ्ट लेखन प्रयोग किया जाता है या नहीं। |
| [setRightToLeft(byte value)](#setRightToLeft-byte-) | निर्धारित करता है कि पैराग्राफ़ में राइट-टू-लेफ्ट लेखन प्रयोग किया जाता है या नहीं। |
| [getLatinLineBreak()](#getLatinLineBreak--) | निर्धारित करता है कि पैराग्राफ़ में लैटिन लाइन ब्रेक प्रयोग किया जाता है या नहीं। |
| [setLatinLineBreak(byte value)](#setLatinLineBreak-byte-) | निर्धारित करता है कि पैराग्राफ़ में लैटिन लाइन ब्रेक प्रयोग किया जाता है या नहीं। |
| [getHangingPunctuation()](#getHangingPunctuation--) | निर्धारित करता है कि पैराग्राफ़ में हैंगिंग पंचुएशन प्रयोग किया जाता है या नहीं। |
| [setHangingPunctuation(byte value)](#setHangingPunctuation-byte-) | निर्धारित करता है कि पैराग्राफ़ में हैंगिंग पंचुएशन प्रयोग किया जाता है या नहीं। |
| [getMarginLeft()](#getMarginLeft--) | पैराग्राफ़ में बाएँ मार्जिन को लौटाता है या सेट करता है (कोई विरासत नहीं)। |
| [setMarginLeft(float value)](#setMarginLeft-float-) | पैराग्राफ़ में बाएँ मार्जिन को लौटाता है या सेट करता है (कोई विरासत नहीं)। |
| [getMarginRight()](#getMarginRight--) | पैराग्राफ़ में दाएँ मार्जिन को लौटाता है या सेट करता है (कोई विरासत नहीं)। |
| [setMarginRight(float value)](#setMarginRight-float-) | पैराग्राफ़ में दाएँ मार्जिन को लौटाता है या सेट करता है (कोई विरासत नहीं)। |
| [getIndent()](#getIndent--) | पैराग्राफ़ की पहली लाइन का इंडेंट/हैंगिंग इंडेंट लौटाता है या सेट करता है (कोई विरासत नहीं)। |
| [setIndent(float value)](#setIndent-float-) | पैराग्राफ़ की पहली लाइन का इंडेंट/हैंगिंग इंडेंट लौटाता है या सेट करता है (कोई विरासत नहीं)। |
| [getDefaultTabSize()](#getDefaultTabSize--) | डिफ़ॉल्ट टैबुलेशन आकार को लौटाता है या सेट करता है (कोई विरासत नहीं)। |
| [setDefaultTabSize(float value)](#setDefaultTabSize-float-) | डिफ़ॉल्ट टैबुलेशन आकार को लौटाता है या सेट करता है (कोई विरासत नहीं)। |
| [getTabs()](#getTabs--) | पैराग्राफ़ की टैबुलेशन को लौटाता है। |
| [getFontAlignment()](#getFontAlignment--) | पैराग्राफ़ में फ़ॉन्ट संरेखण को लौटाता है या सेट करता है (कोई विरासत नहीं)। |
| [setFontAlignment(int value)](#setFontAlignment-int-) | पैराग्राफ़ में फ़ॉन्ट संरेखण को लौटाता है या सेट करता है (कोई विरासत नहीं)। |
| [getDefaultPortionFormat()](#getDefaultPortionFormat--) | पैराग्राफ़ का डिफ़ॉल्ट पोर्शन फ़ॉर्मेट लौटाता है। |
| [getEffective()](#getEffective--) | विरासत लागू करके प्रभावी पैराग्राफ़ फ़ॉर्मेटिंग डेटा प्राप्त करता है। |

### getBullet() {#getBullet--}
```
public abstract IBulletFormat getBullet()
```

पैराग्राफ़ का बुलेट फ़ॉर्मेट लौटाता है। केवल-पढ़ने योग्य [IBulletFormat](../../com.aspose.slides/ibulletformat)।

**Returns:**
[IBulletFormat](../../com.aspose.slides/ibulletformat)

### getDepth() {#getDepth--}
```
public abstract short getDepth()
```

पैराग्राफ़ की गहराई लौटाता है या सेट करता है। मान 0 का अर्थ अपरिभाषित है। पढ़ने/लिखने योग्य शॉर्ट।

**Returns:**
short

### setDepth(short value) {#setDepth-short-}
```
public abstract void setDepth(short value)
```

पैराग्राफ़ की गहराई लौटाता है या सेट करता है। मान 0 का अर्थ अपरिभाषित है। पढ़ने/लिखने योग्य शॉर्ट।

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short |  |

### getAlignment() {#getAlignment--}
```
public abstract int getAlignment()
```

पैराग्राफ़ में टेक्स्ट संरेखण लौटाता है या सेट करता है (कोई विरासत नहीं)। पढ़ने/लिखने योग्य [TextAlignment](../../com.aspose.slides/textalignment)।

**Returns:**
int

### setAlignment(int value) {#setAlignment-int-}
```
public abstract void setAlignment(int value)
```

पैराग्राफ़ में टेक्स्ट संरेखण लौटाता है या सेट करता है (कोई विरासत नहीं)। पढ़ने/लिखने योग्य [TextAlignment](../../com.aspose.slides/textalignment)।

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSpaceWithin() {#getSpaceWithin--}
```
public abstract float getSpaceWithin()
```

पैराग्राफ़ में बेस लाइनों के बीच स्थान लौटाता है या सेट करता है। सकारात्मक मान प्रतिशत दर्शाता है, नकारात्मक मान पॉइंट आकार। कोई विरासत नहीं लागू। पढ़ने/लिखने योग्य फ़्लोट।

**Returns:**
float

### setSpaceWithin(float value) {#setSpaceWithin-float-}
```
public abstract void setSpaceWithin(float value)
```

पैराग्राफ़ में बेस लाइनों के बीच स्थान लौटाता है या सेट करता है। सकारात्मक मान प्रतिशत दर्शाता है, नकारात्मक मान पॉइंट आकार। कोई विरासत नहीं लागू। पढ़ने/लिखने योग्य फ़्लोट।

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getSpaceBefore() {#getSpaceBefore--}
```
public abstract float getSpaceBefore()
```

पैराग्राफ़ में पहली लाइन से पहले स्थान लौटाता है या सेट करता है (कोई विरासत नहीं)। सकारात्मक मान फ़ॉन्ट आकार का प्रतिशत दर्शाता है, नकारात्मक मान पॉइंट आकार। पढ़ने/लिखने योग्य फ़्लोट।

**Returns:**
float

### setSpaceBefore(float value) {#setSpaceBefore-float-}
```
public abstract void setSpaceBefore(float value)
```

पैराग्राफ़ में पहली लाइन से पहले स्थान लौटाता है या सेट करता है (कोई विरासत नहीं)। सकारात्मक मान फ़ॉन्ट आकार का प्रतिशत दर्शाता है, नकारात्मक मान पॉइंट आकार। पढ़ने/लिखने योग्य फ़्लोट।

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getSpaceAfter() {#getSpaceAfter--}
```
public abstract float getSpaceAfter()
```

पैराग्राफ़ में अंतिम लाइन के बाद स्थान लौटाता है या सेट करता है (कोई विरासत नहीं)। सकारात्मक मान फ़ॉन्ट आकार का प्रतिशत दर्शाता है, नकारात्मक मान पॉइंट आकार। पढ़ने/लिखने योग्य फ़्लोट।

**Returns:**
float

### setSpaceAfter(float value) {#setSpaceAfter-float-}
```
public abstract void setSpaceAfter(float value)
```

पैराग्राफ़ में अंतिम लाइन के बाद स्थान लौटाता है या सेट करता है (कोई विरासत नहीं)। सकारात्मक मान फ़ॉन्ट आकार का प्रतिशत दर्शाता है, नकारात्मक मान पॉइंट आकार। पढ़ने/लिखने योग्य फ़्लोट।

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getEastAsianLineBreak() {#getEastAsianLineBreak--}
```
public abstract byte getEastAsianLineBreak()
```

निर्धारित करता है कि पैराग्राफ़ में ईस्ट एशियन लाइन ब्रेक प्रयोग किया जाता है या नहीं। कोई विरासत नहीं लागू। पढ़ने/लिखने योग्य [NullableBool](../../com.aspose.slides/nullablebool)।

**Returns:**
byte

### setEastAsianLineBreak(byte value) {#setEastAsianLineBreak-byte-}
```
public abstract void setEastAsianLineBreak(byte value)
```

निर्धारित करता है कि पैराग्राफ़ में ईस्ट एशियन लाइन ब्रेक प्रयोग किया जाता है या नहीं। कोई विरासत नहीं लागू। पढ़ने/लिखने योग्य [NullableBool](../../com.aspose.slides/nullablebool)।

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getRightToLeft() {#getRightToLeft--}
```
public abstract byte getRightToLeft()
```

निर्धारित करता है कि पैराग्राफ़ में राइट-टू-लेफ्ट लेखन प्रयोग किया जाता है या नहीं। कोई विरासत नहीं लागू। पढ़ने/लिखने योग्य [NullableBool](../../com.aspose.slides/nullablebool)।

**Returns:**
byte

### setRightToLeft(byte value) {#setRightToLeft-byte-}
```
public abstract void setRightToLeft(byte value)
```

निर्धारित करता है कि पैराग्राफ़ में राइट-टू-लेफ्ट लेखन प्रयोग किया जाता है या नहीं। कोई विरासत नहीं लागू। पढ़ने/लिखने योग्य [NullableBool](../../com.aspose.slides/nullablebool)।

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getLatinLineBreak() {#getLatinLineBreak--}
```
public abstract byte getLatinLineBreak()
```

निर्धारित करता है कि पैराग्राफ़ में लैटिन लाइन ब्रेक प्रयोग किया जाता है या नहीं। कोई विरासत नहीं लागू। पढ़ने/लिखने योग्य [NullableBool](../../com.aspose.slides/nullablebool)।

**Returns:**
byte

### setLatinLineBreak(byte value) {#setLatinLineBreak-byte-}
```
public abstract void setLatinLineBreak(byte value)
```

निर्धारित करता है कि पैराग्राफ़ में लैटिन लाइन ब्रेक प्रयोग किया जाता है या नहीं। कोई विरासत नहीं लागू। पढ़ने/लिखने योग्य [NullableBool](../../com.aspose.slides/nullablebool)।

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getHangingPunctuation() {#getHangingPunctuation--}
```
public abstract byte getHangingPunctuation()
```

निर्धारित करता है कि पैराग्राफ़ में हैंगिंग पंचुएशन प्रयोग किया जाता है या नहीं। कोई विरासत नहीं लागू। पढ़ने/लिखने योग्य [NullableBool](../../com.aspose.slides/nullablebool)।

**Returns:**
byte

### setHangingPunctuation(byte value) {#setHangingPunctuation-byte-}
```
public abstract void setHangingPunctuation(byte value)
```

निर्धारित करता है कि पैराग्राफ़ में हैंगिंग पंचुएशन प्रयोग किया जाता है या नहीं। कोई विरासत नहीं लागू। पढ़ने/लिखने योग्य [NullableBool](../../com.aspose.slides/nullablebool)।

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getMarginLeft() {#getMarginLeft--}
```
public abstract float getMarginLeft()
```

पैराग्राफ़ में बाएँ मार्जिन को लौटाता है या सेट करता है (कोई विरासत नहीं)। पढ़ने/लिखने योग्य फ़्लोट।

**Returns:**
float

### setMarginLeft(float value) {#setMarginLeft-float-}
```
public abstract void setMarginLeft(float value)
```

पैराग्राफ़ में बाएँ मार्जिन को लौटाता है या सेट करता है (कोई विरासत नहीं)। पढ़ने/लिखने योग्य फ़्लोट।

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getMarginRight() {#getMarginRight--}
```
public abstract float getMarginRight()
```

पैराग्राफ़ में दाएँ मार्जिन को लौटाता है या सेट करता है (कोई विरासत नहीं)। पढ़ने/लिखने योग्य फ़्लोट।

**Returns:**
float

### setMarginRight(float value) {#setMarginRight-float-}
```
public abstract void setMarginRight(float value)
```

पैराग्राफ़ में दाएँ मार्जिन को लौटाता है या सेट करता है (कोई विरासत नहीं)। पढ़ने/लिखने योग्य फ़्लोट।

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getIndent() {#getIndent--}
```
public abstract float getIndent()
```

पैराग्राफ़ की पहली लाइन का इंडेंट/हैंगिंग इंडेंट लौटाता है या सेट करता है (कोई विरासत नहीं)। हैंगिंग इंडेंट नकारात्मक मान से परिभाषित किया जा सकता है। पढ़ने/लिखने योग्य फ़्लोट।

**Returns:**
float

### setIndent(float value) {#setIndent-float-}
```
public abstract void setIndent(float value)
```

पैराग्राफ़ की पहली लाइन का इंडेंट/हैंगिंग इंडेंट लौटाता है या सेट करता है (कोई विरासत नहीं)। हैंगिंग इंडेंट नकारात्मक मान से परिभाषित किया जा सकता है। पढ़ने/लिखने योग्य फ़्लोट।

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getDefaultTabSize() {#getDefaultTabSize--}
```
public abstract float getDefaultTabSize()
```

डिफ़ॉल्ट टैबुलेशन आकार को लौटाता है या सेट करता है (कोई विरासत नहीं)। पढ़ने/लिखने योग्य फ़्लोट।

**Returns:**
float

### setDefaultTabSize(float value) {#setDefaultTabSize-float-}
```
public abstract void setDefaultTabSize(float value)
```

डिफ़ॉल्ट टैबुलेशन आकार को लौटाता है या सेट करता है (कोई विरासत नहीं)। पढ़ने/लिखने योग्य फ़्लोट।

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getTabs() {#getTabs--}
```
public abstract ITabCollection getTabs()
```

पैराग्राफ़ की टैबुलेशन को लौटाता है। कोई विरासत नहीं लागू। केवल-पढ़ने योग्य [ITabCollection](../../com.aspose.slides/itabcollection)।

**Returns:**
[ITabCollection](../../com.aspose.slides/itabcollection)

### getFontAlignment() {#getFontAlignment--}
```
public abstract int getFontAlignment()
```

पैराग्राफ़ में फ़ॉन्ट संरेखण को लौटाता है या सेट करता है (कोई विरासत नहीं)। पढ़ने/लिखने योग्य [FontAlignment](../../com.aspose.slides/fontalignment)।

**Returns:**
int

### setFontAlignment(int value) {#setFontAlignment-int-}
```
public abstract void setFontAlignment(int value)
```

पैराग्राफ़ में फ़ॉन्ट संरेखण को लौटाता है या सेट करता है (कोई विरासत नहीं)। पढ़ने/लिखने योग्य [FontAlignment](../../com.aspose.slides/fontalignment)।

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getDefaultPortionFormat() {#getDefaultPortionFormat--}
```
public abstract IPortionFormat getDefaultPortionFormat()
```

पैराग्राफ़ का डिफ़ॉल्ट पोर्शन फ़ॉर्मेट लौटाता है। कोई विरासत नहीं लागू। केवल-पढ़ने योग्य [IPortionFormat](../../com.aspose.slides/iportionformat)।

**Returns:**
[IPortionFormat](../../com.aspose.slides/iportionformat)

### getEffective() {#getEffective--}
```
public abstract IParagraphFormatEffectiveData getEffective()
```

विरासत लागू करके प्रभावी पैराग्राफ़ फ़ॉर्मेटिंग डेटा प्राप्त करता है।

**Returns:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) - A [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).