---
title: IBasePortionFormatEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: प्रभावी टेक्स्ट हिस्से स्वरूपण गुणों वाले अपरिवर्तनीय वस्तुओं के लिए बेस इंटरफ़ेस।
type: docs
url: /hi/com.aspose.slides/ibaseportionformateffectivedata/
---```
public interface IBasePortionFormatEffectiveData
```

अपरिवर्तनीय वस्तुओं के लिए बेस इंटरफ़ेस जो प्रभावी टेक्स्ट हिस्से स्वरूपण गुणों को समाहित करती हैं।

## मेथड्स

| विधि | विवरण |
| --- | --- |
| [getLineFormat()](#getLineFormat--) | टेक्स्ट आउटलाइनिंग के लिए LineFormat गुण लौटाता है। |
| [getFillFormat()](#getFillFormat--) | टेक्स्ट FillFormat गुण लौटाता है। |
| [getEffectFormat()](#getEffectFormat--) | टेक्स्ट EffectFormat गुण लौटाता है। |
| [getHighlightColor()](#getHighlightColor--) | टेक्स्ट को हाईलाइट करने के लिए उपयोग किया गया रंग लौटाता है। |
| [getUnderlineLineFormat()](#getUnderlineLineFormat--) | अंडरलाइन लाइन को आउटलाइन करने के लिए उपयोग किए गए LineFormat गुण लौटाता है। |
| [getUnderlineFillFormat()](#getUnderlineFillFormat--) | अंडरलाइन लाइन FillFormat गुण लौटाता है। |
| [getFontBold()](#getFontBold--) | निर्धारित करता है कि फ़ॉन्ट बोल्ड है या नहीं। |
| [getFontItalic()](#getFontItalic--) | निर्धारित करता है कि फ़ॉन्ट इटैलिक है या नहीं। |
| [getKumimoji()](#getKumimoji--) | निर्धारित करता है कि संख्याएँ टेक्स्ट के पूर्वी भाषा-विशिष्ट वर्टिकल लेआउट को अनदेखा करेंगी या नहीं। |
| [getNormaliseHeight()](#getNormaliseHeight--) | निर्धारित करता है कि टेक्स्ट की ऊँचाई को सामान्यीकृत किया जाना चाहिए या नहीं। |
| [getProofDisabled()](#getProofDisabled--) | निर्धारित करता है कि टेक्स्ट को प्रूफ नहीं किया जाना चाहिए या नहीं। |
| [getFontUnderline()](#getFontUnderline--) | टेक्स्ट अंडरलाइन प्रकार लौटाता है। |
| [getTextCapType()](#getTextCapType--) | टेक्स्ट कैपिटलाइज़ेशन प्रकार लौटाता है। |
| [getStrikethroughType()](#getStrikethroughType--) | टेक्स्ट स्ट्राइकथ्रू प्रकार लौटाता है। |
| [getSmartTagClean()](#getSmartTagClean--) | निर्धारित करता है कि स्मार्ट टैग को साफ किया जाना चाहिए या नहीं। |
| [isHardUnderlineLine()](#isHardUnderlineLine--) | निर्धारित करता है कि अंडरलाइन शैली की अपनी LineFormat गुण हैं या यह टेक्स्ट के LineFormat गुणों से विरासत में लेती है। |
| [isHardUnderlineFill()](#isHardUnderlineFill--) | निर्धारित करता है कि अंडरलाइन शैली की अपनी FillFormat गुण हैं या यह टेक्स्ट के FillFormat गुणों से विरासत में लेती है। |
| [getFontHeight()](#getFontHeight--) | टेक्स्ट हिस्से की फ़ॉन्ट ऊँचाई पॉइंट में लौटाता है। |
| [getLatinFont()](#getLatinFont--) | लैटिन फ़ॉन्ट जानकारी लौटाता है। |
| [getEastAsianFont()](#getEastAsianFont--) | ईस्ट एशियन फ़ॉन्ट जानकारी लौटाता है। |
| [getComplexScriptFont()](#getComplexScriptFont--) | जटिल स्क्रिप्ट फ़ॉन्ट जानकारी लौटाता है। |
| [getSymbolFont()](#getSymbolFont--) | सिंबलिक फ़ॉन्ट जानकारी लौटाता है। |
| [getEscapement()](#getEscapement--) | सुपरस्क्रिप्ट या सबस्क्रिप्ट टेक्स्ट लौटाता है। |
| [getKerningMinimalSize()](#getKerningMinimalSize--) | न्यूनतम फ़ॉन्ट आकार लौटाता है, जिसके लिए कीरनिंग चालू किया जाना चाहिए। |
| [getLanguageId()](#getLanguageId--) | भाषा का Id लौटाता है। |
| [getAlternativeLanguageId()](#getAlternativeLanguageId--) | वैकल्पिक भाषा का Id लौटाता है। |
| [getSpacing()](#getSpacing--) | इंटरकैरेक्टर स्पेसिंग वृद्धि पॉइंट में लौटाता है। |

### getLineFormat() {#getLineFormat--}
```
public abstract ILineFormatEffectiveData getLineFormat()
```

टेक्स्ट आउटलाइनिंग के लिए LineFormat गुण लौटाता है। केवल-पढ़ने योग्य [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).

**रिटर्न:**
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata)

### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormatEffectiveData getFillFormat()
```

टेक्स्ट FillFormat गुण लौटाता है। केवल-पढ़ने योग्य [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).

**रिटर्न:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)

### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormatEffectiveData getEffectFormat()
```

टेक्स्ट EffectFormat गुण लौटाता है। केवल-पढ़ने योग्य [IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata).

**रिटर्न:**
[IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata)

### getHighlightColor() {#getHighlightColor--}
```
public abstract Integer getHighlightColor()
```

टेक्स्ट को हाईलाइट करने के लिए उपयोग किया गया रंग लौटाता है। केवल-पढ़ने योग्य java.lang.Integer.

**रिटर्न:**
java.lang.Integer

### getUnderlineLineFormat() {#getUnderlineLineFormat--}
```
public abstract ILineFormatEffectiveData getUnderlineLineFormat()
```

अंडरलाइन लाइन को आउटलाइन करने के लिए उपयोग किए गए LineFormat गुण लौटाता है। केवल-पढ़ने योग्य [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).

**रिटर्न:**
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata)

### getUnderlineFillFormat() {#getUnderlineFillFormat--}
```
public abstract IFillFormatEffectiveData getUnderlineFillFormat()
```

अंडरलाइन लाइन FillFormat गुण लौटाता है। केवल-पढ़ने योग्य [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).

**रिटर्न:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)

### getFontBold() {#getFontBold--}
```
public abstract boolean getFontBold()
```

निश्चित करता है कि फ़ॉन्ट बोल्ड है या नहीं। केवल-पढ़ने योग्य boolean.

**रिटर्न:**
boolean

### getFontItalic() {#getFontItalic--}
```
public abstract boolean getFontItalic()
```

निश्चित करता है कि फ़ॉन्ट इटैलिक है या नहीं। केवल-पढ़ने योग्य boolean.

**रिटर्न:**
boolean

### getKumimoji() {#getKumimoji--}
```
public abstract boolean getKumimoji()
```

निश्चित करता है कि संख्याएँ टेक्स्ट के पूर्वी भाषा-विशिष्ट वर्टिकल लेआउट को अनदेखा करेंगी या नहीं। केवल-पढ़ने योग्य boolean.

**रिटर्न:**
boolean

### getNormaliseHeight() {#getNormaliseHeight--}
```
public abstract boolean getNormaliseHeight()
```

निश्चित करता है कि टेक्स्ट की ऊँचाई को सामान्यीकृत किया जाना चाहिए या नहीं। केवल-पढ़ने योग्य boolean.

**रिटर्न:**
boolean

### getProofDisabled() {#getProofDisabled--}
```
public abstract boolean getProofDisabled()
```

निश्चित करता है कि टेक्स्ट को प्रूफ नहीं किया जाना चाहिए या नहीं। केवल-पढ़ने योग्य boolean.

**रिटर्न:**
boolean

### getFontUnderline() {#getFontUnderline--}
```
public abstract byte getFontUnderline()
```

टेक्स्ट अंडरलाइन प्रकार लौटाता है। केवल-पढ़ने योग्य [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**रिटर्न:**
byte

### getTextCapType() {#getTextCapType--}
```
public abstract byte getTextCapType()
```

टेक्स्ट कैपिटलाइज़ेशन प्रकार लौटाता है। केवल-पढ़ने योग्य [TextCapType](../../com.aspose.slides/textcaptype).

**रिटर्न:**
byte

### getStrikethroughType() {#getStrikethroughType--}
```
public abstract byte getStrikethroughType()
```

टेक्स्ट स्ट्राइकथ्रू प्रकार लौटाता है। केवल-पढ़ने योग्य [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**रिटर्न:**
byte

### getSmartTagClean() {#getSmartTagClean--}
```
public abstract boolean getSmartTagClean()
```

निश्चित करता है कि स्मार्ट टैग को साफ किया जाना चाहिए या नहीं। केवल-पढ़ने योग्य boolean.

**रिटर्न:**
boolean

### isHardUnderlineLine() {#isHardUnderlineLine--}
```
public abstract boolean isHardUnderlineLine()
```

निश्चित करता है कि अंडरलाइन शैली की अपनी LineFormat गुण हैं या यह टेक्स्ट के LineFormat गुणों से विरासत में लेती है। केवल-पढ़ने योग्य boolean.

**रिटर्न:**
boolean

### isHardUnderlineFill() {#isHardUnderlineFill--}
```
public abstract boolean isHardUnderlineFill()
```

निश्चित करता है कि अंडरलाइन शैली की अपनी FillFormat गुण हैं या यह टेक्स्ट के FillFormat गुणों से विरासत में लेती है। केवल-पढ़ने योग्य boolean.

**रिटर्न:**
boolean

### getFontHeight() {#getFontHeight--}
```
public abstract float getFontHeight()
```

टेक्स्ट हिस्से की फ़ॉन्ट ऊँचाई पॉइंट में लौटाता है। केवल-पढ़ने योग्य float.

**रिटर्न:**
float

### getLatinFont() {#getLatinFont--}
```
public abstract IFontData getLatinFont()
```

लैटिन फ़ॉन्ट जानकारी लौटाता है। केवल-पढ़ने योग्य [IFontData](../../com.aspose.slides/ifontdata).

**रिटर्न:**
[IFontData](../../com.aspose.slides/ifontdata)

### getEastAsianFont() {#getEastAsianFont--}
```
public abstract IFontData getEastAsianFont()
```

ईस्ट एशियन फ़ॉन्ट जानकारी लौटाता है। केवल-पढ़ने योग्य [IFontData](../../com.aspose.slides/ifontdata).

**रिटर्न:**
[IFontData](../../com.aspose.slides/ifontdata)

### getComplexScriptFont() {#getComplexScriptFont--}
```
public abstract IFontData getComplexScriptFont()
```

जटिल स्क्रिप्ट फ़ॉन्ट जानकारी लौटाता है। केवल-पढ़ने योग्य [IFontData](../../com.aspose.slides/ifontdata).

**रिटर्न:**
[IFontData](../../com.aspose.slides/ifontdata)

### getSymbolFont() {#getSymbolFont--}
```
public abstract IFontData getSymbolFont()
```

सिंबलिक फ़ॉन्ट जानकारी लौटाता है। केवल-पढ़ने योग्य [IFontData](../../com.aspose.slides/ifontdata).

**रिटर्न:**
[IFontData](../../com.aspose.slides/ifontdata)

### getEscapement() {#getEscapement--}
```
public abstract float getEscapement()
```

सुपरस्क्रिप्ट या सबस्क्रिप्ट टेक्स्ट लौटाता है। मान -100% (सबस्क्रिप्ट) से 100% (सुपरस्क्रिप्ट) तक। केवल-पढ़ने योग्य float.

**रिटर्न:**
float

### getKerningMinimalSize() {#getKerningMinimalSize--}
```
public abstract float getKerningMinimalSize()
```

न्यूनतम फ़ॉन्ट आकार लौटाता है, जिसके लिए कीरनिंग चालू किया जाना चाहिए। केवल-पढ़ने योग्य float.

**रिटर्न:**
float

### getLanguageId() {#getLanguageId--}
```
public abstract String getLanguageId()
```

भाषा का Id लौटाता है। केवल-पढ़ने योग्य String.

**रिटर्न:**
java.lang.String

### getAlternativeLanguageId() {#getAlternativeLanguageId--}
```
public abstract String getAlternativeLanguageId()
```

वैकल्पिक भाषा का Id लौटाता है। केवल-पढ़ने योग्य String.

**रिटर्न:**
java.lang.String

### getSpacing() {#getSpacing--}
```
public abstract float getSpacing()
```

इंटरकैरेक्टर स्पेसिंग वृद्धि पॉइंट में लौटाता है। केवल-पढ़ने योग्य float.

**रिटर्न:**
float