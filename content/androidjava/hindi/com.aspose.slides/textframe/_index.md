---
title: TextFrame
second_title: Java API संदर्भ के माध्यम से Aspose.Slides for Android
description: एक TextFrame का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/textframe/
---
**विरासत:**
java.lang.Object

**सभी कार्यान्वित इंटरफ़ेस:**
[com.aspose.slides.ITextFrame](../../com.aspose.slides/itextframe), com.aspose.slides.IDOMObject
```
public final class TextFrame implements ITextFrame, IDOMObject
```

एक TextFrame का प्रतिनिधित्व करता है।
## विधियाँ

| विधि | वर्णन |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getParagraphs()](#getParagraphs--) | फ़्रेम में सभी पैराग्राफ की सूची लौटाता है। |
| [getText()](#getText--) | एक TextFrame के साधारण पाठ को प्राप्त करता है या सेट करता है। |
| [setText(String value)](#setText-java.lang.String-) | एक TextFrame के साधारण पाठ को प्राप्त करता है या सेट करता है। |
| [getTextFrameFormat()](#getTextFrameFormat--) | इस TextFrame वस्तु के लिए फ़ॉर्मेटिंग ऑब्जेक्ट लौटाता है। |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | समाविष्ट हाइपरलिंक तक आसान पहुँच प्रदान करता है। |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | सभी पैराग्राफ में समान फ़ॉर्मेटिंग वाले रन को जोड़ता है। |
| [highlightText(String text, Integer highlightColor)](#highlightText-java.lang.String-java.lang.Integer-) | निर्दिष्ट रंग के साथ नमूना पाठ के सभी मिलान को हाइलाइट करता है। |
| [highlightText(String text, Integer highlightColor, ITextHighlightingOptions options)](#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextHighlightingOptions-) | निर्दिष्ट रंग के साथ नमूना पाठ के सभी मिलान को हाइलाइट करता है। |
| [splitTextByColumns()](#splitTextByColumns--) | [ITextFrame](../../com.aspose.slides/itextframe) के पाठ सामग्री को स्ट्रिंग्स की एक ऐरे में विभाजित करता है, जहाँ प्रत्येक तत्व फ्रेम के भीतर एक अलग टेक्स्ट कॉलम के अनुरूप होता है। |
| [highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | निर्दिष्ट रंग के साथ नमूना पाठ के सभी मिलान को हाइलाइट करता है। |
| [highlightRegex(String regex, Integer highlightColor, ITextHighlightingOptions options)](#highlightRegex-java.lang.String-java.lang.Integer-com.aspose.slides.ITextHighlightingOptions-) | निर्दिष्ट रंग के साथ नियमित अभिव्यक्ति के सभी मिलान को हाइलाइट करता है। |
| [highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-) | निर्दिष्ट रंग के साथ नियमित अभिव्यक्ति के सभी मिलान को हाइलाइट करता है। |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | निर्दिष्ट पाठ की सभी घटनाओं को दूसरी निर्दिष्ट पाठ से बदलता है। |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | नियमित अभिव्यक्ति के सभी मिलान को निर्दिष्ट स्ट्रिंग से बदलता है। |
| [getSlide()](#getSlide--) | एक TextFrame की मूल स्लाइड लौटाता है। |
| [getPresentation()](#getPresentation--) | एक TextFrame की मूल प्रस्तुति लौटाता है। |
| [getParentShape()](#getParentShape--) | यदि मूल वस्तु IShape इंटरफ़ेस को लागू नहीं करती है तो मूल shape या null लौटाता है। केवल-पढ़ने-योग्य [IShape](../../com.aspose.slides/ishape)। |
| [getParentCell()](#getParentCell--) | यदि मूल वस्तु ICell इंटरफ़ेस को लागू नहीं करती है तो मूल cell या null लौटाता है। |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate ऑब्जेक्ट लौटाता है। केवल-पढ़ने-योग्य IDOMObject।

**रिटर्न:**
com.aspose.slides.IDOMObject

### getParagraphs() {#getParagraphs--}
```
public final IParagraphCollection getParagraphs()
```

फ़्रेम में सभी पैराग्राफ की सूची लौटाता है। केवल-पढ़ने-योग्य [IParagraphCollection](../../com.aspose.slides/iparagraphcollection)।

**रिटर्न:**
[IParagraphCollection](../../com.aspose.slides/iparagraphcollection)

### getText() {#getText--}
```
public final String getText()
```

एक TextFrame के साधारण पाठ को प्राप्त करता है या सेट करता है। पढ़ने-लेखन योग्य String।

मान: पाठ।

**रिटर्न:**
java.lang.String

### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```

एक TextFrame के साधारण पाठ को प्राप्त करता है या सेट करता है। पढ़ने-लेखन योग्य String।

मान: पाठ।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getTextFrameFormat() {#getTextFrameFormat--}
```
public final ITextFrameFormat getTextFrameFormat()
```

इस TextFrame वस्तु के लिए फ़ॉर्मेटिंग ऑब्जेक्ट लौटाता है। केवल-पढ़ने-योग्य [ITextFrameFormat](../../com.aspose.slides/itextframeformat)।

**रिटर्न:**
[ITextFrameFormat](../../com.aspose.slides/itextframeformat)

### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public final IHyperlinkQueries getHyperlinkQueries()
```

समाविष्ट हाइपरलिंक तक आसान पहुँच प्रदान करता है। केवल-पढ़ने-योग्य [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)।

**रिटर्न:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public final void joinPortionsWithSameFormatting()
```

सभी पैराग्राफ में समान फ़ॉर्मेटिंग वाले रन को जोड़ता है।

### highlightText(String text, Integer highlightColor) {#highlightText-java.lang.String-java.lang.Integer-}
```
public final void highlightText(String text, Integer highlightColor)
```

निर्दिष्ट रंग के साथ नमूना पाठ के सभी मिलान को हाइलाइट करता है।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| text | java.lang.String | हाइलाइट करने के लिए पाठ नमूना। |
| highlightColor | java.lang.Integer | पाठ को हाइलाइट करने के लिए रंग। |

### highlightText(String text, Integer highlightColor, ITextHighlightingOptions options) {#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextHighlightingOptions-}
```
public final void highlightText(String text, Integer highlightColor, ITextHighlightingOptions options)
```

निर्दिष्ट रंग के साथ नमूना पाठ के सभी मिलान को हाइलाइट करता है।

--------------------

> ```
> The following sample code shows how to Highlight Text in a TextFrame.
>  
>  try {
>      TextHighlightingOptions textHighlightingOptions = new TextHighlightingOptions();
>      textHighlightingOptions.setWholeWordsOnly(true);
>      // सभी शब्द 'important' को हाइलाइट कर रहा है
>      ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("title", Color.BLUE);
>      // सभी अलग-अलग 'the' घटनाओं को हाइलाइट कर रहा है
>      ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("to", Color.MAGENTA, textHighlightingOptions);
>      pres.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| text | java.lang.String | हाइलाइट करने के लिए पाठ। |
| highlightColor | java.lang.Integer | हाइलाइट करने के लिए रंग। |
| options | [ITextHighlightingOptions](../../com.aspose.slides/itexthighlightingoptions) | हाइलाइटिंग विकल्प। |

### splitTextByColumns() {#splitTextByColumns--}
```
public final String[] splitTextByColumns()
```

[ITextFrame](../../com.aspose.slides/itextframe) के पाठ सामग्री को स्ट्रिंग्स की एक ऐरे में विभाजित करता है, जहाँ प्रत्येक तत्व फ्रेम के भीतर एक अलग टेक्स्ट कॉलम के अनुरूप होता है।

--------------------

> ```
> The following example demonstrates how to use #splitTextByColumns.splitTextByColumns:
>  
>  Presentation pres = new Presentation("example.pptx");
>  try {
>      // स्लाइड पर पहला shape प्राप्त करें और इसे ITextFrame में कास्ट करें
>      ITextFrame textFrame = (ITextFrame) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // टेक्स्ट फ़्रेम की सामग्री को कॉलमों में विभाजित करें
>      String[] columnsText = textFrame.splitTextByColumns();
>      // प्रत्येक कॉलम का पाठ कंसोल पर प्रिंट करें
>      for (String column : columnsText)
>          System.out.println(column);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  ```


**रिटर्न:**
java.lang.String[] - एक स्ट्रिंग्स की ऐरे, जहाँ प्रत्येक स्ट्रिंग [ITextFrame](../../com.aspose.slides/itextframe) में एक विशिष्ट कॉलम की पाठ सामग्री का प्रतिनिधित्व करती है।

--------------------

यदि टेक्स्ट फ्रेम में कई कॉलम नहीं हैं, तो लौटाई गई ऐरे में पूरा पाठ समाहित करने वाला एक ही तत्व होगा। खाली कॉलम को ऐरे में खाली स्ट्रिंग के रूप में दर्शाया जाएगा।

### highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)
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
>      // सभी अलग-अलग 'the' घटनाओं को हाइलाइट कर रहा है
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("the", Color.MAGENTA, textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| text | java.lang.String | हाइलाइट करने के लिए पाठ। |
| highlightColor | java.lang.Integer | हाइलाइट करने के लिए रंग। |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | टेक्स्ट खोज विकल्प [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions)। |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | खोज परिणाम प्राप्त करने के लिए कॉलबैक ऑब्जेक्ट [IFindResultCallback](../../com.aspose.slides/ifindresultcallback)। |

### highlightRegex(String regex, Integer highlightColor, ITextHighlightingOptions options) {#highlightRegex-java.lang.String-java.lang.Integer-com.aspose.slides.ITextHighlightingOptions-}
```
public final void highlightRegex(String regex, Integer highlightColor, ITextHighlightingOptions options)
```

निर्दिष्ट रंग के साथ नियमित अभिव्यक्ति के सभी मिलान को हाइलाइट करता है।

--------------------

> ```
> The following code sample shows how to highlight text in a TextFrame using a regular expression.
>  
>  Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      TextHighlightingOptions options = new TextHighlightingOptions();
>      // सभी शब्द 10 प्रतीकों या उससे अधिक वाले को हाइलाइट कर रहा है
>      ((AutoShape) pres.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightRegex("\\b[^\\s){5,}\\b", Color.BLUE, options);
>      pres.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| regex | java.lang.String | हाइलाइट करने के लिए नियमित अभिव्यक्ति का पाठ। |
| highlightColor | java.lang.Integer | हाइलाइट करने के लिए रंग। |
| options | [ITextHighlightingOptions](../../com.aspose.slides/itexthighlightingoptions) | हाइलाइटिंग विकल्प। |

### highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-}
```
public final void highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)
```

निर्दिष्ट रंग के साथ नियमित अभिव्यक्ति के सभी मिलान को हाइलाइट करता है।

--------------------

> ```
> The following code sample shows how to highlight text in a TextFrame using a regular expression.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{5,}\\b");
>      // सभी शब्द 5 प्रतीकों या उससे अधिक वाले को हाइलाइट कर रहा है
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightRegex(regex, Color.BLUE, null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| regex | java.util.regex.Pattern | हाइलाइट करने के लिए नियमित अभिव्यक्ति java.util.regex.Pattern। |
| highlightColor | java.lang.Integer | हाइलाइट करने के लिए रंग। |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | खोज परिणाम प्राप्त करने के लिए कॉलबैक ऑब्जेक्ट [IFindResultCallback](../../com.aspose.slides/ifindresultcallback)। |

### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
```

निर्दिष्ट पाठ की सभी घटनाओं को दूसरी निर्दिष्ट पाठ से बदलता है।

--------------------

> ```
> The following sample code shows how to replace one speified string with another speified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // सभी अलग-अलग 'the' घटनाओं को '***' से बदलें
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| oldText | java.lang.String | बदलने वाला स्ट्रिंग। |
| newText | java.lang.String | oldText की सभी घटनाओं को बदलने वाला स्ट्रिंग। |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | टेक्स्ट खोज विकल्प [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions)। |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | प्रतिस्थापन संचालन परिणाम सहेजने के लिए कॉलबैक ऑब्जेक्ट [IFindResultCallback](../../com.aspose.slides/ifindresultcallback)। |

### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public final void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```

नियमित अभिव्यक्ति के सभी मिलान को निर्दिष्ट स्ट्रिंग से बदलता है।

--------------------

> ```
> The following sample code shows how to replace text using regular expression with specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{5,}\\b");
>      // सभी शब्द 5 प्रतीकों या उससे अधिक वाले को '***' से बदलें
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().replaceRegex(regex, "***", null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| regex | java.util.regex.Pattern | बदलने के लिए नियमित अभिव्यक्ति java.util.regex.Pattern। |
| newText | java.lang.String | सभी घटनाओं को बदलने वाला स्ट्रिंग। |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | प्रतिस्थापन संचालन परिणाम सहेजने के लिए कॉलबैक ऑब्जेक्ट [IFindResultCallback](../../com.aspose.slides/ifindresultcallback)। |

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

एक TextFrame की मूल स्लाइड लौटाता है। केवल-पढ़ने-योग्य [IBaseSlide](../../com.aspose.slides/ibaseslide)।

**रिटर्न:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

एक TextFrame की मूल प्रस्तुति लौटाता है। केवल-पढ़ने-योग्य [IPresentation](../../com.aspose.slides/ipresentation)।

**रिटर्न:**
[IPresentation](../../com.aspose.slides/ipresentation)

### getParentShape() {#getParentShape--}
```
public final IShape getParentShape()
```

यदि मूल वस्तु IShape इंटरफ़ेस को लागू नहीं करती है तो मूल shape या null लौटाता है। केवल-पढ़ने-योग्य [IShape](../../com.aspose.slides/ishape)।

--------------------

> ```
> The following code sample shows 
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      AutoShape autoShape = (AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      Table table = (Table)presentation.getSlides().get_Item(0).getShapes().get_Item(1);
> 
>      // ये असर्शन हमेशा सत्य हैं
>      Assert.assertTrue(autoShape.getTextFrame().getParentShape() == autoShape);
>      Assert.assertTrue((table.get_Item(0,0).getTextFrame()).getParentShape() == null);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**रिटर्न:**
[IShape](../../com.aspose.slides/ishape)

### getParentCell() {#getParentCell--}
```
public final ICell getParentCell()
```

यदि मूल वस्तु ICell इंटरफ़ेस को लागू नहीं करती है तो मूल cell या null लौटाता है। केवल-पढ़ने-योग्य [ICell](../../com.aspose.slides/icell)।

--------------------

> ```
> The following code sample shows 
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      AutoShape autoShape = (AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      Table table = (Table)presentation.getSlides().get_Item(0).getShapes().get_Item(1);
> 
>      // ये असर्शन हमेशा सत्य हैं
>      Assert.assertTrue(table.get_Item(0,0).getTextFrame().getParentCell() == table.get_Item(0,0));
>      Assert.assertTrue(autoShape.getTextFrame().getParentCell() == null);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**रिटर्न:**
[ICell](../../com.aspose.slides/icell)