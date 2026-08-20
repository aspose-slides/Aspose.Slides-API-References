---
title: IParagraphFormatEffectiveData
second_title: Aspose.Slides for Java API Reference
description: अपरिवर्तनीय वस्तु जो प्रभावी पैराग्राफ़ फ़ॉर्मेटिंग गुणों को शामिल करती है।
type: docs
url: /hi/com.aspose.slides/iparagraphformateffectivedata/
---```
public interface IParagraphFormatEffectiveData
```

अपरिवर्तनीय वस्तु जो प्रभावी पैराग्राफ़ फ़ॉर्मेटिंग गुणों को शामिल करती है।

--------------------

यह इंटरफ़ेस [IParagraphFormat](../../com.aspose.slides/iparagraphformat) इंटरफ़ेस के साथ उपयोग किया जाता है ताकि विरासत लागू किए गए प्रभावी फ़ॉर्मेटिंग मान लौटाए जा सकें।

## विधियां

| विधि | विवरण |
| --- | --- |
| [getBullet()](#getBullet--) | एक पैराग्राफ़ का बुलेट फ़ॉर्मेट लौटाता है। |
| [getDepth()](#getDepth--) | एक पैराग्राफ़ की गहराई लौटाता है। |
| [getAlignment()](#getAlignment--) | एक पैराग्राफ़ में टेक्स्ट संरेखण लौटाता है। |
| [getSpaceWithin()](#getSpaceWithin--) | एक पैराग्राफ़ में बेस लाइनों के बीच की दूरी लौटाता है। |
| [getSpaceBefore()](#getSpaceBefore--) | एक पैराग्राफ़ की पहली लाइन से पहले की जगह लौटाता है। |
| [getSpaceAfter()](#getSpaceAfter--) | एक पैराग्राफ़ की अंतिम लाइन के बाद की जगह लौटाता है। |
| [getEastAsianLineBreak()](#getEastAsianLineBreak--) | निर्धारित करता है कि पैराग्राफ़ में ईस्ट एशियन लाइन ब्रेक उपयोग किया गया है या नहीं। |
| [getRightToLeft()](#getRightToLeft--) | निर्धारित करता है कि पैराग्राफ़ में राइट टू लेफ्ट लेखन उपयोग किया गया है या नहीं। |
| [getLatinLineBreak()](#getLatinLineBreak--) | निर्धारित करता है कि पैराग्राफ़ में लैटिन लाइन ब्रेक उपयोग किया गया है या नहीं। |
| [getHangingPunctuation()](#getHangingPunctuation--) | निर्धारित करता है कि पैराग्राफ़ में हैंगिंग पंक्चुएशन उपयोग किया गया है या नहीं। |
| [getMarginLeft()](#getMarginLeft--) | पैराग्राफ़ में बायां मार्जिन लौटाता है। |
| [getMarginRight()](#getMarginRight--) | पैराग्राफ़ में दायां मार्जिन लौटाता है। |
| [getIndent()](#getIndent--) | पैराग्राफ़ की पहली लाइन इंडेंट/हैंगिंग इंडेंट लौटाता है। |
| [getDefaultTabSize()](#getDefaultTabSize--) | डिफ़ॉल्ट टैब्यूलेशन आकार लौटाता है। |
| [getTabs()](#getTabs--) | पैराग्राफ़ की टैब्यूलेशन लौटाता है। |
| [getFontAlignment()](#getFontAlignment--) | पैराग्राफ़ में फ़ॉन्ट संरेखण लौटाता है। |
| [getDefaultPortionFormat()](#getDefaultPortionFormat--) | पैराग्राफ़ का डिफ़ॉल्ट पोर्शन फ़ॉर्मेट लौटाता है। |

### getBullet() {#getBullet--}
```
public abstract IBulletFormatEffectiveData getBullet()
```

एक पैराग्राफ़ का बुलेट फ़ॉर्मेट लौटाता है। केवल-पढ़ने योग्य [IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata).

**वापसी:**
[IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata)

### getDepth() {#getDepth--}
```
public abstract short getDepth()
```

एक पैराग्राफ़ की गहराई लौटाता है। केवल-पढ़ने योग्य short.

**वापसी:**
short

### getAlignment() {#getAlignment--}
```
public abstract int getAlignment()
```

पैराग्राफ़ में टेक्स्ट संरेखण लौटाता है। केवल-पढ़ने योग्य [TextAlignment](../../com.aspose.slides/textalignment).

**वापसी:**
int

### getSpaceWithin() {#getSpaceWithin--}
```
public abstract float getSpaceWithin()
```

पैराग्राफ़ में बेस लाइनों के बीच की दूरी लौटाता है। केवल-पढ़ने योग्य float.

**वापसी:**
float

### getSpaceBefore() {#getSpaceBefore--}
```
public abstract float getSpaceBefore()
```

पैराग्राफ़ की पहली लाइन से पहले की जगह लौटाता है। केवल-पढ़ने योग्य float.

**वापसी:**
float

### getSpaceAfter() {#getSpaceAfter--}
```
public abstract float getSpaceAfter()
```

पैराग्राफ़ की अंतिम लाइन के बाद की जगह लौटाता है। केवल-पढ़ने योग्य float.

**वापसी:**
float

### getEastAsianLineBreak() {#getEastAsianLineBreak--}
```
public abstract boolean getEastAsianLineBreak()
```

निर्धारित करता है कि पैराग्राफ़ में ईस्ट एशियन लाइन ब्रेक उपयोग किया गया है या नहीं। केवल-पढ़ने योग्य boolean.

**वापसी:**
boolean

### getRightToLeft() {#getRightToLeft--}
```
public abstract boolean getRightToLeft()
```

निर्धारित करता है कि पैराग्राफ़ में राइट टू लेफ्ट लेखन उपयोग किया गया है या नहीं। केवल-पढ़ने योग्य boolean.

**वापसी:**
boolean

### getLatinLineBreak() {#getLatinLineBreak--}
```
public abstract boolean getLatinLineBreak()
```

निर्धारित करता है कि पैराग्राफ़ में लैटिन लाइन ब्रेक उपयोग किया गया है या नहीं। केवल-पढ़ने योग्य boolean.

**वापसी:**
boolean

### getHangingPunctuation() {#getHangingPunctuation--}
```
public abstract boolean getHangingPunctuation()
```

निर्धारित करता है कि पैराग्राफ़ में हैंगिंग पंक्चुएशन उपयोग किया गया है या नहीं। केवल-पढ़ने योग्य boolean.

**वापसी:**
boolean

### getMarginLeft() {#getMarginLeft--}
```
public abstract float getMarginLeft()
```

पैराग्राफ़ में बायां मार्जिन लौटाता है। केवल-पढ़ने योग्य float.

**वापसी:**
float

### getMarginRight() {#getMarginRight--}
```
public abstract float getMarginRight()
```

पैराग्राफ़ में दायां मार्जिन लौटाता है। केवल-पढ़ने योग्य float.

**वापसी:**
float

### getIndent() {#getIndent--}
```
public abstract float getIndent()
```

पैराग्राफ़ की पहली लाइन इंडेंट/हैंगिंग इंडेंट लौटाता है। हैंगिंग इंडेंट नकारात्मक मानों से परिभाषित किया जा सकता है। केवल-पढ़ने योग्य float.

**वापसी:**
float

### getDefaultTabSize() {#getDefaultTabSize--}
```
public abstract float getDefaultTabSize()
```

डिफ़ॉल्ट टैब्यूलेशन आकार लौटाता है। केवल-पढ़ने योग्य float.

**वापसी:**
float

### getTabs() {#getTabs--}
```
public abstract ITabEffectiveData[] getTabs()
```

पैराग्राफ़ की टैब्यूलेशन लौटाता है। केवल-पढ़ने योग्य ITabEffectiveData[].

**वापसी:**
com.aspose.slides.ITabEffectiveData[]

### getFontAlignment() {#getFontAlignment--}
```
public abstract int getFontAlignment()
```

पैराग्राफ़ में फ़ॉन्ट संरेखण लौटाता है। केवल-पढ़ने योग्य [FontAlignment](../../com.aspose.slides/fontalignment).

**वापसी:**
int

### getDefaultPortionFormat() {#getDefaultPortionFormat--}
```
public abstract IPortionFormatEffectiveData getDefaultPortionFormat()
```

पैराग्राफ़ का डिफ़ॉल्ट पोर्शन फ़ॉर्मेट लौटाता है। केवल-पढ़ने योग्य [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).

**वापसी:**
[IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata)