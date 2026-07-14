---
title: TextFrame
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يمثّل TextFrame.
type: docs
url: /ar/com.aspose.slides/textframe/
---
**الوراثة:**  
java.lang.Object

**جميع الواجهات المنفذة:**  
[com.aspose.slides.ITextFrame](../../com.aspose.slides/itextframe), com.aspose.slides.IDOMObject  
```
public final class TextFrame implements ITextFrame, IDOMObject
```

يمثل TextFrame.
## الأساليب

| الطريقة | الوصف |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getParagraphs()](#getParagraphs--) | يعيد القائمة التي تحتوي على جميع الفقرات في الإطار. |
| [getText()](#getText--) | يسترجع أو يعيّن النص العادي لـ TextFrame. |
| [setText(String value)](#setText-java.lang.String-) | يسترجع أو يعيّن النص العادي لـ TextFrame. |
| [getTextFrameFormat()](#getTextFrameFormat--) | يعيد كائن التنسيق لهذا كائن TextFrame. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | يوفر وصولاً سهلاً إلى الروابط التشعبية المحتواة. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | يجمع المقاطع ذات التنسيق المتطابق في جميع الفقرات. |
| [highlightText(String text, Integer highlightColor)](#highlightText-java.lang.String-java.lang.Integer-) | يسلط الضوء على جميع تطابقات النص النموذجي باللون المحدد. |
| [highlightText(String text, Integer highlightColor, ITextHighlightingOptions options)](#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextHighlightingOptions-) | يسلط الضوء على جميع تطابقات النص النموذجي باللون المحدد. |
| [splitTextByColumns()](#splitTextByColumns--) | يقسم محتوى النص لـ [ITextFrame](../../com.aspose.slides/itextframe) إلى مصفوفة من السلاسل، حيث يتطابق كل عنصر مع عمود نصي منفصل داخل الإطار. |
| [highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | يسلط الضوء على جميع تطابقات النص النموذجي باللون المحدد. |
| [highlightRegex(String regex, Integer highlightColor, ITextHighlightingOptions options)](#highlightRegex-java.lang.String-java.lang.Integer-com.aspose.slides.ITextHighlightingOptions-) | يسلط الضوء على جميع تطابقات التعبير النمطي باللون المحدد. |
| [highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-) | يسلط الضوء على جميع تطابقات التعبير النمطي باللون المحدد. |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | يستبدل جميع حالات النص المحدد بنص آخر محدد. |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | يستبدل جميع تطابقات التعبير النمطي بالسلسلة المحددة. |
| [getSlide()](#getSlide--) | يعيد الشريحة الأصلية لـ TextFrame. |
| [getPresentation()](#getPresentation--) | يعيد العرض الأصلي لـ TextFrame. |
| [getParentShape()](#getParentShape--) | يعيد الشكل الأصلي أو null إذا لم يكن الكائن الأصلي ينفّذ واجهة IShape. قراءة فقط [IShape](../../com.aspose.slides/ishape). |
| [getParentCell()](#getParentCell--) | يعيد الخلية الأصلية أو null إذا لم يكن الكائن الأصلي ينفّذ واجهة ICell. |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

يعيد كائن Parent_Immediate. قراءة فقط IDOMObject.

**الإرجاع:**  
com.aspose.slides.IDOMObject

### getParagraphs() {#getParagraphs--}
```
public final IParagraphCollection getParagraphs()
```

يعيد القائمة التي تحتوي على جميع الفقرات في الإطار. قراءة فقط [IParagraphCollection](../../com.aspose.slides/iparagraphcollection).

**الإرجاع:**  
[IParagraphCollection](../../com.aspose.slides/iparagraphcollection)

### getText() {#getText--}
```
public final String getText()
```

يسترجع أو يعيّن النص العادي لـ TextFrame. قراءة/كتابة String.

القيمة: النص.

**الإرجاع:**  
java.lang.String

### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```

يسترجع أو يعيّن النص العادي لـ TextFrame. قراءة/كتابة String.

القيمة: النص.

**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getTextFrameFormat() {#getTextFrameFormat--}
```
public final ITextFrameFormat getTextFrameFormat()
```

يعيد كائن التنسيق لهذا كائن TextFrame. قراءة فقط [ITextFrameFormat](../../com.aspose.slides/itextframeformat).

**الإرجاع:**  
[ITextFrameFormat](../../com.aspose.slides/itextframeformat)

### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public final IHyperlinkQueries getHyperlinkQueries()
```

يوفر وصولاً سهلاً إلى الروابط التشعبية المحتواة. قراءة فقط [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**الإرجاع:**  
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public final void joinPortionsWithSameFormatting()
```

يجمع المقاطع ذات التنسيق المتطابق في جميع الفقرات.

### highlightText(String text, Integer highlightColor) {#highlightText-java.lang.String-java.lang.Integer-}
```
public final void highlightText(String text, Integer highlightColor)
```

يسلط الضوء على جميع تطابقات النص النموذجي باللون المحدد.

**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| text | java.lang.String | نص العينة لتسليط الضوء عليه. |
| highlightColor | java.lang.Integer | اللون لتسليط الضوء على النص. |

### highlightText(String text, Integer highlightColor, ITextHighlightingOptions options) {#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextHighlightingOptions-}
```
public final void highlightText(String text, Integer highlightColor, ITextHighlightingOptions options)
```

يسلط الضوء على جميع تطابقات النص النموذجي باللون المحدد.

---
> ```
> The following sample code shows how to Highlight Text in a TextFrame.
>  
>  try {
>      TextHighlightingOptions textHighlightingOptions = new TextHighlightingOptions();
>      textHighlightingOptions.setWholeWordsOnly(true);
>      // تسليط الضوء على جميع الكلمات 'important'
>      ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("title", Color.BLUE);
>      // تسليط الضوء على جميع حدوث 'the' المنفصل
>      ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("to", Color.MAGENTA, textHighlightingOptions);
>      pres.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| text | java.lang.String | النص لتسليط الضوء عليه. |
| highlightColor | java.lang.Integer | اللون لتسليط الضوء على النص. |
| options | [ITextHighlightingOptions](../../com.aspose.slides/itexthighlightingoptions) | خيارات التسليط. |

### splitTextByColumns() {#splitTextByColumns--}
```
public final String[] splitTextByColumns()
```

يقسم محتوى النص لـ [ITextFrame](../../com.aspose.slides/itextframe) إلى مصفوفة من السلاسل، حيث يتطابق كل عنصر مع عمود نصي منفصل داخل الإطار.

---
> ```
> المثال التالي يوضح كيفية استخدام #splitTextByColumns.splitTextByColumns:
>  
>  Presentation pres = new Presentation("example.pptx");
>  try {
>      // احصل على الشكل الأول في الشريحة وحوله إلى ITextFrame
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

---
إذا لم يحتوي إطار النص على أعمدة متعددة، فستحتوي المصفوفة المرتجعة على عنصر واحد يحتوي على النص الكامل. سيتم تمثيل الأعمدة الفارغة كسلاسل فارغة في المصفوفة.

### highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```

يسلط الضوء على جميع تطابقات النص النموذجي باللون المحدد.

---
> ```
> The following code sample shows how to highlight text in a TextFrame.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // تسليط الضوء على جميع الكلمات 'important'
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("important", Color.BLUE);
>      // تسليط الضوء على جميع حدوث 'the' المنفصل
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("the", Color.MAGENTA, textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| text | java.lang.String | النص لتسليط الضوء عليه. |
| highlightColor | java.lang.Integer | اللون لتسليط الضوء على النص. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | خيارات بحث النص [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | كائن رد النداء لتلقي نتائج البحث [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### highlightRegex(String regex, Integer highlightColor, ITextHighlightingOptions options) {#highlightRegex-java.lang.String-java.lang.Integer-com.aspose.slides.ITextHighlightingOptions-}
```
public final void highlightRegex(String regex, Integer highlightColor, ITextHighlightingOptions options)
```

يسلط الضوء على جميع تطابقات التعبير النمطي باللون المحدد.

---
> ```
> The following code sample shows how to highlight text in a TextFrame using a regular expression.
>  
>  Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      TextHighlightingOptions options = new TextHighlightingOptions();
>      // تسليط الضوء على جميع الكلمات التي تحتوي على 10 رموز أو أكثر
>      ((AutoShape) pres.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightRegex("\\b[^\\s){5,}\\b", Color.BLUE, options);
>      pres.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| regex | java.lang.String | نص التعبير النمطي للحصول على النص لتسليط الضوء عليه. |
| highlightColor | java.lang.Integer | اللون لتسليط الضوء على النص. |
| options | [ITextHighlightingOptions](../../com.aspose.slides/itexthighlightingoptions) | خيارات التسليط. |

### highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-}
```
public final void highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)
```

يسلط الضوء على جميع تطابقات التعبير النمطي باللون المحدد.

---
> ```
> The following code sample shows how to highlight text in a TextFrame using a regular expression.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{5,}\\b");
>      // تسليط الضوء على جميع الكلمات التي تحتوي على 5 رموز أو أكثر
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightRegex(regex, Color.BLUE, null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| regex | java.util.regex.Pattern | التعبير النمطي java.util.regex.Pattern للحصول على السلاسل لتسليط الضوء عليها. |
| highlightColor | java.lang.Integer | اللون لتسليط الضوء على النص. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | كائن رد النداء لتلقي نتائج البحث [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
```

يستبدل جميع حالات النص المحدد بنص آخر محدد.

---
> ```
> The following sample code shows how to replace one speified string with another speified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // استبدال جميع حدوث 'the' المنفصل بـ '***'
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| oldText | java.lang.String | السلسلة التي سيتم استبدالها. |
| newText | java.lang.String | السلسلة التي ستحل محل جميع حالات oldText. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | خيارات بحث النص [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | كائن رد النداء لحفظ نتيجة عملية الاستبدال [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public final void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```

يستبدل جميع تطابقات التعبير النمطي بالسلسلة المحددة.

---
> ```
> The following sample code shows how to replace text using regular expression with specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{5,}\\b");
>      // استبدال جميع الكلمات التي تحتوي على 5 رموز أو أكثر بـ '***'
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().replaceRegex(regex, "***", null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| regex | java.util.regex.Pattern | التعبير النمطي java.util.regex.Pattern للحصول على السلاسل التي سيتم استبدالها. |
| newText | java.lang.String | السلسلة التي ستحل محل جميع حالات السلاسل التي سيتم استبدالها. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | كائن رد النداء لحفظ نتيجة عملية الاستبدال [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

يعيد الشريحة الأصلية لـ TextFrame. قراءة فقط [IBaseSlide](../../com.aspose.slides/ibaseslide).

**الإرجاع:**  
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

يعيد العرض الأصلي لـ TextFrame. قراءة فقط [IPresentation](../../com.aspose.slides/ipresentation).

**الإرجاع:**  
[IPresentation](../../com.aspose.slides/ipresentation)

### getParentShape() {#getParentShape--}
```
public final IShape getParentShape()
```

يعيد الشكل الأصلي أو null إذا لم يكن الكائن الأصلي ينفّذ واجهة IShape. قراءة فقط [IShape](../../com.aspose.slides/ishape).

---
> ```
> The following code sample shows 
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      AutoShape autoShape = (AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      Table table = (Table)presentation.getSlides().get_Item(0).getShapes().get_Item(1);
> 
>      // هذه التأكيدات دائمًا صحيحة
>      Assert.assertTrue(autoShape.getTextFrame().getParentShape() == autoShape);
>      Assert.assertTrue((table.get_Item(0,0).getTextFrame()).getParentShape() == null);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**الإرجاع:**  
[IShape](../../com.aspose.slides/ishape)

### getParentCell() {#getParentCell--}
```
public final ICell getParentCell()
```

يعيد الخلية الأصلية أو null إذا لم يكن الكائن الأصلي ينفّذ واجهة ICell. قراءة فقط [ICell](../../com.aspose.slides/icell).

---
> ```
> The following code sample shows 
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      AutoShape autoShape = (AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      Table table = (Table)presentation.getSlides().get_Item(0).getShapes().get_Item(1);
> 
>      // هذه التأكيدات دائمًا صحيحة
>      Assert.assertTrue(table.get_Item(0,0).getTextFrame().getParentCell() == table.get_Item(0,0));
>      Assert.assertTrue(autoShape.getTextFrame().getParentCell() == null);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**الإرجاع:**  
[ICell](../../com.aspose.slides/icell)