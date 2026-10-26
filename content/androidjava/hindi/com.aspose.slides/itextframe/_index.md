---
title: ITextFrame
second_title: Aspose.Slides for Android जावा API रेफ़रेंस के माध्यम से
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
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getParagraphs()](#getParagraphs--) | फ़्रेम में सभी पैराग्राफ़ों की सूची लौटाता है। |
| [getText()](#getText--) | TextFrame के लिए साधारण पाठ प्राप्त करता है या सेट करता है। |
| [setText(String value)](#setText-java.lang.String-) | TextFrame के लिए साधारण पाठ प्राप्त करता है या सेट करता है। |
| [getTextFrameFormat()](#getTextFrameFormat--) | इस TextFrame ऑब्जेक्ट के लिए फ़ॉर्मेटिंग ऑब्जेक्ट लौटाता है। |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | समाविष्ट हाइपरलिंक तक आसान पहुँच प्रदान करता है। |
| [getParentShape()](#getParentShape--) | यदि पैरेंट ऑब्जेक्ट IShape इंटरफ़ेस को लागू नहीं करता है तो पैरेंट आकार या null लौटाता है। केवल पढ़ने योग्य [IShape](../../com.aspose.slides/ishape)। |
| [getParentCell()](#getParentCell--) | यदि पैरेंट ऑब्जेक्ट ICell इंटरफ़ेस को लागू नहीं करता है तो पैरेंट सेल या null लौटाता है। |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | सभी पैराग्राफ़ों में समान फ़ॉर्मेटिंग वाले रन को जोड़ता है। |
| [highlightText(String text, Integer highlightColor)](#highlightText-java.lang.String-java.lang.Integer-) | निर्दिष्ट रंग के साथ नमूना पाठ के सभी मिलान को हाइलाइट करता है। |
| [splitTextByColumns()](#splitTextByColumns--) | [ITextFrame](../../com.aspose.slides/itextframe) की टेक्स्ट सामग्री को स्ट्रिंग्स की एक एरे में विभाजित करता है, जहाँ प्रत्येक तत्व फ्रेम के भीतर एक अलग टेक्स्ट कॉलम के अनुरूप होता है। |
| [highlightText(String text, Integer highlightColor, ITextHighlightingOptions options)](#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextHighlightingOptions-) | निर्दिष्ट रंग के साथ नमूना पाठ के सभी मिलान को हाइलाइट करता है। |
| [highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | निर्दिष्ट रंग के साथ नमूना पाठ के सभी मिलान को हाइलाइट करता है। |
| [highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-) | निर्दिष्ट रंग के साथ नियमित अभिव्यक्ति के सभी मिलान को हाइलाइट करता है। |
| [highlightRegex(String regex, Integer highlightColor, ITextHighlightingOptions options)](#highlightRegex-java.lang.String-java.lang.Integer-com.aspose.slides.ITextHighlightingOptions-) | निर्दिष्ट रंग के साथ नियमित अभिव्यक्ति के सभी मिलान को हाइलाइट करता है। |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | निर्दिष्ट पाठ की सभी occurrences को दूसरे निर्दिष्ट पाठ से बदलता है। |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | नियमित अभिव्यक्ति के सभी मिलान को निर्दिष्ट स्ट्रिंग से बदलता है। |
### getParagraphs() {#getParagraphs--}
```
public abstract IParagraphCollection getParagraphs()
```


फ़्रेम में सभी पैराग्राफ़ों की सूची लौटाता है। केवल पढ़ने योग्य [IParagraphCollection](../../com.aspose.slides/iparagraphcollection)।

**वापसी:**
[IParagraphCollection](../../com.aspose.slides/iparagraphcollection)
### getText() {#getText--}
```
public abstract String getText()
```


TextFrame के लिए साधारण पाठ प्राप्त करता है या सेट करता है। पढ़ने/लेखन योग्य स्ट्रिंग।

मान: पाठ।

**वापसी:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```


TextFrame के लिए साधारण पाठ प्राप्त करता है या सेट करता है। पढ़ने/लेखन योग्य स्ट्रिंग।

मान: पाठ।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getTextFrameFormat() {#getTextFrameFormat--}
```
public abstract ITextFrameFormat getTextFrameFormat()
```


इस TextFrame ऑब्जेक्ट के लिए फ़ॉर्मेटिंग ऑब्जेक्ट लौटाता है। केवल पढ़ने योग्य [ITextFrameFormat](../../com.aspose.slides/itextframeformat)।

**वापसी:**
[ITextFrameFormat](../../com.aspose.slides/itextframeformat)
### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public abstract IHyperlinkQueries getHyperlinkQueries()
```


समाविष्ट हाइपरलिंक तक आसान पहुँच प्रदान करता है। केवल पढ़ने योग्य [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)।

**वापसी:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)
### getParentShape() {#getParentShape--}
```
public abstract IShape getParentShape()
```


यदि पैरेंट ऑब्जेक्ट IShape इंटरफ़ेस को लागू नहीं करता है तो पैरेंट आकार या null लौटाता है। केवल पढ़ने योग्य [IShape](../../com.aspose.slides/ishape)।

--------------------

> ```
> The following code sample shows 
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      AutoShape autoShape = (AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      Table table = (Table)presentation.getSlides().get_Item(0).getShapes().get_Item(1);
> 
>      // ये अभिव्यक्तियां हमेशा सत्य हैं
>      Assert.assertTrue(autoShape.getTextFrame().getParentShape() == autoShape);
>      Assert.assertTrue((table.get_Item(0,0).getTextFrame()).getParentShape() == null);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**वापसी:**
[IShape](../../com.aspose.slides/ishape)
### getParentCell() {#getParentCell--}
```
public abstract ICell getParentCell()
```


यदि पैरेंट ऑब्जेक्ट ICell इंटरफ़ेस को लागू नहीं करता है तो पैरेंट सेल या null लौटाता है। केवल पढ़ने योग्य [ICell](../../com.aspose.slides/icell)।

--------------------

> ```
> The following code sample shows 
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      AutoShape autoShape = (AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      Table table = (Table)presentation.getSlides().get_Item(0).getShapes().get_Item(1);
> 
>      // ये अभिव्यक्तियां हमेशा सत्य हैं
>      Assert.assertTrue(table.get_Item(0,0).getTextFrame().getParentCell() == table.get_Item(0,0));
>      Assert.assertTrue(autoShape.getTextFrame().getParentCell() == null);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**वापसी:**
[ICell](../../com.aspose.slides/icell)
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```


सभी पैराग्राफ़ों में समान फ़ॉर्मेटिंग वाले रन को जोड़ता है।

### highlightText(String text, Integer highlightColor) {#highlightText-java.lang.String-java.lang.Integer-}
```
public abstract void highlightText(String text, Integer highlightColor)
```


निर्दिष्ट रंग के साथ नमूना पाठ के सभी मिलान को हाइलाइट करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| text | java.lang.String | हाइलाइट करने के लिए पाठ। |
| highlightColor | java.lang.Integer | पाठ को हाइलाइट करने के लिए रंग। |

### splitTextByColumns() {#splitTextByColumns--}
```
public abstract String[] splitTextByColumns()
```


[ITextFrame](../../com.aspose.slides/itextframe) की टेक्स्ट सामग्री को स्ट्रिंग्स की एक एरे में विभाजित करता है, जहाँ प्रत्येक तत्व फ्रेम के भीतर एक अलग टेक्स्ट कॉलम के अनुरूप होता है।

--------------------

> ```
> The following example demonstrates how to use #splitTextByColumns.splitTextByColumns:
>  
>  Presentation pres = new Presentation("example.pptx");
>  try {
>      // स्लाइड पर पहला आकार प्राप्त करें और इसे ITextFrame में कास्ट करें
>      ITextFrame textFrame = (ITextFrame) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // टेक्स्ट फ्रेम की सामग्री को कॉलम्स में विभाजित करें
>      String[] columnsText = textFrame.splitTextByColumns();
>      // प्रत्येक कॉलम का टेक्स्ट कंसोल में प्रिंट करें
>      for (String column : columnsText)
>          System.out.println(column);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**वापसी:**
java.lang.String[] - एक स्ट्रिंग्स एरे, जहाँ प्रत्येक स्ट्रिंग [ITextFrame](../../com.aspose.slides/itextframe) में एक विशिष्ट कॉलम की टेक्स्ट सामग्री का प्रतिनिधित्व करती है।

--------------------

यदि टेक्स्ट फ्रेम में कई कॉलम नहीं हैं, तो लौटाई गई एरे में एक ही तत्व होगा जिसमें पूरा टेक्स्ट होगा। खाली कॉलम एरे में खाली स्ट्रिंग के रूप में प्रदर्शित होंगे।
### highlightText(String text, Integer highlightColor, ITextHighlightingOptions options) {#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextHighlightingOptions-}
```
public abstract void highlightText(String text, Integer highlightColor, ITextHighlightingOptions options)
```


निर्दिष्ट रंग के साथ नमूना पाठ के सभी मिलान को हाइलाइट करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| text | java.lang.String | हाइलाइट करने के लिए पाठ। |
| highlightColor | java.lang.Integer | पाठ को हाइलाइट करने के लिए रंग। |
| options | [ITextHighlightingOptions](../../com.aspose.slides/itexthighlightingoptions) | हाइलाइटिंग विकल्प। |

### highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```


निर्दिष्ट रंग के साथ नमूना पाठ के सभी मिलान को हाइलाइट करता है।

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
>      // सभी अलग-अलग 'the' occurrences को हाइलाइट कर रहा है
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("the", Color.MAGENTA, textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| text | java.lang.String | हाइलाइट करने के लिए पाठ। |
| highlightColor | java.lang.Integer | पाठ को हाइलाइट करने के लिए रंग। |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | टेक्स्ट सर्च विकल्प [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions)। |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | खोज परिणाम प्राप्त करने के लिए कॉलबैक ऑब्जेक्ट [IFindResultCallback](../../com.aspose.slides/ifindresultcallback)। |

### highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)
```


निर्दिष्ट रंग के साथ नियमित अभिव्यक्ति के सभी मिलान को हाइलाइट करता है।

--------------------

> ```
> The following code sample shows how to highlight text in a TextFrame using a regular expression.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{5,}\\b");
>      // सभी शब्दों को हाइलाइट कर रहा है जिनमें 5 या अधिक प्रतीक हैं
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightRegex(regex, Color.BLUE, null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| regex | java.util.regex.Pattern | हाइलाइट करने के लिए स्ट्रिंग्स प्राप्त करने हेतु नियमित अभिव्यक्ति java.util.regex.Pattern। |
| highlightColor | java.lang.Integer | पाठ को हाइलाइट करने के लिए रंग। |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | खोज परिणाम प्राप्त करने के लिए कॉलबैक ऑब्जेक्ट [IFindResultCallback](../../com.aspose.slides/ifindresultcallback)। |

### highlightRegex(String regex, Integer highlightColor, ITextHighlightingOptions options) {#highlightRegex-java.lang.String-java.lang.Integer-com.aspose.slides.ITextHighlightingOptions-}
```
public abstract void highlightRegex(String regex, Integer highlightColor, ITextHighlightingOptions options)
```


निर्दिष्ट रंग के साथ नियमित अभिव्यक्ति के सभी मिलान को हाइलाइट करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| regex | java.lang.String | हाइलाइट करने के लिए नियमित अभिव्यक्ति का टेक्स्ट। |
| highlightColor | java.lang.Integer | पाठ को हाइलाइट करने के लिए रंग। |
| options | [ITextHighlightingOptions](../../com.aspose.slides/itexthighlightingoptions) | हाइलाइटिंग विकल्प। |

### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
```


निर्दिष्ट पाठ की सभी occurrences को दूसरे निर्दिष्ट पाठ से बदलता है।

--------------------

> ```
> The following sample code shows how to replace one specified string with another specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // सभी अलग-अलग 'the' occurrences को '***' के साथ बदलें
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| oldText | java.lang.String | बदलने वाला स्ट्रिंग। |
| newText | java.lang.String | सभी occurrences को बदलने वाला स्ट्रिंग। |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | टेक्स्ट सर्च विकल्प [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions)। |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | खोज परिणाम प्राप्त करने के लिए कॉलबैक ऑब्जेक्ट [IFindResultCallback](../../com.aspose.slides/ifindresultcallback)। |

### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```


नियमित अभिव्यक्ति के सभी मिलान को निर्दिष्ट स्ट्रिंग से बदलता है।

--------------------

> ```
> The following code sample shows how to replace text using regular expression with the specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{5,}\\b");
>      // 5 प्रतीकों या अधिक वाले सभी शब्दों को '***' के साथ बदलें
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().replaceRegex(regex, "***", null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| regex | java.util.regex.Pattern | बदलने हेतु स्ट्रिंग्स प्राप्त करने के लिए नियमित अभिव्यक्ति java.util.regex.Pattern। |
| newText | java.lang.String | बदलने वाले स्ट्रिंग्स की सभी occurrences को बदलने वाला स्ट्रिंग। |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | खोज परिणाम प्राप्त करने के लिए कॉलबैक ऑब्जेक्ट [IFindResultCallback](../../com.aspose.slides/ifindresultcallback)। |