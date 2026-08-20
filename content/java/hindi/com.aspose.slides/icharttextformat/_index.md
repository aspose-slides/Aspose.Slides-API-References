---
title: IChartTextFormat
second_title: Aspose.Slides for Java API Reference
description: चार्ट सीमित सेट के टेक्स्ट फ़ॉर्मेट प्रॉपर्टीज़ के साथ काम करता है।
type: docs
url: /hi/com.aspose.slides/icharttextformat/
---```
public interface IChartTextFormat
```

चार्ट सीमित सेट के टेक्स्ट फ़ॉर्मेट प्रॉपर्टीज़ के साथ काम करता है। IChartTextFormat, IChartTextBlockFormat, IChartParagraphFormat, IChartPortionFormat इंटरफ़ेस इस सीमित सेट का वर्णन करते हैं।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getTextBlockFormat()](#getTextBlockFormat--) | चार्ट टेक्स्ट तत्वों के लिए फ़ॉर्मेट लौटाता है। |
| [getParagraphFormat()](#getParagraphFormat--) | पैराग्राफ़ फ़ॉर्मेट लौटाता है। |
| [getPortionFormat()](#getPortionFormat--) | खंड फ़ॉर्मेट लौटाता है। |
| [copyTo(ITextFrame destTextFrame)](#copyTo-com.aspose.slides.ITextFrame-) | निर्दिष्ट टेक्स्ट फ्रेम में टेक्स्ट फ़ॉर्मेट कॉपी करता है। |
| [copyFrom(ITextFrame sourceTextFrame)](#copyFrom-com.aspose.slides.ITextFrame-) | निर्दिष्ट टेक्स्ट फ्रेम से टेक्स्ट फ़ॉर्मेट कॉपी करता है। |
### getTextBlockFormat() {#getTextBlockFormat--}
```
public abstract IChartTextBlockFormat getTextBlockFormat()
```


चार्ट टेक्स्ट तत्वों के लिए फ़ॉर्मेट लौटाता है। केवल-पढ़ने योग्य [IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat)।

**रिटर्न:**
[IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat)
### getParagraphFormat() {#getParagraphFormat--}
```
public abstract IChartParagraphFormat getParagraphFormat()
```


पैराग्राफ़ फ़ॉर्मेट लौटाता है। केवल-पढ़ने योग्य [IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat)।

**रिटर्न:**
[IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat)
### getPortionFormat() {#getPortionFormat--}
```
public abstract IChartPortionFormat getPortionFormat()
```


खंड फ़ॉर्मेट लौटाता है। केवल-पढ़ने योग्य [IChartPortionFormat](../../com.aspose.slides/ichartportionformat)।

**रिटर्न:**
[IChartPortionFormat](../../com.aspose.slides/ichartportionformat)
### copyTo(ITextFrame destTextFrame) {#copyTo-com.aspose.slides.ITextFrame-}
```
public abstract void copyTo(ITextFrame destTextFrame)
```


निर्दिष्ट टेक्स्ट फ्रेम में टेक्स्ट फ़ॉर्मेट कॉपी करता है।

**पैरामीटर्स:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| destTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | टेक्स्ट फ्रेम जहाँ टेक्स्ट फ़ॉर्मेट कॉपी करना है। |

### copyFrom(ITextFrame sourceTextFrame) {#copyFrom-com.aspose.slides.ITextFrame-}
```
public abstract void copyFrom(ITextFrame sourceTextFrame)
```


निर्दिष्ट टेक्स्ट फ्रेम से टेक्स्ट फ़ॉर्मेट कॉपी करता है।

**पैरामीटर्स:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| sourceTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | टेक्स्ट फ़ॉर्मेट कॉपी करने के लिए टेक्स्ट फ्रेम। |