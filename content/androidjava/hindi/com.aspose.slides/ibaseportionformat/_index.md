---
title: IBasePortionFormat
second_title: Aspose.Slides for Android via Java API Reference
description: This class contains the text portion formatting properties.
type: docs
url: /hi/com.aspose.slides/ibaseportionformat/
---```
public interface IBasePortionFormat
```

यह क्लास टेक्स्ट भाग फ़ॉर्मैटिंग प्रॉपर्टीज़ को समाहित करती है। [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) के विपरीत, इस क्लास की सभी प्रॉपर्टीज़ लिखने योग्य हैं।

--------------------

यह क्लास विशेष भाग के लिए परिभाषित टेक्स्ट भाग फ़ॉर्मैटिंग प्रॉपर्टीज़ को लौटाने और संशोधित करने के लिए उपयोग की जाती है। इसका मतलब है कि मान प्राप्त करने पर कोई इनहेरिटेंस लागू नहीं होता, इसलिए अधिकांश मामलों में आप ऐसे मान प्राप्त करेंगे जो "अपरिभाषित" को दर्शाते हैं।

विरासत सहित प्रभावी फ़ॉर्मैटिंग पैरामीटर मान प्राप्त करने के लिए आपको [IPortionFormat.getEffective](../../com.aspose.slides/iportionformat\#getEffective) मेथड का उपयोग करना होगा जो एक [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) इंस्टेंस लौटाता है।

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getLineFormat()](#getLineFormat--) | टेक्स्ट आउटलाइनिंग के लिए LineFormat प्रॉपर्टीज़ लौटाता है। |
| [getFillFormat()](#getFillFormat--) | टेक्स्ट FillFormat प्रॉपर्टीज़ लौटाता है। |
| [getEffectFormat()](#getEffectFormat--) | टेक्स्ट EffectFormat प्रॉपर्टीज़ लौटाता है। |
| [getHighlightColor()](#getHighlightColor--) | टेक्स्ट को हाइलाइट करने के लिए उपयोग किए गए रंग को लौटाता है। |
| [getUnderlineLineFormat()](#getUnderlineLineFormat--) | अंडरलाइन लाइन को आउटलाइन करने के लिए उपयोग किए गए LineFormat प्रॉपर्टीज़ लौटाता है। |
| [getUnderlineFillFormat()](#getUnderlineFillFormat--) | अंडरलाइन लाइन FillFormat प्रॉपर्टीज़ लौटाता है। |
| [getFontBold()](#getFontBold--) | निर्धारित करता है कि फ़ॉन्ट बोल्ड है या नहीं। |
| [setFontBold(byte value)](#setFontBold-byte-) | निर्धारित करता है कि फ़ॉन्ट बोल्ड है या नहीं। |
| [getFontItalic()](#getFontItalic--) | निर्धारित करता है कि फ़ॉन्ट इटैलिक है या नहीं। |
| [setFontItalic(byte value)](#setFontItalic-byte-) | निर्धारित करता है कि फ़ॉन्ट इटैलिक है या नहीं। |
| [getKumimoji()](#getKumimoji--) | निर्धारित करता है कि संख्याओं को टेक्स्ट के पूर्वीय भाषा-विशिष्ट वर्टिकल लेआउट को नज़रअंदाज़ करना चाहिए या नहीं। |
| [setKumimoji(byte value)](#setKumimoji-byte-) | निर्धारित करता है कि संख्याओं को टेक्स्ट के पूर्वीय भाषा-विशिष्ट वर्टिकल लेआउट को नज़रअंदाज़ करना चाहिए या नहीं। |
| [getNormaliseHeight()](#getNormaliseHeight--) | निर्धारित करता है कि टेक्स्ट की ऊँचाई सामान्यीकृत होनी चाहिए या नहीं। |
| [setNormaliseHeight(byte value)](#setNormaliseHeight-byte-) | निर्धारित करता है कि टेक्स्ट की ऊँचाई सामान्यीकृत होनी चाहिए या नहीं। |
| [getProofDisabled()](#getProofDisabled--) | निर्धारित करता है कि टेक्स्ट को प्रूफ़ नहीं किया जाना चाहिए या नहीं। |
| [setProofDisabled(byte value)](#setProofDisabled-byte-) | निर्धारित करता है कि टेक्स्ट को प्रूफ़ नहीं किया जाना चाहिए या नहीं। |
| [getFontUnderline()](#getFontUnderline--) | टेक्स्ट अंडरलाइन प्रकार को लौटाता है या सेट करता है। |
| [setFontUnderline(byte value)](#setFontUnderline-byte-) | टेक्स्ट अंडरलाइन प्रकार को लौटाता है या सेट करता है। |
| [getTextCapType()](#getTextCapType--) | टेक्स्ट कैपिटलाइज़ेशन प्रकार को लौटाता है या सेट करता है। |
| [setTextCapType(byte value)](#setTextCapType-byte-) | टेक्स्ट कैपिटलाइज़ेशन प्रकार को लौटाता है या सेट करता है। |
| [getStrikethroughType()](#getStrikethroughType--) | टेक्स्ट के स्ट्राइकथ्रू प्रकार को लौटाता है या सेट करता है। |
| [setStrikethroughType(byte value)](#setStrikethroughType-byte-) | टेक्स्ट के स्ट्राइकथ्रू प्रकार को लौटाता है या सेट करता है। |
| [isHardUnderlineLine()](#isHardUnderlineLine--) | निर्धारित करता है कि अंडरलाइन शैली के अपने LineFormat प्रॉपर्टीज़ हैं या यह टेक्स्ट के LineFormat प्रॉपर्टीज़ से विरासत में मिली हैं। |
| [setHardUnderlineLine(byte value)](#setHardUnderlineLine-byte-) | निर्धारित करता है कि अंडरलाइन शैली के अपने LineFormat प्रॉपर्टीज़ हैं या यह टेक्स्ट के LineFormat प्रॉपर्टीज़ से विरासत में मिली हैं। |
| [isHardUnderlineFill()](#isHardUnderlineFill--) | निर्धारित करता है कि अंडरलाइन शैली के अपने FillFormat प्रॉपर्टीज़ हैं या यह टेक्स्ट के FillFormat प्रॉपर्टीज़ से विरासत में मिली हैं। |
| [setHardUnderlineFill(byte value)](#setHardUnderlineFill-byte-) | निर्धारित करता है कि अंडरलाइन शैली के अपने FillFormat प्रॉपर्टीज़ हैं या यह टेक्स्ट के FillFormat प्रॉपर्टीज़ से विरासत में मिली हैं। |
| [getFontHeight()](#getFontHeight--) | एक भाग की फ़ॉन्ट ऊँचाई को लौटाता है या सेट करता है। |
| [setFontHeight(float value)](#setFontHeight-float-) | एक भाग की फ़ॉन्ट ऊँचाई को लौटाता है या सेट करता है। |
| [getLatinFont()](#getLatinFont--) | लैटिन फ़ॉन्ट जानकारी को लौटाता है या सेट करता है। |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | लैटिन फ़ॉन्ट जानकारी को लौटाता है या सेट करता है। |
| [getEastAsianFont()](#getEastAsianFont--) | ईस्ट एशियन फ़ॉन्ट जानकारी को लौटाता है या सेट करता है। |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | ईस्ट एशियन फ़ॉन्ट जानकारी को लौटाता है या सेट करता है। |
| [getComplexScriptFont()](#getComplexScriptFont--) | कॉम्प्लेक्स स्क्रिप्ट फ़ॉन्ट जानकारी को लौटाता है या सेट करता है। |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | कॉम्प्लेक्स स्क्रिप्ट फ़ॉन्ट जानकारी को लौटाता है या सेट करता है। |
| [getSymbolFont()](#getSymbolFont--) | सिम्बोलिक फ़ॉन्ट जानकारी को लौटाता है या सेट करता है। |
| [setSymbolFont(IFontData value)](#setSymbolFont-com.aspose.slides.IFontData-) | सिम्बोलिक फ़ॉन्ट जानकारी को लौटाता है या सेट करता है। |
| [getEscapement()](#getEscapement--) | सुपरस्क्रिप्ट या सबस्क्रिप्ट टेक्स्ट को लौटाता है या सेट करता है। |
| [setEscapement(float value)](#setEscapement-float-) | सुपरस्क्रिप्ट या सबस्क्रिप्ट टेक्स्ट को लौटाता है या सेट करता है। |
| [getKerningMinimalSize()](#getKerningMinimalSize--) | न्यूनतम फ़ॉन्ट आकार को लौटाता है या सेट करता है, जिसके लिए कर्निंग सक्रिय होनी चाहिए। |
| [setKerningMinimalSize(float value)](#setKerningMinimalSize-float-) | न्यूनतम फ़ॉन्ट आकार को लौटाता है या सेट करता है, जिसके लिए कर्निंग सक्रिय होनी चाहिए। |
| [getLanguageId()](#getLanguageId--) | प्रूफ़िंग भाषा का Id लौटाता है या सेट करता है। |
| [setLanguageId(String value)](#setLanguageId-java.lang.String-) | प्रूफ़िंग भाषा का Id लौटाता है या सेट करता है। |
| [getAlternativeLanguageId()](#getAlternativeLanguageId--) | वैकल्पिक भाषा का Id लौटाता है या सेट करता है। |
| [setAlternativeLanguageId(String value)](#setAlternativeLanguageId-java.lang.String-) | वैकल्पिक भाषा का Id लौटाता है या सेट करता है। |
| [getSpacing()](#getSpacing--) | इंटरक्रैक्टर स्पेसिंग इंक्रीमेंट को लौटाता है या सेट करता है। |
| [setSpacing(float value)](#setSpacing-float-) | इंटरक्रैक्टर स्पेसिंग इंक्रीमेंट को लौटाता है या सेट करता है। |
| [getSpellCheck()](#getSpellCheck--) | एक मान प्राप्त करता या सेट करता है जो दर्शाता है कि टेक्स्ट भाग के लिए स्पेल चेकिंग सक्षम है या नहीं। |
| [setSpellCheck(boolean value)](#setSpellCheck-boolean-) | एक मान प्राप्त करता या सेट करता है जो दर्शाता है कि टेक्स्ट भाग के लिए स्पेल चेकिंग सक्षम है या नहीं। |

### getLineFormat() {#getLineFormat--}
```
public abstract ILineFormat getLineFormat()
```

टेक्स्ट आउटलाइनिंग के लिए LineFormat प्रॉपर्टीज़ लौटाता है। कोई इनहेरिटेंस लागू नहीं है। केवल पढ़ने योग्य [ILineFormat](../../com.aspose.slides/ilineformat)।

**वापसी:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

टेक्स्ट FillFormat प्रॉपर्टीज़ लौटाता है। कोई इनहेरिटेंस लागू नहीं है। केवल पढ़ने योग्य [IFillFormat](../../com.aspose.slides/ifillformat)।

**वापसी:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormat getEffectFormat()
```

टेक्स्ट EffectFormat प्रॉपर्टीज़ लौटाता है। कोई इनहेरिटेंस लागू नहीं है। केवल पढ़ने योग्य [IEffectFormat](../../com.aspose.slides/ieffectformat)।

**वापसी:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)

### getHighlightColor() {#getHighlightColor--}
```
public abstract IColorFormat getHighlightColor()
```

टेक्स्ट को हाइलाइट करने के लिए उपयोग किए गए रंग को लौटाता है। कोई इनहेरिटेंस लागू नहीं है। केवल पढ़ने योग्य [IColorFormat](../../com.aspose.slides/icolorformat)।

**वापसी:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getUnderlineLineFormat() {#getUnderlineLineFormat--}
```
public abstract ILineFormat getUnderlineLineFormat()
```

अंडरलाइन लाइन को आउटलाइन करने के लिए उपयोग किए गए LineFormat प्रॉपर्टीज़ लौटाता है। कोई इनहेरिटेंस लागू नहीं है। केवल पढ़ने योग्य [ILineFormat](../../com.aspose.slides/ilineformat)।

**वापसी:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getUnderlineFillFormat() {#getUnderlineFillFormat--}
```
public abstract IFillFormat getUnderlineFillFormat()
```

अंडरलाइन लाइन FillFormat प्रॉपर्टीज़ लौटाता है। कोई इनहेरिटेंस लागू नहीं है। केवल पढ़ने योग्य [IFillFormat](../../com.aspose.slides/ifillformat)।

**वापसी:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getFontBold() {#getFontBold--}
```
public abstract byte getFontBold()
```

निर्धारित करता है कि फ़ॉन्ट बोल्ड है या नहीं। कोई इनहेरिटेंस लागू नहीं है। पढ़ने/लिखने योग्य [NullableBool](../../com.aspose.slides/nullablebool)।

**वापसी:**
byte

### setFontBold(byte value) {#setFontBold-byte-}
```
public abstract void setFontBold(byte value)
```

निर्धारित करता है कि फ़ॉन्ट बोल्ड है या नहीं। कोई इनहेरिटेंस लागू नहीं है। पढ़ने/लिखने योग्य [NullableBool](../../com.aspose.slides/nullablebool)।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | byte |  |

### getFontItalic() {#getFontItalic--}
```
public abstract byte getFontItalic()
```

निर्धारित करता है कि फ़ॉन्ट इटैलिक है या नहीं। कोई इनहेरिटेंस लागू नहीं है। पढ़ने/लिखने योग्य [NullableBool](../../com.aspose.slides/nullablebool)।

**वापसी:**
byte

### setFontItalic(byte value) {#setFontItalic-byte-}
```
public abstract void setFontItalic(byte value)
```

निर्धारित करता है कि फ़ॉन्ट इटैलिक है या नहीं। कोई इनहेरिटेंस लागू नहीं है। पढ़ने/लिखने योग्य [NullableBool](../../com.aspose.slides/nullablebool)।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | byte |  |

### getKumimoji() {#getKumimoji--}
```
public abstract byte getKumimoji()
```

निर्धारित करता है कि संख्याओं को टेक्स्ट के पूर्वीय भाषा-विशिष्ट वर्टिकल लेआउट को नज़रअंदाज़ करना चाहिए या नहीं। कोई इनहेरिटेंस लागू नहीं है। पढ़ने/लिखने योग्य [NullableBool](../../com.aspose.slides/nullablebool)।

**वापसी:**
byte

### setKumimoji(byte value) {#setKumimoji-byte-}
```
public abstract void setKumimoji(byte value)
```

निर्धारित करता है कि संख्याओं को टेक्स्ट के पूर्वीय भाषा-विशिष्ट वर्टिकल लेआउट को नज़रअंदाज़ करना चाहिए या नहीं। कोई इनहेरिटेंस लागू नहीं है। पढ़ने/लिखने योग्य [NullableBool](../../com.aspose.slides/nullablebool)।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | byte |  |

### getNormaliseHeight() {#getNormaliseHeight--}
```
public abstract byte getNormaliseHeight()
```

निर्धारित करता है कि टेक्स्ट की ऊँचाई सामान्यीकृत होनी चाहिए या नहीं। कोई इनहेरिटेंस लागू नहीं है। पढ़ने/लिखने योग्य [NullableBool](../../com.aspose.slides/nullablebool)।

**वापसी:**
byte

### setNormaliseHeight(byte value) {#setNormaliseHeight-byte-}
```
public abstract void setNormaliseHeight(byte value)
```

निर्धारित करता है कि टेक्स्ट की ऊँचाई सामान्यीकृत होनी चाहिए या नहीं। कोई इनहेरिटेंस लागू नहीं है। पढ़ने/लिखने योग्य [NullableBool](../../com.aspose.slides/nullablebool)।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | byte |  |

### getProofDisabled() {#getProofDisabled--}
```
public abstract byte getProofDisabled()
```

निर्धारित करता है कि टेक्स्ट को प्रूफ़ नहीं किया जाना चाहिए या नहीं। कोई इनहेरिटेंस लागू नहीं है। पढ़ने/लिखने योग्य [NullableBool](../../com.aspose.slides/nullablebool)।

**वापसी:**
byte

### setProofDisabled(byte value) {#setProofDisabled-byte-}
```
public abstract void setProofDisabled(byte value)
```

निर्धारित करता है कि टेक्स्ट को प्रूफ़ नहीं किया जाना चाहिए या नहीं। कोई इनहेरिटेंस लागू नहीं है। पढ़ने/लिखने योग्य [NullableBool](../../com.aspose.slides/nullablebool)।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | byte |  |

### getFontUnderline() {#getFontUnderline--}
```
public abstract byte getFontUnderline()
```

टेक्स्ट अंडरलाइन प्रकार को लौटाता है या सेट करता है। कोई इनहेरिटेंस लागू नहीं है। पढ़ने/लिखने योग्य [TextUnderlineType](../../com.aspose.slides/textunderlinetype)।

**वापसी:**
byte

### setFontUnderline(byte value) {#setFontUnderline-byte-}
```
public abstract void setFontUnderline(byte value)
```

टेक्स्ट अंडरलाइन प्रकार को लौटाता है या सेट करता है। कोई इनहेरिटेंस लागू नहीं है। पढ़ने/लिखने योग्य [TextUnderlineType](../../com.aspose.slides/textunderlinetype)।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | byte |  |

### getTextCapType() {#getTextCapType--}
```
public abstract byte getTextCapType()
```

टेक्स्ट कैपिटलाइज़ेशन प्रकार को लौटाता है या सेट करता है। कोई इनहेरिटेंस लागू नहीं है। पढ़ने/लिखने योग्य [TextCapType](../../com.aspose.slides/textcaptype)।

**वापसी:**
byte

### setTextCapType(byte value) {#setTextCapType-byte-}
```
public abstract void setTextCapType(byte value)
```

टेक्स्ट कैपिटलाइज़ेशन प्रकार को लौटाता है या सेट करता है। कोई इनहेरिटेंस लागू नहीं है। पढ़ने/लिखने योग्य [TextCapType](../../com.aspose.slides/textcaptype)।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | byte |  |

### getStrikethroughType() {#getStrikethroughType--}
```
public abstract byte getStrikethroughType()
```

टेक्स्ट के स्ट्राइकथ्रू प्रकार को लौटाता है या सेट करता है। कोई इनहेरिटेंस लागू नहीं है। पढ़ने/लिखने योग्य [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype)।

**वापसी:**
byte

### setStrikethroughType(byte value) {#setStrikethroughType-byte-}
```
public abstract void setStrikethroughType(byte value)
```

टेक्स्ट के स्ट्राइकथ्रू प्रकार को लौटाता है या सेट करता है। कोई इनहेरिटेंस लागू नहीं है। पढ़ने/लिखने योग्य [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype)।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | byte |  |

### isHardUnderlineLine() {#isHardUnderlineLine--}
```
public abstract byte isHardUnderlineLine()
```

निर्धारित करता है कि अंडरलाइन शैली के अपने LineFormat प्रॉपर्टीज़ हैं या यह टेक्स्ट के LineFormat प्रॉपर्टीज़ से विरासत में मिली है। पढ़ने/लिखने योग्य [NullableBool](../../com.aspose.slides/nullablebool)।

**वापसी:**
byte

### setHardUnderlineLine(byte value) {#setHardUnderlineLine-byte-}
```
public abstract void setHardUnderlineLine(byte value)
```

निर्धारित करता है कि अंडरलाइन शैली के अपने LineFormat प्रॉपर्टीज़ हैं या यह टेक्स्ट के LineFormat प्रॉपर्टीज़ से विरासत में मिली है। पढ़ने/लिखने योग्य [NullableBool](../../com.aspose.slides/nullablebool)।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | byte |  |

### isHardUnderlineFill() {#isHardUnderlineFill--}
```
public abstract byte isHardUnderlineFill()
```

निर्धारित करता है कि अंडरलाइन शैली के अपने FillFormat प्रॉपर्टीज़ हैं या यह टेक्स्ट के FillFormat प्रॉपर्टीज़ से विरासत में मिली है। पढ़ने/लिखने योग्य [NullableBool](../../com.aspose.slides/nullablebool)।

**वापसी:**
byte

### setHardUnderlineFill(byte value) {#setHardUnderlineFill-byte-}
```
public abstract void setHardUnderlineFill(byte value)
```

निर्धारित करता है कि अंडरलाइन शैली के अपने FillFormat प्रॉपर्टीज़ हैं या यह टेक्स्ट के FillFormat प्रॉपर्टीज़ से विरासत में मिली है। पढ़ने/लिखने योग्य [NullableBool](../../com.aspose.slides/nullablebool)।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | byte |  |

### getFontHeight() {#getFontHeight--}
```
public abstract float getFontHeight()
```

एक भाग की फ़ॉन्ट ऊँचाई को लौटाता है या सेट करता है। **Float.NaN** का अर्थ है कि ऊँचाई अपरिभाषित है और इसे मास्टर से विरासत में प्राप्त किया जाना चाहिए। पढ़ने/लिखने योग्य float।

**वापसी:**
float

### setFontHeight(float value) {#setFontHeight-float-}
```
public abstract void setFontHeight(float value)
```

एक भाग की फ़ॉन्ट ऊँचाई को लौटाता है या सेट करता है। **Float.NaN** का अर्थ है कि ऊँचाई अपरिभाषित है और इसे मास्टर से विरासत में प्राप्त किया जाना चाहिए। पढ़ने/लिखने योग्य float।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | float |  |

### getLatinFont() {#getLatinFont--}
```
public abstract IFontData getLatinFont()
```

लैटिन फ़ॉन्ट जानकारी को लौटाता है या सेट करता है। Null का अर्थ है कि फ़ॉन्ट अपरिभाषित है और इसे मास्टर से विरासत में प्राप्त किया जाना चाहिए। पढ़ने/लिखने योग्य [IFontData](../../com.aspose.slides/ifontdata)।

**वापसी:**
[IFontData](../../com.aspose.slides/ifontdata)

### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public abstract void setLatinFont(IFontData value)
```

लैटिन फ़ॉन्ट जानकारी को लौटाता है या सेट करता है। Null का अर्थ है कि फ़ॉन्ट अपरिभाषित है और इसे मास्टर से विरासत में प्राप्त किया जाना चाहिए। पढ़ने/लिखने योग्य [IFontData](../../com.aspose.slides/ifontdata)।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEastAsianFont() {#getEastAsianFont--}
```
public abstract IFontData getEastAsianFont()
```

ईस्ट एशियन फ़ॉन्ट जानकारी को लौटाता है या सेट करता है। Null का अर्थ है कि फ़ॉन्ट अपरिभाषित है और इसे मास्टर से विरासत में प्राप्त किया जाना चाहिए। पढ़ने/लिखने योग्य [IFontData](../../com.aspose.slides/ifontdata)।

**वापसी:**
[IFontData](../../com.aspose.slides/ifontdata)

### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public abstract void setEastAsianFont(IFontData value)
```

ईस्ट एशियन फ़ॉन्ट जानकारी को लौटाता है या सेट करता है। Null का अर्थ है कि फ़ॉन्ट अपरिभाषित है और इसे मास्टर से विरासत में प्राप्त किया जाना चाहिए। पढ़ने/लिखने योग्य [IFontData](../../com.aspose.slides/ifontdata)।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getComplexScriptFont() {#getComplexScriptFont--}
```
public abstract IFontData getComplexScriptFont()
```

कॉम्प्लेक्स स्क्रिप्ट फ़ॉन्ट जानकारी को लौटाता है या सेट करता है। Null का अर्थ है कि फ़ॉन्ट अपरिभाषित है और इसे मास्टर से विरासत में प्राप्त किया जाना चाहिए। पढ़ने/लिखने योग्य [IFontData](../../com.aspose.slides/ifontdata)।

**वापसी:**
[IFontData](../../com.aspose.slides/ifontdata)

### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public abstract void setComplexScriptFont(IFontData value)
```

कॉम्प्लेक्स स्क्रिप्ट फ़ॉन्ट जानकारी को लौटाता है या सेट करता है। Null का अर्थ है कि फ़ॉन्ट अपरिभाषित है और इसे मास्टर से विरासत में प्राप्त किया जाना चाहिए। पढ़ने/लिखने योग्य [IFontData](../../com.aspose.slides/ifontdata)।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getSymbolFont() {#getSymbolFont--}
```
public abstract IFontData getSymbolFont()
```

सिम्बोलिक फ़ॉन्ट जानकारी को लौटाता है या सेट करता है। Null का अर्थ है कि फ़ॉन्ट अपरिभाषित है और इसे मास्टर से विरासत में प्राप्त किया जाना चाहिए। पढ़ने/लिखने योग्य [IFontData](../../com.aspose.slides/ifontdata)।

**वापसी:**
[IFontData](../../com.aspose.slides/ifontdata)

### setSymbolFont(IFontData value) {#setSymbolFont-com.aspose.slides.IFontData-}
```
public abstract void setSymbolFont(IFontData value)
```

सिम्बोलिक फ़ॉन्ट जानकारी को लौटाता है या सेट करता है। Null का अर्थ है कि फ़ॉन्ट अपरिभाषित है और इसे मास्टर से विरासत में प्राप्त किया जाना चाहिए। पढ़ने/लिखने योग्य [IFontData](../../com.aspose.slides/ifontdata)।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEscapement() {#getEscapement--}
```
public abstract float getEscapement()
```

सुपरस्क्रिप्ट या सबस्क्रिप्ट टेक्स्ट को लौटाता है या सेट करता है। मान -100% (सबस्क्रिप्ट) से 100% (सुपरस्क्रिप्ट) तक है। **Float.NaN** का अर्थ है कि मान अपरिभाषित है और इसे मास्टर से विरासत में प्राप्त किया जाना चाहिए। पढ़ने/लिखने योग्य float।

**वापसी:**
float

### setEscapement(float value) {#setEscapement-float-}
```
public abstract void setEscapement(float value)
```

सुपरस्क्रिप्ट या सबस्क्रिप्ट टेक्स्ट को लौटाता है या सेट करता है। मान -100% (सबस्क्रिप्ट) से 100% (सुपरस्क्रिप्ट) तक है। **Float.NaN** का अर्थ है कि मान अपरिभाषित है और इसे मास्टर से विरासत में प्राप्त किया जाना चाहिए। पढ़ने/लिखने योग्य float।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | float |  |

### getKerningMinimalSize() {#getKerningMinimalSize--}
```
public abstract float getKerningMinimalSize()
```

न्यूनतम फ़ॉन्ट आकार को लौटाता है या सेट करता है, जिसके लिए कर्निंग सक्रिय होनी चाहिए। **Float.NaN** का अर्थ है कि मान अपरिभाषित है और इसे मास्टर से विरासत में प्राप्त किया जाना चाहिए। पढ़ने/लिखने योग्य float।

**वापसी:**
float

### setKerningMinimalSize(float value) {#setKerningMinimalSize-float-}
```
public abstract void setKerningMinimalSize(float value)
```

न्यूनतम फ़ॉन्ट आकार को लौटाता है या सेट करता है, जिसके लिए कर्निंग सक्रिय होनी चाहिए। **Float.NaN** का अर्थ है कि मान अपरिभाषित है और इसे मास्टर से विरासत में प्राप्त किया जाना चाहिए। पढ़ने/लिखने योग्य float।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | float |  |

### getLanguageId() {#getLanguageId--}
```
public abstract String getLanguageId()
```

प्रूफ़िंग भाषा का Id लौटाता है या सेट करता है। वर्तनी और व्याकरण जाँच के लिए उपयोग किया जाता है। पढ़ने/लिखने योग्य String।

**वापसी:**
java.lang.String

### setLanguageId(String value) {#setLanguageId-java.lang.String-}
```
public abstract void setLanguageId(String value)
```

प्रूफ़िंग भाषा का Id लौटाता है या सेट करता है। वर्तनी और व्याकरण जाँच के लिए उपयोग किया जाता है। पढ़ने/लिखने योग्य String।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternativeLanguageId() {#getAlternativeLanguageId--}
```
public abstract String getAlternativeLanguageId()
```

वैकल्पिक भाषा का Id लौटाता है या सेट करता है। पढ़ने/लिखने योग्य String।

**वापसी:**
java.lang.String

### setAlternativeLanguageId(String value) {#setAlternativeLanguageId-java.lang.String-}
```
public abstract void setAlternativeLanguageId(String value)
```

वैकल्पिक भाषा का Id लौटाता है या सेट करता है। पढ़ने/लिखने योग्य String।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getSpacing() {#getSpacing--}
```
public abstract float getSpacing()
```

इंटरक्रैक्टर स्पेसिंग इंक्रीमेंट को लौटाता है या सेट करता है। **Float.NaN** का अर्थ है कि मान अपरिभाषित है और इसे मास्टर से विरासत में प्राप्त किया जाना चाहिए। पढ़ने/लिखने योग्य float।

**वापसी:**
float

### setSpacing(float value) {#setSpacing-float-}
```
public abstract void setSpacing(float value)
```

इंटरक्रैक्टर स्पेसिंग इंक्रीमेंट को लौटाता है या सेट करता है। **Float.NaN** का अर्थ है कि मान अपरिभाषित है और इसे मास्टर से विरासत में प्राप्त किया जाना चाहिए। पढ़ने/लिखने योग्य float।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | float |  |

### getSpellCheck() {#getSpellCheck--}
```
public abstract boolean getSpellCheck()
```

एक मान प्राप्त करता या सेट करता है जो दर्शाता है कि टेक्स्ट भाग के लिए स्पेल चेकिंग सक्षम है या नहीं। जब यह प्रॉपर्टी false पर सेट की जाती है, तो टेक्स्ट तत्वों के लिए वर्तनी जांच दमन की जाती है। जब true पर सेट की जाती है, तो स्पेल चेकिंग की अनुमति होती है। डिफ़ॉल्ट मान false है।

--------------------

> ```
> Next example demonstrates enabling the SpellCheck flag before saving the presentation:
>  
>  Presentation pres = new Presentation("input.pptx");
>  try {
>      // पहले स्लाइड पर पहले आकार के भीतर पाठ का पहला भाग एक्सेस करें
>      IPortion portion = ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).
>              getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0);
>      // इस पाठ भाग के लिए वर्तनी जांच सक्षम करें
>      portion.getPortionFormat().setSpellCheck(true);
>      // संशोधित प्रस्तुति सहेजें
>      pres.save("output-with-spellcheck.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**वापसी:**
boolean

### setSpellCheck(boolean value) {#setSpellCheck-boolean-}
```
public abstract void setSpellCheck(boolean value)
```

एक मान प्राप्त करता या सेट करता है जो दर्शाता है कि टेक्स्ट भाग के लिए स्पेल चेकिंग सक्षम है या नहीं। जब यह प्रॉपर्टी false पर सेट की जाती है, तो टेक्स्ट तत्वों के लिए वर्तनी जांच दमन की जाती है। जब true पर सेट की जाती है, तो स्पेल चेकिंग की अनुमति होती है। डिफ़ॉल्ट मान false है।

--------------------

> ```
> Next example demonstrates enabling the SpellCheck flag before saving the presentation:
>  
>  Presentation pres = new Presentation("input.pptx");
>  try {
>      // पहले स्लाइड पर पहले आकार के भीतर पाठ का पहला भाग एक्सेस करें
>      IPortion portion = ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).
>              getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0);
>      // इस पाठ भाग के लिए वर्तनी जांच सक्षम करें
>      portion.getPortionFormat().setSpellCheck(true);
>      // संशोधित प्रस्तुति सहेजें
>      pres.save("output-with-spellcheck.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | boolean |  |