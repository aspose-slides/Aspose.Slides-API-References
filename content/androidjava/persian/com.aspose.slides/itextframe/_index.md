---
title: ITextFrame
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایانگر یک TextFrame است.
type: docs
url: /fa/com.aspose.slides/itextframe/
---
**تمام اینترفیس‌های پیاده‌سازی‌شده:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface ITextFrame extends ISlideComponent
```

نمایانگر یک TextFrame است.
## متدها

| متد | توضیح |
| --- | --- |
| [getParagraphs()](#getParagraphs--) | فهرست تمام پاراگراف‌ها را در یک فریم برمی‌گرداند. |
| [getText()](#getText--) | متن ساده برای یک TextFrame را دریافت یا تنظیم می‌کند. |
| [setText(String value)](#setText-java.lang.String-) | متن ساده برای یک TextFrame را دریافت یا تنظیم می‌کند. |
| [getTextFrameFormat()](#getTextFrameFormat--) | شیء قالب‌بندی برای این شیء TextFrame را برمی‌گرداند. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | دسترسی آسان به پیوندهای موجود را فراهم می‌کند. |
| [getParentShape()](#getParentShape--) | شکل والد یا null را برمی‌گرداند اگر شیء والد رابط IShape را پیاده‌سازی نکند فقط-خواندنی [IShape](../../com.aspose.slides/ishape). |
| [getParentCell()](#getParentCell--) | سلول والد یا null را برمی‌گرداند اگر شیء والد رابط ICell را پیاده‌سازی نکند. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | دنباله‌ها را با قالب‌بندی یکسان در تمام پاراگراف‌ها ترکیب می‌کند. |
| [highlightText(String text, Integer highlightColor)](#highlightText-java.lang.String-java.lang.Integer-) | تمام تطابق‌های متن نمونه را با رنگ مشخص برجسته می‌کند. |
| [splitTextByColumns()](#splitTextByColumns--) | متن محتویات [ITextFrame](../../com.aspose.slides/itextframe) را به آرایه‌ای از رشته‌ها تقسیم می‌کند که هر عنصر متناظر با یک ستون متنی جداگانه در فریم است. |
| [highlightText(String text, Integer highlightColor, ITextHighlightingOptions options)](#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextHighlightingOptions-) | تمام تطابق‌های متن نمونه را با رنگ مشخص برجسته می‌کند. |
| [highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | تمام تطابق‌های متن نمونه را با رنگ مشخص برجسته می‌کند. |
| [highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-) | تمام تطابق‌های عبارت منظم را با رنگ مشخص برجسته می‌کند. |
| [highlightRegex(String regex, Integer highlightColor, ITextHighlightingOptions options)](#highlightRegex-java.lang.String-java.lang.Integer-com.aspose.slides.ITextHighlightingOptions-) | تمام تطابق‌های عبارت منظم را با رنگ مشخص برجسته می‌کند. |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | تمام وقوع‌های متن مشخص‌شده را با متن دیگری که مشخص شده است جایگزین می‌کند. |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | تمام تطابق‌های عبارت منظم را با رشته مشخص شده جایگزین می‌کند. |
### getParagraphs() {#getParagraphs--}
```
public abstract IParagraphCollection getParagraphs()
```

فهرست تمام پاراگراف‌ها را در یک فریم برمی‌گرداند فقط-خواندنی [IParagraphCollection](../../com.aspose.slides/iparagraphcollection).

**بازگشت:**
[IParagraphCollection](../../com.aspose.slides/iparagraphcollection)
### getText() {#getText--}
```
public abstract String getText()
```

متن ساده برای یک TextFrame را دریافت یا تنظیم می‌کند. خواندنی/نوشتنی String.

مقدار: متن.

**بازگشت:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```

متن ساده برای یک TextFrame را دریافت یا تنظیم می‌کند. خواندنی/نوشتنی String.

مقدار: متن.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |
### getTextFrameFormat() {#getTextFrameFormat--}
```
public abstract ITextFrameFormat getTextFrameFormat()
```

شیء قالب‌بندی برای این شیء TextFrame را برمی‌گرداند فقط-خواندنی [ITextFrameFormat](../../com.aspose.slides/itextframeformat).

**بازگشت:**
[ITextFrameFormat](../../com.aspose.slides/itextframeformat)
### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public abstract IHyperlinkQueries getHyperlinkQueries()
```

دسترس آسان به پیوندهای موجود را فراهم می‌کند فقط-خواندنی [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**بازگشت:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)
### getParentShape() {#getParentShape--}
```
public abstract IShape getParentShape()
```

شکل والد یا null را برمی‌گرداند اگر شیء والد رابط IShape را پیاده‌سازی نکند فقط-خواندنی [IShape](../../com.aspose.slides/ishape).

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

**بازگشت:**
[IShape](../../com.aspose.slides/ishape)
### getParentCell() {#getParentCell--}
```
public abstract ICell getParentCell()
```

سلول والد یا null را برمی‌گرداند اگر شیء والد رابط ICell را پیاده‌سازی نکند فقط-خواندنی [ICell](../../com.aspose.slides/icell).

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

**بازگشت:**
[ICell](../../com.aspose.slides/icell)
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```

دنباله‌ها را با قالب‌بندی یکسان در تمام پاراگراف‌ها ترکیب می‌کند.
### highlightText(String text, Integer highlightColor) {#highlightText-java.lang.String-java.lang.Integer-}
```
public abstract void highlightText(String text, Integer highlightColor)
```

