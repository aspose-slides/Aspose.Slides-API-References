---
title: ITextFrame
second_title: Aspose.Slides जावा के लिए API रेफ़रेंस
description: एक TextFrame का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/itextframe/
---
**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface ITextFrame extends ISlideComponent
```

एक TextFrame का प्रतिनिधित्व करता है।
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getParagraphs()](#getParagraphs--) | फ़्रेम में सभी पैराग्राफ़ की सूची लौटाता है। |
| [getText()](#getText--) | एक TextFrame के लिए साधारण टेक्स्ट प्राप्त करता है या सेट करता है। |
| [setText(String value)](#setText-java.lang.String-) | एक TextFrame के लिए साधारण टेक्स्ट प्राप्त करता है या सेट करता है। |
| [getTextFrameFormat()](#getTextFrameFormat--) | इस TextFrame ऑब्जेक्ट के फ़ॉर्मेटिंग ऑब्जेक्ट को लौटाता है। |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | समाहित हाइपरलिंक तक आसान पहुँच प्रदान करता है। |
| [getParentShape()](#getParentShape--) | पैरेंट शेप लौटाता है या null यदि पैरेंट ऑब्जेक्ट IShape इंटरफ़ेस लागू नहीं करता है। केवल-पठनीय [IShape](../../com.aspose.slides/ishape). |
| [getTextRect()](#getTextRect--) | पैरेंट शेप की ज्यामिति द्वारा परिभाषित टेक्स्ट आयत प्राप्त करता है। |
| [getParentCell()](#getParentCell--) | यदि पैरेंट ऑब्जेक्ट ICell इंटरफ़ेस लागू नहीं करता है तो पैरेंट सेल या null लौटाता है। |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | सभी पैराग्राफ़ में समान फ़ॉर्मेटिंग वाले रन को जोड़ता है। |
| [highlightText(String text, Color highlightColor)](#highlightText-java.lang.String-java.awt.Color-) | निर्दिष्ट रंग के साथ नमूना टेक्स्ट के सभी मेल को हाइलाइट करता है। |
| [splitTextByColumns()](#splitTextByColumns--) | [ITextFrame](../../com.aspose.slides/itextframe) की टेक्स्ट सामग्री को स्ट्रिंग की एरे में विभाजित करता है, जहाँ प्रत्येक तत्व फ्रेम के भीतर अलग-अलग टेक्स्ट कॉलम से मेल खाता है। |
| [highlightText(String text, Color highlightColor, ITextHighlightingOptions options)](#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextHighlightingOptions-) | निर्दिष्ट रंग के साथ नमूना टेक्स्ट के सभी मेल को हाइलाइट करता है। |
| [highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | निर्दिष्ट रंग के साथ नमूना टेक्स्ट के सभी मेल को हाइलाइट करता है। |
| [highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-) | निर्दिष्ट रंग के साथ रेगुलर एक्सप्रेशन के सभी मेल को हाइलाइट करता है। |
| [highlightRegex(String regex, Color highlightColor, ITextHighlightingOptions options)](#highlightRegex-java.lang.String-java.awt.Color-com.aspose.slides.ITextHighlightingOptions-) | निर्दिष्ट रंग के साथ रेगुलर एक्सप्रेशन के सभी मेल को हाइलाइट करता है। |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | निर्दिष्ट टेक्स्ट की सभी घटनाओं को दूसरे निर्दिष्ट टेक्स्ट से बदलता है। |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | रेगुलर एक्सप्रेशन के सभी मेल को निर्दिष्ट स्ट्रिंग से बदलता है। |
### getParagraphs() {#getParagraphs--}
```
public abstract IParagraphCollection getParagraphs()
```

फ़्रेम में सभी पैराग्राफ़ की सूची लौटाता है। केवल-पठनीय [IParagraphCollection](../../com.aspose.slides/iparagraphcollection).

**रिटर्न:**
[IParagraphCollection](../../com.aspose.slides/iparagraphcollection)
### getText() {#getText--}
```
public abstract String getText()
```

एक TextFrame के लिए साधारण टेक्स्ट प्राप्त करता है या सेट करता है। पढ़ें/लिखें स्ट्रिंग।

मान: टेक्स्ट।

**रिटर्न:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```

एक TextFrame के लिए साधारण टेक्स्ट प्राप्त करता है या सेट करता है। पढ़ें/लिखें स्ट्रिंग।

मान: टेक्स्ट।

**पैरामीटर्स:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |
### getTextFrameFormat() {#getTextFrameFormat--}
```
public abstract ITextFrameFormat getTextFrameFormat()
```

इस TextFrame ऑब्जेक्ट के फ़ॉर्मेटिंग ऑब्जेक्ट को लौटाता है। केवल-पठनीय [ITextFrameFormat](../../com.aspose.slides/itextframeformat).

