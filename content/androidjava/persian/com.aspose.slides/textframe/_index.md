---
title: TextFrame
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایانگر TextFrame است.
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

نمایانگر TextFrame است.
## متدها

| متد | توضیح |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getParagraphs()](#getParagraphs--) | فهرست تمام پاراگراف‌های یک فریم را برمی‌گرداند. |
| [getText()](#getText--) | متن ساده یک TextFrame را دریافت یا تنظیم می‌کند. |
| [setText(String value)](#setText-java.lang.String-) | متن ساده یک TextFrame را دریافت یا تنظیم می‌کند. |
| [getTextFrameFormat()](#getTextFrameFormat--) | شیء قالب‌بندی برای این شیء TextFrame را برمی‌گرداند. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | دسترسی آسان به پیوندهای موجود را فراهم می‌کند. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | دست‌نوشته‌ها با قالب‌بندی یکسان را در تمام پاراگراف‌ها ادغام می‌کند. |
| [highlightText(String text, Integer highlightColor)](#highlightText-java.lang.String-java.lang.Integer-) | تمام مطابقت‌های متن نمونه را با رنگ مشخص شده برجسته می‌کند. |
| [highlightText(String text, Integer highlightColor, ITextHighlightingOptions options)](#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextHighlightingOptions-) | تمام مطابقت‌های متن نمونه را با رنگ مشخص شده برجسته می‌کند. |
| [splitTextByColumns()](#splitTextByColumns--) | محتویات متنی [ITextFrame](../../com.aspose.slides/itextframe) را به آرایه‌ای از رشته‌ها تقسیم می‌کند که هر عنصر متناظر با یک ستون متنی جداگانه درون فریم است. |
| [highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | تمام مطابقت‌های متن نمونه را با رنگ مشخص شده برجسته می‌کند. |
| [highlightRegex(String regex, Integer highlightColor, ITextHighlightingOptions options)](#highlightRegex-java.lang.String-java.lang.Integer-com.aspose.slides.ITextHighlightingOptions-) | تمام مطابقت‌های عبارت منظم را با رنگ مشخص شده برجسته می‌کند. |
| [highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-) | تمام مطابقت‌های عبارت منظم را با رنگ مشخص شده برجسته می‌کند. |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | تمام موارد متن مشخص‌شده را با متن دیگر مشخص‌شده جایگزین می‌کند. |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | تمام مطابقت‌های عبارت منظم را با رشته مشخص‌شده جایگزین می‌کند. |
| [getSlide()](#getSlide--) | اسلاید والد یک TextFrame را برمی‌گرداند. |
| [getPresentation()](#getPresentation--) | ارائه والد یک TextFrame را برمی‌گرداند. |
| [getParentShape()](#getParentShape--) | شکل والد را برمی‌گرداند یا null اگر شی والد رابط IShape را پیاده‌سازی نکند. فقط-خواندنی [IShape](../../com.aspose.slides/ishape). |
| [getParentCell()](#getParentCell--) | سلول والد را برمی‌گرداند یا null اگر شی والد رابط ICell را پیاده‌سازی نکند. |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

شیء Parent_Immediate را برمی‌گرداند. فقط-خواندنی IDOMObject.

**باز می‌گرداند:**
com.aspose.slides.IDOMObject
### getParagraphs() {#getParagraphs--}
```
public final IParagraphCollection getParagraphs()
```

فهرست تمام پاراگراف‌های یک فریم را برمی‌گرداند. فقط-خواندنی [IParagraphCollection](../../com.aspose.slides/iparagraphcollection).

**باز می‌گرداند:**
[IParagraphCollection](../../com.aspose.slides/iparagraphcollection)
### getText() {#getText--}
```
public final String getText()
```

متن ساده یک TextFrame را دریافت یا تنظیم می‌کند. خواند/نوشتن String.

مقدار: متن.

**باز می‌گرداند:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```

متن ساده یک TextFrame را دریافت یا تنظیم می‌کند. خواند/نوشتن String.

مقدار: متن.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |
### getTextFrameFormat() {#getTextFrameFormat--}
```
public final ITextFrameFormat getTextFrameFormat()
```

شیء قالب‌بندی برای این شیء TextFrame را برمی‌گرداند. فقط-خواندنی [ITextFrameFormat](../../com.aspose.slides/itextframeformat).

**باز می‌گرداند:**
[ITextFrameFormat](../../com.aspose.slides/itextframeformat)
### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public final IHyperlinkQueries getHyperlinkQueries()
```

دسترس آسان به پیوندهای موجود را فراهم می‌کند. فقط-خواندنی [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**باز می‌گرداند:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public final void joinPortionsWithSameFormatting()
```

دست‌نوشته‌ها با قالب‌بندی یکسان را در تمام پاراگراف‌ها ادغام می‌کند.

### highlightText(String text, Integer highlightColor) {#highlightText-java.lang.String-java.lang.Integer-}
```
public final void highlightText(String text, Integer highlightColor)
```

تمام مطابقت‌های متن نمونه را با رنگ مشخص شده برجسته می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| text | java.lang.String | نمونه متن برای برجسته کردن. |
| highlightColor | java.lang.Integer | رنگ برای برجسته کردن متن. |
### highlightText(String text, Integer highlightColor, ITextHighlightingOptions options) {#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextHighlightingOptions-}
```
public final void highlightText(String text, Integer highlightColor, ITextHighlightingOptions options)
```

تمام مطابقت‌های متن نمونه را با رنگ مشخص شده برجسته می‌کند.

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
| text | java.lang.String | متن برای برجسته کردن. |
| highlightColor | java.lang.Integer | رنگ برای برجسته کردن متن. |
| options | [ITextHighlightingOptions](../../com.aspose.slides/itexthighlightingoptions) | گزینه‌های برجسته‌سازی. |
### splitTextByColumns() {#splitTextByColumns--}
```
public final String[] splitTextByColumns()
```

محتویات متنی [ITextFrame](../../com.aspose.slides/itextframe) را به آرایه‌ای از رشته‌ها تقسیم می‌کند که هر عنصر متناظر با یک ستون متنی جداگانه درون فریم است.

--------------------

> ```
> The following example demonstrates how to use #splitTextByColumns.splitTextByColumns:
>  
>  Presentation pres = new Presentation("example.pptx");
>  try {
>      // اولین شکل را در اسلاید دریافت کرده و به ITextFrame تبدیل می‌کند
>      ITextFrame textFrame = (ITextFrame) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // محتویات TextFrame را به ستون‌ها تقسیم می‌کند
>      String[] columnsText = textFrame.splitTextByColumns();
>      // متن هر ستون را در کنسول چاپ می‌کند
>      for (String column : columnsText)
>          System.out.println(column);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**باز می‌گرداند:**
java.lang.String[] - آرایه‌ای از رشته‌ها که هر رشته محتوا متن یک ستون خاص در [ITextFrame](../../com.aspose.slides/itextframe) را نشان می‌دهد.

اگر TextFrame چندین ستون نداشته باشد، آرایهٔ بازگشتی یک عنصر دارد که متن کامل را شامل می‌شود. ستون‌های خالی به صورت رشته‌های خالی در آرایه نشان داده می‌شوند.
### highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```

تمام مطابقت‌های متن نمونه را با رنگ مشخص شده برجسته می‌کند.

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
| text | java.lang.String | متن برای برجسته کردن. |
| highlightColor | java.lang.Integer | رنگ برای برجسته کردن متن. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | گزینه‌های جستجوی متن [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | آبجکت بازگشت‌خوانی برای دریافت نتایج جستجو [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |
### highlightRegex(String regex, Integer highlightColor, ITextHighlightingOptions options) {#highlightRegex-java.lang.String-java.lang.Integer-com.aspose.slides.ITextHighlightingOptions-}
```
public final void highlightRegex(String regex, Integer highlightColor, ITextHighlightingOptions options)
```

تمام مطابقت‌های عبارت منظم را با رنگ مشخص شده برجسته می‌کند.

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
| regex | java.lang.String | متن عبارت منظم برای برجسته کردن. |
| highlightColor | java.lang.Integer | رنگ برای برجسته کردن متن. |
| options | [ITextHighlightingOptions](../../com.aspose.slides/itexthighlightingoptions) | گزینه‌های برجسته‌سازی. |
### highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-}
```
public final void highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)
```

تمام مطابقت‌های عبارت منظم را با رنگ مشخص شده برجسته می‌کند.

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
| highlightColor | java.lang.Integer | رنگ برای برجسته کردن متن. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | آبجکت بازگشت‌خوانی برای دریافت نتایج جستجو [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |
### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
```

تمام موارد متن مشخص‌شده را با متن دیگر مشخص‌شده جایگزین می‌کند.

--------------------

> ```
> The following sample code shows how to replace one speified string with another speified string.
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
| newText | java.lang.String | رشته‌ای که تمام موارد oldText را جایگزین می‌کند. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | گزینه‌های جستجوی متن [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | آبجکت بازگشت‌خوانی برای ذخیره نتیجه عملیات جایگزینی [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |
### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public final void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```

تمام مطابقت‌های عبارت منظم را با رشته مشخص‌شده جایگزین می‌کند.

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
| regex | java.util.regex.Pattern | عبارت منظم java.util.regex.Pattern برای دریافت رشته‌های قابل جایگزینی. |
| newText | java.lang.String | رشته‌ای که تمام موارد رشته‌های قابل جایگزینی را جایگزین می‌کند. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | آبجکت بازگشت‌خوانی برای ذخیره نتیجه عملیات جایگزینی [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

اسلاید والد یک TextFrame را برمی‌گرداند. فقط-خواندنی [IBaseSlide](../../com.aspose.slides/ibaseslide).

**باز می‌گرداند:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

ارائه والد یک TextFrame را برمی‌گرداند. فقط-خواندنی [IPresentation](../../com.aspose.slides/ipresentation).

**باز می‌گرداند:**
[IPresentation](../../com.aspose.slides/ipresentation)
### getParentShape() {#getParentShape--}
```
public final IShape getParentShape()
```

شکل والد را برمی‌گرداند یا null اگر شی والد رابط IShape را پیاده‌سازی نکند. فقط-خواندنی [IShape](../../com.aspose.slides/ishape).

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

**باز می‌گرداند:**
[IShape](../../com.aspose.slides/ishape)
### getParentCell() {#getParentCell--}
```
public final ICell getParentCell()
```

سلول والد را برمی‌گرداند یا null اگر شی والد رابط ICell را پیاده‌سازی نکند. فقط-خواندنی [ICell](../../com.aspose.slides/icell).

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

**باز می‌گرداند:**
[ICell](../../com.aspose.slides/icell)