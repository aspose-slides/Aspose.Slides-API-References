---
title: TextFrame
second_title: Aspose.Slides برای Java مرجع API
description: نمایانگر یک TextFrame است.
type: docs
url: /fa/com.aspose.slides/textframe/
---
**ارث‌بری:**
java.lang.Object

**تمام رابط‌های پیاده‌سازی شده:**
[com.aspose.slides.ITextFrame](../../com.aspose.slides/itextframe), com.aspose.slides.IDOMObject
```
public final class TextFrame implements ITextFrame, IDOMObject
```

نمایانگر یک TextFrame است.
## متدها

| متد | توضیح |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getParagraphs()](#getParagraphs--) | لیست تمام پاراگراف‌ها در یک فریم را بازمی‌گرداند. |
| [getText()](#getText--) | متن ساده یک TextFrame را دریافت یا تنظیم می‌کند. |
| [setText(String value)](#setText-java.lang.String-) | متن ساده یک TextFrame را دریافت یا تنظیم می‌کند. |
| [getTextFrameFormat()](#getTextFrameFormat--) | شیء فرمت‌بندی برای این شیء TextFrame را بازمی‌گرداند. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | دسترسی آسان به پیوندهای موجود را فراهم می‌کند. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | بخش‌های متنی با فرمت یکسان را در تمام پاراگراف‌ها ترکیب می‌کند. |
| [highlightText(String text, Color highlightColor)](#highlightText-java.lang.String-java.awt.Color-) | تمام موارد متن نمونه را با رنگ مشخص برجسته می‌کند. |
| [highlightText(String text, Color highlightColor, ITextHighlightingOptions options)](#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextHighlightingOptions-) | تمام موارد متن نمونه را با رنگ مشخص برجسته می‌کند. |
| [splitTextByColumns()](#splitTextByColumns--) | محتوای متنی [ITextFrame](../../com.aspose.slides/itextframe) را به آرایه‌ای از رشته‌ها تقسیم می‌کند که هر عنصر متناظر با یک ستون متنی جداگانه در داخل فریم است. |
| [highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | تمام موارد متن نمونه را با رنگ مشخص برجسته می‌کند. |
| [highlightRegex(String regex, Color highlightColor, ITextHighlightingOptions options)](#highlightRegex-java.lang.String-java.awt.Color-com.aspose.slides.ITextHighlightingOptions-) | تمام موارد عبارات منظم را با رنگ مشخص برجسته می‌کند. |
| [highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-) | تمام موارد عبارات منظم را با رنگ مشخص برجسته می‌کند. |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | تمام موارد متن مشخص شده را با متن دیگری جایگزین می‌کند. |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | تمام موارد عبارات منظم را با رشته مشخص شده جایگزین می‌کند. |
| [getSlide()](#getSlide--) | اسلاید والد یک TextFrame را بازمی‌گرداند. |
| [getPresentation()](#getPresentation--) | ارائه والد یک TextFrame را بازمی‌گرداند. |
| [getParentShape()](#getParentShape--) | شکل والد را بازمی‌گرداند یا در صورت عدم پیاده‌سازی رابط IShape، null برمی‌گرداند. فقط خواندنی [IShape](../../com.aspose.slides/ishape). |
| [getTextRect()](#getTextRect--) | مستطیل متن تعریف‌شده توسط هندسه شکل والد را دریافت می‌کند. |
| [getParentCell()](#getParentCell--) | سلول والد را بازمی‌گرداند یا در صورت عدم پیاده‌سازی رابط ICell، null برمی‌گرداند. |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

شیء Parent_Immediate را بازمی‌گرداند. فقط خواندنی IDOMObject.

**بازمی‌گرداند:**
com.aspose.slides.IDOMObject
### getParagraphs() {#getParagraphs--}
```
public final IParagraphCollection getParagraphs()
```

لیست تمام پاراگراف‌ها در یک فریم را بازمی‌گرداند. فقط خواندنی [IParagraphCollection](../../com.aspose.slides/iparagraphcollection).

**بازمی‌گرداند:**
[IParagraphCollection](../../com.aspose.slides/iparagraphcollection)
### getText() {#getText--}
```
public final String getText()
```

متن ساده یک TextFrame را دریافت یا تنظیم می‌کند. خواندنی/نوشتنی String.

مقدار: متن.

**بازمی‌گرداند:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```

متن ساده یک TextFrame را دریافت یا تنظیم می‌کند. خواندنی/نوشتنی String.

مقدار: متن.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |
### getTextFrameFormat() {#getTextFrameFormat--}
```
public final ITextFrameFormat getTextFrameFormat()
```

شیء فرمت‌بندی برای این شیء TextFrame را بازمی‌گرداند. فقط خواندنی [ITextFrameFormat](../../com.aspose.slides/itextframeformat).

**بازمی‌گرداند:**
[ITextFrameFormat](../../com.aspose.slides/itextframeformat)
### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public final IHyperlinkQueries getHyperlinkQueries()
```

دسترسی آسان به پیوندهای موجود را فراهم می‌کند. فقط خواندنی [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**بازمی‌گرداند:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public final void joinPortionsWithSameFormatting()
```

بخش‌های متنی با فرمت یکسان را در تمام پاراگراف‌ها ترکیب می‌کند.
### highlightText(String text, Color highlightColor) {#highlightText-java.lang.String-java.awt.Color-}
```
public final void highlightText(String text, Color highlightColor)
```

تمام موارد متن نمونه را با رنگ مشخص برجسته می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| text | java.lang.String | نمونه متن برای برجسته‌سازی. |
| highlightColor | java.awt.Color | رنگی که متن را برجسته می‌کند. |
### highlightText(String text, Color highlightColor, ITextHighlightingOptions options) {#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextHighlightingOptions-}
```
public final void highlightText(String text, Color highlightColor, ITextHighlightingOptions options)
```

تمام موارد متن نمونه را با رنگ مشخص برجسته می‌کند.

--------------------

> ```
> The following sample code shows how to Highlight Text in a TextFrame.
>  
>  try {
>      TextHighlightingOptions textHighlightingOptions = new TextHighlightingOptions();
>      textHighlightingOptions.setWholeWordsOnly(true);
>      // برجسته‌سازی تمام کلمات 'important'
>      ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("title", Color.BLUE);
>      // برجسته‌سازی تمام موارد جداگانه 'the'
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
| highlightColor | java.awt.Color | رنگی که متن را برجسته می‌کند. |
| options | [ITextHighlightingOptions](../../com.aspose.slides/itexthighlightingoptions) | گزینه‌های برجسته‌سازی. |
### splitTextByColumns() {#splitTextByColumns--}
```
public final String[] splitTextByColumns()
```

محتوای متنی [ITextFrame](../../com.aspose.slides/itextframe) را به آرایه‌ای از رشته‌ها تقسیم می‌کند که هر عنصر متناظر با یک ستون متنی جداگانه در داخل فریم است.

--------------------

> ```
> The following example demonstrates how to use #splitTextByColumns.splitTextByColumns:
>  
>  Presentation pres = new Presentation("example.pptx");
>  try {
>      // اولین شکل را در اسلاید دریافت کرده و به ITextFrame تبدیل می‌کند
>      ITextFrame textFrame = (ITextFrame) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // محتوای فریم متنی را به ستون‌ها تقسیم می‌کند
>      String[] columnsText = textFrame.splitTextByColumns();
>      // متن هر ستون را در کنسول چاپ می‌کند
>      for (String column : columnsText)
>          System.out.println(column);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**بازمی‌گرداند:**
java.lang.String[] - آرایه‌ای از رشته‌ها که هر رشته متن محتوای یک ستون خاص در [ITextFrame](../../com.aspose.slides/itextframe) را نشان می‌دهد.

اگر فریم متن چندین ستون نداشته باشد، آرایه بازگشتی یک عنصر واحد داشته خواهد بود که متن کامل را شامل می‌شود. ستون‌های خالی به صورت رشته‌های خالی در آرایه نشان داده می‌شوند.
### highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```

تمام موارد متن نمونه را با رنگ مشخص برجسته می‌کند.

--------------------

> ```
> The following code sample shows how to highlight text in a TextFrame.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // برجسته‌سازی تمام کلمات 'important'
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("important", Color.BLUE);
>      // برجسته‌سازی تمام موارد جداگانه 'the'
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
| highlightColor | java.awt.Color | رنگی که متن را برجسته می‌کند. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | گزینه‌های جستجوی متن [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | شیء بازگردانی برای دریافت نتایج جستجو [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |
### highlightRegex(String regex, Color highlightColor, ITextHighlightingOptions options) {#highlightRegex-java.lang.String-java.awt.Color-com.aspose.slides.ITextHighlightingOptions-}
```
public final void highlightRegex(String regex, Color highlightColor, ITextHighlightingOptions options)
```

تمام موارد عبارات منظم را با رنگ مشخص برجسته می‌کند.

--------------------

> ```
> The following code sample shows how to highlight text in a TextFrame using a regular expression.
>  
>  Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      TextHighlightingOptions options = new TextHighlightingOptions();
>      // برجسته‌سازی تمام کلمات با 10 نماد یا بیشتر
>      ((AutoShape) pres.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightRegex("\\b[^\\s){5,}\\b", Color.BLUE, options);
>      pres.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| regex | java.lang.String | متن عبارت منظم برای دریافت متن برجسته. |
| highlightColor | java.awt.Color | رنگی که متن را برجسته می‌کند. |
| options | [ITextHighlightingOptions](../../com.aspose.slides/itexthighlightingoptions) | گزینه‌های برجسته‌سازی. |
### highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-}
```
public final void highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)
```

تمام موارد عبارات منظم را با رنگ مشخص برجسته می‌کند.

--------------------

> ```
> The following code sample shows how to highlight text in a TextFrame using a regular expression.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{5,}\\b");
>      // برجسته‌سازی تمام کلمات با 5 نماد یا بیشتر
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightRegex(regex, Color.BLUE, null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| regex | java.util.regex.Pattern | عبارت منظم java.util.regex.Pattern برای دریافت رشته‌های برجسته. |
| highlightColor | java.awt.Color | رنگی که متن را برجسته می‌کند. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | شیء بازگردانی برای دریافت نتایج جستجو [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |
### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
```

تمام موارد متن مشخص شده را با متن دیگری جایگزین می‌کند.

--------------------

> ```
> The following sample code shows how to replace one speified string with another speified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // تمام موارد جداگانه 'the' را با '***' جایگزین می‌کند
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
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | شیء بازگردانی برای ذخیره نتیجه عملیات جایگزینی [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |
### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public final void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```

تمام موارد عبارات منظم را با رشته مشخص شده جایگزین می‌کند.

--------------------

> ```
> The following sample code shows how to replace text using regular expression with specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{5,}\\b");
>      // تمام کلمات با 5 نماد یا بیشتر را با '***' جایگزین می‌کند
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().replaceRegex(regex, "***", null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| regex | java.util.regex.Pattern | عبارت منظم java.util.regex.Pattern برای دریافت رشته‌های جایگزینی. |
| newText | java.lang.String | رشته‌ای که تمام موارد رشته‌های جایگزین را جایگزین می‌کند. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | شیء بازگردانی برای ذخیره نتیجه عملیات جایگزینی [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

اسلاید والد یک TextFrame را بازمی‌گرداند. فقط خواندنی [IBaseSlide](../../com.aspose.slides/ibaseslide).

**بازمی‌گرداند:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

ارائه والد یک TextFrame را بازمی‌گرداند. فقط خواندنی [IPresentation](../../com.aspose.slides/ipresentation).

**بازمی‌گرداند:**
[IPresentation](../../com.aspose.slides/ipresentation)
### getParentShape() {#getParentShape--}
```
public final IShape getParentShape()
```

شکل والد را بازمی‌گرداند یا در صورت عدم پیاده‌سازی رابط IShape، null برمی‌گرداند. فقط خواندنی [IShape](../../com.aspose.slides/ishape).

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

**بازمی‌گرداند:**
[IShape](../../com.aspose.slides/ishape)
### getTextRect() {#getTextRect--}
```
public final Rectangle2D.Float getTextRect()
```

مستطیل متن تعریف‌شده توسط هندسه شکل والد را دریافت می‌کند.

**بازمی‌گرداند:**
java.awt.geom.Rectangle2D.Float - یک java.awt.geom.Rectangle2D.Float که ناحیه متن را تعریف می‌کند.
### getParentCell() {#getParentCell--}
```
public final ICell getParentCell()
```

سلول والد را بازمی‌گرداند یا در صورت عدم پیاده‌سازی رابط ICell، null برمی‌گرداند. فقط خواندنی [ICell](../../com.aspose.slides/icell).

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

**بازمی‌گرداند:**
[ICell](../../com.aspose.slides/icell)