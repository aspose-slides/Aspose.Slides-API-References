---
title: BasePortionFormat
second_title: Aspose.Slides for Android के लिए Java API रेफ़रेंस
description: सामान्य टेक्स्ट भाग फ़ॉर्मेटिंग गुण।
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

सामान्य टेक्स्ट भाग फ़ॉर्मेटिंग गुण।

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getLineFormat()](#getLineFormat--) | टेक्स्ट रूपरेखा के लिए LineFormat गुण लौटाता है। |
| [getFillFormat()](#getFillFormat--) | टेक्स्ट FillFormat गुण लौटाता है। |
| [getEffectFormat()](#getEffectFormat--) | टेक्स्ट EffectFormat गुण लौटाता है। |
| [getHighlightColor()](#getHighlightColor--) | टेक्स्ट को हाइलाइट करने के लिए उपयोग किया गया रंग लौटाता है। |
| [getUnderlineLineFormat()](#getUnderlineLineFormat--) | अंडरलाइन रेखा को रूपरेखा देने के लिए उपयोग किए गए LineFormat गुण लौटाता है। |
| [getUnderlineFillFormat()](#getUnderlineFillFormat--) | अंडरलाइन रेखा FillFormat गुण लौटाता है। |
| [getFontBold()](#getFontBold--) | निर्धारित करता है कि फ़ॉन्ट बोल्ड है या नहीं। |
| [setFontBold(byte value)](#setFontBold-byte-) | निर्धारित करता है कि फ़ॉन्ट बोल्ड है या नहीं। |
| [getFontItalic()](#getFontItalic--) | निर्धारित करता है कि फ़ॉन्ट इटैलिक है या नहीं। |
| [setFontItalic(byte value)](#setFontItalic-byte-) | निर्धारित करता है कि फ़ॉन्ट इटैलिक है या नहीं। |
| [getKumimoji()](#getKumimoji--) | निर्धारित करता है कि संख्याओं को टेक्स्ट पूर्वी-भाषा-विशिष्ट ऊर्ध्वाधर लेआउट को नज़रअंदाज़ करना चाहिए या नहीं। |
| [setKumimoji(byte value)](#setKumimoji-byte-) | निर्धारित करता है कि संख्याओं को टेक्स्ट पूर्वी-भाषा-विशिष्ट ऊर्ध्वाधर लेआउट को नज़रअंदाज़ करना चाहिए या नहीं। |
| [getNormaliseHeight()](#getNormaliseHeight--) | निर्धारित करता है कि टेक्स्ट की ऊँचाई को सामान्यीकृत किया जाना चाहिए या नहीं। |
| [setNormaliseHeight(byte value)](#setNormaliseHeight-byte-) | निर्धारित करता है कि टेक्स्ट की ऊँचाई को सामान्यीकृत किया जाना चाहिए या नहीं। |
| [getProofDisabled()](#getProofDisabled--) | निर्धारित करता है कि टेक्स्ट प्रूफ़ नहीं किया जाना चाहिए या नहीं। |
| [setProofDisabled(byte value)](#setProofDisabled-byte-) | निर्धारित करता है कि टेक्स्ट प्रूफ़ नहीं किया जाना चाहिए या नहीं। |
| [getFontUnderline()](#getFontUnderline--) | टेक्स्ट अंडरलाइन प्रकार लौटाता है या सेट करता है। |
| [setFontUnderline(byte value)](#setFontUnderline-byte-) | टेक्स्ट अंडरलाइन प्रकार लौटाता है या सेट करता है। |
| [getTextCapType()](#getTextCapType--) | टेक्स्ट कैपिटलाइजेशन प्रकार लौटाता है या सेट करता है। |
| [setTextCapType(byte value)](#setTextCapType-byte-) | टेक्स्ट कैपिटलाइजेशन प्रकार लौटाता है या सेट करता है। |
| [getStrikethroughType()](#getStrikethroughType--) | टेक्स्ट के स्ट्राइकथ्रू प्रकार को लौटाता है या सेट करता है। |
| [setStrikethroughType(byte value)](#setStrikethroughType-byte-) | टेक्स्ट के स्ट्राइकथ्रू प्रकार को लौटाता है या सेट करता है। |
| [isHardUnderlineLine()](#isHardUnderlineLine--) | निर्धारित करता है कि अंडरलाइन शैली के पास अपनी LineFormat गुण हैं या यह टेक्स्ट की LineFormat गुणों से विरासत में प्राप्त करता है। |
| [setHardUnderlineLine(byte value)](#setHardUnderlineLine-byte-) | निर्धारित करता है कि अंडरलाइन शैली के पास अपनी LineFormat गुण हैं या यह टेक्स्ट की LineFormat गुणों से विरासत में प्राप्त करता है। |
| [isHardUnderlineFill()](#isHardUnderlineFill--) | निर्धारित करता है कि अंडरलाइन शैली के पास अपनी FillFormat गुण हैं या यह टेक्स्ट की FillFormat गुणों से विरासत में प्राप्त करता है। |
| [setHardUnderlineFill(byte value)](#setHardUnderlineFill-byte-) | निर्धारित करता है कि अंडरलाइन शैली के पास अपनी FillFormat गुण हैं या यह टेक्स्ट की FillFormat गुणों से विरासत में प्राप्त करता है। |
| [getFontHeight()](#getFontHeight--) | एक भाग की फ़ॉन्ट ऊँचाई को लौटाता है या सेट करता है। |
| [setFontHeight(float value)](#setFontHeight-float-) | एक भाग की फ़ॉन्ट ऊँचाई को लौटाता है या सेट करता है। |
| [getLatinFont()](#getLatinFont--) | लैटिन फ़ॉन्ट जानकारी को लौटाता है या सेट करता है। |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | लैटिन फ़ॉन्ट जानकारी को लौटाता है या सेट करता है। |
| [getEastAsianFont()](#getEastAsianFont--) | ईस्ट एशियन फ़ॉन्ट जानकारी को लौटाता है या सेट करता है। |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | ईस्ट एशियन फ़ॉन्ट जानकारी को लौटाता है या सेट करता है। |
| [getComplexScriptFont()](#getComplexScriptFont--) | जटिल स्क्रिप्ट फ़ॉन्ट जानकारी को लौटाता है या सेट करता है। |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | जटिल स्क्रिप्ट फ़ॉन्ट जानकारी को लौटाता है या सेट करता है। |
| [getSymbolFont()](#getSymbolFont--) | प्रतीकात्मक फ़ॉन्ट जानकारी को लौटाता है या सेट करता है। |
| [setSymbolFont(IFontData value)](#setSymbolFont-com.aspose.slides.IFontData-) | प्रतीकात्मक फ़ॉन्ट जानकारी को लौटाता है या सेट करता है। |
| [getEscapement()](#getEscapement--) | सुपरसक्रिप्ट या सबस्क्रिप्ट टेक्स्ट को लौटाता है या सेट करता है। |
| [setEscapement(float value)](#setEscapement-float-) | सुपरसक्रिप्ट या सबस्क्रिप्ट टेक्स्ट को लौटाता है या सेट करता है। |
| [getKerningMinimalSize()](#getKerningMinimalSize--) | न्यूनतम फ़ॉन्ट आकार को लौटाता है या सेट करता है, जिसके लिए कर्निंग सक्रिय किया जाना चाहिए। |
| [setKerningMinimalSize(float value)](#setKerningMinimalSize-float-) | न्यूनतम फ़ॉन्ट आकार को लौटाता है या सेट करता है, जिसके लिए कर्निंग सक्रिय किया जाना चाहिए। |
| [getLanguageId()](#getLanguageId--) | प्रूफ़िंग भाषा का Id लौटाता है या सेट करता है। |
| [setLanguageId(String value)](#setLanguageId-java.lang.String-) | प्रूफ़िंग भाषा का Id लौटाता है या सेट करता है। |
| [getAlternativeLanguageId()](#getAlternativeLanguageId--) | वैकल्पिक भाषा का Id लौटाता है या सेट करता है। |
| [setAlternativeLanguageId(String value)](#setAlternativeLanguageId-java.lang.String-) | वैकल्पिक भाषा का Id लौटाता है या सेट करता है। |
| [getSpacing()](#getSpacing--) | अक्षर अंतराल वृद्धि को लौटाता है या सेट करता है। |
| [setSpacing(float value)](#setSpacing-float-) | अक्षर अंतराल वृद्धि को लौटाता है या सेट करता है। |
| [getSpellCheck()](#getSpellCheck--) | टेक्स्ट भाग के लिए वर्तनी जांच सक्षम है या नहीं, यह दर्शाने वाले मान को प्राप्त करता या सेट करता है। |
| [setSpellCheck(boolean value)](#setSpellCheck-boolean-) | टेक्स्ट भाग के लिए वर्तनी जांच सक्षम है या नहीं, यह दर्शाने वाले मान को प्राप्त करता या सेट करता है। |

### getVersion() {#getVersion--}
```
public long getVersion()
```

संस्करण। केवल पढ़ने योग्य long।

**वापसी:**
long

### getLineFormat() {#getLineFormat--}
```
public final ILineFormat getLineFormat()
```

टेक्स्ट रूपरेखा के लिए LineFormat गुण लौटाता है। कोई विरासत लागू नहीं। केवल पढ़ने योग्य [ILineFormat](../../com.aspose.slides/ilineformat)।

**वापसी:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```

टेक्स्ट FillFormat गुण लौटाता है। कोई विरासत लागू नहीं। केवल पढ़ने योग्य [IFillFormat](../../com.aspose.slides/ifillformat)।

**वापसी:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getEffectFormat() {#getEffectFormat--}
```
public final IEffectFormat getEffectFormat()
```

टेक्स्ट EffectFormat गुण लौटाता है। कोई विरासत लागू नहीं। केवल पढ़ने योग्य [IEffectFormat](../../com.aspose.slides/ieffectformat)।

**वापसी:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)

### getHighlightColor() {#getHighlightColor--}
```
public final IColorFormat getHighlightColor()
```

टेक्स्ट को हाइलाइट करने के लिए उपयोग किया गया रंग लौटाता है। कोई विरासत लागू नहीं। केवल पढ़ने योग्य [IColorFormat](../../com.aspose.slides/icolorformat)।

**वापसी:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getUnderlineLineFormat() {#getUnderlineLineFormat--}
```
public final ILineFormat getUnderlineLineFormat()
```

अंडरलाइन रेखा को रूपरेखा देने के लिए उपयोग किए गए LineFormat गुण लौटाता है। कोई विरासत लागू नहीं। केवल पढ़ने योग्य [ILineFormat](../../com.aspose.slides/ilineformat)।

**वापसी:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getUnderlineFillFormat() {#getUnderlineFillFormat--}
```
public final IFillFormat getUnderlineFillFormat()
```

अंडरलाइन रेखा FillFormat गुण लौटाता है। कोई विरासत लागू नहीं। केवल पढ़ने योग्य [IFillFormat](../../com.aspose.slides/ifillformat)।

**वापसी:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getFontBold() {#getFontBold--}
```
public final byte getFontBold()
```

निर्धारित करता है कि फ़ॉन्ट बोल्ड है या नहीं। कोई विरासत लागू नहीं। पढ़ने/लिखने योग्य [NullableBool](../../com.aspose.slides/nullablebool)।

**वापसी:**
byte

### setFontBold(byte value) {#setFontBold-byte-}
```
public final void setFontBold(byte value)
```

निर्धारित करता है कि फ़ॉन्ट बोल्ड है या नहीं। कोई विरासत लागू नहीं। पढ़ने/लिखने योग्य [NullableBool](../../com.aspose.slides/nullablebool)।

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getFontItalic() {#getFontItalic--}
```
public final byte getFontItalic()
```

निर्धारित करता है कि फ़ॉन्ट इटैलिक है या नहीं। कोई विरासत लागू नहीं। पढ़ने/लिखने योग्य [NullableBool](../../com.aspose.slides/nullablebool)।

**वापसी:**
byte

### setFontItalic(byte value) {#setFontItalic-byte-}
```
public final void setFontItalic(byte value)
```

निर्धारित करता है कि फ़ॉन्ट इटैलिक है या नहीं। कोई विरासत लागू नहीं। पढ़ने/लिखने योग्य [NullableBool](../../com.aspose.slides/nullablebool)।

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getKumimoji() {#getKumimoji--}
```
public final byte getKumimoji()
```

निर्धारित करता है कि संख्याओं को टेक्स्ट पूर्वी-भाषा-विशिष्ट ऊर्ध्वाधर लेआउट को नज़रअंदाज़ करना चाहिए या नहीं। कोई विरासत लागू नहीं। पढ़ने/लिखने योग्य [NullableBool](../../com.aspose.slides/nullablebool)।

**वापसी:**
byte

### setKumimoji(byte value) {#setKumimoji-byte-}
```
public final void setKumimoji(byte value)
```

निर्धारित करता है कि संख्याओं को टेक्स्ट पूर्वी-भाषा-विशिष्ट ऊर्ध्वाधर लेआउट को नज़रअंदाज़ करना चाहिए या नहीं। कोई विरासत लागू नहीं। पढ़ने/लिखने योग्य [NullableBool](../../com.aspose.slides/nullablebool)।

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getNormaliseHeight() {#getNormaliseHeight--}
```
public final byte getNormaliseHeight()
```

निर्धारित करता है कि टेक्स्ट की ऊँचाई को सामान्यीकृत किया जाना चाहिए या नहीं। कोई विरासत लागू नहीं। पढ़ने/लिखने योग्य [NullableBool](../../com.aspose.slides/nullablebool)।

**वापसी:**
byte

### setNormaliseHeight(byte value) {#setNormaliseHeight-byte-}
```
public final void setNormaliseHeight(byte value)
```

निर्धारित करता है कि टेक्स्ट की ऊँचाई को सामान्यीकृत किया जाना चाहिए या नहीं। कोई विरासत लागू नहीं। पढ़ने/लिखने योग्य [NullableBool](../../com.aspose.slides/nullablebool)।

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getProofDisabled() {#getProofDisabled--}
```
public final byte getProofDisabled()
```

निर्धारित करता है कि टेक्स्ट प्रूफ़ नहीं किया जाना चाहिए या नहीं। कोई विरासत लागू नहीं। पढ़ने/लिखने योग्य [NullableBool](../../com.aspose.slides/nullablebool)।

**वापसी:**
byte

### setProofDisabled(byte value) {#setProofDisabled-byte-}
```
public final void setProofDisabled(byte value)
```

निर्धारित करता है कि टेक्स्ट प्रूफ़ नहीं किया जाना चाहिए या नहीं। कोई विरासत लागू नहीं। पढ़ने/लिखने योग्य [NullableBool](../../com.aspose.slides/nullablebool)।

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getFontUnderline() {#getFontUnderline--}
```
public final byte getFontUnderline()
```

टेक्स्ट अंडरलाइन प्रकार लौटाता है या सेट करता है। कोई विरासत लागू नहीं। पढ़ने/लिखने योग्य [TextUnderlineType](../../com.aspose.slides/textunderlinetype)।

**वापसी:**
byte

### setFontUnderline(byte value) {#setFontUnderline-byte-}
```
public final void setFontUnderline(byte value)
```

टेक्स्ट अंडरलाइन प्रकार लौटाता है या सेट करता है। कोई विरासत लागू नहीं। पढ़ने/लिखने योग्य [TextUnderlineType](../../com.aspose.slides/textunderlinetype)।

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getTextCapType() {#getTextCapType--}
```
public final byte getTextCapType()
```

टेक्स्ट कैपिटलाइजेशन प्रकार लौटाता है या सेट करता है। कोई विरासत लागू नहीं। पढ़ने/लिखने योग्य [TextCapType](../../com.aspose.slides/textcaptype)।

**वापसी:**
byte

### setTextCapType(byte value) {#setTextCapType-byte-}
```
public final void setTextCapType(byte value)
```

टेक्स्ट कैपिटलाइजेशन प्रकार लौटाता है या सेट करता है। कोई विरासत लागू नहीं। पढ़ने/लिखने योग्य [TextCapType](../../com.aspose.slides/textcaptype)।

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getStrikethroughType() {#getStrikethroughType--}
```
public final byte getStrikethroughType()
```

टेक्स्ट के स्ट्राइकथ्रू प्रकार को लौटाता है या सेट करता है। कोई विरासत लागू नहीं। पढ़ने/लिखने योग्य [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype)।

**वापसी:**
byte

### setStrikethroughType(byte value) {#setStrikethroughType-byte-}
```
public final void setStrikethroughType(byte value)
```

टेक्स्ट के स्ट्राइकथ्रू प्रकार को लौटाता है या सेट करता है। कोई विरासत लागू नहीं। पढ़ने/लिखने योग्य [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype)।

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### isHardUnderlineLine() {#isHardUnderlineLine--}
```
public final byte isHardUnderlineLine()
```

निर्धारित करता है कि अंडरलाइन शैली के पास अपनी LineFormat गुण हैं या यह टेक्स्ट की LineFormat गुणों से विरासत में प्राप्त करता है। पढ़ने/लिखने योग्य [NullableBool](../../com.aspose.slides/nullablebool)।

**वापसी:**
byte

### setHardUnderlineLine(byte value) {#setHardUnderlineLine-byte-}
```
public final void setHardUnderlineLine(byte value)
```

निर्धारित करता है कि अंडरलाइन शैली के पास अपनी LineFormat गुण हैं या यह टेक्स्ट की LineFormat गुणों से विरासत में प्राप्त करता है। पढ़ने/लिखने योग्य [NullableBool](../../com.aspose.slides/nullablebool)।

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### isHardUnderlineFill() {#isHardUnderlineFill--}
```
public final byte isHardUnderlineFill()
```

निर्धारित करता है कि अंडरलाइन शैली के पास अपनी FillFormat गुण हैं या यह टेक्स्ट की FillFormat गुणों से विरासत में प्राप्त करता है। पढ़ने/लिखने योग्य [NullableBool](../../com.aspose.slides/nullablebool)।

**वापसी:**
byte

### setHardUnderlineFill(byte value) {#setHardUnderlineFill-byte-}
```
public final void setHardUnderlineFill(byte value)
```

निर्धारित करता है कि अंडरलाइन शैली के पास अपनी FillFormat गुण हैं या यह टेक्स्ट की FillFormat गुणों से विरासत में प्राप्त करता है। पढ़ने/लिखने योग्य [NullableBool](../../com.aspose.slides/nullablebool)।

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getFontHeight() {#getFontHeight--}
```
public final float getFontHeight()
```

फ़ॉन्ट ऊँचाई को लौटाता या सेट करता है। **Float.NaN** का मतलब है कि ऊँचाई अपरिभाषित है और इसे मास्टर से विरासत में प्राप्त होना चाहिए। पढ़ने/लिखने योग्य float .

**वापसी:**
float

### setFontHeight(float value) {#setFontHeight-float-}
```
public final void setFontHeight(float value)
```

फ़ॉन्ट ऊँचाई को लौटाता या सेट करता है। **Float.NaN** का मतलब है कि ऊँचाई अपरिभाषित है और इसे मास्टर से विरासत में प्राप्त होना चाहिए। पढ़ने/लिखने योग्य float .

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getLatinFont() {#getLatinFont--}
```
public final IFontData getLatinFont()
```

लैटिन फ़ॉन्ट जानकारी को लौटाता या सेट करता है। Null का मतलब है कि फ़ॉन्ट अपरिभाषित है और इसे मास्टर से विरासत में प्राप्त होना चाहिए। पढ़ने/लिखने योग्य [IFontData](../../com.aspose.slides/ifontdata)।

**वापसी:**
[IFontData](../../com.aspose.slides/ifontdata)

### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public final void setLatinFont(IFontData value)
```

लैटिन फ़ॉन्ट जानकारी को लौटाता या सेट करता है। Null का मतलब है कि फ़ॉन्ट अपरिभाषित है और इसे मास्टर से विरासत में प्राप्त होना चाहिए। पढ़ने/लिखने योग्य [IFontData](../../com.aspose.slides/ifontdata)।

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEastAsianFont() {#getEastAsianFont--}
```
public final IFontData getEastAsianFont()
```

ईस्ट एशियन फ़ॉन्ट जानकारी को लौटाता या सेट करता है। Null का मतलब है कि फ़ॉन्ट अपरिभाषित है और इसे मास्टर से विरासत में प्राप्त होना चाहिए। पढ़ने/लिखने योग्य [IFontData](../../com.aspose.slides/ifontdata)।

**वापसी:**
[IFontData](../../com.aspose.slides/ifontdata)

### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public final void setEastAsianFont(IFontData value)
```

ईस्ट एशियन फ़ॉन्ट जानकारी को लौटाता या सेट करता है। Null का मतलब है कि फ़ॉन्ट अपरिभाषित है और इसे मास्टर से विरासत में प्राप्त होना चाहिए। पढ़ने/लिखने योग्य [IFontData](../../com.aspose.slides/ifontdata)।

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getComplexScriptFont() {#getComplexScriptFont--}
```
public final IFontData getComplexScriptFont()
```

जटिल स्क्रिप्ट फ़ॉन्ट जानकारी को लौटाता या सेट करता है। Null का मतलब है कि फ़ॉन्ट अपरिभाषित है और इसे मास्टर से विरासत में प्राप्त होना चाहिए। पढ़ने/लिखने योग्य [IFontData](../../com.aspose.slides/ifontdata)।

**वापसी:**
[IFontData](../../com.aspose.slides/ifontdata)

### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public final void setComplexScriptFont(IFontData value)
```

जटिल स्क्रिप्ट फ़ॉन्ट जानकारी को लौटाता या सेट करता है। Null का मतलब है कि फ़ॉन्ट अपरिभाषित है और इसे मास्टर से विरासत में प्राप्त होना चाहिए। पढ़ने/लिखने योग्य [IFontData](../../com.aspose.slides/ifontdata)।

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getSymbolFont() {#getSymbolFont--}
```
public final IFontData getSymbolFont()
```

प्रतीकात्मक फ़ॉन्ट जानकारी को लौटाता या सेट करता है। Null का मतलब है कि फ़ॉन्ट अपरिभाषित है और इसे मास्टर से विरासत में प्राप्त होना चाहिए। पढ़ने/लिखने योग्य [IFontData](../../com.aspose.slides/ifontdata)।

**वापसी:**
[IFontData](../../com.aspose.slides/ifontdata)

### setSymbolFont(IFontData value) {#setSymbolFont-com.aspose.slides.IFontData-}
```
public final void setSymbolFont(IFontData value)
```

प्रतीकात्मक फ़ॉन्ट जानकारी को लौटाता या सेट करता है। Null का मतलब है कि फ़ॉन्ट अपरिभाषित है और इसे मास्टर से विरासत में प्राप्त होना चाहिए। पढ़ने/लिखने योग्य [IFontData](../../com.aspose.slides/ifontdata)।

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEscapement() {#getEscapement--}
```
public final float getEscapement()
```

सुपरसक्रिप्ट या सबस्क्रिप्ट टेक्स्ट को लौटाता या सेट करता है। मान -100% (सबस्क्रिप्ट) से 100% (सुपरसक्रिप्ट) तक हो सकता है। **Float.NaN** का मतलब है कि मान अपरिभाषित है और इसे मास्टर से विरासत में प्राप्त होना चाहिए। पढ़ने/लिखने योग्य float .

**वापसी:**
float

### setEscapement(float value) {#setEscapement-float-}
```
public final void setEscapement(float value)
```

सुपरसक्रिप्ट या सबस्क्रिप्ट टेक्स्ट को लौटाता या सेट करता है। मान -100% (सबस्क्रिप्ट) से 100% (सुपरसक्रिप्ट) तक हो सकता है। **Float.NaN** का मतलब है कि मान अपरिभाषित है और इसे मास्टर से विरासत में प्राप्त होना चाहिए। पढ़ने/लिखने योग्य float .

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getKerningMinimalSize() {#getKerningMinimalSize--}
```
public final float getKerningMinimalSize()
```

न्यूनतम फ़ॉन्ट आकार को लौटाता है या सेट करता है, जिसके लिए कर्निंग सक्रिय किया जाना चाहिए। **Float.NaN** का मतलब है कि मान अपरिभाषित है और इसे मास्टर से विरासत में प्राप्त होना चाहिए। पढ़ने/लिखने योग्य float .

**वापसी:**
float

### setKerningMinimalSize(float value) {#setKerningMinimalSize-float-}
```
public final void setKerningMinimalSize(float value)
```

न्यूनतम फ़ॉन्ट आकार को लौटाता है या सेट करता है, जिसके लिए कर्निंग सक्रिय किया जाना चाहिए। **Float.NaN** का मतलब है कि मान अपरिभाषित है और इसे मास्टर से विरासत में प्राप्त होना चाहिए। पढ़ने/लिखने योग्य float .

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getLanguageId() {#getLanguageId--}
```
public final String getLanguageId()
```

प्रूफ़िंग भाषा का Id लौटाता या सेट करता है। वर्तनी और व्याकरण जांच के लिए उपयोग किया जाता है। पढ़ने/लिखने योग्य String.

**वापसी:**
java.lang.String

### setLanguageId(String value) {#setLanguageId-java.lang.String-}
```
public final void setLanguageId(String value)
```

प्रूफ़िंग भाषा का Id लौटाता या सेट करता है। वर्तनी और व्याकरण जांच के लिए उपयोग किया जाता है। पढ़ने/लिखने योग्य String.

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternativeLanguageId() {#getAlternativeLanguageId--}
```
public final String getAlternativeLanguageId()
```

वैकल्पिक भाषा का Id लौटाता या सेट करता है। पढ़ने/लिखने योग्य String.

**वापसी:**
java.lang.String

### setAlternativeLanguageId(String value) {#setAlternativeLanguageId-java.lang.String-}
```
public final void setAlternativeLanguageId(String value)
```

वैकल्पिक भाषा का Id लौटाता या सेट करता है। पढ़ने/लिखने योग्य String.

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getSpacing() {#getSpacing--}
```
public final float getSpacing()
```

अक्षर अंतराल वृद्धि को लौटाता या सेट करता है। **Float.NaN** का मतलब है कि मान अपरिभाषित है और इसे मास्टर से विरासत में प्राप्त होना चाहिए। पढ़ने/लिखने योग्य float .

**वापसी:**
float

### setSpacing(float value) {#setSpacing-float-}
```
public final void setSpacing(float value)
```

अक्षर अंतराल वृद्धि को लौटाता या सेट करता है। **Float.NaN** का मतलब है कि मान अपरिभाषित है और इसे मास्टर से विरासत में प्राप्त होना चाहिए। पढ़ने/लिखने योग्य float .

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getSpellCheck() {#getSpellCheck--}
```
public final boolean getSpellCheck()
```

टेक्स्ट भाग के लिए स्पेल चेकिंग सक्षम है या नहीं, यह दर्शाने वाले मान को प्राप्त करता या सेट करता है। जब यह गुण false पर सेट किया जाता है, तो टेक्स्ट तत्वों के लिए वर्तनी जाँच दबा दी जाती है। जब true पर सेट किया जाता है, तो स्पेल चेकिंग की अनुमति होती है। डिफ़ॉल्ट मान false है।

--------------------

> ```
> Next example demonstrates enabling the SpellCheck flag before saving the presentation:
>  
>  Presentation pres = new Presentation("input.pptx");
>  try {
>      // पहले स्लाइड पर पहले शेप के भीतर टेक्स्ट का पहला भाग एक्सेस करें
>      IPortion portion = ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).
>              getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0);
>      // इस टेक्स्ट भाग के लिए स्पेल चेकिंग सक्षम करें
>      portion.getPortionFormat().setSpellCheck(true);
>      // संशोधित प्रेज़ेंटेशन को सहेजें
>      pres.save("output-with-spellcheck.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**वापसी:**
boolean

### setSpellCheck(boolean value) {#setSpellCheck-boolean-}
```
public final void setSpellCheck(boolean value)
```

टेक्स्ट भाग के लिए स्पेल चेकिंग सक्षम है या नहीं, यह दर्शाने वाले मान को प्राप्त करता या सेट करता है। जब यह गुण false पर सेट किया जाता है, तो टेक्स्ट तत्वों के लिए वर्तनी जाँच दबा दी जाती है। जब true पर सेट किया जाता है, तो स्पेल चेकिंग की अनुमति होती है। डिफ़ॉल्ट मान false है।

--------------------

> ```
> Next example demonstrates enabling the SpellCheck flag before saving the presentation:
>  
>  Presentation pres = new Presentation("input.pptx");
>  try {
>      // पहले स्लाइड पर पहले शेप के भीतर टेक्स्ट का पहला भाग एक्सेस करें
>      IPortion portion = ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).
>              getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0);
>      // इस टेक्स्ट भाग के लिए स्पेल चेकिंग सक्षम करें
>      portion.getPortionFormat().setSpellCheck(true);
>      // संशोधित प्रेज़ेंटेशन को सहेजें
>      pres.save("output-with-spellcheck.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |