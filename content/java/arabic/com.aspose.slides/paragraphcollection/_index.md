---
title: ParagraphCollection
second_title: Aspose.Slides لمرجع API لجافا
description: يمثل مجموعة من الفقرات.
type: docs
url: /ar/com.aspose.slides/paragraphcollection/
---
**الوراثة:**  
java.lang.Object, com.aspose.slides.DomObject

**جميع الواجهات المنفذة:**  
[com.aspose.slides.IParagraphCollection](../../com.aspose.slides/iparagraphcollection)  
```
public final class ParagraphCollection extends DomObject<TextFrame> implements IParagraphCollection
```

يمثل مجموعة من الفقرات.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getCount()](#getCount--) | يعرض عدد العناصر الموجودة فعليًا في المجموعة. |
| [isReadOnly()](#isReadOnly--) | يعرض قيمة تشير إلى ما إذا كان [IGenericCollection](../../com.aspose.slides/igenericcollection) للقراءة فقط. |
| [get_Item(int index)](#get-Item-int-) | يعرض العنصر عند الفهرس المحدد. |
| [add(IParagraph value)](#add-com.aspose.slides.IParagraph-) | يضيف Paragraph إلى نهاية المجموعة. |
| [add(IParagraphCollection value)](#add-com.aspose.slides.IParagraphCollection-) | يضيف محتوى ParagraphCollection إلى نهاية المجموعة. |
| [indexOf(IParagraph item)](#indexOf-com.aspose.slides.IParagraph-) | يحدد فهرس عنصر معين في القائمة. |
| [insert(int index, IParagraph value)](#insert-int-com.aspose.slides.IParagraph-) | يدخل Paragraph في المجموعة عند الفهرس المحدد. |
| [insert(int index, IParagraphCollection value)](#insert-int-com.aspose.slides.IParagraphCollection-) | يدخل محتوى ParagraphCollection في المجموعة عند الفهرس المحدد. |
| [clear()](#clear--) | يزيل جميع العناصر من المجموعة. |
| [contains(IParagraph item)](#contains-com.aspose.slides.IParagraph-) | يحدد ما إذا كان [IGenericCollection](../../com.aspose.slides/igenericcollection) يحتوي على قيمة معينة. |
| [copyTo(IParagraph[] array, int arrayIndex)](#copyTo-com.aspose.slides.IParagraph---int-) | ينسخ عناصر [IGenericCollection](../../com.aspose.slides/igenericcollection) إلى مصفوفة، بدءًا من فهرس مصفوفة معين. |
| [removeAt(int index)](#removeAt-int-) | يزيل العنصر عند الفهرس المحدد في المجموعة. |
| [remove(IParagraph item)](#remove-com.aspose.slides.IParagraph-) | يزيل الظهور الأول لكائن معين من [IGenericCollection](../../com.aspose.slides/igenericcollection). |
| [iterator()](#iterator--) | يرجع كائنًا (enumerator) يتجول عبر المجموعة. |
| [iteratorJava()](#iteratorJava--) | يرجع مؤشراً (iterator) جافا لكامل المجموعة. |
| [getSlide()](#getSlide--) | يرجع الشريحة الأصلية لمجموعة الفقرات. |
| [getPresentation()](#getPresentation--) | يرجع العرض التقديمي الأصلي لمجموعة الفقرات. |
| [addFromHtml(String text)](#addFromHtml-java.lang.String-) | يضيف نصًا من سلسلة HTML محددة إلى المجموعة. |
| [addFromHtml(String text, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | يضيف نصًا من سلسلة HTML محددة إلى المجموعة. |
| [exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)](#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-) | يحول الفقرات المحددة إلى HTML ويعيدها ككائن String. |

### getCount() {#getCount--}
```
public final int getCount()
```

يعرض عدد العناصر الموجودة فعليًا في المجموعة. للقراءة فقط int.

**الإرجاع:**  
int

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

يعرض قيمة تشير إلى ما إذا كان [IGenericCollection](../../com.aspose.slides/igenericcollection) للقراءة فقط. للقراءة فقط boolean.

**الإرجاع:**  
boolean - true إذا كان [IGenericCollection](../../com.aspose.slides/igenericcollection) للقراءة فقط؛ وإلا false.

### get_Item(int index) {#get-Item-int-}
```
public final IParagraph get_Item(int index)
```

يعرض العنصر عند الفهرس المحدد.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int |  |

**الإرجاع:**  
[IParagraph](../../com.aspose.slides/iparagraph)

### add(IParagraph value) {#add-com.aspose.slides.IParagraph-}
```
public final void add(IParagraph value)
```

يضيف Paragraph إلى نهاية المجموعة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | Paragraph الذي سيُضاف إلى نهاية المجموعة. |

### add(IParagraphCollection value) {#add-com.aspose.slides.IParagraphCollection-}
```
public final int add(IParagraphCollection value)
```

يضيف محتوى ParagraphCollection إلى نهاية المجموعة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | ParagraphCollection الذي سيُضاف إلى نهاية المجموعة. |

**الإرجاع:**  
int - الفهرس الذي تمت فيه إضافة Paragraph أو -1 إذا لم يكن هناك ما يضاف.

### indexOf(IParagraph item) {#indexOf-com.aspose.slides.IParagraph-}
```
public final int indexOf(IParagraph item)
```

يحدد فهرس عنصر معين في القائمة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | الكائن لتحديد موقعه في القائمة. |

**الإرجاع:**  
int - فهرس العنصر إذا وجد في القائمة؛ وإلا -1.

### insert(int index, IParagraph value) {#insert-int-com.aspose.slides.IParagraph-}
```
public final void insert(int index, IParagraph value)
```

يدخل Paragraph في المجموعة عند الفهرس المحدد.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس القائم على الصفر الذي يجب إدراج Paragraph عنده. |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | Paragraph الذي سيتم إدراجه. |

### insert(int index, IParagraphCollection value) {#insert-int-com.aspose.slides.IParagraphCollection-}
```
public final void insert(int index, IParagraphCollection value)
```

يدخل محتوى ParagraphCollection في المجموعة عند الفهرس المحدد.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس القائم على الصفر الذي يجب إدراج الفقرات عنده. |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | الفقرات التي سيتم إدراجها. |

### clear() {#clear--}
```
public final void clear()
```

يزيل جميع العناصر من المجموعة.

### contains(IParagraph item) {#contains-com.aspose.slides.IParagraph-}
```
public final boolean contains(IParagraph item)
```

يحدد ما إذا كان [IGenericCollection](../../com.aspose.slides/igenericcollection) يحتوي على قيمة معينة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | الكائن لتحديد موقعه في [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**الإرجاع:**  
boolean - true إذا وُجد العنصر في [IGenericCollection](../../com.aspose.slides/igenericcollection)؛ وإلا false.

### copyTo(IParagraph[] array, int arrayIndex) {#copyTo-com.aspose.slides.IParagraph---int-}
```
public final void copyTo(IParagraph[] array, int arrayIndex)
```

ينسخ عناصر [IGenericCollection](../../com.aspose.slides/igenericcollection) إلى مصفوفة، بدءًا من فهرس مصفوفة معين.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| array | [IParagraph\[\]](../../com.aspose.slides/iparagraph) | المصفوفة أحادية البُعد التي هي وجهة العناصر المنقولة من [IGenericCollection](../../com.aspose.slides/igenericcollection). يجب أن تكون المصفوفة ذات فهرسة صفرية. |
| arrayIndex | int | الفهرس القائم على الصفر في المصفوفة حيث يبدأ النسخ. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

يزيل العنصر عند الفهرس المحدد في المجموعة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس القائم على الصفر للعنصر الذي سيُزال. |

### remove(IParagraph item) {#remove-com.aspose.slides.IParagraph-}
```
public final boolean remove(IParagraph item)
```

يزيل الظهور الأول لكائن معين من [IGenericCollection](../../com.aspose.slides/igenericcollection).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | الكائن لإزالته من [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**الإرجاع:**  
boolean - true إذا تمت إزالة العنصر بنجاح من [IGenericCollection](../../com.aspose.slides/igenericcollection)؛ وإلا false. تُعيد هذه الطريقة false أيضًا إذا لم يُعثر على العنصر في الأصل [IGenericCollection](../../com.aspose.slides/igenericcollection).

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IParagraph> iterator()
```

يرجع مفهرسًا (enumerator) يتجول عبر المجموعة.

**الإرجاع:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IParagraph> - IGenericEnumerator يمكن استخدامه للتجول عبر المجموعة.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IParagraph> iteratorJava()
```

يرجع مؤشراً (iterator) جافا للمجموعة بالكامل.

**الإرجاع:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IParagraph> - java.util.Iterator للمجموعة بالكامل.

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

يرجع الشريحة الأصلية لمجموعة الفقرات. للقراءة فقط [BaseSlide](../../com.aspose.slides/baseslide).

**الإرجاع:**  
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

يرجع العرض التقديمي الأصلي لمجموعة الفقرات. للقراءة فقط [IPresentation](../../com.aspose.slides/ipresentation).

**الإرجاع:**  
[IPresentation](../../com.aspose.slides/ipresentation)

### addFromHtml(String text) {#addFromHtml-java.lang.String-}
```
public final void addFromHtml(String text)
```

يضيف نصًا من سلسلة HTML محددة إلى المجموعة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| text | java.lang.String | نص HTML. |

### addFromHtml(String text, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final void addFromHtml(String text, IExternalResourceResolver resolver, String uri)
```

يضيف نصًا من سلسلة HTML محددة إلى المجموعة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| text | java.lang.String | نص HTML. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | كائن رد اتصال Resolver يقوم بحل عناوين URI وجلب الكائنات المشار إليها. |
| uri | java.lang.String | URI لإضافة مستند HTML. يُستخدم لحل الروابط النسبية. |

تحديد resolver قد يسبب ثغرة محتملة. استخدمه بحذر.

### exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options) {#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-}
```
public final String exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)
```

يحوّل الفقرات المحددة إلى HTML ويعيده ككائن String.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| firstParagraphIndex | int | فهرس الفقرة الأولى، int |
| paragraphsCount | int | عدد الفقرات، int |
| options | [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) | خيارات التحويل [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) |

**الإرجاع:**  
java.lang.String - HTML المُنتج.