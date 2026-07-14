---
title: IChartTextFormat
second_title: Aspose.Slides for Android via Java API Reference
description: Chart operate with restricted set of text format properties.
type: docs
url: /hi/com.aspose.slides/icharttextformat/
---```
public interface IChartTextFormat
```

चार्ट पाठ स्वरूप गुणों के प्रतिबंधित सेट के साथ कार्य करता है। IChartTextFormat, IChartTextBlockFormat, IChartParagraphFormat, IChartPortionFormat इंटरफ़ेस इस प्रतिबंधित सेट का वर्णन करते हैं।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getTextBlockFormat()](#getTextBlockFormat--) | चार्ट पाठ तत्वों के लिए स्वरूप लौटाता है। |
| [getParagraphFormat()](#getParagraphFormat--) | पैराग्राफ स्वरूप लौटाता है। |
| [getPortionFormat()](#getPortionFormat--) | पोर्शन स्वरूप लौटाता है। |
| [copyTo(ITextFrame destTextFrame)](#copyTo-com.aspose.slides.ITextFrame-) | निर्दिष्ट टेक्स्ट फ्रेम में पाठ स्वरूप की प्रतिलिपि बनाता है। |
| [copyFrom(ITextFrame sourceTextFrame)](#copyFrom-com.aspose.slides.ITextFrame-) | निर्दिष्ट टेक्स्ट फ्रेम से पाठ स्वरूप की प्रतिलिपि बनाता है। |
### getTextBlockFormat() {#getTextBlockFormat--}
```
public abstract IChartTextBlockFormat getTextBlockFormat()
```


चार्ट पाठ तत्वों के लिए स्वरूप लौटाता है। केवल पढ़ने योग्य [IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat)।

**वापसी:**
[IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat)
### getParagraphFormat() {#getParagraphFormat--}
```
public abstract IChartParagraphFormat getParagraphFormat()
```


पैराग्राफ स्वरूप लौटाता है। केवल पढ़ने योग्य [IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat)।

**वापसी:**
[IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat)
### getPortionFormat() {#getPortionFormat--}
```
public abstract IChartPortionFormat getPortionFormat()
```


पोर्शन स्वरूप लौटाता है। केवल पढ़ने योग्य [IChartPortionFormat](../../com.aspose.slides/ichartportionformat)।

**वापसी:**
[IChartPortionFormat](../../com.aspose.slides/ichartportionformat)
### copyTo(ITextFrame destTextFrame) {#copyTo-com.aspose.slides.ITextFrame-}
```
public abstract void copyTo(ITextFrame destTextFrame)
```


निर्दिष्ट टेक्स्ट फ्रेम में पाठ स्वरूप की प्रतिलिपि बनाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| destTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | पाठ स्वरूप को प्रतिलिपि करने के लिए टेक्स्ट फ्रेम। |

### copyFrom(ITextFrame sourceTextFrame) {#copyFrom-com.aspose.slides.ITextFrame-}
```
public abstract void copyFrom(ITextFrame sourceTextFrame)
```


निर्दिष्ट टेक्स्ट फ्रेम से पाठ स्वरूप की प्रतिलिपि बनाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sourceTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | पाठ स्वरूप को प्रतिलिपि करने के लिए टेक्स्ट फ्रेम। |