---
title: ParagraphFormat
second_title: Aspose.Slides के लिए Java API संदर्भ
description: यह वर्ग पैराग्राफ फ़ॉर्मेटिंग गुणधर्मों को समाहित करता है।
type: docs
url: /hi/com.aspose.slides/paragraphformat/
---
**विरासत:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IParagraphFormat](../../com.aspose.slides/iparagraphformat), [com.aspose.slides.IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat)
```
public final class ParagraphFormat extends PVIObject implements IParagraphFormat, IChartParagraphFormat
```

यह वर्ग पैराग्राफ फ़ॉर्मेटिंग गुणधर्मों को समाहित करता है। [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) के विपरीत, इस वर्ग की सभी गुणधर्म लिखे जा सकते हैं।

--------------------

यह वर्ग विशेष पैराग्राफ के लिए परिभाषित पैराग्राफ फ़ॉर्मेटिंग गुणधर्मों को वापस देने और संशोधित करने के लिए उपयोग किया जाता है। इसका अर्थ है कि मान प्राप्त करते समय कोई विरासत लागू नहीं होती, इसलिए अधिकांश मामलों में आपको "undefined" अर्थ वाले मान मिलेंगे।

विरासत सहित प्रभावी फ़ॉर्मेटिंग पैरामीटर मान प्राप्त करने के लिए आपको [getEffective](../../com.aspose.slides/paragraphformat\#getEffective) विधि का उपयोग करना होगा जो एक [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) उदाहरण लौटाती है।
## Constructors

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [ParagraphFormat()](#ParagraphFormat--) | एक नया [ParagraphFormat](../../com.aspose.slides/paragraphformat) वर्ग का इंस्टेंस आरंभ करता है। |
## Methods

| विधि | विवरण |
| --- | --- |
| [getBullet()](#getBullet--) | पराग्राफ का बुलेट फ़ॉर्मेट लौटाता है। |
| [getDepth()](#getDepth--) | पराग्राफ की गहराई को लौटाता है या सेट करता है। |
| [setDepth(short value)](#setDepth-short-) | पराग्राफ की गहराई को लौटाता है या सेट करता है। |
| [getAlignment()](#getAlignment--) | विरासत के बिना पराग्राफ में पाठ संरेखन को लौटाता है या सेट करता है। |
| [setAlignment(int value)](#setAlignment-int-) | विरासत के बिना पराग्राफ में पाठ संरेखन को लौटाता है या सेट करता है। |
| [getSpaceWithin()](#getSpaceWithin--) | पराग्राफ में मूल रेखाओं के बीच स्थान को लौटाता है या सेट करता है। |
| [setSpaceWithin(float value)](#setSpaceWithin-float-) | पराग्राफ में मूल रेखाओं के बीच स्थान को लौटाता है या सेट करता है। |
| [getSpaceBefore()](#getSpaceBefore--) | विरासत के बिना पराग्राफ में पहली रेखा से पहले के स्थान को लौटाता है या सेट करता है। |
| [setSpaceBefore(float value)](#setSpaceBefore-float-) | विरासत के बिना पराग्राफ में पहली रेखा से पहले के स्थान को लौटाता है या सेट करता है। |
| [getSpaceAfter()](#getSpaceAfter--) | विरासत के बिना पराग्राफ में अंतिम रेखा के बाद के स्थान को लौटाता है या सेट करता है। |
| [setSpaceAfter(float value)](#setSpaceAfter-float-) | विरासत के बिना पराग्राफ में अंतिम रेखा के बाद के स्थान को लौटाता है या सेट करता है। |
| [getEastAsianLineBreak()](#getEastAsianLineBreak--) | निर्धारित करता है कि क्या पैराग्राफ में ईस्ट एशियन लाइन ब्रेक उपयोग किया जाता है। |
| [setEastAsianLineBreak(byte value)](#setEastAsianLineBreak-byte-) | निर्धारित करता है कि क्या पैराग्राफ में ईस्ट एशियन लाइन ब्रेक उपयोग किया जाता है। |
| [getRightToLeft()](#getRightToLeft--) | निर्धारित करता है कि क्या पैराग्राफ में दाएँ-से-बाएँ लेखन उपयोग किया जाता है। |
| [setRightToLeft(byte value)](#setRightToLeft-byte-) | निर्धारित करता है कि क्या पैराग्राफ में दाएँ-से-बाएँ लेखन उपयोग किया जाता है। |
| [getLatinLineBreak()](#getLatinLineBreak--) | निर्धारित करता है कि क्या पैराग्राफ में लैटिन लाइन ब्रेक उपयोग किया जाता है। |
| [setLatinLineBreak(byte value)](#setLatinLineBreak-byte-) | निर्धारित करता है कि क्या पैराग्राफ में लैटिन लाइन ब्रेक उपयोग किया जाता है। |
| [getHangingPunctuation()](#getHangingPunctuation--) | निर्धारित करता है कि क्या पैराग्राफ में हैंगिंग पंक्चर उपयोग किया जाता है। |
| [setHangingPunctuation(byte value)](#setHangingPunctuation-byte-) | निर्धारित करता है कि क्या पैराग्राफ में हैंगिंग पंक्चर उपयोग किया जाता है। |
| [getMarginLeft()](#getMarginLeft--) | विरासत के बिना पराग्राफ में बाईं मार्जिन को लौटाता है या सेट करता है। |
| [setMarginLeft(float value)](#setMarginLeft-float-) | विरासत के बिना पराग्राफ में बाईं मार्जिन को लौटाता है या सेट करता है। |
| [getMarginRight()](#getMarginRight--) | विरासत के बिना पराग्राफ में दाईं मार्जिन को लौटाता है या सेट करता है। |
| [setMarginRight(float value)](#setMarginRight-float-) | विरासत के बिना पराग्राफ में दाईं मार्जिन को लौटाता है या सेट करता है। |
| [getIndent()](#getIndent--) | विरासत के बिना पराग्राफ की पहली पंक्ति इंडेंट/हैंगिंग इंडेंट को लौटाता है या सेट करता है। |
| [setIndent(float value)](#setIndent-float-) | विरासत के बिना पराग्राफ की पहली पंक्ति इंडेंट/हैंगिंग इंडेंट को लौटाता है या सेट करता है। |
| [getDefaultTabSize()](#getDefaultTabSize--) | विरासत के बिना डिफ़ॉल्ट टैब्युलेशन आकार को लौटाता है या सेट करता है। |
| [setDefaultTabSize(float value)](#setDefaultTabSize-float-) | विरासत के बिना डिफ़ॉल्ट टैब्युलेशन आकार को लौटाता है या सेट करता है। |
| [getTabs()](#getTabs--) | पराग्राफ की टैब्युलेशन को लौटाता है। |
| [getFontAlignment()](#getFontAlignment--) | विरासत के बिना पराग्राफ में फ़ॉन्ट संरेखन को लौटाता है या सेट करता है। |
| [setFontAlignment(int value)](#setFontAlignment-int-) | विरासत के बिना पराग्राफ में फ़ॉन्ट संरेखन को लौटाता है या सेट करता है। |
| [getDefaultPortionFormat()](#getDefaultPortionFormat--) | पराग्राफ का डिफ़ॉल्ट पोर्शन फ़ॉर्मेट लौटाता है। |
| [getEffective()](#getEffective--) | विरासत लागू करके प्रभावी पैराग्राफ फ़ॉर्मेटिंग डेटा प्राप्त करता है। |
| [getVersion()](#getVersion--) |  |

### ParagraphFormat() {#ParagraphFormat--}
```
public ParagraphFormat()
```


एक नया [ParagraphFormat](../../com.aspose.slides/paragraphformat) वर्ग का इंस्टेंस आरंभ करता है।

### getBullet() {#getBullet--}
```
public final IBulletFormat getBullet()
```


पराग्राफ का बुलेट फ़ॉर्मेट लौटाता है। केवल-पढ़ने योग्य [IBulletFormat](../../com.aspose.slides/ibulletformat)।

**Returns:**
[IBulletFormat](../../com.aspose.slides/ibulletformat)
### getDepth() {#getDepth--}
```
public final short getDepth()
```


पराग्राफ की गहराई को लौटाता है या सेट करता है। मान 0 का अर्थ अपरिभाषित है। पढ़ें/लिखें  short .

**Returns:**
short
### setDepth(short value) {#setDepth-short-}
```
public final void setDepth(short value)
```


पराग्राफ की गहराई को लौटाता है या सेट करता है। मान 0 का अर्थ अपरिभाषित है। पढ़ें/लिखें  short .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short |  |

### getAlignment() {#getAlignment--}
```
public final int getAlignment()
```


विरासत के बिना पराग्राफ में पाठ संरेखन को लौटाता है या सेट करता है। पढ़ें/लिखें [TextAlignment](../../com.aspose.slides/textalignment).

--------------------

> ```
> The following sample code shows how to Align Text Paragraphs in PowerPoint Presentation.
>  
>  // एक Presentation ऑब्जेक्ट बनाएं जो PPTX फ़ाइल का प्रतिनिधित्व करता है
>  Presentation pres = new Presentation("ParagraphsAlignment.pptx");
>  try {
>      // पहली स्लाइड तक पहुँच रहा है
>      ISlide slide = pres.getSlides().get_Item(0);
>      // स्लाइड में पहले और दूसरे प्लेसहोल्डर तक पहुँच रहा है और इसे AutoShape के रूप में टाइपकास्ट कर रहा है
>      ITextFrame tf1 = ((IAutoShape)slide.getShapes().get_Item(0)).getTextFrame();
>      ITextFrame tf2 = ((IAutoShape)slide.getShapes().get_Item(1)).getTextFrame();
>      // दोनों प्लेसहोल्डरों में टेक्स्ट बदलें
>      tf1.setText("Center Align by Aspose");
>      tf2.setText("Center Align by Aspose");
>      // प्लेसहोल्डरों का पहला पैराग्राफ प्राप्त कर रहा है
>      IParagraph para1 = tf1.getParagraphs().get_Item(0);
>      IParagraph para2 = tf2.getParagraphs().get_Item(0);
>      // टेक्स्ट पैराग्राफ को केंद्र में संरेखित कर रहा है
>      para1.getParagraphFormat().setAlignment(TextAlignment.Center);
>      para2.getParagraphFormat().setAlignment(TextAlignment.Center);
>      //प्रेजेंटेशन को PPTX फ़ाइल के रूप में लिख रहा है
>      pres.save("Centeralign_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Returns:**
int
### setAlignment(int value) {#setAlignment-int-}
```
public final void setAlignment(int value)
```


विरासत के बिना पराग्राफ में पाठ संरेखन को लौटाता है या सेट करता है। पढ़ें/लिखें [TextAlignment](../../com.aspose.slides/textalignment).

--------------------

> ```
> The following sample code shows how to Align Text Paragraphs in PowerPoint Presentation.
>  
>  // एक Presentation ऑब्जेक्ट बनाएं जो PPTX फ़ाइल का प्रतिनिधित्व करता है
>  Presentation pres = new Presentation("ParagraphsAlignment.pptx");
>  try {
>      // पहली स्लाइड तक पहुँच रहा है
>      ISlide slide = pres.getSlides().get_Item(0);
>      // स्लाइड में पहले और दूसरे प्लेसहोल्डर तक पहुँच रहे हैं और इसे AutoShape के रूप में टाइपकास्ट कर रहे हैं
>      ITextFrame tf1 = ((IAutoShape)slide.getShapes().get_Item(0)).getTextFrame();
>      ITextFrame tf2 = ((IAutoShape)slide.getShapes().get_Item(1)).getTextFrame();
>      // दोनों प्लेसहोल्डरों में टेक्स्ट बदलें
>      tf1.setText("Center Align by Aspose");
>      tf2.setText("Center Align by Aspose");
>      // प्लेसहोल्डरों का पहला पैराग्राफ प्राप्त कर रहे हैं
>      IParagraph para1 = tf1.getParagraphs().get_Item(0);
>      IParagraph para2 = tf2.getParagraphs().get_Item(0);
>      // टेक्स्ट पैराग्राफ को केंद्र में संरेखित कर रहे हैं
>      para1.getParagraphFormat().setAlignment(TextAlignment.Center);
>      para2.getParagraphFormat().setAlignment(TextAlignment.Center);
>      // प्रेजेंटेशन को PPTX फ़ाइल के रूप में लिख रहे हैं
>      pres.save("Centeralign_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSpaceWithin() {#getSpaceWithin--}
```
public final float getSpaceWithin()
```


पराग्राफ में मूल रेखाओं के बीच स्थान को लौटाता है या सेट करता है। सकारात्मक मान प्रतिशत दर्शाता है, नकारात्मक मान बिंदुओं में आकार। कोई विरासत लागू नहीं। पढ़ें/लिखें  float .

**Returns:**
float
### setSpaceWithin(float value) {#setSpaceWithin-float-}
```
public final void setSpaceWithin(float value)
```


पराग्राफ में मूल रेखाओं के बीच स्थान को लौटाता है या सेट करता है। सकारात्मक मान प्रतिशत दर्शाता है, नकारात्मक मान बिंदुओं में आकार। कोई विरासत लागू नहीं। पढ़ें/लिखें  float .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getSpaceBefore() {#getSpaceBefore--}
```
public final float getSpaceBefore()
```


विरासत के बिना पराग्राफ में पहली रेखा से पहले के स्थान को लौटाता है या सेट करता है। सकारात्मक मान फ़ॉन्ट आकार का प्रतिशत दर्शाता है, नकारात्मक मान बिंदु आकार दर्शाता है। पढ़ें/लिखें  float .

**Returns:**
float
### setSpaceBefore(float value) {#setSpaceBefore-float-}
```
public final void setSpaceBefore(float value)
```


विरासत के बिना पराग्राफ में पहली रेखा से पहले के स्थान को लौटाता है या सेट करता है। सकारात्मक मान फ़ॉन्ट आकार का प्रतिशत दर्शाता है, नकारात्मक मान बिंदु आकार दर्शाता है। पढ़ें/लिखें  float .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getSpaceAfter() {#getSpaceAfter--}
```
public final float getSpaceAfter()
```


विरासत के बिना पराग्राफ में अंतिम रेखा के बाद के स्थान को लौटाता है या सेट करता है। सकारात्मक मान फ़ॉन्ट आकार का प्रतिशत दर्शाता है, नकारात्मक मान बिंदु आकार दर्शाता है। पढ़ें/लिखें  float .

**Returns:**
float
### setSpaceAfter(float value) {#setSpaceAfter-float-}
```
public final void setSpaceAfter(float value)
```


विरासत के बिना पराग्राफ में अंतिम रेखा के बाद के स्थान को लौटाता है या सेट करता है। सकारात्मक मान फ़ॉन्ट आकार का प्रतिशत दर्शाता है, नकारात्मक मान बिंदु आकार दर्शाता है। पढ़ें/लिखें  float .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getEastAsianLineBreak() {#getEastAsianLineBreak--}
```
public final byte getEastAsianLineBreak()
```


पराग्राफ में ईस्ट एशियन लाइन ब्रेक उपयोग किया जाता है या नहीं निर्धारित करता है। कोई विरासत लागू नहीं। पढ़ें/लिखें [NullableBool](../../com.aspose.slides/nullablebool).

**Returns:**
byte
### setEastAsianLineBreak(byte value) {#setEastAsianLineBreak-byte-}
```
public final void setEastAsianLineBreak(byte value)
```


पराग्राफ में ईस्ट एशियन लाइन ब्रेक उपयोग किया जाता है या नहीं निर्धारित करता है। कोई विरासत लागू नहीं। पढ़ें/लिखें [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getRightToLeft() {#getRightToLeft--}
```
public final byte getRightToLeft()
```


पराग्राफ में दाएँ-से-बाएँ लेखन उपयोग किया जाता है या नहीं निर्धारित करता है। कोई विरासत लागू नहीं। पढ़ें/लिखें [NullableBool](../../com.aspose.slides/nullablebool).

**Returns:**
byte
### setRightToLeft(byte value) {#setRightToLeft-byte-}
```
public final void setRightToLeft(byte value)
```


पराग्राफ में दाएँ-से-बाएँ लेखन उपयोग किया जाता है या नहीं निर्धारित करता है। कोई विरासत लागू नहीं। पढ़ें/लिखें [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getLatinLineBreak() {#getLatinLineBreak--}
```
public final byte getLatinLineBreak()
```


पराग्राफ में लैटिन लाइन ब्रेक उपयोग किया जाता है या नहीं निर्धारित करता है। कोई विरासत लागू नहीं। पढ़ें/लिखें [NullableBool](../../com.aspose.slides/nullablebool).

**Returns:**
byte
### setLatinLineBreak(byte value) {#setLatinLineBreak-byte-}
```
public final void setLatinLineBreak(byte value)
```


पराग्राफ में लैटिन लाइन ब्रेक उपयोग किया जाता है या नहीं निर्धारित करता है। कोई विरासत लागू नहीं। पढ़ें/लिखें [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getHangingPunctuation() {#getHangingPunctuation--}
```
public final byte getHangingPunctuation()
```


पराग्राफ में हैंगिंग पंक्चर उपयोग किया जाता है या नहीं निर्धारित करता है। कोई विरासत लागू नहीं। पढ़ें/लिखें [NullableBool](../../com.aspose.slides/nullablebool).

**Returns:**
byte
### setHangingPunctuation(byte value) {#setHangingPunctuation-byte-}
```
public final void setHangingPunctuation(byte value)
```


पराग्राफ में हैंगिंग पंक्चर उपयोग किया जाता है या नहीं निर्धारित करता है। कोई विरासत लागू नहीं। पढ़ें/लिखें [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getMarginLeft() {#getMarginLeft--}
```
public final float getMarginLeft()
```


विरासत के बिना पराग्राफ में बाईं मार्जिन को लौटाता है या सेट करता है। पढ़ें/लिखें  float .

**Returns:**
float
### setMarginLeft(float value) {#setMarginLeft-float-}
```
public final void setMarginLeft(float value)
```


विरासत के बिना पराग्राफ में बाईं मार्जिन को लौटाता है या सेट करता है। पढ़ें/लिखें  float .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getMarginRight() {#getMarginRight--}
```
public final float getMarginRight()
```


विरासत के बिना पराग्राफ में दाईं मार्जिन को लौटाता है या सेट करता है। पढ़ें/लिखें  float .

**Returns:**
float
### setMarginRight(float value) {#setMarginRight-float-}
```
public final void setMarginRight(float value)
```


विरासत के बिना पराग्राफ में दाईं मार्जिन को लौटाता है या सेट करता है। पढ़ें/लिखें  float .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getIndent() {#getIndent--}
```
public final float getIndent()
```


विरासत के बिना पराग्राफ की पहली पंक्ति इंडेंट/हैंगिंग इंडेंट को लौटाता है या सेट करता है। हैंगिंग इंडेंट नकारात्मक मानों से परिभाषित हो सकता है। पढ़ें/लिखें  float .

**Returns:**
float
### setIndent(float value) {#setIndent-float-}
```
public final void setIndent(float value)
```


विरासत के बिना पराग्राफ की पहली पंक्ति इंडेंट/हैंगिंग इंडेंट को लौटाता है या सेट करता है। हैंगिंग इंडेंट नकारात्मक मानों से परिभाषित हो सकता है। पढ़ें/लिखें  float .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getDefaultTabSize() {#getDefaultTabSize--}
```
public final float getDefaultTabSize()
```


विरासत के बिना डिफ़ॉल्ट टैब्युलेशन आकार को लौटाता है या सेट करता है। पढ़ें/लिखें  float .

**Returns:**
float
### setDefaultTabSize(float value) {#setDefaultTabSize-float-}
```
public final void setDefaultTabSize(float value)
```


विरासत के बिना डिफ़ॉल्ट टैब्युलेशन आकार को लौटाता है या सेट करता है। पढ़ें/लिखें  float .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getTabs() {#getTabs--}
```
public final ITabCollection getTabs()
```


पराग्राफ की टैब्युलेशन को लौटाता है। कोई विरासत लागू नहीं। केवल-पढ़ने योग्य [ITabCollection](../../com.aspose.slides/itabcollection).

**Returns:**
[ITabCollection](../../com.aspose.slides/itabcollection)
### getFontAlignment() {#getFontAlignment--}
```
public final int getFontAlignment()
```


विरासत के बिना पराग्राफ में फ़ॉन्ट संरेखन को लौटाता है या सेट करता है। पढ़ें/लिखें [FontAlignment](../../com.aspose.slides/fontalignment).

**Returns:**
int
### setFontAlignment(int value) {#setFontAlignment-int-}
```
public final void setFontAlignment(int value)
```


विरासत के बिना पराग्राफ में फ़ॉन्ट संरेखन को लौटाता है या सेट करता है। पढ़ें/लिखें [FontAlignment](../../com.aspose.slides/fontalignment).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getDefaultPortionFormat() {#getDefaultPortionFormat--}
```
public final IPortionFormat getDefaultPortionFormat()
```


पराग्राफ का डिफ़ॉल्ट पोर्शन फ़ॉर्मेट लौटाता है। कोई विरासत लागू नहीं। केवल-पढ़ने योग्य [IPortionFormat](../../com.aspose.slides/iportionformat).

**Returns:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### getEffective() {#getEffective--}
```
public final IParagraphFormatEffectiveData getEffective()
```


विरासत लागू करके प्रभावी पैराग्राफ फ़ॉर्मेटिंग डेटा प्राप्त करता है।

--------------------

> ```
> This example demonstrates getting some effective paragraph format properties.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>  	IAutoShape shape = (IAutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>  	IParagraphFormatEffectiveData effectiveParagraphFormat = shape.getTextFrame().getParagraphs().get_Item(0).getParagraphFormat().getEffective();
>  	System.out.println("Text alignment: " + effectiveParagraphFormat.getAlignment());
>  	System.out.println("Indent: " + effectiveParagraphFormat.getIndent());
>  	System.out.println("Bullet type: " + effectiveParagraphFormat.getBullet().getType());
>  } finally {
>   if (pres != null) pres.dispose();
>  }
> ```


**Returns:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) - एक [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()
```


संस्करण। केवल-पढ़ने योग्य long.

**Returns:**
long