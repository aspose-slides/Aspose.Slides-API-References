---
title: TextFrame
second_title: مرجع API لـ Aspose.Slides للـ Java
description: يمثل TextFrame.
type: docs
url: /ar/com.aspose.slides/textframe/
---
**الوراثة:**  
java.lang.Object

**كل الواجهات المنفذة:**  
[com.aspose.slides.ITextFrame](../../com.aspose.slides/itextframe), com.aspose.slides.IDOMObject  
```
public final class TextFrame implements ITextFrame, IDOMObject
```

يمثل إطار نص.

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getParagraphs()](#getParagraphs--) | يعيد قائمة بجميع الفقرات في الإطار. |
| [getText()](#getText--) | يحصل أو يحدد النص العادي لإطار النص. |
| [setText(String value)](#setText-java.lang.String-) | يحصل أو يحدد النص العادي لإطار النص. |
| [getTextFrameFormat()](#getTextFrameFormat--) | يعيد كائن التنسيق لهذا الكائن TextFrame. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | يوفر وصولاً سهلاً إلى الارتباطات التشعبية المحتواة. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | ينضم السلاسل ذات التنسيق نفسه في جميع الفقرات. |
| [highlightText(String text, Color highlightColor)](#highlightText-java.lang.String-java.awt.Color-) | يبرز جميع التطابقات للنص العيّني باللون المحدد. |
| [highlightText(String text, Color highlightColor, ITextHighlightingOptions options)](#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextHighlightingOptions-) | يبرز جميع التطابقات للنص العيّني باللون المحدد. |
| [splitTextByColumns()](#splitTextByColumns--) | يفصل محتوى النص لـ [ITextFrame](../../com.aspose.slides/itextframe) إلى مصفوفة من السلاسل، حيث يمثل كل عنصر عمود نص منفصل داخل الإطار. |
| [highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | يبرز جميع التطابقات للنص العيّني باللون المحدد. |
| [highlightRegex(String regex, Color highlightColor, ITextHighlightingOptions options)](#highlightRegex-java.lang.String-java.awt.Color-com.aspose.slides.ITextHighlightingOptions-) | يبرز جميع التطابقات للتعبير النمطي باللون المحدد. |
| [highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-) | يبرز جميع التطابقات للتعبير النمطي باللون المحدد. |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | يستبدل جميع حالات النص المحدد بنص آخر محدد. |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | يستبدل جميع التطابقات للتعبير النمطي بالسلسلة المحددة. |
| [getSlide()](#getSlide--) | يعيد الشريحة الأصلية لإطار النص. |
| [getPresentation()](#getPresentation--) | يعيد العرض الأصلي لإطار النص. |
| [getParentShape()](#getParentShape--) | يعيد الشكل الأصل أو null إذا كان الكائن الأصلي لا ينفذ واجهة IShape للقراءة فقط [IShape](../../com.aspose.slides/ishape). |
| [getTextRect()](#getTextRect--) | يحصل على مستطيل النص المحدد بجغرافية الشكل الأصلي. |
| [getParentCell()](#getParentCell--) | يعيد الخلية الأصل أو null إذا كان الكائن الأصلي لا ينفذ واجهة ICell. |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

يعيد كائن Parent_Immediate. للقراءة فقط IDOMObject.

**يعيد:**  
com.aspose.slides.IDOMObject

### getParagraphs() {#getParagraphs--}
```
public final IParagraphCollection getParagraphs()
```

يعيد قائمة بجميع الفقرات في الإطار. للقراءة فقط [IParagraphCollection](../../com.aspose.slides/iparagraphcollection).

**يعيد:**  
[IParagraphCollection](../../com.aspose.slides/iparagraphcollection)

### getText() {#getText--}
```
public final String getText()
```

يحصل أو يحدد النص العادي لإطار النص. قابل للقراءة والكتابة String.

القيمة: النص.

**يعيد:**  
java.lang.String

### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```

يحصل أو يحدد النص العادي لإطار النص. قابل للقراءة والكتابة String.

القيمة: النص.

**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getTextFrameFormat() {#getTextFrameFormat--}
```
public final ITextFrameFormat getTextFrameFormat()
```

يعيد كائن التنسيق لهذا الكائن TextFrame. للقراءة فقط [ITextFrameFormat](../../com.aspose.slides/itextframeformat).

**يعيد:**  
[ITextFrameFormat](../../com.aspose.slides/itextframeformat)

### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public final IHyperlinkQueries getHyperlinkQueries()
```

يوفر وصولاً سهلاً إلى الارتباطات التشعبية المحتواة. للقراءة فقط [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**يعيد:**  
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public final void joinPortionsWithSameFormatting()
```

ينضم السلاسل ذات التنسيق نفسه في جميع الفقرات.

### highlightText(String text, Color highlightColor) {#highlightText-java.lang.String-java.awt.Color-}
```
public final void highlightText(String text, Color highlightColor)
```

يبرز جميع التطابقات للنص العيّني باللون المحدد.

**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| text | java.lang.String | عينة النص للتمييز. |
| highlightColor | java.awt.Color | اللون لتظليل النص. |

### highlightText(String text, Color highlightColor, ITextHighlightingOptions options) {#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextHighlightingOptions-}
```
public final void highlightText(String text, Color highlightColor, ITextHighlightingOptions options)
```

يبرز جميع التطابقات للنص العيّني باللون المحدد.

> ```
> يوضح الكود التالي كيفية تمييز النص في TextFrame.
>  
>  try {
>      TextHighlightingOptions textHighlightingOptions = new TextHighlightingOptions();
>      textHighlightingOptions.setWholeWordsOnly(true);
>      // تمييز جميع الكلمات 'important'
>      ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("title", Color.BLUE);
>      // تمييز جميع الحالات المنفصلة لكلمة 'the'
>      ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("to", Color.MAGENTA, textHighlightingOptions);
>      pres.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| text | java.lang.String | العينة النصية للتمييز. |
| highlightColor | java.awt.Color | اللون لتظليل النص. |
| options | [ITextHighlightingOptions](../../com.aspose.slides/itexthighlightingoptions) | خيارات التمييز. |

### splitTextByColumns() {#splitTextByColumns--}
```
public final String[] splitTextByColumns()
```

يفصل محتوى النص لـ [ITextFrame](../../com.aspose.slides/itextframe) إلى مصفوفة من السلاسل، حيث يمثل كل عنصر عمود نص منفصل داخل الإطار.

> ```
> يوضح المثال التالي كيفية استخدام #splitTextByColumns.splitTextByColumns:
>  
>  Presentation pres = new Presentation("example.pptx");
>  try {
>      // احصل على الشكل الأول في الشريحة وحوله إلى ITextFrame
>      ITextFrame textFrame = (ITextFrame) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // قسم محتوى إطار النص إلى أعمدة
>      String[] columnsText = textFrame.splitTextByColumns();
>      // اطبع نص كل عمود إلى وحدة التحكم
>      for (String column : columnsText)
>          System.out.println(column);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**يعيد:**  
java.lang.String[] - مصفوفة من السلاسل، حيث تمثل كل سلسلة محتوى النص لعمود محدد في [ITextFrame](../../com.aspose.slides/itextframe).

إذا لم يحتوي إطار النص على أعمدة متعددة، فستحتوي المصفوفة المُعادة على عنصر واحد يحتوي على النص الكامل. ستمثل الأعمدة الفارغة سلاسل فارغة في المصفوفة.

### highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```

يبرز جميع التطابقات للنص العيّني باللون المحدد.

> ```
> The following code sample shows how to highlight text in a TextFrame.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // تمييز جميع الكلمات 'important'
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("important", Color.BLUE);
>      // تمييز جميع الحالات المنفصلة لكلمة 'the'
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("the", Color.MAGENTA, textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| text | java.lang.String | النص للتمييز. |
| highlightColor | java.awt.Color | اللون لتظليل النص. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | خيارات البحث النصي [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | كائن الاسترجاع لتلقي نتائج البحث [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### highlightRegex(String regex, Color highlightColor, ITextHighlightingOptions options) {#highlightRegex-java.lang.String-java.awt.Color-com.aspose.slides.ITextHighlightingOptions-}
```
public final void highlightRegex(String regex, Color highlightColor, ITextHighlightingOptions options)
```

يبرز جميع التطابقات للتعبير النمطي باللون المحدد.

> ```
> يوضح المثال البرمجي التالي كيفية تمييز النص في TextFrame باستخدام تعبير نمطي.
>  
>  Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      TextHighlightingOptions options = new TextHighlightingOptions();
>      // تمييز جميع الكلمات التي تتكون من 10 رموز أو أكثر
>      ((AutoShape) pres.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightRegex("\\b[^\\s){5,}\\b", Color.BLUE, options);
>      pres.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| regex | java.lang.String | نص التعبير النمطي للحصول على النص للتمييز. |
| highlightColor | java.awt.Color | اللون لتظليل النص. |
| options | [ITextHighlightingOptions](../../com.aspose.slides/itexthighlightingoptions) | خيارات التمييز. |

### highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-}
```
public final void highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)
```

يبرز جميع التطابقات للتعبير النمطي باللون المحدد.

> ```
> يوضح المثال البرمجي التالي كيفية تمييز النص في TextFrame باستخدام تعبير نمطي.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{5,}\\b");
>      // تمييز جميع الكلمات التي تتكون من 5 رموز أو أكثر
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightRegex(regex, Color.BLUE, null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| regex | java.util.regex.Pattern | التعبير النمطي java.util.regex.Pattern للحصول على السلاسل للتمييز. |
| highlightColor | java.awt.Color | اللون لتظليل النص. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | كائن الاسترجاع لتلقي نتائج البحث [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
```

يستبدل جميع حالات النص المحدد بنص آخر محدد.

> ```
> يوضح الكود العيني التالي كيفية استبدال سلسلة محددة بأخرى محددة.
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


**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| oldText | java.lang.String | السلسلة المراد استبدالها. |
| newText | java.lang.String | السلسلة التي ستحل محل جميع حالات oldText. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | خيارات البحث النصي [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | كائن الاسترجاع لحفظ نتيجة عملية الاستبدال [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public final void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```

يستبدل جميع التطابقات للتعبير النمطي بالسلسلة المحددة.

> ```
> The following sample code shows how to replace text using regular expression with specified string.
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

**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| regex | java.util.regex.Pattern | التعبير النمطي java.util.regex.Pattern للحصول على السلاسل التي ستحل محلها. |
| newText | java.lang.String | السلسلة التي ستحل محل جميع حالات السلاسل التي ستحل محلها. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | كائن الاسترجاع لحفظ نتيجة عملية الاستبدال [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

يعيد الشريحة الأصل لإطار النص. للقراءة فقط [IBaseSlide](../../com.aspose.slides/ibaseslide).

**يعيد:**  
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

يعيد العرض الأصلي لإطار النص. للقراءة فقط [IPresentation](../../com.aspose.slides/ipresentation).

**يعيد:**  
[IPresentation](../../com.aspose.slides/ipresentation)

### getParentShape() {#getParentShape--}
```
public final IShape getParentShape()
```

يعيد الشكل الأصل أو null إذا كان الكائن الأصلي لا ينفذ واجهة IShape للقراءة فقط [IShape](../../com.aspose.slides/ishape).

> ```
> The following code sample shows 
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      AutoShape autoShape = (AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      Table table = (Table)presentation.getSlides().get_Item(0).getShapes().get_Item(1);
> 
>      // هذه التأكيدات صحيحة دائمًا
>      Assert.assertTrue(autoShape.getTextFrame().getParentShape() == autoShape);
>      Assert.assertTrue((table.get_Item(0,0).getTextFrame()).getParentShape() == null);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**يعيد:**  
[IShape](../../com.aspose.slides/ishape)

### getTextRect() {#getTextRect--}
```
public final Rectangle2D.Float getTextRect()
```

يحصل على مستطيل النص المحدد بجغرافية الشكل الأصل.

**يعيد:**  
java.awt.geom.Rectangle2D.Float - كائن java.awt.geom.Rectangle2D.Float يحدد مساحة النص.

### getParentCell() {#getParentCell--}
```
public final ICell getParentCell()
```

يعيد الخلية الأصل أو null إذا كان الكائن الأصلي لا ينفذ واجهة ICell. للقراءة فقط [ICell](../../com.aspose.slides/icell).

> ```
> يوضح المثال البرمجي التالي 
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      AutoShape autoShape = (AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      Table table = (Table)presentation.getSlides().get_Item(0).getShapes().get_Item(1);
> 
>      // هذه التأكيدات صحيحة دائمًا
>      Assert.assertTrue(table.get_Item(0,0).getTextFrame().getParentCell() == table.get_Item(0,0));
>      Assert.assertTrue(autoShape.getTextFrame().getParentCell() == null);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**يعيد:**  
[ICell](../../com.aspose.slides/icell)