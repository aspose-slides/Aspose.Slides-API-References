---
title: ParagraphFormat
second_title: Java API रेफ़रेंस के द्वारा Android के लिए Aspose.Slides
description: यह क्लास पैराग्राफ फ़ॉर्मेटिंग प्रॉपर्टीज़ को समाहित करती है।
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

यह क्लास पैराग्राफ फ़ॉर्मेटिंग प्रॉपर्टीज़ को समाहित करती है। [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) के विपरीत, इस क्लास की सभी प्रॉपर्टीज़ लेखनीय हैं।

--------------------

यह क्लास किसी विशिष्ट पैराग्राफ के लिए परिभाषित पैराग्राफ फ़ॉर्मेटिंग प्रॉपर्टीज़ को लौटाने और संशोधित करने के लिए उपयोग की जाती है। इसका अर्थ है कि मान प्राप्त करते समय कोई विरासत लागू नहीं होती, इसलिए अधिकांश मामलों में आपको "अनिर्धारित" मान मिलेंगे।

विरासत सहित प्रभावी फ़ॉर्मेटिंग पैरामीटर मान प्राप्त करने के लिए आपको [getEffective](../../com.aspose.slides/paragraphformat\#getEffective) मेथड का उपयोग करना होगा जो एक [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) इंस्टेंस लौटाता है।

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [ParagraphFormat()](#ParagraphFormat--) | एक नया इंस्टेंस प्रारम्भ करता है [ParagraphFormat](../../com.aspose.slides/paragraphformat) क्लास का। |

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getBullet()](#getBullet--) | पैराग्राफ का बुलेट फ़ॉर्मेट लौटाता है। |
| [getDepth()](#getDepth--) | पैराग्राफ की गहराई को लौटाता या सेट करता है। |
| [setDepth(short value)](#setDepth-short-) | पैराग्राफ की गहराई को लौटाता या सेट करता है। |
| [getAlignment()](#getAlignment--) | पैराग्राफ में टेक्स्ट संरेखण को लौटाता या सेट करता है, बिना विरासत के। |
| [setAlignment(int value)](#setAlignment-int-) | पैराग्राफ में टेक्स्ट संरेखण को लौटाता या सेट करता है, बिना विरासत के। |
| [getSpaceWithin()](#getSpaceWithin--) | पैराग्राफ में बेस लाइनों के बीच की दूरी को लौटाता या सेट करता है। |
| [setSpaceWithin(float value)](#setSpaceWithin-float-) | पैराग्राफ में बेस लाइनों के बीच की दूरी को लौटाता या सेट करता है। |
| [getSpaceBefore()](#getSpaceBefore--) | पैराग्राफ में पहली लाइन से पहले की दूरी को लौटाता या सेट करता है, बिना विरासत के। |
| [setSpaceBefore(float value)](#setSpaceBefore-float-) | पैराग्राफ में पहली लाइन से पहले की दूरी को लौटाता या सेट करता है, बिना विरासत के। |
| [getSpaceAfter()](#getSpaceAfter--) | पैराग्राफ में अंतिम लाइन के बाद की दूरी को लौटाता या सेट करता है, बिना विरासत के। |
| [setSpaceAfter(float value)](#setSpaceAfter-float-) | पैराग्राफ में अंतिम लाइन के बाद की दूरी को लौटाता या सेट करता है, बिना विरासत के। |
| [getEastAsianLineBreak()](#getEastAsianLineBreak--) | निर्धारित करता है कि पैराग्राफ में ईस्ट एशियन लाइनब्रेक उपयोग किया गया है या नहीं। |
| [setEastAsianLineBreak(byte value)](#setEastAsianLineBreak-byte-) | निर्धारित करता है कि पैराग्राफ में ईस्ट एशियन लाइनब्रेक उपयोग किया गया है या नहीं। |
| [getRightToLeft()](#getRightToLeft--) | निर्धारित करता है कि पैराग्राफ में राइट टू लेफ्ट लेखन उपयोग हो रहा है या नहीं। |
| [setRightToLeft(byte value)](#setRightToLeft-byte-) | निर्धारित करता है कि पैराग्राफ में राइट टू लेफ्ट लेखन उपयोग हो रहा है या नहीं। |
| [getLatinLineBreak()](#getLatinLineBreak--) | निर्धारित करता है कि पैराग्राफ में लैटिन लाइनब्रेक उपयोग हो रहा है या नहीं। |
| [setLatinLineBreak(byte value)](#setLatinLineBreak-byte-) | निर्धारित करता है कि पैराग्राफ में लैटिन लाइनब्रेक उपयोग हो रहा है या नहीं। |
| [getHangingPunctuation()](#getHangingPunctuation--) | निर्धारित करता है कि पैराग्राफ में हैंगिंग पंक्टुएशन उपयोग हो रहा है या नहीं। |
| [setHangingPunctuation(byte value)](#setHangingPunctuation-byte-) | निर्धारित करता है कि पैराग्राफ में हैंगिंग पंक्टुएशन उपयोग हो रहा है या नहीं। |
| [getMarginLeft()](#getMarginLeft--) | पैराग्राफ में बायाँ मार्जिन लौटाता या सेट करता है, बिना विरासत के। |
| [setMarginLeft(float value)](#setMarginLeft-float-) | पैराग्राफ में बायाँ मार्जिन लौटाता या सेट करता है, बिना विरासत के। |
| [getMarginRight()](#getMarginRight--) | पैराग्राफ में दायाँ मार्जिन लौटाता या सेट करता है, बिना विरासत के। |
| [setMarginRight(float value)](#setMarginRight-float-) | पैराग्राफ में दायाँ मार्जिन लौटाता या सेट करता है, बिना विरासत के। |
| [getIndent()](#getIndent--) | पैराग्राफ की पहली लाइन इंडेंट/हैंगिंग इंडेंट को बिना विरासत के लौटाता या सेट करता है। |
| [setIndent(float value)](#setIndent-float-) | पैराग्राफ की पहली लाइन इंडेंट/हैंगिंग इंडेंट को बिना विरासत के लौटाता या सेट करता है। |
| [getDefaultTabSize()](#getDefaultTabSize--) | डिफॉल्ट टैबुलेशन साइज़ को लौटाता या सेट करता है, बिना विरासत के। |
| [setDefaultTabSize(float value)](#setDefaultTabSize-float-) | डिफॉल्ट टैबुलेशन साइज़ को लौटाता या सेट करता है, बिना विरासत के। |
| [getTabs()](#getTabs--) | पैराग्राफ की टैबुलेशन को लौटाता है। |
| [getFontAlignment()](#getFontAlignment--) | पैराग्राफ में फ़ॉन्ट संरेखण को लौटाता या सेट करता है, बिना विरासत के। |
| [setFontAlignment(int value)](#setFontAlignment-int-) | पैराग्राफ में फ़ॉन्ट संरेखण को लौटाता या सेट करता है, बिना विरासत के। |
| [getDefaultPortionFormat()](#getDefaultPortionFormat--) | पैराग्राफ का डिफॉल्ट पोर्शन फ़ॉर्मेट लौटाता है। |
| [getEffective()](#getEffective--) | विरासत लागू हो कर प्रभावी पैराग्राफ फ़ॉर्मेटिंग डेटा प्राप्त करता है। |
| [getVersion()](#getVersion--) |  |

### ParagraphFormat() {#ParagraphFormat--}
```
public ParagraphFormat()
```

एक नया इंस्टेंस प्रारम्भ करता है [ParagraphFormat](../../com.aspose.slides/paragraphformat) क्लास का।

### getBullet() {#getBullet--}
```
public final IBulletFormat getBullet()
```

पैराग्राफ का बुलेट फ़ॉर्मेट लौटाता है। केवल पढ़ने योग्य [IBulletFormat](../../com.aspose.slides/ibulletformat)।

**रिटर्न:**
[IBulletFormat](../../com.aspose.slides/ibulletformat)

### getDepth() {#getDepth--}
```
public final short getDepth()
```

पैराग्राफ की गहराई को लौटाता या सेट करता है। मान 0 अनिर्धारित मान को दर्शाता है। पढ़ने-लिखने योग्य  short .

**रिटर्न:**
short

### setDepth(short value) {#setDepth-short-}
```
public final void setDepth(short value)
```

पैराग्राफ की गहराई को लौटाता या सेट करता है। मान 0 अनिर्धारित मान को दर्शाता है। पढ़ने-लिखने योग्य  short .

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | short |  |

### getAlignment() {#getAlignment--}
```
public final int getAlignment()
```

पैराग्राफ में टेक्स्ट संरेखण को लौटाता या सेट करता है, बिना विरासत के। पढ़ने-लिखने योग्य [TextAlignment](../../com.aspose.slides/textalignment)।

--------------------

> ```
> The following sample code shows how to Align Text Paragraphs in PowerPoint Presentation.
>  
>  // एक Presentation ऑब्जेक्ट बनाएँ जो PPTX फाइल का प्रतिनिधित्व करता है
>  Presentation pres = new Presentation("ParagraphsAlignment.pptx");
>  try {
>      // पहली स्लाइड तक पहुंचना
>      ISlide slide = pres.getSlides().get_Item(0);
>      // स्लाइड में प्रथम और द्वितीय प्लेसहोल्डर तक पहुंचना और उसे AutoShape के रूप में टाइपकास्ट करना
>      ITextFrame tf1 = ((IAutoShape)slide.getShapes().get_Item(0)).getTextFrame();
>      ITextFrame tf2 = ((IAutoShape)slide.getShapes().get_Item(1)).getTextFrame();
>      // दोनों प्लेसहोल्डर में टेक्स्ट बदलें
>      tf1.setText("Center Align by Aspose");
>      tf2.setText("Center Align by Aspose");
>      // प्लेसहोल्डर के प्रथम पैराग्राफ को प्राप्त करना
>      IParagraph para1 = tf1.getParagraphs().get_Item(0);
>      IParagraph para2 = tf2.getParagraphs().get_Item(0);
>      // टेक्स्ट पैराग्राफ को केंद्र में संरेखित करना
>      para1.getParagraphFormat().setAlignment(TextAlignment.Center);
>      para2.getParagraphFormat().setAlignment(TextAlignment.Center);
>      //प्रेज़ेंटेशन को PPTX फ़ाइल के रूप में लिखना
>      pres.save("Centeralign_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**रिटर्न:**
int

### setAlignment(int value) {#setAlignment-int-}
```
public final void setAlignment(int value)
```

पैराग्राफ में टेक्स्ट संरेखण को लौटाता या सेट करता है, बिना विरासत के। पढ़ने-लिखने योग्य [TextAlignment](../../com.aspose.slides/textalignment)।

--------------------

> ```
> The following sample code shows how to Align Text Paragraphs in PowerPoint Presentation.
>  
>  // PPTX फ़ाइल का प्रतिनिधित्व करने वाला Presentation ऑब्जेक्ट बनाएं
>  Presentation pres = new Presentation("ParagraphsAlignment.pptx");
>  try {
>      // पहली स्लाइड तक पहुंच रहे हैं
>      ISlide slide = pres.getSlides().get_Item(0);
>      // स्लाइड में पहला और दूसरा प्लेसहोल्डर तक पहुंच रहे हैं और इसे AutoShape के रूप में टाइपकास्ट कर रहे हैं
>      ITextFrame tf1 = ((IAutoShape)slide.getShapes().get_Item(0)).getTextFrame();
>      ITextFrame tf2 = ((IAutoShape)slide.getShapes().get_Item(1)).getTextFrame();
>      // दोनों प्लेसहोल्डर में टेक्स्ट बदलें
>      tf1.setText("Center Align by Aspose");
>      tf2.setText("Center Align by Aspose");
>      // प्लेसहोल्डर के पहले पैराग्राफ को प्राप्त कर रहे हैं
>      IParagraph para1 = tf1.getParagraphs().get_Item(0);
>      IParagraph para2 = tf2.getParagraphs().get_Item(0);
>      // टेक्स्ट पैराग्राफ को केंद्र में संरेखित कर रहे हैं
>      para1.getParagraphFormat().setAlignment(TextAlignment.Center);
>      para2.getParagraphFormat().setAlignment(TextAlignment.Center);
>      // प्रस्तुति को PPTX फ़ाइल के रूप में लिखें
>      pres.save("Centeralign_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | int |  |

### getSpaceWithin() {#getSpaceWithin--}
```
public final float getSpaceWithin()
```

पैराग्राफ में बेस लाइनों के बीच की दूरी को लौटाता या सेट करता है। सकारात्मक मान प्रतिशत दर्शाता है, नकारात्मक - पॉइंट्स में आकार। कोई विरासत लागू नहीं। पढ़ने-लिखने योग्य  float .

**रिटर्न:**
float

### setSpaceWithin(float value) {#setSpaceWithin-float-}
```
public final void setSpaceWithin(float value)
```

पैराग्राफ में बेस लाइनों के बीच की दूरी को लौटाता या सेट करता है। सकारात्मक मान प्रतिशत दर्शाता है, नकारात्मक - पॉइंट्स में आकार। कोई विरासत लागू नहीं। पढ़ने-लिखने योग्य  float .

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | float |  |

### getSpaceBefore() {#getSpaceBefore--}
```
public final float getSpaceBefore()
```

पैराग्राफ में पहली लाइन से पहले की दूरी को लौटाता या सेट करता है, बिना विरासत के। सकारात्मक मान फ़ॉन्ट साइज का प्रतिशत दर्शाता है जिसे व्हाइट स्पेस होना चाहिए। नकारात्मक मान व्हाइट स्पेस का आकार पॉइंट साइज में दर्शाता है। पढ़ने-लिखने योग्य  float .

**रिटर्न:**
float

### setSpaceBefore(float value) {#setSpaceBefore-float-}
```
public final void setSpaceBefore(float value)
```

पैराग्राफ में पहली लाइन से पहले की दूरी को लौटाता या सेट करता है, बिना विरासत के। सकारात्मक मान फ़ॉन्ट साइज का प्रतिशत दर्शाता है जिसे व्हाइट स्पेस होना चाहिए। नकारात्मक मान व्हाइट स्पेस का आकार पॉइंट साइज में दर्शाता है। पढ़ने-लिखने योग्य  float .

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | float |  |

### getSpaceAfter() {#getSpaceAfter--}
```
public final float getSpaceAfter()
```

पैराग्राफ में अंतिम लाइन के बाद की दूरी को लौटाता या सेट करता है, बिना विरासत के। सकारात्मक मान फ़ॉन्ट साइज का प्रतिशत दर्शाता है जिसे व्हाइट स्पेस होना चाहिए। नकारात्मक मान व्हाइट स्पेस का आकार पॉइंट साइज में दर्शाता है। पढ़ने-लिखने योग्य  float .

**रिटर्न:**
float

### setSpaceAfter(float value) {#setSpaceAfter-float-}
```
public final void setSpaceAfter(float value)
```

पैराग्राफ में अंतिम लाइन के बाद की दूरी को लौटाता या सेट करता है, बिना विरासत के। सकारात्मक मान फ़ॉन्ट साइज का प्रतिशत दर्शाता है जिसे व्हाइट स्पेस होना चाहिए। नकारात्मक मान व्हाइट स्पेस का आकार पॉइंट साइज में दर्शाता है। पढ़ने-लिखने योग्य  float .

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | float |  |

### getEastAsianLineBreak() {#getEastAsianLineBreak--}
```
public final byte getEastAsianLineBreak()
```

निर्धारित करता है कि पैराग्राफ में ईस्ट एशियन लाइनब्रेक उपयोग किया गया है या नहीं। कोई विरासत लागू नहीं। पढ़ने-लिखने योग्य [NullableBool](../../com.aspose.slides/nullablebool)।

**रिटर्न:**
byte

### setEastAsianLineBreak(byte value) {#setEastAsianLineBreak-byte-}
```
public final void setEastAsianLineBreak(byte value)
```

निर्धारित करता है कि पैराग्राफ में ईस्ट एशियन लाइनब्रेक उपयोग किया गया है या नहीं। कोई विरासत लागू नहीं। पढ़ने-लिखने योग्य [NullableBool](../../com.aspose.slides/nullablebool)।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | byte |  |

### getRightToLeft() {#getRightToLeft--}
```
public final byte getRightToLeft()
```

निर्धारित करता है कि पैराग्राफ में राइट टू लेफ्ट लेखन उपयोग हो रहा है या नहीं। कोई विरासत लागू नहीं। पढ़ने-लिखने योग्य [NullableBool](../../com.aspose.slides/nullablebool)।

**रिटर्न:**
byte

### setRightToLeft(byte value) {#setRightToLeft-byte-}
```
public final void setRightToLeft(byte value)
```

निर्धारित करता है कि पैराग्राफ में राइट टू लेफ्ट लेखन उपयोग हो रहा है या नहीं। कोई विरासत लागू नहीं। पढ़ने-लिखने योग्य [NullableBool](../../com.aspose.slides/nullablebool)।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | byte |  |

### getLatinLineBreak() {#getLatinLineBreak--}
```
public final byte getLatinLineBreak()
```

निर्धारित करता है कि पैराग्राफ में लैटिन लाइनब्रेक उपयोग हो रहा है या नहीं। कोई विरासत लागू नहीं। पढ़ने-लिखने योग्य [NullableBool](../../com.aspose.slides/nullablebool)।

**रिटर्न:**
byte

### setLatinLineBreak(byte value) {#setLatinLineBreak-byte-}
```
public final void setLatinLineBreak(byte value)
```

निर्धारित करता है कि पैराग्राफ में लैटिन लाइनब्रेक उपयोग हो रहा है या नहीं। कोई विरासत लागू नहीं। पढ़ने-लिखने योग्य [NullableBool](../../com.aspose.slides/nullablebool)।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | byte |  |

### getHangingPunctuation() {#getHangingPunctuation--}
```
public final byte getHangingPunctuation()
```

निर्धारित करता है कि पैराग्राफ में हैंगिंग पंक्टुएशन उपयोग हो रहा है या नहीं। कोई विरासत लागू नहीं। पढ़ने-लिखने योग्य [NullableBool](../../com.aspose.slides/nullablebool)।

**रिटर्न:**
byte

### setHangingPunctuation(byte value) {#setHangingPunctuation-byte-}
```
public final void setHangingPunctuation(byte value)
```

निर्धारित करता है कि पैराग्राफ में हैंगिंग पंक्टुएशन उपयोग हो रहा है या नहीं। कोई विरासत लागू नहीं। पढ़ने-लिखने योग्य [NullableBool](../../com.aspose.slides/nullablebool)।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | byte |  |

### getMarginLeft() {#getMarginLeft--}
```
public final float getMarginLeft()
```

पैराग्राफ में बायाँ मार्जिन लौटाता या सेट करता है, बिना विरासत के। पढ़ने-लिखने योग्य  float .

**रिटर्न:**
float

### setMarginLeft(float value) {#setMarginLeft-float-}
```
public final void setMarginLeft(float value)
```

पैराग्राफ में बायाँ मार्जिन लौटाता या सेट करता है, बिना विरासत के। पढ़ने-लिखने योग्य  float .

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | float |  |

### getMarginRight() {#getMarginRight--}
```
public final float getMarginRight()
```

पैराग्राफ में दायाँ मार्जिन लौटाता या सेट करता है, बिना विरासत के। पढ़ने-लिखने योग्य  float .

**रिटर्न:**
float

### setMarginRight(float value) {#setMarginRight-float-}
```
public final void setMarginRight(float value)
```

पैराग्राफ में दायाँ मार्जिन लौटाता या सेट करता है, बिना विरासत के। पढ़ने-लिखने योग्य  float .

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | float |  |

### getIndent() {#getIndent--}
```
public final float getIndent()
```

पैराग्राफ की पहली लाइन इंडेंट/हैंगिंग इंडेंट को बिना विरासत के लौटाता या सेट करता है। हैंगिंग इंडेंट नकारात्मक मानों से परिभाषित किया जा सकता है। पढ़ने-लिखने योग्य  float .

**रिटर्न:**
float

### setIndent(float value) {#setIndent-float-}
```
public final void setIndent(float value)
```

पैराग्राफ की पहली लाइन इंडेंट/हैंगिंग इंडेंट को बिना विरासत के लौटाता या सेट करता है। हैंगिंग इंडेंट नकारात्मक मानों से परिभाषित किया जा सकता है। पढ़ने-लिखने योग्य  float .

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | float |  |

### getDefaultTabSize() {#getDefaultTabSize--}
```
public final float getDefaultTabSize()
```

डिफॉल्ट टैबुलेशन साइज़ को बिना विरासत के लौटाता या सेट करता है। पढ़ने-लिखने योग्य  float .

**रिटर्न:**
float

### setDefaultTabSize(float value) {#setDefaultTabSize-float-}
```
public final void setDefaultTabSize(float value)
```

डिफॉल्ट टैबुलेशन साइज़ को बिना विरासत के लौटाता या सेट करता है। पढ़ने-लिखने योग्य  float .

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | float |  |

### getTabs() {#getTabs--}
```
public final ITabCollection getTabs()
```

पैराग्राफ की टैबुलेशन को लौटाता है। कोई विरासत लागू नहीं। केवल पढ़ने योग्य [ITabCollection](../../com.aspose.slides/itabcollection)।

**रिटर्न:**
[ITabCollection](../../com.aspose.slides/itabcollection)

### getFontAlignment() {#getFontAlignment--}
```
public final int getFontAlignment()
```

पैराग्राफ में फ़ॉन्ट संरेखण को लौटाता या सेट करता है, बिना विरासत के। पढ़ने-लिखने योग्य [FontAlignment](../../com.aspose.slides/fontalignment)।

**रिटर्न:**
int

### setFontAlignment(int value) {#setFontAlignment-int-}
```
public final void setFontAlignment(int value)
```

पैराग्राफ में फ़ॉन्ट संरेखण को लौटाता या सेट करता है, बिना विरासत के। पढ़ने-लिखने योग्य [FontAlignment](../../com.aspose.slides/fontalignment)।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | int |  |

### getDefaultPortionFormat() {#getDefaultPortionFormat--}
```
public final IPortionFormat getDefaultPortionFormat()
```

पैराग्राफ का डिफॉल्ट पोर्शन फ़ॉर्मेट लौटाता है। कोई विरासत लागू नहीं। केवल पढ़ने योग्य [IPortionFormat](../../com.aspose.slides/iportionformat)।

**रिटर्न:**
[IPortionFormat](../../com.aspose.slides/iportionformat)

### getEffective() {#getEffective--}
```
public final IParagraphFormatEffectiveData getEffective()
```

विरासत लागू हो कर प्रभावी पैराग्राफ फ़ॉर्मेटिंग डेटा प्राप्त करता है।

--------------------

> ```
> यह उदाहरण कुछ प्रभावी पैराग्राफ फ़ॉर्मेट गुण प्राप्त करने का प्रदर्शन करता है.
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


**रिटर्न:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) - A [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).

### getVersion() {#getVersion--}
```
public long getVersion()
```

संस्करण। केवल पढ़ने योग्य long।

**रिटर्न:**
long