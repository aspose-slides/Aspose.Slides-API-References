---
title: IFontSubstRule
second_title: Aspose.Slides for Android via Java API Reference
description: फ़ॉन्ट प्रतिस्थापन जानकारी का प्रतिनिधित्व करता है
type: docs
url: /hi/com.aspose.slides/ifontsubstrule/
---```
public interface IFontSubstRule
```

फ़ॉन्ट प्रतिस्थापन जानकारी का प्रतिनिधित्व करता है
## विधियाँ

| मेथड | विवरण |
| --- | --- |
| [getSourceFont()](#getSourceFont--) | Font to substitute Read-only [IFontData](../../com.aspose.slides/ifontdata). |
| [getDestFont()](#getDestFont--) | Font to use for substitution Read-only [IFontData](../../com.aspose.slides/ifontdata). |
| [getReplaceFontCondition()](#getReplaceFontCondition--) | Rule to apply for substitution Read-only [FontSubstCondition](../../com.aspose.slides/fontsubstcondition). |
### getSourceFont() {#getSourceFont--}
```
public abstract IFontData getSourceFont()
```


प्रतिस्थापित करने के लिए फ़ॉन्ट केवल पढ़ने योग्य [IFontData](../../com.aspose.slides/ifontdata).

**रिटर्न:**
[IFontData](../../com.aspose.slides/ifontdata)
### getDestFont() {#getDestFont--}
```
public abstract IFontData getDestFont()
```


प्रतिस्थापन के लिए उपयोग करने वाला फ़ॉन्ट केवल पढ़ने योग्य [IFontData](../../com.aspose.slides/ifontdata).

**रिटर्न:**
[IFontData](../../com.aspose.slides/ifontdata)
### getReplaceFontCondition() {#getReplaceFontCondition--}
```
public abstract int getReplaceFontCondition()
```


प्रतिस्थापन लागू करने के लिए नियम केवल पढ़ने योग्य [FontSubstCondition](../../com.aspose.slides/fontsubstcondition).

**रिटर्न:**
int