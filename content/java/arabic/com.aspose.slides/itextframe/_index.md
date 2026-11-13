---
title: ITextFrame
second_title: مرجع API Aspose.Slides للغة Java
description: يمثل TextFrame.
type: docs
url: /ar/com.aspose.slides/itextframe/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface ITextFrame extends ISlideComponent
```

يمثل TextFrame.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getParagraphs()](#getParagraphs--) | إرجاع قائمة جميع الفقرات في إطار. |
| [getText()](#getText--) | الحصول على النص العادي أو تعيينه لإطار TextFrame. |
| [setText(String value)](#setText-java.lang.String-) | الحصول على النص العادي أو تعيينه لإطار TextFrame. |
| [getTextFrameFormat()](#getTextFrameFormat--) | إرجاع كائن التنسيق لهذا الكائن TextFrame. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | توفير وصول سهل إلى الروابط التشعبية المحتواة. |
| [getParentShape()](#getParentShape--) | إرجاع الشكل الأب أو null إذا كان الكائن الأب لا يطبق واجهة IShape. للقراءة فقط [IShape](../../com.aspose.slides/ishape). |
| [getTextRect()](#getTextRect--) | الحصول على مستطيل النص المحدد بواسطة هندسة الشكل الأب. |
| [getParentCell()](#getParentCell--) | إرجاع الخلية الأب أو null إذا كان الكائن الأب لا يطبق واجهة ICell. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | دمج القطع ذات التنسيق المتطابق في جميع الفقرات. |
| [highlightText(String text, Color highlightColor)](#highlightText-java.lang.String-java.awt.Color-) | تظليل جميع التطابقات للنص العينة باللون المحدد. |
| [splitTextByColumns()](#splitTextByColumns--) | تقسيم محتوى النص في [ITextFrame](../../com.aspose.slides/itextframe) إلى مصفوفة من السلاسل، حيث يتطابق كل عنصر مع عمود نص منفصل داخل الإطار. |
| [highlightText(String text, Color highlightColor, ITextHighlightingOptions options)](#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextHighlightingOptions-) | تظليل جميع التطابقات للنص العينة باللون المحدد. |
| [highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | تظليل جميع التطابقات للنص العينة باللون المحدد. |
| [highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-) | تظليل جميع التطابقات للتعبير النمطي باللون المحدد. |
| [highlightRegex(String regex, Color highlightColor, ITextHighlightingOptions options)](#highlightRegex-java.lang.String-java.awt.Color-com.aspose.slides.ITextHighlightingOptions-) | تظليل جميع التطابقات للتعبير النمطي باللون المحدد. |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | استبدال جميع حدوث النص المحدد بنص آخر محدد. |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | استبدال جميع التطابقات للتعبير النمطي بالسلسلة المحددة. |
### getParagraphs() {#getParagraphs--}
```
public abstract IParagraphCollection getParagraphs()
```

إرجاع قائمة جميع الفقرات في إطار. للقراءة فقط [IParagraphCollection](../../com.aspose.slides/iparagraphcollection).

**الإرجاع:**
[IParagraphCollection](../../com.aspose.slides/iparagraphcollection)
### getText() {#getText--}
```
public abstract String getText()
```

الحصول على النص العادي أو تعيينه لإطار TextFrame. قراءة/كتابة String.

القيمة: النص.

**الإرجاع:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```

الحصول على النص العادي أو تعيينه لإطار TextFrame. قراءة/كتابة String.

