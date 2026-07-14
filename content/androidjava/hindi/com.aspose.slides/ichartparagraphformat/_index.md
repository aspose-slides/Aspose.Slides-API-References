---
title: IChartParagraphFormat
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a paragraph formatting properties of a chart.
type: docs
url: /hi/com.aspose.slides/ichartparagraphformat/
---```
public interface IChartParagraphFormat
```

एक चार्ट के पैराग्राफ फ़ॉर्मैटिंग गुणों का प्रतिनिधित्व करता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getAlignment()](#getAlignment--) | पैराग्राफ में टेक्स्ट संरेखण को लौटाता है या सेट करता है। |
| [setAlignment(int value)](#setAlignment-int-) | पैराग्राफ में टेक्स्ट संरेखण को लौटाता है या सेट करता है। |
| [getSpaceWithin()](#getSpaceWithin--) | पैराग्राफ में बेस लाइनों के बीच के अंतराल की मात्रा को लौटाता है या सेट करता है। |
| [setSpaceWithin(float value)](#setSpaceWithin-float-) | पैराग्राफ में बेस लाइनों के बीच के अंतराल की मात्रा को लौटाता है या सेट करता है। |
| [getSpaceBefore()](#getSpaceBefore--) | पैराग्राफ में पहली लाइन से पहले के अंतराल की मात्रा को लौटाता है या सेट करता है। |
| [setSpaceBefore(float value)](#setSpaceBefore-float-) | पैराग्राफ में पहली लाइन से पहले के अंतराल की मात्रा को लौटाता है या सेट करता है। |
| [getSpaceAfter()](#getSpaceAfter--) | पैराग्राफ में अंतिम लाइन के बाद के अंतराल की मात्रा को लौटाता है या सेट करता है। |
| [setSpaceAfter(float value)](#setSpaceAfter-float-) | पैराग्राफ में अंतिम लाइन के बाद के अंतराल की मात्रा को लौटाता है या सेट करता है। |
| [getEastAsianLineBreak()](#getEastAsianLineBreak--) | निर्धारित करता है कि क्या पैराग्राफ में ईस्ट एशियन लाइन ब्रेक उपयोग किया जाता है। |
| [setEastAsianLineBreak(byte value)](#setEastAsianLineBreak-byte-) | निर्धारित करता है कि क्या पैराग्राफ में ईस्ट एशियन लाइन ब्रेक उपयोग किया जाता है। |
| [getRightToLeft()](#getRightToLeft--) | निर्धारित करता है कि क्या पैराग्राफ में दाएँ से बाएँ लिखना उपयोग किया जाता है। |
| [setRightToLeft(byte value)](#setRightToLeft-byte-) | निर्धारित करता है कि क्या पैराग्राफ में दाएँ से बाएँ लिखना उपयोग किया जाता है। |
| [getLatinLineBreak()](#getLatinLineBreak--) | निर्धारित करता है कि क्या पैराग्राफ में लैटिन लाइन ब्रेक उपयोग किया जाता है। |
| [setLatinLineBreak(byte value)](#setLatinLineBreak-byte-) | निर्धारित करता है कि क्या पैराग्राफ में लैटिन लाइन ब्रेक उपयोग किया जाता है। |
| [getHangingPunctuation()](#getHangingPunctuation--) | निर्धारित करता है कि क्या पैराग्राफ में हैंगिंग पंक्टुएशन उपयोग किया जाता है। |
| [setHangingPunctuation(byte value)](#setHangingPunctuation-byte-) | निर्धारित करता है कि क्या पैराग्राफ में हैंगिंग पंक्टुएशन उपयोग किया जाता है। |
| [getMarginLeft()](#getMarginLeft--) | पैराग्राफ में बाएँ मार्जिन को लौटाता है या सेट करता है। |
| [setMarginLeft(float value)](#setMarginLeft-float-) | पैराग्राफ में बाएँ मार्जिन को लौटाता है या सेट करता है। |
| [getMarginRight()](#getMarginRight--) | पैराग्राफ में दाएँ मार्जिन को लौटाता है या सेट करता है। |
| [setMarginRight(float value)](#setMarginRight-float-) | पैराग्राफ में दाएँ मार्जिन को लौटाता है या सेट करता है। |
| [getIndent()](#getIndent--) | पैराग्राफ की पहली लाइन इंडेंट/हैंगिंग इंडेंट को लौटाता है या सेट करता है। |
| [setIndent(float value)](#setIndent-float-) | पैराग्राफ की पहली लाइन इंडेंट/हैंगिंग इंडेंट को लौटाता है या सेट करता है। |
| [getDefaultTabSize()](#getDefaultTabSize--) | डिफ़ॉल्ट टैबुलेशन आकार को लौटाता है या सेट करता है। |
| [setDefaultTabSize(float value)](#setDefaultTabSize-float-) | डिफ़ॉल्ट टैबुलेशन आकार को लौटाता है या सेट करता है। |
| [getTabs()](#getTabs--) | पैराग्राफ की टैबुलेशन को लौटाता है। |
| [getFontAlignment()](#getFontAlignment--) | पैराग्राफ में फ़ॉन्ट संरेखण को लौटाता है या सेट करता है। |
| [setFontAlignment(int value)](#setFontAlignment-int-) | पैराग्राफ में फ़ॉन्ट संरेखण को लौटाता है या सेट करता है। |
### getAlignment() {#getAlignment--}
```
public abstract int getAlignment()
```


पैराग्राफ में टेक्स्ट संरेखण को लौटाता है या सेट करता है। पढ़ें/लिखें [TextAlignment](../../com.aspose.slides/textalignment).

**वापसी:**
int
### setAlignment(int value) {#setAlignment-int-}
```
public abstract void setAlignment(int value)
```


पैराग्राफ में टेक्स्ट संरेखण को लौटाता है या सेट करता है। पढ़ें/लिखें [TextAlignment](../../com.aspose.slides/textalignment).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |
### getSpaceWithin() {#getSpaceWithin--}
```
public abstract float getSpaceWithin()
```


पैराग्राफ में बेस लाइनों के बीच के अंतराल की मात्रा को लौटाता है या सेट करता है। पढ़ें/लिखें float.

**वापसी:**
float
### setSpaceWithin(float value) {#setSpaceWithin-float-}
```
public abstract void setSpaceWithin(float value)
```


पैराग्राफ में बेस लाइनों के बीच के अंतराल की मात्रा को लौटाता है या सेट करता है। पढ़ें/लिखें float.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |
### getSpaceBefore() {#getSpaceBefore--}
```
public abstract float getSpaceBefore()
```


पैराग्राफ में पहली लाइन से पहले के अंतराल की मात्रा को लौटाता है या सेट करता है। पढ़ें/लिखें float.

**वापसी:**
float
### setSpaceBefore(float value) {#setSpaceBefore-float-}
```
public abstract void setSpaceBefore(float value)
```


पैराग्राफ में पहली लाइन से पहले के अंतराल की मात्रा को लौटाता है या सेट करता है। पढ़ें/लिखें float.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |
### getSpaceAfter() {#getSpaceAfter--}
```
public abstract float getSpaceAfter()
```


पैराग्राफ में अंतिम लाइन के बाद के अंतराल की मात्रा को लौटाता है या सेट करता है। पढ़ें/लिखें float.

**वापसी:**
float
### setSpaceAfter(float value) {#setSpaceAfter-float-}
```
public abstract void setSpaceAfter(float value)
```


पैराग्राफ में अंतिम लाइन के बाद के अंतराल की मात्रा को लौटाता है या सेट करता है। पढ़ें/लिखें float.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |
### getEastAsianLineBreak() {#getEastAsianLineBreak--}
```
public abstract byte getEastAsianLineBreak()
```


निर्धारित करता है कि क्या पैराग्राफ में ईस्ट एशियन लाइन ब्रेक उपयोग किया जाता है। पढ़ें/लिखें [NullableBool](../../com.aspose.slides/nullablebool).

**वापसी:**
byte
### setEastAsianLineBreak(byte value) {#setEastAsianLineBreak-byte-}
```
public abstract void setEastAsianLineBreak(byte value)
```


निर्धारित करता है कि क्या पैराग्राफ में ईस्ट एशियन लाइन ब्रेक उपयोग किया जाता है। पढ़ें/लिखें [NullableBool](../../com.aspose.slides/nullablebool).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |
### getRightToLeft() {#getRightToLeft--}
```
public abstract byte getRightToLeft()
```


निर्धारित करता है कि क्या पैराग्राफ में दाएँ से बाएँ लिखना उपयोग किया जाता है। पढ़ें/लिखें [NullableBool](../../com.aspose.slides/nullablebool).

**वापसी:**
byte
### setRightToLeft(byte value) {#setRightToLeft-byte-}
```
public abstract void setRightToLeft(byte value)
```


निर्धारित करता है कि क्या पैराग्राफ में दाएँ से बाएँ लिखना उपयोग किया जाता है। पढ़ें/लिखें [NullableBool](../../com.aspose.slides/nullablebool).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |
### getLatinLineBreak() {#getLatinLineBreak--}
```
public abstract byte getLatinLineBreak()
```


निर्धारित करता है कि क्या पैराग्राफ में लैटिन लाइन ब्रेक उपयोग किया जाता है। पढ़ें/लिखें [NullableBool](../../com.aspose.slides/nullablebool).

**वापसी:**
byte
### setLatinLineBreak(byte value) {#setLatinLineBreak-byte-}
```
public abstract void setLatinLineBreak(byte value)
```


निर्धारित करता है कि क्या पैराग्राफ में लैटिन लाइन ब्रेक उपयोग किया जाता है। पढ़ें/लिखें [NullableBool](../../com.aspose.slides/nullablebool).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |
### getHangingPunctuation() {#getHangingPunctuation--}
```
public abstract byte getHangingPunctuation()
```


निर्धारित करता है कि क्या पैराग्राफ में हैंगिंग पंक्टुएशन उपयोग किया जाता है। पढ़ें/लिखें [NullableBool](../../com.aspose.slides/nullablebool).

**वापसी:**
byte
### setHangingPunctuation(byte value) {#setHangingPunctuation-byte-}
```
public abstract void setHangingPunctuation(byte value)
```


निर्धारित करता है कि क्या पैराग्राफ में हैंगिंग पंक्टुएशन उपयोग किया जाता है। पढ़ें/लिखें [NullableBool](../../com.aspose.slides/nullablebool).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |
### getMarginLeft() {#getMarginLeft--}
```
public abstract float getMarginLeft()
```


पैराग्राफ में बाएँ मार्जिन को लौटाता है या सेट करता है। पढ़ें/लिखें float.

**वापसी:**
float
### setMarginLeft(float value) {#setMarginLeft-float-}
```
public abstract void setMarginLeft(float value)
```


पैराग्राफ में बाएँ मार्जिन को लौटाता है या सेट करता है। पढ़ें/लिखें float.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |
### getMarginRight() {#getMarginRight--}
```
public abstract float getMarginRight()
```


पैराग्राफ में दाएँ मार्जिन को लौटाता है या सेट करता है। पढ़ें/लिखें float.

**वापसी:**
float
### setMarginRight(float value) {#setMarginRight-float-}
```
public abstract void setMarginRight(float value)
```


पैराग्राफ में दाएँ मार्जिन को लौटाता है या सेट करता है। पढ़ें/लिखें float.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |
### getIndent() {#getIndent--}
```
public abstract float getIndent()
```


पैराग्राफ की पहली लाइन इंडेंट/हैंगिंग इंडेंट को लौटाता है या सेट करता है। हैंगिंग इंडेंट नकारात्मक मानों से परिभाषित हो सकता है। पढ़ें/लिखें float.

**वापसी:**
float
### setIndent(float value) {#setIndent-float-}
```
public abstract void setIndent(float value)
```


पैराग्राफ की पहली लाइन इंडेंट/हैंगिंग इंडेंट को लौटाता है या सेट करता है। हैंगिंग इंडेंट नकारात्मक मानों से परिभाषित हो सकता है। पढ़ें/लिखें float.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |
### getDefaultTabSize() {#getDefaultTabSize--}
```
public abstract float getDefaultTabSize()
```


डिफ़ॉल्ट टैबुलेशन आकार को लौटाता है या सेट करता है। पढ़ें/लिखें float.

**वापसी:**
float
### setDefaultTabSize(float value) {#setDefaultTabSize-float-}
```
public abstract void setDefaultTabSize(float value)
```


डिफ़ॉल्ट टैबुलेशन आकार को लौटाता है या सेट करता है। पढ़ें/लिखें float.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |
### getTabs() {#getTabs--}
```
public abstract ITabCollection getTabs()
```


पैराग्राफ की टैबुलेशन को लौटाता है। केवल-पढ़ें [ITabCollection](../../com.aspose.slides/itabcollection).

**वापसी:**
[ITabCollection](../../com.aspose.slides/itabcollection)
### getFontAlignment() {#getFontAlignment--}
```
public abstract int getFontAlignment()
```


फ़ॉन्ट संरेखण को लौटाता है या सेट करता है। पढ़ें/लिखें [FontAlignment](../../com.aspose.slides/fontalignment).

**वापसी:**
int
### setFontAlignment(int value) {#setFontAlignment-int-}
```
public abstract void setFontAlignment(int value)
```


फ़ॉन्ट संरेखण को लौटाता है या सेट करता है। पढ़ें/लिखें [FontAlignment](../../com.aspose.slides/fontalignment).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |