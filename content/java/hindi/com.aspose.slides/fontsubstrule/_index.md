---
title: FontSubstRule
second_title: Aspose.Slides के लिए जावा API संदर्भ
description: फ़ॉन्ट प्रतिस्थापन जानकारी का प्रतिनिधित्व करता है
type: docs
url: /hi/com.aspose.slides/fontsubstrule/
---
**विरासत:**
java.lang.Object

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IFontSubstRule](../../com.aspose.slides/ifontsubstrule)
```
public class FontSubstRule implements IFontSubstRule
```

फ़ॉन्ट प्रतिस्थापन जानकारी का प्रतिनिधित्व करता है
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [FontSubstRule(IFontData sourceFont, IFontData destFont)](#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-) | नया इंस्टेंस बनाता है। |
| [FontSubstRule(IFontData sourceFont, IFontData destFont, int fontSubstRule)](#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-int-) | नया इंस्टेंस बनाता है। |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getSourceFont()](#getSourceFont--) | प्रतिस्थापित करने के लिए फ़ॉन्ट। |
| [getDestFont()](#getDestFont--) | प्रतिस्थापन के लिए उपयोग करने वाला फ़ॉन्ट। |
| [getReplaceFontCondition()](#getReplaceFontCondition--) | प्रतिस्थापन के लिए लागू किया जाने वाला नियम। |
### FontSubstRule(IFontData sourceFont, IFontData destFont) {#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-}
```
public FontSubstRule(IFontData sourceFont, IFontData destFont)
```


नया इंस्टेंस बनाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | स्रोत फ़ॉन्ट। |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | गंतव्य फ़ॉन्ट। |

### FontSubstRule(IFontData sourceFont, IFontData destFont, int fontSubstRule) {#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-int-}
```
public FontSubstRule(IFontData sourceFont, IFontData destFont, int fontSubstRule)
```


नया इंस्टेंस बनाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | स्रोत फ़ॉन्ट। |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | गंतव्य फ़ॉन्ट। |
| fontSubstRule | int | फ़ॉन्ट प्रतिस्थापन नियम। |
### getSourceFont() {#getSourceFont--}
```
public final IFontData getSourceFont()
```


प्रतिस्थापित करने के लिए फ़ॉन्ट। केवल-पढ़ने योग्य [IFontData](../../com.aspose.slides/ifontdata)।

**रिटर्न:**
[IFontData](../../com.aspose.slides/ifontdata)
### getDestFont() {#getDestFont--}
```
public final IFontData getDestFont()
```


प्रतिस्थापन के लिए उपयोग करने वाला फ़ॉन्ट। केवल-पढ़ने योग्य [IFontData](../../com.aspose.slides/ifontdata)।

**रिटर्न:**
[IFontData](../../com.aspose.slides/ifontdata)
### getReplaceFontCondition() {#getReplaceFontCondition--}
```
public final int getReplaceFontCondition()
```


प्रतिस्थापन के लिए लागू किया जाने वाला नियम। केवल-पढ़ने योग्य [FontSubstCondition](../../com.aspose.slides/fontsubstcondition)।

**रिटर्न:**
int