---
title: IBasePortionFormat
second_title: Aspose.Slides for Java API संदर्भ
description: यह क्लास टेक्स्ट पार्टिशन फ़ॉर्मेटिंग प्रॉपर्टीज़ को शामिल करती है।
type: docs
url: /hi/com.aspose.slides/ibaseportionformat/
---```
public interface IBasePortionFormat
```

यह क्लास टेक्स्ट पार्टिशन फ़ॉर्मेटिंग प्रॉपर्टीज़ को शामिल करती है। [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) के विपरीत, इस क्लास की सभी प्रॉपर्टीज़ लिखने योग्य हैं।

--------------------

यह क्लास विशिष्ट भाग के लिए परिभाषित टेक्स्ट पार्टिशन फ़ॉर्मेटिंग प्रॉपर्टीज़ को लौटाने और संशोधित करने के लिये उपयोग की जाती है। इसका मतलब है कि मान प्राप्त करते समय कोई इनहेरिटेंस लागू नहीं होती इसलिए अधिकांश मामलों में आप मान "अपरिभाषित" प्राप्त करेंगे।

इफेक्टिव फ़ॉर्मेटिंग पैरामीटर मानों को इनहेरिटेड सहित प्राप्त करने के लिये आपको [IPortionFormat.getEffective](../../com.aspose.slides/iportionformat\#getEffective) मेथड का उपयोग करना होगा जो एक [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) इंस्टेंस लौटाता है।

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getLineFormat()](#getLineFormat--) | टेक्स्ट आउटलाइनिंग के लिए LineFormat प्रॉपर्टीज़ को लौटाता है। |
| [getFillFormat()](#getFillFormat--) | टेक्स्ट FillFormat प्रॉपर्टीज़ को लौटाता है। |
| [getEffectFormat()](#getEffectFormat--) | टेक्स्ट EffectFormat प्रॉपर्टीज़ को लौटाता है। |
| [getHighlightColor()](#getHighlightColor--) | टेक्स्ट को हाईलाइट करने के लिए उपयोग किए गए रंग को लौटाता है। |
| [getUnderlineLineFormat()](#getUnderlineLineFormat--) | अंडरलाइन लाइन को आउटलाइन करने के लिये उपयोग किए गए LineFormat प्रॉपर्टीज़ को लौटाता है। |
| [getUnderlineFillFormat()](#getUnderlineFillFormat--) | अंडरलाइन लाइन FillFormat प्रॉपर्टीज़ को लौटाता है। |
| [getFontBold()](#getFontBold--) | फ़ॉन्ट बोल्ड है या नहीं निर्धारित करता है। |
| [setFontBold(byte value)](#setFontBold-byte-) | फ़ॉन्ट बोल्ड है या नहीं निर्धारित करता है। |
| [getFontItalic()](#getFontItalic--) | फ़ॉन्ट इटैलिक है या नहीं निर्धारित करता है। |
| [setFontItalic(byte value)](#setFontItalic-byte-) | फ़ॉन्ट इटैलिक है या नहीं निर्धारित करता है। |
| [getKumimoji()](#getKumimoji--) | नंबरों को टेक्स्ट के पूर्वी भाषा-विशिष्ट वर्टिकल लेआउट को अनदेखा करना चाहिए या नहीं निर्धारित करता है। |
| [setKumimoji(byte value)](#setKumimoji-byte-) | नंबरों को टेक्स्ट के पूर्वी भाषा-विशिष्ट वर्टिकल लेआउट को अनदेखा करना चाहिए या नहीं निर्धारित करता है। |
| [getNormaliseHeight()](#getNormaliseHeight--) | टेक्स्ट की ऊँचाई को सामान्यीकृत किया जाना चाहिए या नहीं निर्धारित करता है। |
| [setNormaliseHeight(byte value)](#setNormaliseHeight-byte-) | टेक्स्ट की ऊँचाई को सामान्यीकृत किया जाना चाहिए या नहीं निर्धारित करता है। |
| [getProofDisabled()](#getProofDisabled--) | टेक्स्ट को प्रूफ़ नहीं किया जाना चाहिए या नहीं निर्धारित करता है। |
| [setProofDisabled(byte value)](#setProofDisabled-byte-) | टेक्स्ट को प्रूफ़ नहीं किया जाना चाहिए या नहीं निर्धारित करता है। |
| [getFontUnderline()](#getFontUnderline--) | टेक्स्ट अंडरलाइन प्रकार को लौटाता या सेट करता है। |
| [setFontUnderline(byte value)](#setFontUnderline-byte-) | टेक्स्ट अंडरलाइन प्रकार को लौटाता या सेट करता है। |
| [getTextCapType()](#getTextCapType--) | टेक्स्ट कैपिटलाइज़ेशन प्रकार को लौटाता या सेट करता है। |
| [setTextCapType(byte value)](#setTextCapType-byte-) | टेक्स्ट कैपिटलाइज़ेशन प्रकार को लौटाता या सेट करता है। |
| [getStrikethroughType()](#getStrikethroughType--) | टेक्स्ट के स्ट्राइकथ्रू प्रकार को लौटाता या सेट करता है। |
| [setStrikethroughType(byte value)](#setStrikethroughType-byte-) | टेक्स्ट के स्ट्राइकथ्रू प्रकार को लौटाता या सेट करता है। |
| [isHardUnderlineLine()](#isHardUnderlineLine--) | निर्धारित करता है कि अंडरलाइन शैली की अपनी LineFormat प्रॉपर्टीज़ हैं या वह टेक्स्ट की LineFormat प्रॉपर्टीज़ से विरासत में लेती है। |
| [setHardUnderlineLine(byte value)](#setHardUnderlineLine-byte-) | निर्धारित करता है कि अंडरलाइन शैली की अपनी LineFormat प्रॉपर्टीज़ हैं या वह टेक्स्ट की LineFormat प्रॉपर्टीज़ से विरासत में लेती है। |
| [isHardUnderlineFill()](#isHardUnderlineFill--) | निर्धारित करता है कि अंडरलाइन शैली की अपनी FillFormat प्रॉपर्टीज़ हैं या वह टेक्स्ट की FillFormat प्रॉपर्टीज़ से विरासत में लेती है। |
| [setHardUnderlineFill(byte value)](#setHardUnderlineFill-byte-) | निर्धारित करता है कि अंडरलाइन शैली की अपनी FillFormat प्रॉपर्टीज़ हैं या वह टेक्स्ट की FillFormat प्रॉपर्टीज़ से विरासत में लेती है। |
| [getFontHeight()](#getFontHeight--) | एक भाग की फ़ॉन्ट ऊँचाई को लौटाता या सेट करता है। |
| [setFontHeight(float value)](#setFontHeight-float-) | एक भाग की फ़ॉन्ट ऊँचाई को लौटाता या सेट करता है। |
| [getLatinFont()](#getLatinFont--) | लैटिन फ़ॉन्ट जानकारी को लौटाता या सेट करता है। |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | लैटिन फ़ॉन्ट जानकारी को लौटाता या सेट करता है। |
| [getEastAsianFont()](#getEastAsianFont--) | ईस्ट एशियन फ़ॉन्ट जानकारी को लौटाता या सेट करता है। |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | ईस्ट एशियन फ़ॉन्ट जानकारी को लौटाता या सेट करता है। |
| [getComplexScriptFont()](#getComplexScriptFont--) | कम्प्लेक्स स्क्रिप्ट फ़ॉन्ट जानकारी को लौटाता या सेट करता है। |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | कम्प्लेक्स स्क्रिप्ट फ़ॉन्ट जानकारी को लौटाता या सेट करता है। |
| [getSymbolFont()](#getSymbolFont--) | सिम्बॉलिक फ़ॉन्ट जानकारी को लौटाता या सेट करता है। |
| [setSymbolFont(IFontData value)](#setSymbolFont-com.aspose.slides.IFontData-) | सिम्बॉलिक फ़ॉन्ट जानकारी को लौटाता या सेट करता है। |
| [getEscapement()](#getEscapement--) | सुपरस्क्रिप्ट या सबस्क्रिप्ट टेक्स्ट को लौटाता या सेट करता है। |
| [setEscapement(float value)](#setEscapement-float-) | सुपरस्क्रिप्ट या सबस्क्रिप्ट टेक्स्ट को लौटाता या सेट करता है। |
| [getKerningMinimalSize()](#getKerningMinimalSize--) | न्यूनतम फ़ॉन्ट आकार को लौटाता या सेट करता है, जिसके लिए करनिंग सक्रिय किया जाना चाहिए। |
| [setKerningMinimalSize(float value)](#setKerningMinimalSize-float-) | न्यूनतम फ़ॉन्ट आकार को लौटाता या सेट करता है, जिसके लिए करनिंग सक्रिय किया जाना चाहिए। |
| [getLanguageId()](#getLanguageId--) | प्रूफ़िंग भाषा का Id लौटाता या सेट करता है। |
| [setLanguageId(String value)](#setLanguageId-java.lang.String-) | प्रूफ़िंग भाषा का Id लौटाता या सेट करता है। |
| [getAlternativeLanguageId()](#getAlternativeLanguageId--) | वैकल्पिक भाषा का Id लौटाता या सेट करता है। |
| [setAlternativeLanguageId(String value)](#setAlternativeLanguageId-java.lang.String-) | वैकल्पिक भाषा का Id लौटा

ए या सेट करता है। |
| [getSpacing()](#getSpacing--) | इंटरकैरेक्टर स्पेसिंग इन्क्रीमेंट को लौटाता या सेट करता है। |
| [setSpacing(float value)](#setSpacing-float-) | इंटरकैरेक्टर स्पेसिंग इन्क्रीमेंट को लौटाता या सेट करता है। |
| [getSpellCheck()](#getSpellCheck--) | टेक्स्ट भाग के लिये स्पेल चेकिंग सक्षम है या नहीं, यह दर्शाने वाला मान प्राप्त करता या सेट करता है। |
| [setSpellCheck(boolean value)](#setSpellCheck-boolean-) | टेक्स्ट भाग के लिये स्पेल चेकिंग सक्षम है या नहीं, यह दर्शाने वाला मान प्राप्त करता या सेट करता है। |

### getLineFormat() {#getLineFormat--}
```
public abstract ILineFormat getLineFormat()
```

टेक्स्ट आउटलाइनिंग के लिए LineFormat प्रॉपर्टीज़ को लौटाता है। कोई इनहेरिटेंस लागू नहीं। केवल-पढ़ने योग्य [ILineFormat](../../com.aspose.slides/ilineformat)।

**रिटर्न:**  
[ILineFormat](../../com.aspose.slides/ilineformat)

### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

टेक्स्ट FillFormat प्रॉपर्टीज़ को लौटाता है। कोई इनहेरिटेंस लागू नहीं। केवल-पढ़ने योग्य [IFillFormat](../../com.aspose.slides/ifillformat)।

**रिटर्न:**  
[IFillFormat](../../com.aspose.slides/ifillformat)

### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormat getEffectFormat()
```

टेक्स्ट EffectFormat प्रॉपर्टीज़ को लौटाता है। कोई इनहेरिटेंस लागू नहीं। केवल-पढ़ने योग्य [IEffectFormat](../../com.aspose.slides/ieffectformat)।

**रिटर्न:**  
[IEffectFormat](../../com.aspose.slides/ieffectformat)

### getHighlightColor() {#getHighlightColor--}
```
public abstract IColorFormat getHighlightColor()
```

टेक्स्ट को हाईलाइट करने के लिए उपयोग किए गए रंग को लौटाता है। कोई इनहेरिटेंस लागू नहीं। केवल-पढ़ने योग्य [IColorFormat](../../com.aspose.slides/icolorformat)।

**रिटर्न:**  
[IColorFormat](../../com.aspose.slides/icolorformat)

### getUnderlineLineFormat() {#getUnderlineLineFormat--}
```
public abstract ILineFormat getUnderlineLineFormat()
```

अंडरलाइन लाइन को आउटलाइन करने के लिये उपयोग किए गए LineFormat प्रॉपर्टीज़ को लौटाता है। कोई इनहेरिटेंस लागू नहीं। केवल-पढ़ने योग्य [ILineFormat](../../com.aspose.slides/ilineformat)।

**रिटर्न:**  
[ILineFormat](../../com.aspose.slides/ilineformat)

### getUnderlineFillFormat() {#getUnderlineFillFormat--}
```
public abstract IFillFormat getUnderlineFillFormat()
```

अंडरलाइन लाइन FillFormat प्रॉपर्टीज़ को लौटाता है। कोई इनहेरिटेंस लागू नहीं। केवल-पढ़ने योग्य [IFillFormat](../../com.aspose.slides/ifillformat)।

**रिटर्न:**  
[IFillFormat](../../com.aspose.slides/ifillformat)

### getFontBold() {#getFontBold--}
```
public abstract byte getFontBold()
```

फ़ॉन्ट बोल्ड है या नहीं निर्धारित करता है। कोई इनहेरिटेंस लागू नहीं। पढ़ें/लिखें [NullableBool](../../com.aspose.slides/nullablebool)।

**रिटर्न:**  
byte

### setFontBold(byte value) {#setFontBold-byte-}
```
public abstract void setFontBold(byte value)
```

फ़ॉन्ट बोल्ड है या नहीं निर्धारित करता है। कोई इनहेरिटेंस लागू नहीं। पढ़ें/लिखें [NullableBool](../../com.aspose.slides/nullablebool)।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |

### getFontItalic() {#getFontItalic--}
```
public abstract byte getFontItalic()
```

फ़ॉन्ट इटैलिक है या नहीं निर्धारित करता है। कोई इनहेरिटेंस लागू नहीं। पढ़ें/लिखें [NullableBool](../../com.aspose.slides/nullablebool)।

**रिटर्न:**  
byte

### setFontItalic(byte value) {#setFontItalic-byte-}
```
public abstract void setFontItalic(byte value)
```

फ़ॉन्ट इटैलिक है या नहीं निर्धारित करता है। कोई इनहेरिटेंस लागू नहीं। पढ़ें/लिखें [NullableBool](../../com.aspose.slides/nullablebool)।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |

### getKumimoji() {#getKumimoji--}
```
public abstract byte getKumimoji()
```

नंबरों को टेक्स्ट के पूर्वी भाषा-विशिष्ट वर्टिकल लेआउट को अनदेखा करना चाहिए या नहीं निर्धारित करता है। कोई इनहेरिटेंस लागू नहीं। पढ़ें/लिखें [NullableBool](../../com.aspose.slides/nullablebool)।

**रिटर्न:**  
byte

### setKumimoji(byte value) {#setKumimoji-byte-}
```
public abstract void setKumimoji(byte value)
```

नंबरों को टेक्स्ट के पूर्वी भाषा-विशिष्ट वर्टिकल लेआउट को अनदेखा करना चाहिए या नहीं निर्धारित करता है। कोई इनहेरिटेंस लागू नहीं। पढ़ें/लिखें [NullableBool](../../com.aspose.slides/nullablebool)।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |

### getNormaliseHeight() {#getNormaliseHeight--}
```
public abstract byte getNormaliseHeight()
```

टेक्स्ट की ऊँचाई को सामान्यीकृत किया जाना चाहिए या नहीं निर्धारित करता है। कोई इनहेरिटेंस लागू नहीं। पढ़ें/लिखें [NullableBool](../../com.aspose.slides/nullablebool)।

**रिटर्न:**  
byte

### setNormaliseHeight(byte value) {#setNormaliseHeight-byte-}
```
public abstract void setNormaliseHeight(byte value)
```

टेक्स्ट की ऊँचाई को सामान्यीकृत किया जाना चाहिए या नहीं निर्धारित करता है। कोई इनहेरिटेंस लागू नहीं। पढ़ें/लिखें [NullableBool](../../com.aspose.slides/nullablebool)।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |

### getProofDisabled() {#getProofDisabled--}
```
public abstract byte getProofDisabled()
```

टेक्स्ट को प्रूफ़ नहीं किया जाना चाहिए या नहीं निर्धारित करता है। कोई इनहेरिटेंस लागू नहीं। पढ़ें/लिखें [NullableBool](../../com.aspose.slides/nullablebool)।

**रिटर्न:**  
byte

### setProofDisabled(byte value) {#setProofDisabled-byte-}
```
public abstract void setProofDisabled(byte value)
```

टेक्स्ट को प्रूफ़ नहीं किया जाना चाहिए या नहीं निर्धारित करता है। कोई इनहेरिटेंस लागू नहीं। पढ़ें/लिखें [NullableBool](../../com.aspose.slides/nullablebool)।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |

### getFontUnderline() {#getFontUnderline--}
```
public abstract byte getFontUnderline()
```

टेक्स्ट अंडरलाइन प्रकार को लौटाता या सेट करता है। कोई इनहेरिटेंस लागू नहीं। पढ़ें/लिखें [TextUnderlineType](../../com.aspose.slides/textunderlinetype)।

**रिटर्न:**  
byte

### setFontUnderline(byte value) {#setFontUnderline-byte-}
```
public abstract void setFontUnderline(byte value)
```

टेक्स्ट अंडरलाइन प्रकार को लौटाता या सेट करता है। कोई इनहेरिटेंस लागू नहीं। पढ़ें/लिखें [TextUnderlineType](../../com.aspose.slides/textunderlinetype)।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |

### getTextCapType() {#getTextCapType--}
```
public abstract byte getTextCapType()
```

टेक्स्ट कैपिटलाइज़ेशन प्रकार को लौटाता या सेट करता है। कोई इनहेरिटेंस लागू नहीं। पढ़ें/लिखें [TextCapType](../../com.aspose.slides/textcaptype)।

**रिटर्न:**  
byte

### setTextCapType(byte value) {#setTextCapType-byte-}
```
public abstract void setTextCapType(byte value)
```

टेक्स्ट कैपिटलाइज़ेशन प्रकार को लौटाता या सेट करता है। कोई इनहेरिटेंस लागू नहीं। पढ़ें/लिखें [TextCapType](../../com.aspose.slides/textcaptype)।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |

### getStrikethroughType() {#getStrikethroughType--}
```
public abstract byte getStrikethroughType()
```

टेक्स्ट के स्ट्राइकथ्रू प्रकार को लौटाता या सेट करता है। कोई इनहेरिटेंस लागू नहीं। पढ़ें/लिखें [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype)।

**रिटर्न:**  
byte

### setStrikethroughType(byte value) {#setStrikethroughType-byte-}
```
public abstract void setStrikethroughType(byte value)
```

टेक्स्ट के स्ट्राइकथ्रू प्रकार को लौटाता या सेट करता है। कोई इनहेरिटेंस लागू नहीं। पढ़ें/लिखें [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype)।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |

### isHardUnderlineLine() {#isHardUnderlineLine--}
```
public abstract byte isHardUnderlineLine()
```

निर्धारित करता है कि अंडरलाइन शैली की अपनी LineFormat प्रॉपर्टीज़ हैं या वह टेक्स्ट की LineFormat प्रॉपर्टीज़ से विरासत में लेती है। पढ़ें/लिखें [NullableBool](../../com.aspose.slides/nullablebool)।

**रिटर्न:**  
byte

### setHardUnderlineLine(byte value) {#setHardUnderlineLine-byte-}
```
public abstract void setHardUnderlineLine(byte value)
```

निर्धारित करता है कि अंडरलाइन शैली की अपनी LineFormat प्रॉपर्टीज़ हैं या वह टेक्स्ट की LineFormat प्रॉपर्टीज़ से विरासत में लेती है। पढ़ें/लिखें [NullableBool](../../com.aspose.slides/nullablebool)।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |

### isHardUnderlineFill() {#isHardUnderlineFill--}
```
public abstract byte isHardUnderlineFill()
```

निर्धारित करता है कि अंडरलाइन शैली की अपनी FillFormat प्रॉपर्टीज़ हैं या वह टेक्स्ट की FillFormat प्रॉपर्टीज़ से विरासत में लेती है। पढ़ें/लिखें [NullableBool](../../com.aspose.slides/nullablebool)।

**रिटर्न:**  
byte

### setHardUnderlineFill(byte value) {#setHardUnderlineFill-byte-}
```
public abstract void setHardUnderlineFill(byte value)
```

निर्धारित करता है कि अंडरलाइन शैली की अपनी FillFormat प्रॉपर्टीज़ हैं या वह टेक्स्ट की FillFormat प्रॉपर्टीज़ से विरासत में लेती है। पढ़ें/लिखें [NullableBool](../../com.aspose.slides/nullablebool)।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |

### getFontHeight() {#getFontHeight--}
```
public abstract float getFontHeight()
```

एक भाग की फ़ॉन्ट ऊँचाई को लौटाता या सेट करता है। **Float.NaN** का अर्थ है ऊँचाई अपरिभाषित है और इसे मास्टर से विरासत में लेना चाहिए। पढ़ें/लिखें float।

**रिटर्न:**  
float

### setFontHeight(float value) {#setFontHeight-float-}
```
public abstract void setFontHeight(float value)
```

एक भाग की फ़ॉन्ट ऊँचाई को लौटाता या सेट करता है। **Float.NaN** का अर्थ है ऊँचाई अपरिभाषित है और इसे मास्टर से विरासत में लेना चाहिए। पढ़ें/लिखें float।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### getLatinFont() {#getLatinFont--}
```
public abstract IFontData getLatinFont()
```

लैटिन फ़ॉन्ट जानकारी को लौटाता या सेट करता है। null का अर्थ है फ़ॉन्ट अपरिभाषित है और इसे मास्टर से विरासत में लेना चाहिए। पढ़ें/लिखें [IFontData](../../com.aspose.slides/ifontdata)।

**रिटर्न:**  
[IFontData](../../com.aspose.slides/ifontdata)

### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public abstract void setLatinFont(IFontData value)
```

लैटिन फ़ॉन्ट जानकारी को लौटाता या सेट करता है। null का अर्थ है फ़ॉन्ट अपरिभाषित है और इसे मास्टर से विरासत में लेना चाहिए। पढ़ें/लिखें [IFontData](../../com.aspose.slides/ifontdata)।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEastAsianFont() {#getEastAsianFont--}
```
public abstract IFontData getEastAsianFont()
```

ईस्ट एशियन फ़ॉन्ट जानकारी को लौटाता या सेट करता है। null का अर्थ है फ़ॉन्ट अपरिभाषित है और इसे मास्टर से विरासत में लेना चाहिए। पढ़ें/लिखें [IFontData](../../com.aspose.slides/ifontdata)।

**रिटर्न:**  
[IFontData](../../com.aspose.slides/ifontdata)

### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public abstract void setEastAsianFont(IFontData value)
```

ईस्ट एशियन फ़ॉन्ट जानकारी को लौटाता या सेट करता है। null का अर्थ है फ़ॉन्ट अपरिभाषित है और इसे मास्टर से विरासत में लेना चाहिए। पढ़ें/लिखें [IFontData](../../com.aspose.slides/ifontdata)।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getComplexScriptFont() {#getComplexScriptFont--}
```
public abstract IFontData getComplexScriptFont()
```

कम्प्लेक्स स्क्रिप्ट फ़ॉन्ट जानकारी को लौटाता या सेट करता है। null का अर्थ है फ़ॉन्ट अपरिभाषित है और इसे मास्टर से विरासत में लेना चाहिए। पढ़ें/लिखें [IFontData](../../com.aspose.slides/ifontdata)।

**रिटर्न:**  
[IFontData](../../com.aspose.slides/ifontdata)

### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public abstract void setComplexScriptFont(IFontData value)
```

कम्प्लेक्स स्क्रिप्ट फ़ॉन्ट जानकारी को लौटाता या सेट करता है। null का अर्थ है फ़ॉन्ट अपरिभाषित है और इसे मास्टर से विरासत में लेना चाहिए। पढ़ें/लिखें [IFontData](../../com.aspose.slides/ifontdata)।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getSymbolFont() {#getSymbolFont--}
```
public abstract IFontData getSymbolFont()
```

सिम्बॉलिक फ़ॉन्ट जानकारी को लौटाता या सेट करता है। null का अर्थ है फ़ॉन्ट अपरिभाषित है और इसे मास्टर से विरासत में लेना चाहिए। पढ़ें/लिखें [IFontData](../../com.aspose.slides/ifontdata)।

**रिटर्न:**  
[IFontData](../../com.aspose.slides/ifontdata)

### setSymbolFont(IFontData value) {#setSymbolFont-com.aspose.slides.IFontData-}
```
public abstract void setSymbolFont(IFontData value)
```

सिम्बॉलिक फ़ॉन्ट जानकारी को लौटाता या सेट करता है। null का अर्थ है फ़ॉन्ट अपरिभाषित है और इसे मास्टर से विरासत में लेना चाहिए। पढ़ें/लिखें [IFontData](../../com.aspose.slides/ifontdata)।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEscapement() {#getEscapement--}
```
public abstract float getEscapement()
```

सुपरस्क्रिप्ट या सबस्क्रिप्ट टेक्स्ट को लौटाता या सेट करता है। -100% (सबस्क्रिप्ट) से 100% (सुपरस्क्रिप्ट) तक का मान। **Float.NaN** का अर्थ है मान अपरिभाषित है और इसे मास्टर से विरासत में लेना चाहिए। पढ़ें/लिखें float।

**रिटर्न:**  
float

### setEscapement(float value) {#setEscapement-float-}
```
public abstract void setEscapement(float value)
```

सुपरस्क्रिप्ट या सबस्क्रिप्ट टेक्स्ट को लौटाता या सेट करता है। -100% (सबस्क्रिप्ट) से 100% (सुपरस्क्रिप्ट) तक का मान। **Float.NaN** का अर्थ है मान अपरिभाषित है और इसे मास्टर से विरासत में लेना चाहिए। पढ़ें/लिखें float।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### getKerningMinimalSize() {#getKerningMinimalSize--}
```
public abstract float getKerningMinimalSize()
```

न्यूनतम फ़ॉन्ट आकार को लौटाता या सेट करता है, जिसके लिए करनिंग सक्रिय किया जाना चाहिए। **Float.NaN** का अर्थ है मान अपरिभाषित है और इसे मास्टर से विरासत में लेना चाहिए। पढ़ें/लिखें float।

**रिटर्न:**  
float

### setKerningMinimalSize(float value) {#setKerningMinimalSize-float-}
```
public abstract void setKerningMinimalSize(float value)
```

न्यूनतम फ़ॉन्ट आकार को लौटाता या सेट करता है, जिसके लिए करनिंग सक्रिय किया जाना चाहिए। **Float.NaN** का अर्थ है मान अपरिभाषित है और इसे मास्टर से विरासत में लेना चाहिए। पढ़ें/लिखें float।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### getLanguageId() {#getLanguageId--}
```
public abstract String getLanguageId()
```

प्रूफ़िंग भाषा का Id लौटाता या सेट करता है। स्पेलिंग और ग्रामर जांच के लिये उपयोग किया जाता है। पढ़ें/लिखें String।

**रिटर्न:**  
java.lang.String

### setLanguageId(String value) {#setLanguageId-java.lang.String-}
```
public abstract void setLanguageId(String value)
```

प्रूफ़िंग भाषा का Id लौटाता या सेट करता है। स्पेलिंग और ग्रामर जांच के लिये उपयोग किया जाता है। पढ़ें/लिखें String।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternativeLanguageId() {#getAlternativeLanguageId--}
```
public abstract String getAlternativeLanguageId()
```

वैकल्पिक भाषा का Id लौटाता या सेट करता है। पढ़ें/लिखें String।

**रिटर्न:**  
java.lang.String

### setAlternativeLanguageId(String value) {#setAlternativeLanguageId-java.lang.String-}
```
public abstract void setAlternativeLanguageId(String value)
```

वैकल्पिक भाषा का Id लौटाता या सेट करता है। पढ़ें/लिखें String।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getSpacing() {#getSpacing--}
```
public abstract float getSpacing()
```

इंटरकैरेक्टर स्पेसिंग इन्क्रीमेंट को लौटाता या सेट करता है। **Float.NaN** का अर्थ है मान अपरिभाषित है और इसे मास्टर से विरासत में लेना चाहिए। पढ़ें/लिखें float।

**रिटर्न:**  
float

### setSpacing(float value) {#setSpacing-float-}
```
public abstract void setSpacing(float value)
```

इंटरकैरेक्टर स्पेसिंग इन्क्रीमेंट को लौटाता या सेट करता है। **Float.NaN** का अर्थ है मान अपरिभाषित है और इसे मास्टर से विरासत में लेना चाहिए। पढ़ें/लिखें float।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### getSpellCheck() {#getSpellCheck--}
```
public abstract boolean getSpellCheck()
```

एक मान को प्राप्त करता या सेट करता है जो दर्शाता है कि टेक्स्ट भाग के लिये स्पेल चेकिंग सक्षम है या नहीं। जब यह प्रॉपर्टी false पर सेट होती है तो टेक्स्ट एलिमेंट्स के लिये स्पेलिंग जांच दमन की जाती है। जब true पर सेट होती है तो स्पेल चेकिंग अनुमति प्राप्त होती है। डिफ़ॉल्ट मान false है।

--------------------

> ```
> Next example demonstrates enabling the SpellCheck flag before saving the presentation:
>  
>  Presentation pres = new Presentation("input.pptx");
>  try {
>      // Access the first portion of text inside the first shape on the first slide
>      IPortion portion = ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).
>              getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0);
>      // Enable spell checking for this text portion
>      portion.getPortionFormat().setSpellCheck(true);
>      // Save the modified presentation
>      pres.save("output-with-spellcheck.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**रिटर्न:**  
boolean

### setSpellCheck(boolean value) {#setSpellCheck-boolean-}
```
public abstract void setSpellCheck(boolean value)
```

एक मान को प्राप्त करता या सेट करता है जो दर्शाता है कि टेक्स्ट भाग के लिये स्पेल चेकिंग सक्षम है या नहीं। जब यह प्रॉपर्टी false पर सेट होती है तो टेक्स्ट एलिमेंट्स के लिये स्पेलिंग जांच दमन की जाती है। जब true पर सेट होती है तो स्पेल चेकिंग अनुमति प्राप्त होती है। डिफ़ॉल्ट मान false है।

--------------------

> ```
> Next example demonstrates enabling the SpellCheck flag before saving the presentation:
>  
>  Presentation pres = new Presentation("input.pptx");
>  try {
>      // Access the first portion of text inside the first shape on the first slide
>      IPortion portion = ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).
>              getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0);
>      // Enable spell checking for this text portion
>      portion.getPortionFormat().setSpellCheck(true);
>      // Save the modified presentation
>      pres.save("output-with-spellcheck.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |