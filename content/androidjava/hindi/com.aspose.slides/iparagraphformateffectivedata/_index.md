---
title: IParagraphFormatEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: अपरिवर्तनीय वस्तु जो प्रभावी अनुच्छेद स्वरूपण गुणों को समाहित करती है।
type: docs
url: /hi/com.aspose.slides/iparagraphformateffectivedata/
---```
public interface IParagraphFormatEffectiveData
```

अपरिवर्तनीय वस्तु जो प्रभावी अनुच्छेद स्वरूपण गुणों को समाहित करती है।

--------------------

यह इंटरफ़ेस [IParagraphFormat](../../com.aspose.slides/iparagraphformat) इंटरफ़ेस के साथ उपयोग किया जाता है ताकि विरासत लागू किए गए प्रभावी स्वरूपण मान लौटाए जा सकें।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getBullet()](#getBullet--) | एक अनुच्छेद का बुलेट स्वरूप लौटाता है। |
| [getDepth()](#getDepth--) | एक अनुच्छेद की गहराई लौटाता है। |
| [getAlignment()](#getAlignment--) | एक अनुच्छेद में पाठ संरेखण लौटाता है। |
| [getSpaceWithin()](#getSpaceWithin--) | एक अनुच्छेद में बेस लाइनों के बीच स्थान की मात्रा लौटाता है। |
| [getSpaceBefore()](#getSpaceBefore--) | एक अनुच्छेद में पहली लाइन से पहले स्थान की मात्रा लौटाता है। |
| [getSpaceAfter()](#getSpaceAfter--) | एक अनुच्छेद में अंतिम लाइन के बाद स्थान की मात्रा लौटाता है। |
| [getEastAsianLineBreak()](#getEastAsianLineBreak--) | निर्धारित करता है कि क्या East Asian लाइन ब्रेक उपयोग किया जाता है। |
| [getRightToLeft()](#getRightToLeft--) | निर्धारित करता है कि क्या Right to Left लेखन उपयोग किया जाता है। |
| [getLatinLineBreak()](#getLatinLineBreak--) | निर्धारित करता है कि क्या Latin लाइन ब्रेक उपयोग किया जाता है। |
| [getHangingPunctuation()](#getHangingPunctuation--) | निर्धारित करता है कि क्या हैंकिंग विराम चिह्न उपयोग किया जाता है। |
| [getMarginLeft()](#getMarginLeft--) | एक अनुच्छेद में बायाँ मार्जिन लौटाता है। |
| [getMarginRight()](#getMarginRight--) | एक अनुच्छेद में दायाँ मार्जिन लौटाता है। |
| [getIndent()](#getIndent--) | अनुच्छेद की पहली पंक्ति का इंडेंट/हैंगिंग इंडेंट लौटाता है। |
| [getDefaultTabSize()](#getDefaultTabSize--) | डिफ़ॉल्ट टैबुलेशन आकार लौटाता है। |
| [getTabs()](#getTabs--) | एक अनुच्छेद की टैबुलेशन लौटाता है। |
| [getFontAlignment()](#getFontAlignment--) | एक अनुच्छेद में फ़ॉन्ट संरेखण लौटाता है। |
| [getDefaultPortionFormat()](#getDefaultPortionFormat--) | एक अनुच्छेद का डिफ़ॉल्ट पोर्शन स्वरूप लौटाता है। |
### getBullet() {#getBullet--}
```
public abstract IBulletFormatEffectiveData getBullet()
```


एक अनुच्छेद का बुलेट स्वरूप लौटाता है। केवल-पढ़ने योग्य [IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata)।

**वापसी:**
[IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata)
### getDepth() {#getDepth--}
```
public abstract short getDepth()
```


एक अनुच्छेद की गहराई लौटाता है। केवल-पढ़ने योग्य short।

**वापसी:**
short
### getAlignment() {#getAlignment--}
```
public abstract int getAlignment()
```


एक अनुच्छेद में पाठ संरेखण लौटाता है। केवल-पढ़ने योग्य [TextAlignment](../../com.aspose.slides/textalignment)।

**वापसी:**
int
### getSpaceWithin() {#getSpaceWithin--}
```
public abstract float getSpaceWithin()
```


एक अनुच्छेद में बेस लाइनों के बीच स्थान की मात्रा लौटाता है। केवल-पढ़ने योग्य float।

**वापसी:**
float
### getSpaceBefore() {#getSpaceBefore--}
```
public abstract float getSpaceBefore()
```


एक अनुच्छेद में पहली लाइन से पहले स्थान की मात्रा लौटाता है। केवल-पढ़ने योग्य float।

**वापसी:**
float
### getSpaceAfter() {#getSpaceAfter--}
```
public abstract float getSpaceAfter()
```


एक अनुच्छेद में अंतिम लाइन के बाद स्थान की मात्रा लौटाता है। केवल-पढ़ने योग्य float।

**वापसी:**
float
### getEastAsianLineBreak() {#getEastAsianLineBreak--}
```
public abstract boolean getEastAsianLineBreak()
```


निर्धारित करता है कि क्या East Asian लाइन ब्रेक उपयोग किया जाता है। केवल-पढ़ने योग्य boolean।

**वापसी:**
boolean
### getRightToLeft() {#getRightToLeft--}
```
public abstract boolean getRightToLeft()
```


निर्धारित करता है कि क्या Right to Left लेखन उपयोग किया जाता है। केवल-पढ़ने योग्य boolean।

**वापसी:**
boolean
### getLatinLineBreak() {#getLatinLineBreak--}
```
public abstract boolean getLatinLineBreak()
```


निर्धारित करता है कि क्या Latin लाइन ब्रेक उपयोग किया जाता है। केवल-पढ़ने योग्य boolean।

**वापसी:**
boolean
### getHangingPunctuation() {#getHangingPunctuation--}
```
public abstract boolean getHangingPunctuation()
```


निर्धारित करता है कि क्या हैंकिंग विराम चिह्न उपयोग किया जाता है। केवल-पढ़ने योग्य boolean।

**वापसी:**
boolean
### getMarginLeft() {#getMarginLeft--}
```
public abstract float getMarginLeft()
```


एक अनुच्छेद में बायाँ मार्जिन लौटाता है। केवल-पढ़ने योग्य float।

**वापसी:**
float
### getMarginRight() {#getMarginRight--}
```
public abstract float getMarginRight()
```


एक अनुच्छेद में दायाँ मार्जिन लौटाता है। केवल-पढ़ने योग्य float।

**वापसी:**
float
### getIndent() {#getIndent--}
```
public abstract float getIndent()
```


अनुच्छेद की पहली पंक्ति का इंडेंट/हैंगिंग इंडेंट लौटाता है। नकारात्मक मानों से हैंगिंग इंडेंट निर्धारित किया जा सकता है। केवल-पढ़ने योग्य float।

**वापसी:**
float
### getDefaultTabSize() {#getDefaultTabSize--}
```
public abstract float getDefaultTabSize()
```


डिफ़ॉल्ट टैबुलेशन आकार लौटाता है। केवल-पढ़ने योग्य float।

**वापसी:**
float
### getTabs() {#getTabs--}
```
public abstract ITabEffectiveData[] getTabs()
```


एक अनुच्छेद की टैबुलेशन लौटाता है। केवल-पढ़ने योग्य ITabEffectiveData[]।

**वापसी:**
com.aspose.slides.ITabEffectiveData[]
### getFontAlignment() {#getFontAlignment--}
```
public abstract int getFontAlignment()
```


एक अनुच्छेद में फ़ॉन्ट संरेखण लौटाता है। केवल-पढ़ने योग्य [FontAlignment](../../com.aspose.slides/fontalignment)।

**वापसी:**
int
### getDefaultPortionFormat() {#getDefaultPortionFormat--}
```
public abstract IPortionFormatEffectiveData getDefaultPortionFormat()
```


एक अनुच्छेद का डिफ़ॉल्ट पोर्शन स्वरूप लौटाता है। केवल-पढ़ने योग्य [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata)।

**वापसी:**
[IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata)