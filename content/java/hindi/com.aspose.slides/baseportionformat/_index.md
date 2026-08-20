---
title: BasePortionFormat
second_title: Aspose.Slides के लिए Java API संदर्भ
description: सामान्य टेक्स्ट भाग फ़ॉर्मेटिंग प्रॉपर्टीज़।
type: docs
url: /hi/com.aspose.slides/baseportionformat/
---
**विरासत:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**सभी लागू इंटरफ़ेस:**  
[com.aspose.slides.IBasePortionFormat](../../com.aspose.slides/ibaseportionformat)  
```
public abstract class BasePortionFormat extends PVIObject implements IBasePortionFormat
```

सामान्य टेक्स्ट भाग फ़ॉर्मेटिंग प्रॉपर्टीज़।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getLineFormat()](#getLineFormat--) | टेक्स्ट की रूपरेखा के लिए LineFormat प्रॉपर्टीज़ लौटाता है। |
| [getFillFormat()](#getFillFormat--) | टेक्स्ट FillFormat प्रॉपर्टीज़ लौटाता है। |
| [getEffectFormat()](#getEffectFormat--) | टेक्स्ट EffectFormat प्रॉपर्टीज़ लौटाता है। |
| [getHighlightColor()](#getHighlightColor--) | टेक्स्ट को हाइलाइट करने के लिए उपयोग किए गए रंग को लौटाता है। |
| [getUnderlineLineFormat()](#getUnderlineLineFormat--) | अंडरलाइन लाइन की रूपरेखा के लिए उपयोग किए गए LineFormat प्रॉपर्टीज़ लौटाता है। |
| [getUnderlineFillFormat()](#getUnderlineFillFormat--) | अंडरलाइन लाइन FillFormat प्रॉपर्टीज़ लौटाता है। |
| [getFontBold()](#getFontBold--) | निर्धारित करता है कि फ़ॉन्ट बोल्ड है या नहीं। |
| [setFontBold(byte value)](#setFontBold-byte-) | निर्धारित करता है कि फ़ॉन्ट बोल्ड है या नहीं। |
| [getFontItalic()](#getFontItalic--) | निर्धारित करता है कि फ़ॉन्ट इटैलिक है या नहीं। |
| [setFontItalic(byte value)](#setFontItalic-byte-) | निर्धारित करता है कि फ़ॉन्ट इटैलिक है या नहीं। |
| [getKumimoji()](#getKumimoji--) | निर्धारित करता है कि संख्याएँ टेक्स्ट के पूर्वी भाषा-विशिष्ट वर्टिकल लेआउट को नज़रअंदाज़ करनी चाहिए या नहीं। |
| [setKumimoji(byte value)](#setKumimoji-byte-) | निर्धारित करता है कि संख्याएँ टेक्स्ट के पूर्वी भाषा-विशिष्ट वर्टिकल लेआउट को नज़रअंदाज़ करनी चाहिए या नहीं। |
| [getNormaliseHeight()](#getNormaliseHeight--) | निर्धारित करता है कि टेक्स्ट की ऊँचाई सामान्यीकृत होनी चाहिए या नहीं। |
| [setNormaliseHeight(byte value)](#setNormaliseHeight-byte-) | निर्धारित करता है कि टेक्स्ट की ऊँचाई सामान्यीकृत होनी चाहिए या नहीं। |
| [getProofDisabled()](#getProofDisabled--) | निर्धारित करता है कि टेक्स्ट को प्रूफ़ नहीं किया जाना चाहिए या नहीं। |
| [setProofDisabled(byte value)](#setProofDisabled-byte-) | निर्धारित करता है कि टेक्स्ट को प्रूफ़ नहीं किया जाना चाहिए या नहीं। |
| [getFontUnderline()](#getFontUnderline--) | टेक्स्ट अंडरलाइन प्रकार को लौटाता या सेट करता है। |
| [setFontUnderline(byte value)](#setFontUnderline-byte-) | टेक्स्ट अंडरलाइन प्रकार को लौटाता या सेट करता है। |
| [getTextCapType()](#getTextCapType--) | टेक्स्ट कैपिटलाइज़ेशन प्रकार को लौटाता या सेट करता है। |
| [setTextCapType(byte value)](#setTextCapType-byte-) | टेक्स्ट कैपिटलाइज़ेशन प्रकार को लौटाता या सेट करता है। |
| [getStrikethroughType()](#getStrikethroughType--) | टेक्स्ट स्ट्राइकथ्रू प्रकार को लौटाता या सेट करता है। |
| [setStrikethroughType(byte value)](#setStrikethroughType-byte-) | टेक्स्ट स्ट्राइकथ्रू प्रकार को लौटाता या सेट करता है। |
| [isHardUnderlineLine()](#isHardUnderlineLine--) | निर्धारित करता है कि अंडरलाइन शैली की अपनी LineFormat प्रॉपर्टीज़ हैं या यह टेक्स्ट की LineFormat प्रॉपर्टीज़ से विरासत में मिलती हैं। |
| [setHardUnderlineLine(byte value)](#setHardUnderlineLine-byte-) | निर्धारित करता है कि अंडरलाइन शैली की अपनी LineFormat प्रॉपर्टीज़ हैं या यह टेक्स्ट की LineFormat प्रॉपर्टीज़ से विरासत में मिलती हैं। |
| [isHardUnderlineFill()](#isHardUnderlineFill--) | निर्धारित करता है कि अंडरलाइन शैली की अपनी FillFormat प्रॉपर्टीज़ हैं या यह टेक्स्ट की FillFormat प्रॉपर्टीज़ से विरासत में मिलती हैं। |
| [setHardUnderlineFill(byte value)](#setHardUnderlineFill-byte-) | निर्धारित करता है कि अंडरलाइन शैली की अपनी FillFormat प्रॉपर्टीज़ हैं या यह टेक्स्ट की FillFormat प्रॉपर्टीज़ से विरासत में मिलती हैं। |
| [getFontHeight()](#getFontHeight--) | एक भाग की फ़ॉन्ट ऊँचाई को लौटाता या सेट करता है। |
| [setFontHeight(float value)](#setFontHeight-float-) | एक भाग की फ़ॉन्ट ऊँचाई को लौटाता या सेट करता है। |
| [getLatinFont()](#getLatinFont--) | Latin फ़ॉन्ट जानकारी को लौटाता या सेट करता है। |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | Latin फ़ॉन्ट जानकारी को लौटाता या सेट करता है। |
| [getEastAsianFont()](#getEastAsianFont--) | East Asian फ़ॉन्ट जानकारी को लौटाता या सेट करता है। |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | East Asian फ़ॉन्ट जानकारी को लौटाता या सेट करता है। |
| [getComplexScriptFont()](#getComplexScriptFont--) | कम्प्लेक्स स्क्रिप्ट फ़ॉन्ट जानकारी को लौटाता या सेट करता है। |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | कम्प्लेक्स स्क्रिप्ट फ़ॉन्ट जानकारी को लौटाता या सेट करता है। |
| [getSymbolFont()](#getSymbolFont--) | सिंबॉलिक फ़ॉन्ट जानकारी को लौटाता या सेट करता है। |
| [setSymbolFont(IFontData value)](#setSymbolFont-com.aspose.slides.IFontData-) | सिंबॉलिक फ़ॉन्ट जानकारी को लौटाता या सेट करता है। |
| [getEscapement()](#getEscapement--) | सुपरस्क्रिप्ट या सबस्क्रिप्ट टेक्स्ट को लौटाता या सेट करता है। |
| [setEscapement(float value)](#setEscapement-float-) | सुपरस्क्रिप्ट या सबस्क्रिप्ट टेक्स्ट को लौटाता या सेट करता है। |
| [getKerningMinimalSize()](#getKerningMinimalSize--) | न्यूनतम फ़ॉन्ट आकार को लौटाता या सेट करता है, जिसके लिए कर्निंग चालू होना चाहिए। |
| [setKerningMinimalSize(float value)](#setKerningMinimalSize-float-) | न्यूनतम फ़ॉन्ट आकार को लौटाता या सेट करता है, जिसके लिए कर्निंग चालू होना चाहिए। |
| [getLanguageId()](#getLanguageId--) | प्रूफ़िंग भाषा का Id लौटाता या सेट करता है। |
| [setLanguageId(String value)](#setLanguageId-java.lang.String-) | प्रूफ़िंग भाषा का Id लौटाता या सेट करता है। |
| [getAlternativeLanguageId()](#getAlternativeLanguageId--) | वैकल्पिक भाषा का Id लौटाता या सेट करता है। |
| [setAlternativeLanguageId(String value)](#setAlternativeLanguageId-java.lang.String-) | वैकल्पिक भाषा का Id लौटाता या सेट करता है। |
| [getSpacing()](#getSpacing--) | अक्षर-सम्बंधी अंतराल वृद्धि को लौटाता या सेट करता है। |
| [setSpacing(float value)](#setSpacing-float-) | अक्षर-सम्बंधी अंतराल वृद्धि को लौटाता या सेट करता है। |
| [getSpellCheck()](#getSpellCheck--) | एक मान को प्राप्त या सेट करता है जो दर्शाता है कि टेक्स्ट भाग के लिए स्पेल चेकिंग सक्षम है या नहीं। |
| [setSpellCheck(boolean value)](#setSpellCheck-boolean-) | एक मान को प्राप्त या सेट करता है जो दर्शाता है कि टेक्स्ट भाग के लिए स्पेल चेकिंग सक्षम है या नहीं। |

### getVersion() {#getVersion--}
```
public long getVersion()
```

संस्करण। पढ़ने-केवल long.

**रिटर्न:**  
long

### getLineFormat() {#getLineFormat--}
```
public final ILineFormat getLineFormat()
```

टेक्स्ट की रूपरेखा के लिए LineFormat प्रॉपर्टीज़ लौटाता है। कोई विरासत लागू नहीं। पढ़ने-केवल [ILineFormat](../../com.aspose.slides/ilineformat).

**रिटर्न:**  
[ILineFormat](../../com.aspose.slides/ilineformat)

### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```

टेक्स्ट FillFormat प्रॉपर्टीज़ लौटाता है। कोई विरासत लागू नहीं। पढ़ने-केवल [IFillFormat](../../com.aspose.slides/ifillformat).

**रिटर्न:**  
[IFillFormat](../../com.aspose.slides/ifillformat)

### getEffectFormat() {#getEffectFormat--}
```
public final IEffectFormat getEffectFormat()
```

टेक्स्ट EffectFormat प्रॉपर्टीज़ लौटाता है। कोई विरासत लागू नहीं। पढ़ने-केवल [IEffectFormat](../../com.aspose.slides/ieffectformat).

**रिटर्न:**  
[IEffectFormat](../../com.aspose.slides/ieffectformat)

### getHighlightColor() {#getHighlightColor--}
```
public final IColorFormat getHighlightColor()
```

टेक्स्ट को हाइलाइट करने के लिए उपयोग किए गए रंग को लौटाता है। कोई विरासत लागू नहीं। पढ़ने-केवल [IColorFormat](../../com.aspose.slides/icolorformat).

**रिटर्न:**  
[IColorFormat](../../com.aspose.slides/icolorformat)

### getUnderlineLineFormat() {#getUnderlineLineFormat--}
```
public final ILineFormat getUnderlineLineFormat()
```

अंडरलाइन लाइन की रूपरेखा के लिए उपयोग किए गए LineFormat प्रॉपर्टीज़ लौटाता है। कोई विरासत लागू नहीं। पढ़ने-केवल [ILineFormat](../../com.aspose.slides/ilineformat).

**रिटर्न:**  
[ILineFormat](../../com.aspose.slides/ilineformat)

### getUnderlineFillFormat() {#getUnderlineFillFormat--}
```
public final IFillFormat getUnderlineFillFormat()
```

अंडरलाइन लाइन FillFormat प्रॉपर्टीज़ लौटाता है। कोई विरासत लागू नहीं। पढ़ने-केवल [IFillFormat](../../com.aspose.slides/ifillformat).

**रिटर्न:**  
[IFillFormat](../../com.aspose.slides/ifillformat)

### getFontBold() {#getFontBold--}
```
public final byte getFontBold()
```

निर्धारित करता है कि फ़ॉन्ट बोल्ड है या नहीं। कोई विरासत लागू नहीं। पढ़ने/लिखने योग्य [NullableBool](../../com.aspose.slides/nullablebool).

**रिटर्न:**  
byte

### setFontBold(byte value) {#setFontBold-byte-}
```
public final void setFontBold(byte value)
```

निर्धारित करता है कि फ़ॉन्ट बोल्ड है या नहीं। कोई विरासत लागू नहीं। पढ़ने/लिखने योग्य [NullableBool](../../com.aspose.slides/nullablebool).

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | byte |  |

### getFontItalic() {#getFontItalic--}
```
public final byte getFontItalic()
```

निर्धारित करता है कि फ़ॉन्ट इटैलिक है या नहीं। कोई विरासत लागू नहीं। पढ़ने/लिखने योग्य [NullableBool](../../com.aspose.slides/nullablebool).

**रिटर्न:**  
byte

### setFontItalic(byte value) {#setFontItalic-byte-}
```
public final void setFontItalic(byte value)
```

निर्धारित करता है कि फ़ॉन्ट इटैलिक है या नहीं। कोई विरासत लागू नहीं। पढ़ने/लिखने योग्य [NullableBool](../../com.aspose.slides/nullablebool).

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | byte |  |

### getKumimoji() {#getKumimoji--}
```
public final byte getKumimoji()
```

निर्धारित करता है कि संख्याएँ टेक्स्ट के पूर्वी भाषा-विशिष्ट वर्टिकल लेआउट को नज़रअंदाज़ करनी चाहिए या नहीं। कोई विरासत लागू नहीं। पढ़ने/लिखने योग्य [NullableBool](../../com.aspose.slides/nullablebool).

**रिटर्न:**  
byte

### setKumimoji(byte value) {#setKumimoji-byte-}
```
public final void setKumimoji(byte value)
```

निर्धारित करता है कि संख्याएँ टेक्स्ट के पूर्वी भाषा-विशिष्ट वर्टिकल लेआउट को नज़रअंदाज़ करनी चाहिए या नहीं। कोई विरासत लागू नहीं। पढ़ने/लिखने योग्य [NullableBool](../../com.aspose.slides/nullablebool).

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | byte |  |

### getNormaliseHeight() {#getNormaliseHeight--}
```
public final byte getNormaliseHeight()
```

निर्धारित करता है कि टेक्स्ट की ऊँचाई सामान्यीकृत होनी चाहिए या नहीं। कोई विरासत लागू नहीं। पढ़ने/लिखने योग्य [NullableBool](../../com.aspose.slides/nullablebool).

**रिटर्न:**  
byte

### setNormaliseHeight(byte value) {#setNormaliseHeight-byte-}
```
public final void setNormaliseHeight(byte value)
```

निर्धारित करता है कि टेक्स्ट की ऊँचाई सामान्यीकृत होनी चाहिए या नहीं। कोई विरासत लागू नहीं। पढ़ने/लिखने योग्य [NullableBool](../../com.aspose.slides/nullablebool).

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | byte |  |

### getProofDisabled() {#getProofDisabled--}
```
public final byte getProofDisabled()
```

निर्धारित करता है कि टेक्स्ट को प्रूफ़ नहीं किया जाना चाहिए या नहीं। कोई विरासत लागू नहीं। पढ़ने/लिखने योग्य [NullableBool](../../com.aspose.slides/nullablebool).

**रिटर्न:**  
byte

### setProofDisabled(byte value) {#setProofDisabled-byte-}
```
public final void setProofDisabled(byte value)
```

निर्धारित करता है कि टेक्स्ट को प्रूफ़ नहीं किया जाना चाहिए या नहीं। कोई विरासत लागू नहीं। पढ़ने/लिखने योग्य [NullableBool](../../com.aspose.slides/nullablebool).

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | byte |  |

### getFontUnderline() {#getFontUnderline--}
```
public final byte getFontUnderline()
```

टेक्स्ट अंडरलाइन प्रकार को लौटाता या सेट करता है। कोई विरासत लागू नहीं। पढ़ने/लिखने योग्य [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**रिटर्न:**  
byte

### setFontUnderline(byte value) {#setFontUnderline-byte-}
```
public final void setFontUnderline(byte value)
```

टेक्स्ट अंडरलाइन प्रकार को लौटाता या सेट करता है। कोई विरासत लागू नहीं। पढ़ने/लिखने योग्य [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | byte |  |

### getTextCapType() {#getTextCapType--}
```
public final byte getTextCapType()
```

टेक्स्ट कैपिटलाइज़ेशन प्रकार को लौटाता या सेट करता है। कोई विरासत लागू नहीं। पढ़ने/लिखने योग्य [TextCapType](../../com.aspose.slides/textcaptype).

**रिटर्न:**  
byte

### setTextCapType(byte value) {#setTextCapType-byte-}
```
public final void setTextCapType(byte value)
```

टेक्स्ट कैपिटलाइज़ेशन प्रकार को लौटाता या सेट करता है। कोई विरासत लागू नहीं। पढ़ने/लिखने योग्य [TextCapType](../../com.aspose.slides/textcaptype).

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | byte |  |

### getStrikethroughType() {#getStrikethroughType--}
```
public final byte getStrikethroughType()
```

टेक्स्ट स्ट्राइकथ्रू प्रकार को लौटाता या सेट करता है। कोई विरासत लागू नहीं। पढ़ने/लिखने योग्य [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**रिटर्न:**  
byte

### setStrikethroughType(byte value) {#setStrikethroughType-byte-}
```
public final void setStrikethroughType(byte value)
```

टेक्स्ट स्ट्राइकथ्रू प्रकार को लौटाता या सेट करता है। कोई विरासत लागू नहीं। पढ़ने/लिखने योग्य [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | byte |  |

### isHardUnderlineLine() {#isHardUnderlineLine--}
```
public final byte isHardUnderlineLine()
```

निर्धारित करता है कि अंडरलाइन शैली की अपनी LineFormat प्रॉपर्टीज़ हैं या यह टेक्स्ट की LineFormat प्रॉपर्टीज़ से विरासत में मिलती हैं। पढ़ने/लिखने योग्य [NullableBool](../../com.aspose.slides/nullablebool).

**रिटर्न:**  
byte

### setHardUnderlineLine(byte value) {#setHardUnderlineLine-byte-}
```
public final void setHardUnderlineLine(byte value)
```

निर्धारित करता है कि अंडरलाइन शैली की अपनी LineFormat प्रॉपर्टीज़ हैं या यह टेक्स्ट की LineFormat प्रॉपर्टीज़ से विरासत में मिलती हैं। पढ़ने/लिखने योग्य [NullableBool](../../com.aspose.slides/nullablebool).

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | byte |  |

### isHardUnderlineFill() {#isHardUnderlineFill--}
```
public final byte isHardUnderlineFill()
```

निर्धारित करता है कि अंडरलाइन शैली की अपनी FillFormat प्रॉपर्टीज़ हैं या यह टेक्स्ट की FillFormat प्रॉपर्टीज़ से विरासत में मिलती हैं। पढ़ने/लिखने योग्य [NullableBool](../../com.aspose.slides/nullablebool).

**रिटर्न:**  
byte

### setHardUnderlineFill(byte value) {#setHardUnderlineFill-byte-}
```
public final void setHardUnderlineFill(byte value)
```

निर्धारित करता है कि अंडरलाइन शैली की अपनी FillFormat प्रॉपर्टीज़ हैं या यह टेक्स्ट की FillFormat प्रॉपर्टीज़ से विरासत में मिलती हैं। पढ़ने/लिखने योग्य [NullableBool](../../com.aspose.slides/nullablebool).

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | byte |  |

### getFontHeight() {#getFontHeight--}
```
public final float getFontHeight()
```

फ़ॉन्ट ऊँचाई को लौटाता या सेट करता है। **Float.NaN** का अर्थ है कि ऊँचाई अनिर्धारित है और इसे मास्टर से विरासत में लेना चाहिए। पढ़ने/लिखने योग्य  float .

**रिटर्न:**  
float

### setFontHeight(float value) {#setFontHeight-float-}
```
public final void setFontHeight(float value)
```

फ़ॉन्ट ऊँचाई को लौटाता या सेट करता है। **Float.NaN** का अर्थ है कि ऊँचाई अनिर्धारित है और इसे मास्टर से विरासत में लेना चाहिए। पढ़ने/लिखने योग्य  float .

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | float |  |

### getLatinFont() {#getLatinFont--}
```
public final IFontData getLatinFont()
```

Latin फ़ॉन्ट जानकारी को लौटाता या सेट करता है। Null का अर्थ है फ़ॉन्ट अनिर्धारित है और इसे मास्टर से विरासत में लेना चाहिए। पढ़ने/लिखने योग्य [IFontData](../../com.aspose.slides/ifontdata).

**रिटर्न:**  
[IFontData](../../com.aspose.slides/ifontdata)

### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public final void setLatinFont(IFontData value)
```

Latin फ़ॉन्ट जानकारी को लौटाता या सेट करता है। Null का अर्थ है फ़ॉन्ट अनिर्धारित है और इसे मास्टर से विरासत में लेना चाहिए। पढ़ने/लिखने योग्य [IFontData](../../com.aspose.slides/ifontdata).

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEastAsianFont() {#getEastAsianFont--}
```
public final IFontData getEastAsianFont()
```

East Asian फ़ॉन्ट जानकारी को लौटाता या सेट करता है। Null का अर्थ है फ़ॉन्ट अनिर्धारित है और इसे मास्टर से विरासत में लेना चाहिए। पढ़ने/लिखने योग्य [IFontData](../../com.aspose.slides/ifontdata).

**रिटर्न:**  
[IFontData](../../com.aspose.slides/ifontdata)

### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public final void setEastAsianFont(IFontData value)
```

East Asian फ़ॉन्ट जानकारी को लौटाता या सेट करता है। Null का अर्थ है फ़ॉन्ट अनिर्धारित है और इसे मास्टर से विरासत में लेना चाहिए। पढ़ने/लिखने योग्य [IFontData](../../com.aspose.slides/ifontdata).

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getComplexScriptFont() {#getComplexScriptFont--}
```
public final IFontData getComplexScriptFont()
```

कम्प्लेक्स स्क्रिप्ट फ़ॉन्ट जानकारी को लौटाता या सेट करता है। Null का अर्थ है फ़ॉन्ट अनिर्धारित है और इसे मास्टर से विरासत में लेना चाहिए। पढ़ने/लिखने योग्य [IFontData](../../com.aspose.slides/ifontdata).

**रिटर्न:**  
[IFontData](../../com.aspose.slides/ifontdata)

### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public final void setComplexScriptFont(IFontData value)
```

कम्प्लेक्स स्क्रिप्ट फ़ॉन्ट जानकारी को लौटाता या सेट करता है। Null का अर्थ है फ़ॉन्ट अनिर्धारित है और इसे मास्टर से विरासत में लेना चाहिए। पढ़ने/लिखने योग्य [IFontData](../../com.aspose.slides/ifontdata).

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getSymbolFont() {#getSymbolFont--}
```
public final IFontData getSymbolFont()
```

सिंबॉलिक फ़ॉन्ट जानकारी को लौटाता या सेट करता है। Null का अर्थ है फ़ॉन्ट अनिर्धारित है और इसे मास्टर से विरासत में लेना चाहिए। पढ़ने/लिखने योग्य [IFontData](../../com.aspose.slides/ifontdata).

**रिटर्न:**  
[IFontData](../../com.aspose.slides/ifontdata)

### setSymbolFont(IFontData value) {#setSymbolFont-com.aspose.slides.IFontData-}
```
public final void setSymbolFont(IFontData value)
```

सिंबॉलिक फ़ॉन्ट जानकारी को लौटाता या सेट करता है। Null का अर्थ है फ़ॉन्ट अनिर्धारित है और इसे मास्टर से विरासत में लेना चाहिए। पढ़ने/लिखने योग्य [IFontData](../../com.aspose.slides/ifontdata).

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEscapement() {#getEscapement--}
```
public final float getEscapement()
```

सुपरस्क्रिप्ट या सबस्क्रिप्ट टेक्स्ट को लौटाता या सेट करता है। मान -100% (सबस्क्रिप्ट) से 100% (सुपरस्क्रिप्ट) तक हो सकता है। **Float.NaN** का अर्थ है मान अनिर्धारित है और इसे मास्टर से विरासत में लेना चाहिए। पढ़ने/लिखने योग्य  float .

**रिटर्न:**  
float

### setEscapement(float value) {#setEscapement-float-}
```
public final void setEscapement(float value)
```

सुपरस्क्रिप्ट या सबस्क्रिप्ट टेक्स्ट को लौटाता या सेट करता है। मान -100% (सबस्क्रिप्ट) से 100% (सुपरस्क्रिप्ट) तक हो सकता है। **Float.NaN** का अर्थ है मान अनिर्धारित है और इसे मास्टर से विरासत में लेना चाहिए। पढ़ने/लिखने योग्य  float .

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | float |  |

### getKerningMinimalSize() {#getKerningMinimalSize--}
```
public final float getKerningMinimalSize()
```

न्यूनतम फ़ॉन्ट आकार को लौटाता या सेट करता है, जिसके लिए कर्निंग चालू होना चाहिए। **Float.NaN** का अर्थ है मान अनिर्धारित है और इसे मास्टर से विरासत में लेना चाहिए। पढ़ने/लिखने योग्य  float .

**रिटर्न:**  
float

### setKerningMinimalSize(float value) {#setKerningMinimalSize-float-}
```
public final void setKerningMinimalSize(float value)
```

न्यूनतम फ़ॉन्ट आकार को लौटाता या सेट करता है, जिसके लिए कर्निंग चालू होना चाहिए। **Float.NaN** का अर्थ है मान अनिर्धारित है और इसे मास्टर से विरासत में लेना चाहिए। पढ़ने/लिखने योग्य  float .

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | float |  |

### getLanguageId() {#getLanguageId--}
```
public final String getLanguageId()
```

प्रूफ़िंग भाषा का Id लौटाता या सेट करता है। वर्तनी और व्याकरण जाँच के लिये उपयोग किया जाता है। पढ़ने/लिखने योग्य String.

**रिटर्न:**  
java.lang.String

### setLanguageId(String value) {#setLanguageId-java.lang.String-}
```
public final void setLanguageId(String value)
```

प्रूफ़िंग भाषा का Id लौटाता या सेट करता है। वर्तनी और व्याकरण जाँच के लिये उपयोग किया जाता है। पढ़ने/लिखने योग्य String.

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternativeLanguageId() {#getAlternativeLanguageId--}
```
public final String getAlternativeLanguageId()
```

वैकल्पिक भाषा का Id लौटाता या सेट करता है। पढ़ने/लिखने योग्य String.

**रिटर्न:**  
java.lang.String

### setAlternativeLanguageId(String value) {#setAlternativeLanguageId-java.lang.String-}
```
public final void setAlternativeLanguageId(String value)
```

वैकल्पिक भाषा का Id लौटाता या सेट करता है। पढ़ने/लिखने योग्य String.

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getSpacing() {#getSpacing--}
```
public final float getSpacing()
```

अक्षर-सम्बंधी अंतराल वृद्धि को लौटाता या सेट करता है। **Float.NaN** का अर्थ है मान अनिर्धारित है और इसे मास्टर से विरासत में लेना चाहिए। पढ़ने/लिखने योग्य  float .

**रिटर्न:**  
float

### setSpacing(float value) {#setSpacing-float-}
```
public final void setSpacing(float value)
```

अक्षर-सम्बंधी अंतराल वृद्धि को लौटाता या सेट करता है। **Float.NaN** का अर्थ है मान अनिर्धारित है और इसे मास्टर से विरासत में लेना चाहिए। पढ़ने/लिखने योग्य  float .

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | float |  |

### getSpellCheck() {#getSpellCheck--}
```
public final boolean getSpellCheck()
```

एक मान को प्राप्त या सेट करता है जो दर्शाता है कि टेक्स्ट भाग के लिए स्पेल चेकिंग सक्षम है या नहीं। जब यह प्रॉपर्टी false पर सेट की जाती है, तो टेक्स्ट तत्वों के लिये वर्तनी जाँच दमन की जाती है। जब true पर सेट की जाती है, तो स्पेल चेकिंग की अनुमति होती है। डिफ़ॉल्ट मान false है।

**रिटर्न:**  
boolean

--------------------

> ```
> Next example demonstrates enabling the SpellCheck flag before saving the presentation:
>  
>  Presentation pres = new Presentation("input.pptx");
>  try {
>      // पहले स्लाइड पर पहली आकृति के भीतर टेक्स्ट का पहला भाग एक्सेस करें
>      IPortion portion = ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).
>              getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0);
>      // इस टेक्स्ट भाग के लिए वर्तनी जाँच को सक्षम करें
>      portion.getPortionFormat().setSpellCheck(true);
>      // संशोधित प्रस्तुति को सहेजें
>      pres.save("output-with-spellcheck.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**रिटर्न:**  
boolean

### setSpellCheck(boolean value) {#setSpellCheck-boolean-}
```
public final void setSpellCheck(boolean value)
```

एक मान को प्राप्त या सेट करता है जो दर्शाता है कि टेक्स्ट भाग के लिये स्पेल चेकिंग सक्षम है या नहीं। जब यह प्रॉपर्टी false पर सेट की जाती है, तो टेक्स्ट तत्वों के लिये वर्तनी जाँच दमन की जाती है। जब true पर सेट की जाती है, तो स्पेल चेकिंग की अनुमति होती है। डिफ़ॉल्ट मान false है।

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | boolean |  |

--------------------

> ```
> Next example demonstrates enabling the SpellCheck flag before saving the presentation:
>  
>  Presentation pres = new Presentation("input.pptx");
>  try {
>      // पहले स्लाइड पर पहली आकृति के भीतर टेक्स्ट का पहला भाग एक्सेस करें
>      IPortion portion = ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).
>              getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0);
>      // इस टेक्स्ट भाग के लिये वर्तनी जाँच को सक्षम करें
>      portion.getPortionFormat().setSpellCheck(true);
>      // संशोधित प्रस्तुति को सहेजें
>      pres.save("output-with-spellcheck.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