القيمة: النص.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getTextFrameFormat() {#getTextFrameFormat--}
```
public abstract ITextFrameFormat getTextFrameFormat()
```

إرجاع كائن التنسيق لهذا الكائن TextFrame. للقراءة فقط [ITextFrameFormat](../../com.aspose.slides/itextframeformat).

**الإرجاع:**
[ITextFrameFormat](../../com.aspose.slides/itextframeformat)
### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public abstract IHyperlinkQueries getHyperlinkQueries()
```

توفر وصول سهل إلى الروابط التشعبية المحتواة. للقراءة فقط [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**الإرجاع:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)
### getParentShape() {#getParentShape--}
```
public abstract IShape getParentShape()
```

إرجاع الشكل الأب أو null إذا كان الكائن الأب لا يطبق واجهة IShape. للقراءة فقط [IShape](../../com.aspose.slides/ishape).

--------------------

> ```
> The following code sample shows 
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      AutoShape autoShape = (AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      Table table = (Table)presentation.getSlides().get_Item(0).getShapes().get_Item(1);
> 
>      // هذه العبارات دائمًا صحيحة
>      Assert.assertTrue(autoShape.getTextFrame().getParentShape() == autoShape);
>      Assert.assertTrue((table.get_Item(0,0).getTextFrame()).getParentShape() == null);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**الإرجاع:**
[IShape](../../com.aspose.slides/ishape)
### getTextRect() {#getTextRect--}
```
public abstract Rectangle2D.Float getTextRect()
```

الحصول على مستطيل النص المحدد بواسطة هندسة الشكل الأب.

**الإرجاع:**
java.awt.geom.Rectangle2D.Float - كائن java.awt.geom.Rectangle2D.Float يحدد مساحة النص.

--------------------

إحداثيات المستطيل نسبية إلى الزاوية العليا اليسرى للشكل الأب.
### getParentCell() {#getParentCell--}
```
public abstract ICell getParentCell()
```

إرجاع الخلية الأب أو null إذا كان الكائن الأب لا يطبق واجهة ICell. للقراءة فقط [ICell](../../com.aspose.slides/icell).

--------------------

> ```
> The following code sample shows 
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      AutoShape autoShape = (AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      Table table = (Table)presentation.getSlides().get_Item(0).getShapes().get_Item(1);
> 
>      // هذه العبارات دائمًا صحيحة
>      Assert.assertTrue(table.get_Item(0,0).getTextFrame().getParentCell() == table.get_Item(0,0));
>      Assert.assertTrue(autoShape.getTextFrame().getParentCell() == null);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**الإرجاع:**
[ICell](../../com.aspose.slides/icell)
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```

دمج القطع ذات التنسيق المتطابق في جميع الفقرات.

### highlightText(String text, Color highlightColor) {#highlightText-java.lang.String-java.awt.Color-}
```
public abstract void highlightText(String text, Color highlightColor)
```

تظليل جميع التطابقات للنص العينة باللون المحدد.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| text | java.lang.String | النص المراد تظليله. |
| highlightColor | java.awt.Color | اللون المستخدم لتظليل النص. |

### splitTextByColumns() {#splitTextByColumns--}
```
public abstract String[] splitTextByColumns()
```

تقسيم محتوى النص في [ITextFrame](../../com.aspose.slides/itextframe) إلى مصفوفة من السلاسل، حيث يتطابق كل عنصر مع عمود نص منفصل داخل الإطار.

--------------------

> ```
> The following example demonstrates how to use #splitTextByColumns.splitTextByColumns:
>  
>  Presentation pres = new Presentation("example.pptx");
>  try {
>      // احصل على الشكل الأول في الشريحة وقم بتحويله إلى ITextFrame
>      ITextFrame textFrame = (ITextFrame) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // قسّم محتوى إطار النص إلى أعمدة
>      String[] columnsText = textFrame.splitTextByColumns();
>      // اطبع نص كل عمود إلى وحدة التحكم
>      for (String column : columnsText)
>          System.out.println(column);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**الإرجاع:**
java.lang.String[] - مصفوفة من السلاسل، حيث تمثل كل سلسلة محتوى النص لعمود محدد في [ITextFrame](../../com.aspose.slides/itextframe).

--------------------

إذا لم يحتوي إطار النص على أعمدة متعددة، فستحتوي المصفوفة المرجعة على عنصر واحد يحتوي على النص الكامل. الأعمدة الفارغة ستمثل كسلاسل فارغة في المصفوفة.
### highlightText(String text, Color highlightColor, ITextHighlightingOptions options) {#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextHighlightingOptions-}
```
public abstract void highlightText(String text, Color highlightColor, ITextHighlightingOptions options)
```

تظليل جميع التطابقات للنص العينة باللون المحدد.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| text | java.lang.String | النص المراد تظليله. |
| highlightColor | java.awt.Color | اللون المستخدم لتظليل النص. |
| options | [ITextHighlightingOptions](../../com.aspose.slides/itexthighlightingoptions) | خيارات التظليل. |

### highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```

تظليل جميع التطابقات للنص العينة باللون المحدد.

--------------------

> ```
> The following code sample shows how to highlight text in a TextFrame.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // تظليل جميع الكلمات 'important'
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("important", Color.BLUE);
>      // تظليل جميع تكرارات 'the' المستقلة
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("the", Color.MAGENTA, textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| text | java.lang.String | النص المراد تظليله. |
| highlightColor | java.awt.Color | اللون المستخدم لتظليل النص. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | خيارات البحث عن النص [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | كائن الاسترجاع لتلقي نتائج البحث [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)
```

تظليل جميع التطابقات للتعبير النمطي باللون المحدد.

--------------------

> ```
> The following code sample shows how to highlight text in a TextFrame using a regular expression.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{5,}\\b");
>      // تظليل جميع الكلمات التي تتكون من 5 رموز أو أكثر
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightRegex(regex, Color.BLUE, null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| regex | java.util.regex.Pattern | التعبير النمطي java.util.regex.Pattern للحصول على السلاسل لتظليلها. |
| highlightColor | java.awt.Color | اللون المستخدم لتظليل النص. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | كائن الاسترجاع لتلقي نتائج البحث [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### highlightRegex(String regex, Color highlightColor, ITextHighlightingOptions options) {#highlightRegex-java.lang.String-java.awt.Color-com.aspose.slides.ITextHighlightingOptions-}
```
public abstract void highlightRegex(String regex, Color highlightColor, ITextHighlightingOptions options)
```

تظليل جميع التطابقات للتعبير النمطي باللون المحدد.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| regex | java.lang.String | نص التعبير النمطي للحصول على النص المراد تظليله. |
| highlightColor | java.awt.Color | اللون المستخدم لتظليل النص. |
| options | [ITextHighlightingOptions](../../com.aspose.slides/itexthighlightingoptions) | خيارات التظليل. |

### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
```

استبدال جميع حدوث النص المحدد بنص آخر محدد.

--------------------

> ```
> The following sample code shows how to replace one specified string with another specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // استبدال جميع حالات 'the' المنفصلة بـ '***'
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| oldText | java.lang.String | السلسلة التي سيتم استبدالها. |
| newText | java.lang.String | السلسلة التي ستحل محل جميع حدوث oldText. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | خيارات البحث عن النص [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | كائن الاسترجاع لتلقي نتائج البحث [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```

استبدال جميع التطابقات للتعبير النمطي بالسلسلة المحددة.

--------------------

> ```
> The following code sample shows how to replace text using regular expression with the specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{5,}\\b");
>      // استبدال جميع الكلمات التي تتكون من 5 رموز أو أكثر بـ '***'
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().replaceRegex(regex, "***", null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| regex | java.util.regex.Pattern | التعبير النمطي java.util.regex.Pattern للحصول على السلاسل التي سيتم استبدالها. |
| newText | java.lang.String | السلسلة التي ستحل محل جميع حدوث السلاسل التي سيتم استبدالها. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | كائن الاسترجاع لتلقي نتائج البحث [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |