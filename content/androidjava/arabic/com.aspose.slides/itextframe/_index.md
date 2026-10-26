---
title: ITextFrame
second_title: Aspose.Slides لنظام Android عبر مرجع API جافا
description: يمثل TextFrame.
type: docs
url: /ar/com.aspose.slides/itextframe/
---
**جميع الواجهات التي تم تنفيذها:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface ITextFrame extends ISlideComponent
```

يمثل TextFrame.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getParagraphs()](#getParagraphs--) | يرجع قائمة جميع الفقرات في الإطار. |
| [getText()](#getText--) | يحصل أو يحدد النص العادي لإطار TextFrame. |
| [setText(String value)](#setText-java.lang.String-) | يحصل أو يحدد النص العادي لإطار TextFrame. |
| [getTextFrameFormat()](#getTextFrameFormat--) | يرجع كائن التنسيق لهذا الكائن TextFrame. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | يوفر وصولًا سهلًا إلى الروابط التشعبية الموجودة. |
| [getParentShape()](#getParentShape--) | يرجع الشكل الأب أو null إذا لم ينفّذ الكائن الأب واجهة IShape. قراءة فقط [IShape](../../com.aspose.slides/ishape). |
| [getParentCell()](#getParentCell--) | يرجع الخلية الأب أو null إذا لم ينفّذ الكائن الأب واجهة ICell. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | ينضمّ المقاطع ذات التنسيق المتطابق في جميع الفقرات. |
| [highlightText(String text, Integer highlightColor)](#highlightText-java.lang.String-java.lang.Integer-) | يُبرز جميع مطابقة النص النموذجي باللون المحدد. |
| [splitTextByColumns()](#splitTextByColumns--) | يقسّم محتوى النص الخاص بـ [ITextFrame](../../com.aspose.slides/itextframe) إلى مصفوفة من السلاسل، حيث يتطابق كل عنصر مع عمود نص منفصل داخل الإطار. |
| [highlightText(String text, Integer highlightColor, ITextHighlightingOptions options)](#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextHighlightingOptions-) | يُبرز جميع مطابقة النص النموذجي باللون المحدد. |
| [highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | يُبرز جميع مطابقة النص النموذجي باللون المحدد. |
| [highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-) | يُبرز جميع مطابقة التعبير النمطي باللون المحدد. |
| [highlightRegex(String regex, Integer highlightColor, ITextHighlightingOptions options)](#highlightRegex-java.lang.String-java.lang.Integer-com.aspose.slides.ITextHighlightingOptions-) | يُبرز جميع مطابقة التعبير النمطي باللون المحدد. |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | يستبدل جميع حدوث النص المحدد بنص آخر محدد. |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | يستبدل جميع مطابقة التعبير النمطي بالسلسلة المحددة. |

### getParagraphs() {#getParagraphs--}
```
public abstract IParagraphCollection getParagraphs()
```

يرجع قائمة جميع الفقرات في الإطار. قراءة فقط [IParagraphCollection](../../com.aspose.slides/iparagraphcollection).

**القيمة المرجعة:**
[IParagraphCollection](../../com.aspose.slides/iparagraphcollection)

### getText() {#getText--}
```
public abstract String getText()
```

يحصل أو يحدد النص العادي لإطار TextFrame. قراءة/كتابة String.

القيمة: النص.

**القيمة المرجعة:**
java.lang.String

### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```

يحصل أو يحدد النص العادي لإطار TextFrame. قراءة/كتابة String.

