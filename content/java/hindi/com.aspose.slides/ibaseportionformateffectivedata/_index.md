---
title: IBasePortionFormatEffectiveData
second_title: Aspose.Slides for Java API Reference
description: अपरिवर्तनीय वस्तुओं के लिए आधार इंटरफ़ेस जो प्रभावी टेक्स्ट भाग फ़ॉर्मेटिंग गुणों को समाहित करती हैं।
type: docs
url: /hi/com.aspose.slides/ibaseportionformateffectivedata/
---```
public interface IBasePortionFormatEffectiveData
```

अपरिवर्तनीय वस्तुओं के लिए आधार इंटरफ़ेस जो प्रभावी टेक्स्ट भाग फ़ॉर्मेटिंग गुणों को समाहित करती हैं।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getLineFormat()](#getLineFormat--) | पाठ रूपरेखा के लिए LineFormat गुण लौटाता है। |
| [getFillFormat()](#getFillFormat--) | पाठ FillFormat गुण लौटाता है। |
| [getEffectFormat()](#getEffectFormat--) | पाठ EffectFormat गुण लौटाता है। |
| [getHighlightColor()](#getHighlightColor--) | पाठ को हाईलाइट करने के लिए उपयोग किया गया रंग लौटाता है। |
| [getUnderlineLineFormat()](#getUnderlineLineFormat--) | अंडरलाइन लाइन का रूपरेखा देने के लिए उपयोग किए गए LineFormat गुण लौटाता है। |
| [getUnderlineFillFormat()](#getUnderlineFillFormat--) | अंडरलाइन लाइन FillFormat गुण लौटाता है। |
| [getFontBold()](#getFontBold--) | निर्धारित करता है कि फ़ॉन्ट बोल्ड है या नहीं। |
| [getFontItalic()](#getFontItalic--) | निर्धारित करता है कि फ़ॉन्ट इटैलिक है या नहीं। |
| [getKumimoji()](#getKumimoji--) | निर्धारित करता है कि संख्याएँ पाठ के ईस्टरर्न भाषा-विशिष्ट वर्टिकल लेआउट को अनदेखा करें। |
| [getNormaliseHeight()](#getNormaliseHeight--) | निर्धारित करता है कि पाठ की ऊँचाई को सामान्यीकृत किया जाना चाहिए या नहीं। |
| [getProofDisabled()](#getProofDisabled--) | निर्धारित करता है कि पाठ को प्रूफ नहीं किया जाना चाहिए। |
| [getFontUnderline()](#getFontUnderline--) | पाठ अंडरलाइन प्रकार लौटाता है। |
| [getTextCapType()](#getTextCapType--) | पाठ कैपिटलाइज़ेशन प्रकार लौटाता है। |
| [getStrikethroughType()](#getStrikethroughType--) | पाठ स्ट्राइकथ्रू प्रकार लौटाता है। |
| [getSmartTagClean()](#getSmartTagClean--) | निर्धारित करता है कि स्मार्ट टैग साफ़ किया जाना चाहिए या नहीं। |
| [isHardUnderlineLine()](#isHardUnderlineLine--) | निर्धारित करता है कि अंडरलाइन शैली के पास अपने स्वयं के LineFormat गुण हैं या वह पाठ के LineFormat गुणों से विरासत में प्राप्त करता है। |
| [isHardUnderlineFill()](#isHardUnderlineFill--) | निर्धारित करता है कि अंडरलाइन शैली के पास अपने स्वयं के FillFormat गुण हैं या वह पाठ के FillFormat गुणों से विरासत में प्राप्त करता है। |
| [getFontHeight()](#getFontHeight--) | पाठ भाग की फ़ॉन्ट ऊँचाई, पॉइंट्स में लौटाता है। |
| [getLatinFont()](#getLatinFont--) | Latin फ़ॉन्ट जानकारी लौटाता है। |
| [getEastAsianFont()](#getEastAsianFont--) | East Asian फ़ॉन्ट जानकारी लौटाता है। |
| [getComplexScriptFont()](#getComplexScriptFont--) | जटिल स्क्रिप्ट फ़ॉन्ट जानकारी लौटाता है। |
| [getSymbolFont()](#getSymbolFont--) | सिंबोलिक फ़ॉन्ट जानकारी लौटाता है। |
| [getEscapement()](#getEscapement--) | सुपरस्क्रिप्ट या सबस्क्रिप्ट पाठ लौटाता है। |
| [getKerningMinimalSize()](#getKerningMinimalSize--) | न्यूनतम फ़ॉन्ट आकार लौटाता है, जिसके लिए करनिंग चालू किया जाना चाहिए। |
| [getLanguageId()](#getLanguageId--) | भाषा का Id लौटाता है। |
| [getAlternativeLanguageId()](#getAlternativeLanguageId--) | वैकल्पिक भाषा का Id लौटाता है। |
| [getSpacing()](#getSpacing--) | अंतः-चरित्र स्पेसिंग वृद्धि, पॉइंट्स में लौटाता है। |
### getLineFormat() {#getLineFormat--}
```
public abstract ILineFormatEffectiveData getLineFormat()
```

पाठ रूपरेखा के लिए LineFormat गुण लौटाता है। केवल-पढ़ने योग्य [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).

**रिटर्न:**
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata)
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormatEffectiveData getFillFormat()
```

पाठ FillFormat गुण लौटाता है। केवल-पढ़ने योग्य [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).

**रिटर्न:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)
### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormatEffectiveData getEffectFormat()
```

पाठ EffectFormat गुण लौटाता है। केवल-पढ़ने योग्य [IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata).

**रिटर्न:**
[IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata)
### getHighlightColor() {#getHighlightColor--}
```
public abstract Color getHighlightColor()
```

पाठ को हाईलाइट करने के लिए उपयोग किया गया रंग लौटाता है। केवल-पढ़ने योग्य java.awt.Color.

**रिटर्न:**
java.awt.Color
### getUnderlineLineFormat() {#getUnderlineLineFormat--}
```
public abstract ILineFormatEffectiveData getUnderlineLineFormat()
```

अंडरलाइन लाइन का रूपरेखा देने के लिए उपयोग किए गए LineFormat गुण लौटाता है। केवल-पढ़ने योग्य [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).

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

निर्धारित करता है कि फ़ॉन्ट बोल्ड है या नहीं। केवल-पढ़ने योग्य boolean.

**रिटर्न:**
boolean
### getFontItalic() {#getFontItalic--}
```
public abstract boolean getFontItalic()
```

निर्धारित करता है कि फ़ॉन्ट इटैलिक है या नहीं। केवल-पढ़ने योग्य boolean.

**रिटर्न:**
boolean
### getKumimoji() {#getKumimoji--}
```
public abstract boolean getKumimoji()
```

निर्धारित करता है कि संख्याएँ पाठ के ईस्टरर्न भाषा-विशिष्ट वर्टिकल लेआउट को अनदेखा करें। केवल-पढ़ने योग्य boolean.

**रिटर्न:**
boolean
### getNormaliseHeight() {#getNormaliseHeight--}
```
public abstract boolean getNormaliseHeight()
```

निर्धारित करता है कि पाठ की ऊँचाई को सामान्यीकृत किया जाना चाहिए या नहीं। केवल-पढ़ने योग्य boolean.

**रिटर्न:**
boolean
### getProofDisabled() {#getProofDisabled--}
```
public abstract boolean getProofDisabled()
```

निर्धारित करता है कि पाठ को प्रूफ नहीं किया जाना चाहिए। केवल-पढ़ने योग्य boolean.

**रिटर्न:**
boolean
### getFontUnderline() {#getFontUnderline--}
```
public abstract byte getFontUnderline()
```

पाठ अंडरलाइन प्रकार लौटाता है। केवल-पढ़ने योग्य [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**रिटर्न:**
byte
### getTextCapType() {#getTextCapType--}
```
public abstract byte getTextCapType()
```

पाठ कैपिटलाइज़ेशन प्रकार लौटाता है। केवल-पढ़ने योग्य [TextCapType](../../com.aspose.slides/textcaptype).

**रिटर्न:**
byte
### getStrikethroughType() {#getStrikethroughType--}
```
public abstract byte getStrikethroughType()
```

पाठ स्ट्राइकथ्रू प्रकार लौटाता है। केवल-पढ़ने योग्य [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**रिटर्न:**
byte
### getSmartTagClean() {#getSmartTagClean--}
```
public abstract boolean getSmartTagClean()
```

निर्धारित करता है कि स्मार्ट टैग साफ़ किया जाना चाहिए या नहीं। केवल-पढ़ने योग्य boolean.

**रिटर्न:**
boolean
### isHardUnderlineLine() {#isHardUnderlineLine--}
```
public abstract boolean isHardUnderlineLine()
```

निर्धारित करता है कि अंडरलाइन शैली के पास अपने स्वयं के LineFormat गुण हैं या वह पाठ के LineFormat गुणों से विरासत में प्राप्त करता है। केवल-पढ़ने योग्य boolean.

**रिटर्न:**
boolean
### isHardUnderlineFill() {#isHardUnderlineFill--}
```
public abstract boolean isHardUnderlineFill()
```

निर्धारित करता है कि अंडरलाइन शैली के पास अपने स्वयं के FillFormat गुण हैं या वह पाठ के FillFormat गुणों से विरासत में प्राप्त करता है। केवल-पढ़ने योग्य boolean.

**रिटर्न:**
boolean
### getFontHeight() {#getFontHeight--}
```
public abstract float getFontHeight()
```

पाठ भाग की फ़ॉन्ट ऊँचाई, पॉइंट्स में लौटाता है। केवल-पढ़ने योग्य float.

**रिटर्न:**
float
### getLatinFont() {#getLatinFont--}
```
public abstract IFontData getLatinFont()
```

Latin फ़ॉन्ट जानकारी लौटाता है। केवल-पढ़ने योग्य [IFontData](../../com.aspose.slides/ifontdata).

**रिटर्न:**
[IFontData](../../com.aspose.slides/ifontdata)
### getEastAsianFont() {#getEastAsianFont--}
```
public abstract IFontData getEastAsianFont()
```

East Asian फ़ॉन्ट जानकारी लौटाता है। केवल-पढ़ने योग्य [IFontData](../../com.aspose.slides/ifontdata).

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

सिंबोलिक फ़ॉन्ट जानकारी लौटाता है। केवल-पढ़ने योग्य [IFontData](../../com.aspose.slides/ifontdata).

**रिटर्न:**
[IFontData](../../com.aspose.slides/ifontdata)
### getEscapement() {#getEscapement--}
```
public abstract float getEscapement()
```

सुपरस्क्रिप्ट या सबस्क्रिप्ट पाठ लौटाता है। मान -100% (सबस्क्रिप्ट) से 100% (सुपरस्क्रिप्ट) तक। केवल-पढ़ने योग्य float.

**रिटर्न:**
float
### getKerningMinimalSize() {#getKerningMinimalSize--}
```
public abstract float getKerningMinimalSize()
```

न्यूनतम फ़ॉन्ट आकार लौटाता है, जिसके लिए करनिंग चालू किया जाना चाहिए। केवल-पढ़ने योग्य float.

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

अंतः-चरित्र स्पेसिंग वृद्धि, पॉइंट्स में लौटाता है। केवल-पढ़ने योग्य float.

**रिटर्न:**
float