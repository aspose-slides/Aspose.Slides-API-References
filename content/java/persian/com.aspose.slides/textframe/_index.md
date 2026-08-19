---
title: TextFrame
second_title: مرجع API Aspose.Slides برای Java
description: نمایانگر یک TextFrame است.
type: docs
url: /fa/com.aspose.slides/textframe/
---
**ارث‌بری:**
java.lang.Object

**همهٔ رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.ITextFrame](../../com.aspose.slides/itextframe), com.aspose.slides.IDOMObject
```
public final class TextFrame implements ITextFrame, IDOMObject
```

نمایانگر یک TextFrame است.
## متدها

| متد | توضیح |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getParagraphs()](#getParagraphs--) | فهرست تمام پاراگراف‌ها در یک قاب را برمی‌گرداند. |
| [getText()](#getText--) | متن ساده یک TextFrame را دریافت یا تنظیم می‌کند. |
| [setText(String value)](#setText-java.lang.String-) | متن ساده یک TextFrame را دریافت یا تنظیم می‌کند. |
| [getTextFrameFormat()](#getTextFrameFormat--) | شیء قالب‌بندی برای این شیء TextFrame را برمی‌گرداند. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | دسترسی آسان به پیوندهای موجود را فراهم می‌کند. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | بخش‌های با قالب‌بندی یکسان را در تمام پاراگراف‌ها ترکیب می‌کند. |
| [highlightText(String text, Color highlightColor)](#highlightText-java.lang.String-java.awt.Color-) | تمام مطابقت‌های متن نمونه را با رنگ مشخص برجسته می‌کند. |
| [highlightText(String text, Color highlightColor, ITextHighlightingOptions options)](#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextHighlightingOptions-) | تمام مطابقت‌های متن نمونه را با رنگ مشخص برجسته می‌کند. |
| [splitTextByColumns()](#splitTextByColumns--) | محتویات متنی [ITextFrame](../../com.aspose.slides/itextframe) را به آرایه‌ای از رشته‌ها تقسیم می‌کند که هر عنصر متن مربوط به یک ستون متنی جداگانه در قاب است. |
| [highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | تمام مطابقت‌های متن نمونه را با رنگ مشخص برجسته می‌کند. |
| [highlightRegex(String regex, Color highlightColor, ITextHighlightingOptions options)](#highlightRegex-java.lang.String-java.awt.Color-com.aspose.slides.ITextHighlightingOptions-) | تمام مطابقت‌های عبارت منظم را با رنگ مشخص برجسته می‌کند. |
| [highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-) | تمام مطابقت‌های عبارت منظم را با رنگ مشخص برجسته می‌کند. |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | تمام موارد متن مشخص را با متن دیگر مشخص جایگزین می‌کند. |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | تمام مطابقت‌های عبارت منظم را با رشتهٔ مشخص جایگزین می‌کند. |
| [getSlide()](#getSlide--) | اسلاید والد یک TextFrame را برمی‌گرداند. |
| [getPresentation()](#getPresentation--) | ارائهٔ والد یک TextFrame را برمی‌گرداند. |
| [getParentShape()](#getParentShape--) | شکل والد یا null را برمی‌گرداند اگر شیء والد رابط IShape را پیاده‌سازی نکند فقط‌خواندنی [IShape](../../com.aspose.slides/ishape). |
| [getParentCell()](#getParentCell--) | سلول والد یا null را برمی‌گرداند اگر شیء والد رابط ICell را پیاده‌سازی نکند. |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

شیء Parent_Immediate را برمی‌گرداند. فقط‌خواندنی IDOMObject.

**باز می‌گردد:**
com.aspose.slides.IDOMObject
### getParagraphs() {#getParagraphs--}
```
public final IParagraphCollection getParagraphs()
```

فهرست تمام پاراگراف‌ها در یک قاب را برمی‌گرداند. فقط‌خواندنی [IParagraphCollection](../../com.aspose.slides/iparagraphcollection).

**باز می‌گردد:**
[IParagraphCollection](../../com.aspose.slides/iparagraphcollection)
### getText() {#getText--}
```
public final String getText()
```

متن ساده یک TextFrame را دریافت یا تنظیم می‌کند. قابل‌خواندن/نوشتن String.

مقدار: متن.

**باز می‌گردد:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```

متن ساده یک TextFrame را دریافت یا تنظیم می‌کند. قابل‌خواندن/نوشتن String.

مقدار: متن.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |
### getTextFrameFormat() {#getTextFrameFormat--}
```
public final ITextFrameFormat getTextFrameFormat()
```

شیء قالب‌بندی برای این شیء TextFrame را برمی‌گرداند. فقط‌خواندنی [ITextFrameFormat](../../com.aspose.slides/itextframeformat).

**باز می‌گردد:**
[ITextFrameFormat](../../com.aspose.slides/itextframeformat)
### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public final IHyperlinkQueries getHyperlinkQueries()
```

دسترسی آسان به پیوندهای موجود را فراهم می‌کند. فقط‌خواندنی [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**باز می‌گردد:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public final void joinPortionsWithSameFormatting()
```

بخش‌های با قالب‌بندی یکسان را در تمام پاراگراف‌ها ترکیب می‌کند.
### highlightText(String text, Color highlightColor) {#highlightText-java.lang.String-java.awt.Color-}
```
public final void highlightText(String text, Color highlightColor)
```

تمام مطابقت‌های متن نمونه را با رنگ مشخص برجسته می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| text | java.lang.String | نمونهٔ متنی برای برجسته‌سازی. |
| highlightColor | java.awt.Color | رنگی که متن با آن برجسته می‌شود. |
### highlightText(String text, Color highlightColor, ITextHighlightingOptions options) {#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextHighlightingOptions-}
```
public final void highlightText(String text, Color highlightColor, ITextHighlightingOptions options)
```

تمام مطابقت‌های متن نمونه را با رنگ مشخص برجسته می‌کند.

--------------------

> ```
> The following sample code shows how to Highlight Text in a TextFrame.
>  
>  try {
>      TextHighlightingOptions textHighlightingOptions = new TextHighlightingOptions();
>      textHighlightingOptions.setWholeWordsOnly(true);
>      // highlighting all words 'important'
>      ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("title", Color.BLUE);
>      // highlighting all separate 'the' occurrences
>      ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("to", Color.MAGENTA, textHighlightingOptions);
>      pres.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| text | java.lang.String | متن برای برجسته‌سازی. |
| highlightColor | java.awt.Color | رنگی که متن با آن برجسته می‌شود. |
| options | [ITextHighlightingOptions](../../com.aspose.slides/itexthighlightingoptions) | گزینه‌های برجسته‌سازی. |
### splitTextByColumns() {#splitTextByColumns--}
```
public final String[] splitTextByColumns()
```

محتویات متنی [ITextFrame](../../com.aspose.slides/itextframe) را به آرایه‌ای از رشته‌ها تقسیم می‌کند که هر عنصر متن مربوط به یک ستون متنی جداگانه در قاب است.

--------------------

> ```
> The following example demonstrates how to use #splitTextByColumns.splitTextByColumns:
>  
>  Presentation pres = new Presentation("example.pptx");
>  try {
>      // Get the first shape on the slide and cast it to ITextFrame
>      ITextFrame textFrame = (ITextFrame) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // Split the text frame content into columns
>      String[] columnsText = textFrame.splitTextByColumns();
>      // Print each column's text to the console
>      for (String column : columnsText)
>          System.out.println(column);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**باز می‌گردد:**
java.lang.String[] - آرایه‌ای از رشته‌ها که هر رشته محتوای متنی یک ستون خاص در [ITextFrame](../../com.aspose.slides/itextframe) را نشان می‌دهد.

--------------------

اگر فریم متن شامل چندین ستون نباشد، آرایهٔ بازگردانده‌شده یک عنصر واحد شامل متن کامل خواهد داشت. ستون‌های خالی به صورت رشته‌های خالی در آرایه نشان داده می‌شوند.
### highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```

تمام مطابقت‌های متن نمونه را با رنگ مشخص برجسته می‌کند.

--------------------

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

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| text | java.lang.String | متن برای برجسته‌سازی. |
| highlightColor | java.awt.Color | رنگی که متن با آن برجسته می‌شود. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | گزینه‌های جستجوی متن [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | شیء بازخوانی برای دریافت نتایج جستجو [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |
### highlightRegex(String regex, Color highlightColor, ITextHighlightingOptions options) {#highlightRegex-java.lang.String-java.awt.Color-com.aspose.slides.ITextHighlightingOptions-}
```
public final void highlightRegex(String regex, Color highlightColor, ITextHighlightingOptions options)
```

تمام مطابقت‌های عبارت منظم را با رنگ مشخص برجسته می‌کند.

--------------------

> ```
> The following code sample shows how to highlight text in a TextFrame using a regular expression.
>  
>  Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      TextHighlightingOptions options = new TextHighlightingOptions();
>      // highlighting all words with 10 symbols or longer
>      ((AutoShape) pres.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightRegex("\\b[^\\s){5,}\\b", Color.BLUE, options);
>      pres.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| regex | java.lang.String | متن عبارت منظم برای برجسته‌سازی. |
| highlightColor | java.awt.Color | رنگی که متن با آن برجسته می‌شود. |
| options | [ITextHighlightingOptions](../../com.aspose.slides/itexthighlightingoptions) | گزینه‌های برجسته‌سازی. |
### highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-}
```
public final void highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)
```

تمام مطابقت‌های عبارت منظم را با رنگ مشخص برجسته می‌کند.

--------------------

> ```
> The following code sample shows how to highlight text in a TextFrame using a regular expression.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{5,}\\b");
>      // highlighting all words with 5 symbols or longer
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightRegex(regex, Color.BLUE, null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| regex | java.util.regex.Pattern | عبارت منظم java.util.regex.Pattern برای دریافت رشته‌های برجسته‌شده. |
| highlightColor | java.awt.Color | رنگی که متن با آن برجسته می‌شود. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | شیء بازخوانی برای دریافت نتایج جستجو [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |
### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
```

تمام موارد متن مشخص را با متن دیگر مشخص جایگزین می‌کند.

--------------------

> ```
> The following sample code shows how to replace one speified string with another speified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // جایگزینی تمام موارد جداگانهٔ 'the' با '***'
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| oldText | java.lang.String | رشته‌ای که باید جایگزین شود. |
| newText | java.lang.String | رشته‌ای که تمام موارد oldText را جایگزین می‌کند. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | گزینه‌های جستجوی متن [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | شیء بازخوانی برای ذخیرهٔ نتیجه عملیات جایگزینی [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |
### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public final void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```

تمام مطابقت‌های عبارت منظم را با رشتهٔ مشخص جایگزین می‌کند.

--------------------

> ```
> The following sample code shows how to replace text using regular expression with specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{5,}\\b");
>      // جایگزینی تمام کلمات با 5 نماد یا بیشتر با '***'
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().replaceRegex(regex, "***", null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| regex | java.util.regex.Pattern | عبارت منظم java.util.regex.Pattern برای دریافت رشته‌های جایگزین‌شده. |
| newText | java.lang.String | رشته‌ای که تمام موارد رشته‌های جایگزین‌شده را جایگزین می‌کند. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | شیء بازخوانی برای ذخیرهٔ نتیجه عملیات جایگزینی [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

اسلاید والد یک TextFrame را برمی‌گرداند. فقط‌خواندنی [IBaseSlide](../../com.aspose.slides/ibaseslide).

**باز می‌گردد:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

ارائهٔ والد یک TextFrame را برمی‌گرداند. فقط‌خواندنی [IPresentation](../../com.aspose.slides/ipresentation).

**باز می‌گردد:**
[IPresentation](../../com.aspose.slides/ipresentation)
### getParentShape() {#getParentShape--}
```
public final IShape getParentShape()
```

شکل والد یا null را برمی‌گرداند اگر شیء والد رابط IShape را پیاده‌سازی نکند فقط‌خواندنی [IShape](../../com.aspose.slides/ishape).

--------------------

> ```
> The following code sample shows 
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      AutoShape autoShape = (AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      Table table = (Table)presentation.getSlides().get_Item(0).getShapes().get_Item(1);
> 
>      // این ادعاها همیشه صحیح هستند
>      Assert.assertTrue(autoShape.getTextFrame().getParentShape() == autoShape);
>      Assert.assertTrue((table.get_Item(0,0).getTextFrame()).getParentShape() == null);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**باز می‌گردد:**
[IShape](../../com.aspose.slides/ishape)
### getParentCell() {#getParentCell--}
```
public final ICell getParentCell()
```

سلول والد یا null را برمی‌گرداند اگر شیء والد رابط ICell را پیاده‌سازی نکند فقط‌خواندنی [ICell](../../com.aspose.slides/icell).

--------------------

> ```
> The following code sample shows 
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      AutoShape autoShape = (AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      Table table = (Table)presentation.getSlides().get_Item(0).getShapes().get_Item(1);
> 
>      // این ادعاها همیشه صحیح هستند
>      Assert.assertTrue(table.get_Item(0,0).getTextFrame().getParentCell() == table.get_Item(0,0));
>      Assert.assertTrue(autoShape.getTextFrame().getParentCell() == null);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**باز می‌گردد:**
[ICell](../../com.aspose.slides/icell)