القيمة: النص.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getTextFrameFormat() {#getTextFrameFormat--}
```
public abstract ITextFrameFormat getTextFrameFormat()
```

يرجع كائن التنسيق لهذا الكائن TextFrame. قراءة فقط [ITextFrameFormat](../../com.aspose.slides/itextframeformat).

**القيمة المرجعة:**
[ITextFrameFormat](../../com.aspose.slides/itextframeformat)

### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public abstract IHyperlinkQueries getHyperlinkQueries()
```

يوفر وصولًا سهلًا إلى الروابط التشعبية الموجودة. قراءة فقط [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**القيمة المرجعة:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)

### getParentShape() {#getParentShape--}
```
public abstract IShape getParentShape()
```

يرجع الشكل الأب أو null إذا لم ينفّذ الكائن الأب واجهة IShape. قراءة فقط [IShape](../../com.aspose.slides/ishape).

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


**القيمة المرجعة:**
[IShape](../../com.aspose.slides/ishape)

### getParentCell() {#getParentCell--}
```
public abstract ICell getParentCell()
```

يرجع الخلية الأب أو null إذا لم ينفّذ الكائن الأب واجهة ICell. قراءة فقط [ICell](../../com.aspose.slides/icell).

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


**القيمة المرجعة:**
[ICell](../../com.aspose.slides/icell)

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```

ينضمّ المقاطع ذات التنسيق المتطابق في جميع الفقرات.

### highlightText(String text, Integer highlightColor) {#highlightText-java.lang.String-java.lang.Integer-}
```
public abstract void highlightText(String text, Integer highlightColor)
```

يُبرز جميع مطابقة النص النموذجي باللون المحدد.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| text | java.lang.String | النص الذي سيتم تمييزه. |
| highlightColor | java.lang.Integer | اللون لتحديد النص. |

### splitTextByColumns() {#splitTextByColumns--}
```
public abstract String[] splitTextByColumns()
```

يقسّم محتوى النص الخاص بـ [ITextFrame](../../com.aspose.slides/itextframe) إلى مصفوفة من السلاسل، حيث يتطابق كل عنصر مع عمود نص منفصل داخل الإطار.

> ```
> The following example demonstrates how to use #splitTextByColumns.splitTextByColumns:
>  
>  Presentation pres = new Presentation("example.pptx");
>  try {
>      // الحصول على الشكل الأول في الشريحة وتحويله إلى ITextFrame
>      ITextFrame textFrame = (ITextFrame) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // تقسيم محتوى إطار النص إلى أعمدة
>      String[] columnsText = textFrame.splitTextByColumns();
>      // طباعة نص كل عمود إلى وحدة التحكم
>      for (String column : columnsText)
>          System.out.println(column);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**القيمة المرجعة:**
java.lang.String[] - مصفوفة من السلاسل، حيث تمثل كل سلسلة محتوى النص لعمود محدد في [ITextFrame](../../com.aspose.slides/itextframe).

إذا لم يحتوي إطار النص على أعمدة متعددة، فإن المصفوفة المرتجعة ستحتوي على عنصر واحد يحتوي على النص الكامل. سيتم تمثيل الأعمدة الفارغة كسلاسل فارغة في المصفوفة.

### highlightText(String text, Integer highlightColor, ITextHighlightingOptions options) {#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextHighlightingOptions-}
```
public abstract void highlightText(String text, Integer highlightColor, ITextHighlightingOptions options)
```

يُبرز جميع مطابقة النص النموذجي باللون المحدد.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| text | java.lang.String | النص الذي سيتم تمييزه. |
| highlightColor | java.lang.Integer | اللون لتحديد النص. |
| options | [ITextHighlightingOptions](../../com.aspose.slides/itexthighlightingoptions) | خيارات التمييز. |

### highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```

يُبرز جميع مطابقة النص النموذجي باللون المحدد.

> ```
> The following code sample shows how to highlight text in a TextFrame.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // highlighting all words 'important'
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("important", Color.BLUE);
>      // highlighting all separate 'the' occurrences
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("the", Color.MAGENTA, textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| text | java.lang.String | النص الذي سيتم تمييزه. |
| highlightColor | java.lang.Integer | اللون لتحديد النص. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | خيارات بحث النص [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | كائن الاستدعاء لتلقي نتائج البحث [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)
```

يُبرز جميع مطابقة التعبير النمطي باللون المحدد.

> ```
> The following code sample shows how to highlight text in a TextFrame using a regular expression.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{5,}\\b");
>      // تمييز جميع الكلمات التي تتكون من 5 أحرف أو أكثر
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightRegex(regex, Color.BLUE, null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| regex | java.util.regex.Pattern | التعبير النمطي java.util.regex.Pattern للحصول على السلاسل لتحديدها. |
| highlightColor | java.lang.Integer | اللون لتحديد النص. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | كائن الاستدعاء لتلقي نتائج البحث [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### highlightRegex(String regex, Integer highlightColor, ITextHighlightingOptions options) {#highlightRegex-java.lang.String-java.lang.Integer-com.aspose.slides.ITextHighlightingOptions-}
```
public abstract void highlightRegex(String regex, Integer highlightColor, ITextHighlightingOptions options)
```

يُبرز جميع مطابقة التعبير النمطي باللون المحدد.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| regex | java.lang.String | نص التعبير النمطي للحصول على النص لتحديده. |
| highlightColor | java.lang.Integer | اللون لتحديد النص. |
| options | [ITextHighlightingOptions](../../com.aspose.slides/itexthighlightingoptions) | خيارات التمييز. |

### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
```

يستبدل جميع حدوث النص المحدد بنص آخر محدد.

> ```
> The following sample code shows how to replace one specified string with another specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // استبدال جميع حدوثات كلمة 'the' المنفصلة بـ '***'
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
| newText | java.lang.String | السلسلة التي ستحل محل جميع حدوث النص القديم. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | خيارات بحث النص [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | كائن الاستدعاء لتلقي نتائج البحث [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```

يستبدل جميع مطابقة التعبير النمطي بالسلسلة المحددة.

> ```
> The following code sample shows how to replace text using regular expression with the specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{5,}\\b");
>      // استبدال جميع الكلمات التي يتجاوز طولها 5 أحرف بـ '***'
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().replaceRegex(regex, "***", null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| regex | java.util.regex.Pattern | التعبير النمطي java.util.regex.Pattern للحصول على السلاسل لاستبدالها. |
| newText | java.lang.String | السلسلة التي ستحل محل جميع حدوث السلاسل التي سيتم استبدالها. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | كائن الاستدعاء لتلقي نتائج البحث [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |