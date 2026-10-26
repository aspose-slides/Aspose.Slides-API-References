---
title: ChartTextFormat
second_title: Java API संदर्भ के द्वारा Android के लिये Aspose.Slides
description: चार्ट टेक्स्ट तत्वों के लिए डिफ़ॉल्ट टेक्स्ट फ़ॉर्मेटिंग निर्दिष्ट करता है।
type: docs
url: /hi/com.aspose.slides/charttextformat/
---
**विरासत:**
java.lang.Object

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IChartTextFormat](../../com.aspose.slides/icharttextformat), com.aspose.slides.IDOMObject
```
public class ChartTextFormat implements IChartTextFormat, IDOMObject
```

चार्ट टेक्स्ट तत्वों के लिए डिफ़ॉल्ट टेक्स्ट फ़ॉर्मेटिंग निर्दिष्ट करता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getTextBlockFormat()](#getTextBlockFormat--) | TextBlockFormat. |
| [getParagraphFormat()](#getParagraphFormat--) | ParagraphFormat. |
| [getPortionFormat()](#getPortionFormat--) | PortionFormat. |
| [copyTo(ITextFrame destTextFrame)](#copyTo-com.aspose.slides.ITextFrame-) | निर्दिष्ट टेक्स्ट फ्रेम में टेक्स्ट फ़ॉर्मेट कॉपी करता है। |
| [copyFrom(ITextFrame sourceTextFrame)](#copyFrom-com.aspose.slides.ITextFrame-) | निर्दिष्ट टेक्स्ट फ्रेम से टेक्स्ट फ़ॉर्मेट कॉपी करता है। |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getTextBlockFormat() {#getTextBlockFormat--}
```
public final IChartTextBlockFormat getTextBlockFormat()
```

TextBlockFormat. केवल-पढ़ने योग्य [IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat).

**वापसी:**
[IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat)
### getParagraphFormat() {#getParagraphFormat--}
```
public final IChartParagraphFormat getParagraphFormat()
```

ParagraphFormat. केवल-पढ़ने योग्य [IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat).

**वापसी:**
[IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat)
### getPortionFormat() {#getPortionFormat--}
```
public final IChartPortionFormat getPortionFormat()
```

PortionFormat. केवल-पढ़ने योग्य [IChartPortionFormat](../../com.aspose.slides/ichartportionformat).

**वापसी:**
[IChartPortionFormat](../../com.aspose.slides/ichartportionformat)
### copyTo(ITextFrame destTextFrame) {#copyTo-com.aspose.slides.ITextFrame-}
```
public final void copyTo(ITextFrame destTextFrame)
```

निर्दिष्ट टेक्स्ट फ्रेम में टेक्स्ट फ़ॉर्मेट कॉपी करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| destTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | Text frame to copy text format to. |
### copyFrom(ITextFrame sourceTextFrame) {#copyFrom-com.aspose.slides.ITextFrame-}
```
public final void copyFrom(ITextFrame sourceTextFrame)
```

निर्दिष्ट टेक्स्ट फ्रेम से टेक्स्ट फ़ॉर्मेट कॉपी करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sourceTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | Text frame to copy text format. |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate ऑब्जेक्ट को लौटाता है। केवल-पढ़ने योग्य IDOMObject।

**वापसी:**
com.aspose.slides.IDOMObject