تمام تطابق‌های متن نمونه را با رنگ مشخص برجسته می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| text | java.lang.String | متنی که باید برجسته شود. |
| highlightColor | java.lang.Integer | رنگی که متن باید به آن برجسته شود. |
### splitTextByColumns() {#splitTextByColumns--}
```
public abstract String[] splitTextByColumns()
```

محتوای متنی [ITextFrame](../../com.aspose.slides/itextframe) را به آرایه‌ای از رشته‌ها تقسیم می‌کند که هر عنصر متناظر با یک ستون متنی جداگانه در فریم است.

--------------------

> ```
> The following example demonstrates how to use #splitTextByColumns.splitTextByColumns:
>  
>  Presentation pres = new Presentation("example.pptx");
>  try {
>      // دریافت اولین شکل در اسلاید و تبدیل آن به ITextFrame
>      ITextFrame textFrame = (ITextFrame) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // متن فریم را به ستون‌ها تقسیم کنید
>      String[] columnsText = textFrame.splitTextByColumns();
>      // متن هر ستون را در کنسول چاپ کنید
>      for (String column : columnsText)
>          System.out.println(column);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**بازگشت:**
java.lang.String[] - آرایه‌ای از رشته‌ها که هر رشته محتوای متنی یک ستون خاص در [ITextFrame](../../com.aspose.slides/itextframe) را نشان می‌دهد.

اگر TextFrame شامل چندین ستون نباشد، آرایه برگردانده‌شده یک عنصر واحد حاوی تمام متن خواهد داشت. ستون‌های خالی به صورت رشته‌های خالی در آرایه نمایش داده می‌شوند.
### highlightText(String text, Integer highlightColor, ITextHighlightingOptions options) {#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextHighlightingOptions-}
```
public abstract void highlightText(String text, Integer highlightColor, ITextHighlightingOptions options)
```

تمام تطابق‌های متن نمونه را با رنگ مشخص برجسته می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| text | java.lang.String | متنی که باید برجسته شود. |
| highlightColor | java.lang.Integer | رنگی که متن باید به آن برجسته شود. |
| options | [ITextHighlightingOptions](../../com.aspose.slides/itexthighlightingoptions) | گزینه‌های برجسته‌سازی. |
### highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```

تمام تطابق‌های متن نمونه را با رنگ مشخص برجسته می‌کند.

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
| text | java.lang.String | متنی که باید برجسته شود. |
| highlightColor | java.lang.Integer | رنگی که متن باید به آن برجسته شود. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | گزینه‌های جستجوی متن [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | شیء callback برای دریافت نتایج جستجو [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |
### highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)
```

تمام تطابق‌های عبارت منظم را با رنگ مشخص برجسته می‌کند.

--------------------

> ```
> The following code sample shows how to highlight text in a TextFrame using a regular expression.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{5,}\\b");
>      // برجسته‌سازی تمام واژه‌های با 5 نماد یا بیشتر
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightRegex(regex, Color.BLUE, null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| regex | java.util.regex.Pattern | عبارت منظم java.util.regex.Pattern برای به‌دست آوردن رشته‌ها جهت برجسته‌سازی. |
| highlightColor | java.lang.Integer | رنگی که متن باید به آن برجسته شود. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | شیء callback برای دریافت نتایج جستجو [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |
### highlightRegex(String regex, Integer highlightColor, ITextHighlightingOptions options) {#highlightRegex-java.lang.String-java.lang.Integer-com.aspose.slides.ITextHighlightingOptions-}
```
public abstract void highlightRegex(String regex, Integer highlightColor, ITextHighlightingOptions options)
```

تمام تطابق‌های عبارت منظم را با رنگ مشخص برجسته می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| regex | java.lang.String | متن عبارت منظم برای به‌دست آوردن متنی که باید برجسته شود. |
| highlightColor | java.lang.Integer | رنگی که متن باید به آن برجسته شود. |
| options | [ITextHighlightingOptions](../../com.aspose.slides/itexthighlightingoptions) | گزینه‌های برجسته‌سازی. |
### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
```

تمام وقوع‌های متن مشخص‌شده را با متن دیگری که مشخص شده است جایگزین می‌کند.

--------------------

> ```
> The following sample code shows how to replace one specified string with another specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // جایگزینی تمام موارد جداگانه 'the' با '***'
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
| newText | java.lang.String | رشته‌ای که تمام وقوع‌های oldText را جایگزین می‌کند. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | گزینه‌های جستجوی متن [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | شیء callback برای دریافت نتایج جستجو [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |
### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```

تمام تطابق‌های عبارت منظم را با رشته مشخص شده جایگزین می‌کند.

--------------------

> ```
> The following code sample shows how to replace text using regular expression with the specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{5,}\\b");
>      // جایگزینی تمام واژگان با 5 نماد یا بیشتر با '***'
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().replaceRegex(regex, "***", null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| regex | java.util.regex.Pattern | عبارت منظم java.util.regex.Pattern برای به‌دست آوردن رشته‌ها جهت جایگزینی. |
| newText | java.lang.String | رشته‌ای که تمام وقوع‌های رشته‌های جایگزین شونده را جایگزین می‌کند. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | شیء callback برای دریافت نتایج جستجو [IFindResultCallback](../../com.aspose.slides/ifindresultcallback).