**रिटर्न:**
[ITextFrameFormat](../../com.aspose.slides/itextframeformat)
### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public abstract IHyperlinkQueries getHyperlinkQueries()
```

समाहित हाइपरलिंक्स तक आसान पहुँच प्रदान करता है। केवल-पठनीय [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**रिटर्न:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)
### getParentShape() {#getParentShape--}
```
public abstract IShape getParentShape()
```

पैरेंट शेप लौटाता है या null यदि पैरेंट ऑब्जेक्ट IShape इंटरफ़ेस लागू नहीं करता है। केवल-पठनीय [IShape](../../com.aspose.slides/ishape).

--------------------

> ```
> The following code sample shows 
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      AutoShape autoShape = (AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      Table table = (Table)presentation.getSlides().get_Item(0).getShapes().get_Item(1);
> 
>      // ये अभिकथन हमेशा सत्य हैं
>      Assert.assertTrue(autoShape.getTextFrame().getParentShape() == autoShape);
>      Assert.assertTrue((table.get_Item(0,0).getTextFrame()).getParentShape() == null);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**रिटर्न:**
[IShape](../../com.aspose.slides/ishape)
### getTextRect() {#getTextRect--}
```
public abstract Rectangle2D.Float getTextRect()
```

पैरेंट शेप की ज्यामिति द्वारा परिभाषित टेक्स्ट आयत प्राप्त करता है।

**रिटर्न:**
java.awt.geom.Rectangle2D.Float - एक java.awt.geom.Rectangle2D.Float जो टेक्स्ट क्षेत्र को परिभाषित करता है।

--------------------

आयत के निर्देशांक पैरेंट शेप के शीर्ष-बाएँ कोने के सापेक्ष होते हैं।
### getParentCell() {#getParentCell--}
```
public abstract ICell getParentCell()
```

यदि पैरेंट ऑब्जेक्ट ICell इंटरफ़ेस लागू नहीं करता है तो पैरेंट सेल या null लौटाता है। केवल-पठनीय [ICell](../../com.aspose.slides/icell).

--------------------

> ```
> The following code sample shows 
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      AutoShape autoShape = (AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      Table table = (Table)presentation.getSlides().get_Item(0).getShapes().get_Item(1);
> 
>      // ये अभिकथन हमेशा सत्य हैं
>      Assert.assertTrue(table.get_Item(0,0).getTextFrame().getParentCell() == table.get_Item(0,0));
>      Assert.assertTrue(autoShape.getTextFrame().getParentCell() == null);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**रिटर्न:**
[ICell](../../com.aspose.slides/icell)
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```

सभी पैराग्राफ़ में समान फ़ॉर्मेटिंग वाले रन को जोड़ता है।

### highlightText(String text, Color highlightColor) {#highlightText-java.lang.String-java.awt.Color-}
```
public abstract void highlightText(String text, Color highlightColor)
```

निर्दिष्ट रंग के साथ नमूना टेक्स्ट के सभी मेल को हाइलाइट करता है।

**पैरामीटर्स:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| text | java.lang.String | हाइलाइट करने के लिए टेक्स्ट। |
| highlightColor | java.awt.Color | टेक्स्ट को हाइलाइट करने का रंग। |
### splitTextByColumns() {#splitTextByColumns--}
```
public abstract String[] splitTextByColumns()
```

[ITextFrame](../../com.aspose.slides/itextframe) की टेक्स्ट सामग्री को स्ट्रिंग की एरे में विभाजित करता है, जहाँ प्रत्येक तत्व फ्रेम के भीतर अलग-अलग टेक्स्ट कॉलम से मेल खाता है।

--------------------

> ```
> The following example demonstrates how to use #splitTextByColumns.splitTextByColumns:
>  
>  Presentation pres = new Presentation("example.pptx");
>  try {
>      // स्लाइड पर पहला आकार प्राप्त करें और उसे ITextFrame में कास्ट करें
>      ITextFrame textFrame = (ITextFrame) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // टेक्स्ट फ्रेम की सामग्री को कॉलमों में विभाजित करें
>      String[] columnsText = textFrame.splitTextByColumns();
>      // प्रत्येक कॉलम के टेक्स्ट को कन्सोल में प्रिंट करें
>      for (String column : columnsText)
>          System.out.println(column);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**रिटर्न:**
java.lang.String[] - स्ट्रिंग्स की एरे, जहाँ प्रत्येक स्ट्रिंग [ITextFrame](../../com.aspose.slides/itextframe) में एक विशिष्ट कॉलम की टेक्स्ट सामग्री का प्रतिनिधित्व करता है।

--------------------

यदि टेक्स्ट फ्रेम में कई कॉलम नहीं हैं, तो लौटाई गई एरे में पूर्ण टेक्स्ट वाले एक ही तत्व होंगे। खाली कॉलम एरे में खाली स्ट्रिंग्स के रूप में दर्शाए जाएंगे।
### highlightText(String text, Color highlightColor, ITextHighlightingOptions options) {#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextHighlightingOptions-}
```
public abstract void highlightText(String text, Color highlightColor, ITextHighlightingOptions options)
```

निर्दिष्ट रंग के साथ नमूना टेक्स्ट के सभी मेल को हाइलाइट करता है।

**पैरामीटर्स:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| text | java.lang.String | हाइलाइट करने के लिए टेक्स्ट। |
| highlightColor | java.awt.Color | टेक्स्ट को हाइलाइट करने का रंग। |
| options | [ITextHighlightingOptions](../../com.aspose.slides/itexthighlightingoptions) | हाइलाइटिंग विकल्प। |
### highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```

निर्दिष्ट रंग के साथ नमूना टेक्स्ट के सभी मेल को हाइलाइट करता है।

--------------------

> ```
> The following code sample shows how to highlight text in a TextFrame.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // सभी शब्द 'important' को हाइलाइट कर रहा है
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("important", Color.BLUE);
>      // सभी अलग-अलग 'the' उपस्थिति को हाइलाइट कर रहा है
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("the", Color.MAGENTA, textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**पैरामीटर्स:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| text | java.lang.String | हाइलाइट करने के लिए टेक्स्ट। |
| highlightColor | java.awt.Color | टेक्स्ट को हाइलाइट करने का रंग। |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | टेक्स्ट खोज विकल्प [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions)। |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | सर्च परिणाम प्राप्त करने के लिए कॉलबैक ऑब्जेक्ट [IFindResultCallback](../../com.aspose.slides/ifindresultcallback)। |
### highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)
```

निर्दिष्ट रंग के साथ रेगुलर एक्सप्रेशन के सभी मेल को हाइलाइट करता है।

--------------------

> ```
> The following code sample shows how to highlight text in a TextFrame using a regular expression.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{5,}\\b");
>      // 5 प्रतीकों या उससे अधिक वाले सभी शब्दों को हाइलाइट कर रहा है
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightRegex(regex, Color.BLUE, null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**पैरामीटर्स:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| regex | java.util.regex.Pattern | हाइलाइट करने के लिए स्ट्रिंग्स प्राप्त करने हेतु रेगुलर एक्सप्रेशन java.util.regex.Pattern। |
| highlightColor | java.awt.Color | टेक्स्ट को हाइलाइट करने का रंग। |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | सर्च परिणाम प्राप्त करने के लिए कॉलबैक ऑब्जेक्ट [IFindResultCallback](../../com.aspose.slides/ifindresultcallback)। |
### highlightRegex(String regex, Color highlightColor, ITextHighlightingOptions options) {#highlightRegex-java.lang.String-java.awt.Color-com.aspose.slides.ITextHighlightingOptions-}
```
public abstract void highlightRegex(String regex, Color highlightColor, ITextHighlightingOptions options)
```

निर्दिष्ट रंग के साथ रेगुलर एक्सप्रेशन के सभी मेल को हाइलाइट करता है।

**पैरामीटर्स:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| regex | java.lang.String | हाइलाइट करने के लिए टेक्स्ट प्राप्त करने हेतु रेगुलर एक्सप्रेशन का टेक्स्ट। |
| highlightColor | java.awt.Color | टेक्स्ट को हाइलाइट करने का रंग। |
| options | [ITextHighlightingOptions](../../com.aspose.slides/itexthighlightingoptions) | हाइलाइटिंग विकल्प। |
### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
```

निर्दिष्ट टेक्स्ट की सभी घटनाओं को दूसरे निर्दिष्ट टेक्स्ट से बदलता है।

--------------------

> ```
> The following sample code shows how to replace one specified string with another specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // सभी अलग-अलग 'the' उपस्थितियों को '***' से बदलें
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**पैरामीटर्स:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| oldText | java.lang.String | बदलने वाली स्ट्रिंग। |
| newText | java.lang.String | oldText की सभी घटनाओं को बदलने वाली स्ट्रिंग। |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | टेक्स्ट खोज विकल्प [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions)। |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | सर्च परिणाम प्राप्त करने के लिए कॉलबैक ऑब्जेक्ट [IFindResultCallback](../../com.aspose.slides/ifindresultcallback)। |
### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```

रेगुलर एक्सप्रेशन के सभी मेल को निर्दिष्ट स्ट्रिंग से बदलता है।

--------------------

> ```
> The following code sample shows how to replace text using regular expression with the specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{5,}\\b");
>      // 5 प्रतीकों या उससे अधिक वाले सभी शब्दों को '***' से बदलें
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().replaceRegex(regex, "***", null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**पैरामीटर्स:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| regex | java.util.regex.Pattern | बदलने के लिए स्ट्रिंग्स प्राप्त करने हेतु रेगुलर एक्सप्रेशन java.util.regex.Pattern। |
| newText | java.lang.String | बदले जाने वाली स्ट्रिंग्स की सभी घटनाओं को बदलने वाली स्ट्रिंग। |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | सर्च परिणाम प्राप्त करने के लिए कॉलबैक ऑब्जेक्ट [IFindResultCallback](../../com.aspose.slides/ifindresultcallback)।