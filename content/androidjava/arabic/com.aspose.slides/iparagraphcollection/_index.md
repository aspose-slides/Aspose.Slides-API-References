---
title: IParagraphCollection
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يمثل مجموعة من الفقرات.
type: docs
url: /ar/com.aspose.slides/iparagraphcollection/
---
**جميع الواجهات المنفذة:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable, [com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IParagraphCollection extends System.Collections.Generic.IGenericEnumerable<IParagraph>, ISlideComponent
```

يمثل مجموعة من الفقرات.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | يحصل على العنصر في الفهرس المحدد. |
| [getCount()](#getCount--) | يحصل على عدد العناصر الموجودة فعليًا في المجموعة. |
| [add(IParagraph value)](#add-com.aspose.slides.IParagraph-) | يضيف Paragraph إلى نهاية المجموعة. |
| [add(IParagraphCollection value)](#add-com.aspose.slides.IParagraphCollection-) | يضيف محتوى ParagraphCollection إلى نهاية المجموعة. |
| [insert(int index, IParagraph value)](#insert-int-com.aspose.slides.IParagraph-) | يدخل Paragraph في المجموعة عند الفهرس المحدد. |
| [insert(int index, IParagraphCollection value)](#insert-int-com.aspose.slides.IParagraphCollection-) | يدخل محتوى ParagraphCollection في المجموعة عند الفهرس المحدد. |
| [clear()](#clear--) | يزيل جميع العناصر من المجموعة. |
| [removeAt(int index)](#removeAt-int-) | يزيل العنصر عند الفهرس المحدد في المجموعة. |
| [remove(IParagraph item)](#remove-com.aspose.slides.IParagraph-) | يزيل أول حدوث لفقرة معينة. |
| [addFromHtml(String text)](#addFromHtml-java.lang.String-) | يضيف نصًا من سلسلة HTML المحددة إلى المجموعة. |
| [addFromHtml(String text, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | يضيف نصًا من سلسلة HTML المحددة إلى المجموعة. |
| [exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)](#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-) | يحوّل الفقرات المحددة إلى HTML ويعيدها ككائن String. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IParagraph get_Item(int index)
```

يحصل على العنصر في الفهرس المحدد.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int |  |

**القيمة المرجعة:**
[IParagraph](../../com.aspose.slides/iparagraph)
### getCount() {#getCount--}
```
public abstract int getCount()
```

يحصل على عدد العناصر الموجودة فعليًا في المجموعة. int للقراءة فقط.

**القيمة المرجعة:**
int
### add(IParagraph value) {#add-com.aspose.slides.IParagraph-}
```
public abstract void add(IParagraph value)
```

يضيف Paragraph إلى نهاية المجموعة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | ال Paragraph لإضافته إلى نهاية المجموعة. |

### add(IParagraphCollection value) {#add-com.aspose.slides.IParagraphCollection-}
```
public abstract int add(IParagraphCollection value)
```

يضيف محتوى ParagraphCollection إلى نهاية المجموعة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | ال ParagraphCollection لإضافته إلى نهاية المجموعة. |

**القيمة المرجعة:**
int - الفهرس الذي أضيف فيه Paragraph أو -1 إذا لم يكن هناك ما يضيف.
### insert(int index, IParagraph value) {#insert-int-com.aspose.slides.IParagraph-}
```
public abstract void insert(int index, IParagraph value)
```

يدخل Paragraph في المجموعة عند الفهرس المحدد.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري الذي يجب إدراج Paragraph عنده. |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | ال Paragraph للإدراج. |

### insert(int index, IParagraphCollection value) {#insert-int-com.aspose.slides.IParagraphCollection-}
```
public abstract void insert(int index, IParagraphCollection value)
```

يدخل محتوى ParagraphCollection في المجموعة عند الفهرس المحدد.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري الذي يجب إدراج الفقرات عنده. |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | الفقرات للإدراج. |

### clear() {#clear--}
```
public abstract void clear()
```

يزيل جميع العناصر من المجموعة.

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

يزيل العنصر عند الفهرس المحدد في المجموعة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري للعنصر الذي يجب إزالته. |

### remove(IParagraph item) {#remove-com.aspose.slides.IParagraph-}
```
public abstract boolean remove(IParagraph item)
```

يزيل أول حدوث لفقرة معينة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | الفقرة لإزالتها من المجموعة. |

**القيمة المرجعة:**
boolean - true إذا تم إزالة العنصر بنجاح؛ وإلا false.
### addFromHtml(String text) {#addFromHtml-java.lang.String-}
```
public abstract void addFromHtml(String text)
```

يضيف نصًا من سلسلة HTML المحددة إلى المجموعة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| text | java.lang.String | نص HTML. |

### addFromHtml(String text, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract void addFromHtml(String text, IExternalResourceResolver resolver, String uri)
```

يضيف نصًا من سلسلة HTML المحددة إلى المجموعة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| text | java.lang.String | نص HTML. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | كائن استدعاء الرجوع Resolver الذي يحل URI ويجلب الكائنات المشار إليها. |
| uri | java.lang.String | URI لإضافة مستند HTML. يستخدم لحل الروابط النسبية.

--------------------

يمكن أن يُدخل تحديد resolver ثغرةً محتملةً. استخدمه بحذر. |
### exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options) {#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-}
```
public abstract String exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)
```

يحوّل الفقرات المحددة إلى HTML ويعيدها ككائن String.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| firstParagraphIndex | int | الفهرس الأول للفقرة int |
| paragraphsCount | int | عدد الفقرات int |
| options | [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) | خيارات التحويل [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) |

**القيمة المرجعة:**
java.lang.String - HTML المُنشأ.