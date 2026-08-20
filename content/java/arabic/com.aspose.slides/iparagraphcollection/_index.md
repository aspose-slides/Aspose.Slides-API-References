---
title: IParagraphCollection
second_title: مرجع API لمكتبة Aspose.Slides للـ Java
description: يمثل مجموعة من الفقرات.
type: docs
url: /ar/com.aspose.slides/iparagraphcollection/
---
**All Implemented Interfaces:**
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
| [add(IParagraph value)](#add-com.aspose.slides.IParagraph-) | يضيف فقرة إلى نهاية المجموعة. |
| [add(IParagraphCollection value)](#add-com.aspose.slides.IParagraphCollection-) | يضيف محتوى من ParagraphCollection إلى نهاية المجموعة. |
| [insert(int index, IParagraph value)](#insert-int-com.aspose.slides.IParagraph-) | يدخل فقرة في المجموعة في الفهرس المحدد. |
| [insert(int index, IParagraphCollection value)](#insert-int-com.aspose.slides.IParagraphCollection-) | يدخل محتوى من ParagraphCollection في المجموعة في الفهرس المحدد. |
| [clear()](#clear--) | يزيل جميع العناصر من المجموعة. |
| [removeAt(int index)](#removeAt-int-) | يزيل العنصر في الفهرس المحدد من المجموعة. |
| [remove(IParagraph item)](#remove-com.aspose.slides.IParagraph-) | يزيل أول ظهور لفقرة محددة. |
| [addFromHtml(String text)](#addFromHtml-java.lang.String-) | يضيف نصًا من سلسلة HTML المحددة إلى المجموعة. |
| [addFromHtml(String text, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | يضيف نصًا من سلسلة HTML المحددة إلى المجموعة. |
| [exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)](#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-) | يحول الفقرات المحددة إلى HTML ويعيدها ككائن String. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IParagraph get_Item(int index)
```

يحصل على العنصر في الفهرس المحدد.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int |  |

**القيمة المرجعة:**
[IParagraph](../../com.aspose.slides/iparagraph)
### getCount() {#getCount--}
```
public abstract int getCount()
```

يحصل على عدد العناصر الموجودة فعليًا في المجموعة. عدد صحيح للقراءة فقط.

**القيمة المرجعة:**
int
### add(IParagraph value) {#add-com.aspose.slides.IParagraph-}
```
public abstract void add(IParagraph value)
```

يضيف فقرة إلى نهاية المجموعة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | الفقرة التي سيتم إضافتها إلى نهاية المجموعة. |

### add(IParagraphCollection value) {#add-com.aspose.slides.IParagraphCollection-}
```
public abstract int add(IParagraphCollection value)
```

يضيف محتوى من ParagraphCollection إلى نهاية المجموعة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | مجموعة الفقرات التي سيتم إضافتها إلى نهاية المجموعة. |

**القيمة المرجعة:**
int - الفهرس الذي تم إضافة الفقرة إليه أو -1 إذا لم يكن هناك شيء للإضافة.
### insert(int index, IParagraph value) {#insert-int-com.aspose.slides.IParagraph-}
```
public abstract void insert(int index, IParagraph value)
```

يدخل فقرة في المجموعة في الفهرس المحدد.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري الذي يجب إدخال الفقرة عنده. |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | الفقرة التي سيتم إدخالها. |

### insert(int index, IParagraphCollection value) {#insert-int-com.aspose.slides.IParagraphCollection-}
```
public abstract void insert(int index, IParagraphCollection value)
```

يدخل محتوى من ParagraphCollection في المجموعة في الفهرس المحدد.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري الذي يجب إدخال الفقرات عنده. |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | الفقرات التي سيتم إدخالها. |

### clear() {#clear--}
```
public abstract void clear()
```

يزيل جميع العناصر من المجموعة.

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

يزيل العنصر في الفهرس المحدد من المجموعة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري للعنصر الذي سيتم إزالته. |

### remove(IParagraph item) {#remove-com.aspose.slides.IParagraph-}
```
public abstract boolean remove(IParagraph item)
```

يزيل أول ظهور لفقرة محددة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | الفقرة التي سيتم إزالتها من المجموعة. |

**القيمة المرجعة:**
boolean - true إذا تم إزالة العنصر بنجاح؛ وإلا false.
### addFromHtml(String text) {#addFromHtml-java.lang.String-}
```
public abstract void addFromHtml(String text)
```

يضيف نصًا من سلسلة HTML المحددة إلى المجموعة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| text | java.lang.String | نص HTML. |

### addFromHtml(String text, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract void addFromHtml(String text, IExternalResourceResolver resolver, String uri)
```

يضيف نصًا من سلسلة HTML المحددة إلى المجموعة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| text | java.lang.String | نص HTML. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | كائن رد نداء محلل يقوم بحل URI وجلب الكائنات المشار إليها. |
| uri | java.lang.String | URI لإضافة مستند HTML. يُستَخدم لحل الروابط النسبية.

--------------------

يمكن أن يؤدي تحديد محلل إلى إدخال ثغرة أمنية محتملة. استخدمه بحذر. |
### exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options) {#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-}
```
public abstract String exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)
```

يحول الفقرات المحددة إلى HTML ويعيدها ككائن String.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| firstParagraphIndex | int | فهرس الفقرة الأولى عدد صحيح |
| paragraphsCount | int | عدد الفقرات عدد صحيح |
| options | [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) | خيارات التحويل [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) |

**القيمة المرجعة:**
java.lang.String - HTML مولد.