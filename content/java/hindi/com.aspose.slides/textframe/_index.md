---
title: TextFrame
second_title: Aspose.Slides for Java API संदर्भ
description: एक TextFrame का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/textframe/
---
**विरासत:**
java.lang.Object

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.ITextFrame](../../com.aspose.slides/itextframe), com.aspose.slides.IDOMObject
```
public final class TextFrame implements ITextFrame, IDOMObject
```

एक TextFrame का प्रतिनिधित्व करता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getParagraphs()](#getParagraphs--) | फ़्रेम में सभी पैराग्राफ़ की सूची लौटाता है। |
| [getText()](#getText--) | एक TextFrame के साधारण पाठ को प्राप्त करता है या सेट करता है। |
| [setText(String value)](#setText-java.lang.String-) | एक TextFrame के साधारण पाठ को प्राप्त करता है या सेट करता है। |
| [getTextFrameFormat()](#getTextFrameFormat--) | इस TextFrame ऑब्जेक्ट के लिए स्वरूपण ऑब्जेक्ट लौटाता है। |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | निहित हाइपरलिंक तक आसान पहुँच प्रदान करता है। |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | सभी पैराग्राफ़ में समान स्वरूपण वाले रन को जोड़ता है। |
| [highlightText(String text, Color highlightColor)](#highlightText-java.lang.String-java.awt.Color-) | उदाहरण पाठ की सभी मेलों को निर्दिष्ट रंग से हाइलाइट करता है। |
| [highlightText(String text, Color highlightColor, ITextHighlightingOptions options)](#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextHighlightingOptions-) | उदाहरण पाठ की सभी मेलों को निर्दिष्ट रंग से हाइलाइट करता है। |
| [splitTextByColumns()](#splitTextByColumns--) | [ITextFrame](../../com.aspose.slides/itextframe) की पाठ सामग्री को स्ट्रिंग्स की एक सरणी में विभाजित करता है, जहाँ प्रत्येक तत्व फ़्रेम के भीतर अलग-अलग पाठ कॉलम से मेल खाता है। |
| [highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | उदाहरण पाठ की सभी मेलों को निर्दिष्ट रंग से हाइलाइट करता है। |
| [highlightRegex(String regex, Color highlightColor, ITextHighlightingOptions options)](#highlightRegex-java.lang.String-java.awt.Color-com.aspose.slides.ITextHighlightingOptions-) | नियमित अभिव्यक्ति की सभी मेलों को निर्दिष्ट रंग से हाइलाइट करता है। |
| [highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-) | नियमित अभिव्यक्ति की सभी मेलों को निर्दिष्ट रंग से हाइलाइट करता है। |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | निर्दिष्ट पाठ की सभी घटनाओं को दूसरे निर्दिष्ट पाठ से बदलता है। |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | नियमित अभिव्यक्ति की सभी मेलों को निर्दिष्ट स्ट्रिंग से बदलता है। |
| [getSlide()](#getSlide--) | एक TextFrame की पैरेंट स्लाइड लौटाता है। |
| [getPresentation()](#getPresentation--) | एक TextFrame की पैरेंट प्रस्तुति लौटाता है। |
| [getParentShape()](#getParentShape--) | पैरेंट शैप लौटाता है या null यदि पैरेंट ऑब्जेक्ट IShape इंटरफ़ेस लागू नहीं करता है। केवल-पढ़ने योग्य [IShape](../../com.aspose.slides/ishape)। |
| [getTextRect()](#getTextRect--) | पैरेंट शैप की ज्यामिति द्वारा परिभाषित टेक्स्ट आयत प्राप्त करता है। |
| [getParentCell()](#getParentCell--) | पैरेंट सेल लौटाता है या null यदि पैरेंट ऑब्जेक्ट ICell इंटरफ़ेस लागू नहीं करता है। |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate ऑब्जेक्ट लौटाता है। केवल-पढ़ने योग्य IDOMObject।

**वापसी:**
com.aspose.slides.IDOMObject

### getParagraphs() {#getParagraphs--}
```
public final IParagraphCollection getParagraphs()
```

फ़्रेम में सभी पैराग्राफ़ की सूची लौटाता है। केवल-पढ़ने योग्य [IParagraphCollection](../../com.aspose.slides/iparagraphcollection)।

**वापसी:**
[IParagraphCollection](../../com.aspose.slides/iparagraphcollection)

### getText() {#getText--}
```
public final String getText()
```

एक TextFrame के साधारण पाठ को प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य String।

मान: पाठ।

**वापसी:**
java.lang.String

### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```

एक TextFrame के साधारण पाठ को प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य String।

मान: पाठ।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getTextFrameFormat() {#getTextFrameFormat--}
```
public final ITextFrameFormat getTextFrameFormat()
```

इस TextFrame ऑब्जेक्ट के लिए स्वरूपण ऑब्जेक्ट लौटाता है। केवल-पढ़ने योग्य [ITextFrameFormat](../../com.aspose.slides/itextframeformat)।

**वापसी:**
[ITextFrameFormat](../../com.aspose.slides/itextframeformat)

### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public final IHyperlinkQueries getHyperlinkQueries()
```

निहित हाइपरलिंक तक आसान पहुँच प्रदान करता है। केवल-पढ़ने योग्य [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)।

**वापसी:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public final void joinPortionsWithSameFormatting()
```

सभी पैराग्राफ़ में समान स्वरूपण वाले रन को जोड़ता है।

### highlightText(String text, Color highlightColor) {#highlightText-java.lang.String-java.awt.Color-}
```
public final void highlightText(String text, Color highlightColor)
```

उदाहरण पाठ की सभी मेलों को निर्दिष्ट रंग से हाइलाइट करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| text | java.lang.String | हाइलाइट करने के लिए नमूना पाठ। |
| highlightColor | java.awt.Color | पाठ को हाइलाइट करने का रंग। |

### highlightText(String text, Color highlightColor, ITextHighlightingOptions options) {#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextHighlightingOptions-}
```
public final void highlightText(String text, Color highlightColor, ITextHighlightingOptions options)
```

उदाहरण पाठ की सभी मेलों को निर्दिष्ट रंग से हाइलाइट करता है।

--------------------

> ```
> The following sample code shows how to Highlight Text in a TextFrame.
>  
>  try {
>      TextHighlightingOptions textHighlightingOptions = new TextHighlightingOptions();
>      textHighlightingOptions.setWholeWordsOnly(true);
>      // सभी शब्द 'important' को हाइलाइट करना
>      ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("title", Color.BLUE);
>      // सभी अलग-अलग 'the' घटनाओं को हाइलाइट करना
>      ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("to", Color.MAGENTA, textHighlightingOptions);
>      pres.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| text | java.lang.String | हाइलाइट करने के लिए पाठ। |
| highlightColor | java.awt.Color | पाठ को हाइलाइट करने का रंग। |
| options | [ITextHighlightingOptions](../../com.aspose.slides/itexthighlightingoptions) | हाइलाइट विकल्प। |

### splitTextByColumns() {#splitTextByColumns--}
```
public final String[] splitTextByColumns()
```

[ITextFrame](../../com.aspose.slides/itextframe) की पाठ सामग्री को स्ट्रिंग्स की एक सरणी में विभाजित करता है, जहाँ प्रत्येक तत्व फ़्रेम के भीतर अलग-अलग पाठ कॉलम से मेल खाता है।

--------------------

> ```
> The following example demonstrates how to use #splitTextByColumns.splitTextByColumns:
>  
>  Presentation pres = new Presentation("example.pptx");
>  try {
>      // स्लाइड पर पहला शैप प्राप्त करें और इसे ITextFrame में कास्ट करें
>      ITextFrame textFrame = (ITextFrame) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // टेक्स्ट फ्रेम की सामग्री को कॉलम में विभाजित करें
>      String[] columnsText = textFrame.splitTextByColumns();
>      // प्रत्येक कॉलम का टेक्स्ट कंसोल में प्रिंट करें
>      for (String column : columnsText)
>          System.out.println(column);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**वापसी:**
java.lang.String[] - स्ट्रिंग्स की एक सरणी, जहाँ प्रत्येक स्ट्रिंग [ITextFrame](../../com.aspose.slides/itextframe) में एक विशिष्ट कॉलम की पाठ सामग्री का प्रतिनिधित्व करती है।

यदि टेक्स्ट फ़्रेम में कई कॉलम नहीं हैं, तो लौटाई गई सरणी में एक ही तत्व होगा जिसमें संपूर्ण पाठ होगा। खाली कॉलम को सरणी में खाली स्ट्रिंग के रूप में दर्शाया जाएगा।

### highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```

उदाहरण पाठ की सभी मेलों को निर्दिष्ट रंग से हाइलाइट करता है।

--------------------

> ```
> The following code sample shows how to highlight text in a TextFrame.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // सभी शब्द 'important' को हाइलाइट करना
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("important", Color.BLUE);
>      // सभी अलग-अलग 'the' घटनाओं को हाइलाइट करना
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
| highlightColor | java.awt.Color | पाठ को हाइलाइट करने का रंग। |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | पाठ खोज विकल्प [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions)। |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | खोज परिणाम प्राप्त करने के लिए कॉलबैक ऑब्जेक्ट [IFindResultCallback](../../com.aspose.slides/ifindresultcallback)। |

### highlightRegex(String regex, Color highlightColor, ITextHighlightingOptions options) {#highlightRegex-java.lang.String-java.awt.Color-com.aspose.slides.ITextHighlightingOptions-}
```
public final void highlightRegex(String regex, Color highlightColor, ITextHighlightingOptions options)
```

नियमित अभिव्यक्ति की सभी मेलों को निर्दिष्ट रंग से हाइलाइट करता है।

--------------------

> ```
> The following code sample shows how to highlight text in a TextFrame using a regular expression.
>  
>  Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      TextHighlightingOptions options = new TextHighlightingOptions();
>      // 10 अक्षरों या उससे अधिक वाले सभी शब्दों को हाइलाइट करना
>      ((AutoShape) pres.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightRegex("\\b[^\\s){5,}\\b", Color.BLUE, options);
>      pres.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| regex | java.lang.String | हाइलाइट करने के लिए पाठ प्राप्त करने हेतु नियमित अभिव्यक्ति का पाठ। |
| highlightColor | java.awt.Color | पाठ को हाइलाइट करने का रंग। |
| options | [ITextHighlightingOptions](../../com.aspose.slides/itexthighlightingoptions) | हाइलाइट विकल्प। |

### highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-}
```
public final void highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)
```

नियमित अभिव्यक्ति की सभी मेलों को निर्दिष्ट रंग से हाइलाइट करता है।

--------------------

> ```
> The following code sample shows how to highlight text in a TextFrame using a regular expression.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{5,}\\b");
>      // 5 प्रतीकों या उससे अधिक वाले सभी शब्दों को हाइलाइट करना
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightRegex(regex, Color.BLUE, null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| regex | java.util.regex.Pattern | हाइलाइट करने हेतु स्ट्रिंग्स प्राप्त करने के लिए java.util.regex.Pattern नियमित अभिव्यक्ति। |
| highlightColor | java.awt.Color | पाठ को हाइलाइट करने का रंग। |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | खोज परिणाम प्राप्त करने के लिए कॉलबैक ऑब्जेक्ट [IFindResultCallback](../../com.aspose.slides/ifindresultcallback)। |

### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
```

निर्दिष्ट पाठ की सभी घटनाओं को दूसरे निर्दिष्ट पाठ से बदलता है।

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

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| oldText | java.lang.String | बदलने के लिए स्ट्रिंग। |
| newText | java.lang.String | oldText की सभी घटनाओं को बदलने के लिए स्ट्रिंग। |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | पाठ खोज विकल्प [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions)। |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | बदलाव ऑपरेशन परिणाम सहेजने के लिए कॉलबैक ऑब्जेक्ट [IFindResultCallback](../../com.aspose.slides/ifindresultcallback)। |

### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public final void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```

नियमित अभिव्यक्ति की सभी मेलों को निर्दिष्ट स्ट्रिंग से बदलता है।

--------------------

> ```
> The following sample code shows how to replace text using regular expression with specified string.
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

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| regex | java.util.regex.Pattern | बदलने के लिए स्ट्रिंग्स प्राप्त करने हेतु java.util.regex.Pattern नियमित अभिव्यक्ति। |
| newText | java.lang.String | बदलने के लिए स्ट्रिंग। |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | बदलाव ऑपरेशन परिणाम सहेजने के लिए कॉलबैक ऑब्जेक्ट [IFindResultCallback](../../com.aspose.slides/ifindresultcallback)। |

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

एक TextFrame की पैरेंट स्लाइड लौटाता है। केवल-पढ़ने योग्य [IBaseSlide](../../com.aspose.slides/ibaseslide)।

**वापसी:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

एक TextFrame की पैरेंट प्रस्तुति लौटाता है। केवल-पढ़ने योग्य [IPresentation](../../com.aspose.slides/ipresentation)।

**वापसी:**
[IPresentation](../../com.aspose.slides/ipresentation)

### getParentShape() {#getParentShape--}
```
public final IShape getParentShape()
```

पैरेंट शैप लौटाता है या null यदि पैरेंट ऑब्जेक्ट IShape इंटरफ़ेस लागू नहीं करता है। केवल-पढ़ने योग्य [IShape](../../com.aspose.slides/ishape)।

--------------------

> ```
> The following code sample shows 
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      AutoShape autoShape = (AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      Table table = (Table)presentation.getSlides().get_Item(0).getShapes().get_Item(1);
> 
>      // ये पुष्टिकरण हमेशा सत्य होते हैं
>      Assert.assertTrue(autoShape.getTextFrame().getParentShape() == autoShape);
>      Assert.assertTrue((table.get_Item(0,0).getTextFrame()).getParentShape() == null);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**वापसी:**
[IShape](../../com.aspose.slides/ishape)

### getTextRect() {#getTextRect--}
```
public final Rectangle2D.Float getTextRect()
```

पैरेंट शैप की ज्यामिति द्वारा परिभाषित टेक्स्ट आयत प्राप्त करता है।

**वापसी:**
java.awt.geom.Rectangle2D.Float - एक java.awt.geom.Rectangle2D.Float जो पाठ क्षेत्र को परिभाषित करता है।

### getParentCell() {#getParentCell--}
```
public final ICell getParentCell()
```

पैरेंट सेल लौटाता है या null यदि पैरेंट ऑब्जेक्ट ICell इंटरफ़ेस लागू नहीं करता है। केवल-पढ़ने योग्य [ICell](../../com.aspose.slides/icell)।

--------------------

> ```
> The following code sample shows 
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      AutoShape autoShape = (AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      Table table = (Table)presentation.getSlides().get_Item(0).getShapes().get_Item(1);
> 
>      // ये पुष्टिकरण हमेशा सत्य होते हैं
>      Assert.assertTrue(table.get_Item(0,0).getTextFrame().getParentCell() == table.get_Item(0,0));
>      // ये पुष्टिकरण हमेशा सत्य होते हैं
>      Assert.assertTrue(autoShape.getTextFrame().getParentCell() == null);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**वापसी:**
[ICell](../../com.aspose.slides/icell)