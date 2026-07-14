---
title: ParagraphCollection
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
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

| Method | Description |
| --- | --- |
| [getCount()](#getCount--) | يحصل على عدد العناصر الفعلية الموجودة في المجموعة. |
| [isReadOnly()](#isReadOnly--) | يحصل على قيمة تشير إلى ما إذا كان [IGenericCollection](../../com.aspose.slides/igenericcollection) للقراءة فقط. |
| [get_Item(int index)](#get-Item-int-) | يحصل على العنصر عند الفهرس المحدد. |
| [add(IParagraph value)](#add-com.aspose.slides.IParagraph-) | يضيف Paragraph إلى نهاية المجموعة. |
| [add(IParagraphCollection value)](#add-com.aspose.slides.IParagraphCollection-) | يضيف محتوى ParagraphCollection إلى نهاية المجموعة. |
| [indexOf(IParagraph item)](#indexOf-com.aspose.slides.IParagraph-) | يحدد الفهرس لعنصر محدد في List. |
| [insert(int index, IParagraph value)](#insert-int-com.aspose.slides.IParagraph-) | يدخل Paragraph في المجموعة عند الفهرس المحدد. |
| [insert(int index, IParagraphCollection value)](#insert-int-com.aspose.slides.IParagraphCollection-) | يدخل محتوى ParagraphCollection في المجموعة عند الفهرس المحدد. |
| [clear()](#clear--) | يزيل جميع العناصر من المجموعة. |
| [contains(IParagraph item)](#contains-com.aspose.slides.IParagraph-) | يحدد ما إذا كان [IGenericCollection](../../com.aspose.slides/igenericcollection) يحتوي على قيمة محددة. |
| [copyTo(IParagraph[] array, int arrayIndex)](#copyTo-com.aspose.slides.IParagraph---int-) | ينسخ عناصر [IGenericCollection](../../com.aspose.slides/igenericcollection) إلى مصفوفة، بدءًا من فهرس مصفوفة معين. |
| [removeAt(int index)](#removeAt-int-) | يزيل العنصر عند الفهرس المحدد في المجموعة. |
| [remove(IParagraph item)](#remove-com.aspose.slides.IParagraph-) | يزيل أول ظهور لكائن محدد من [IGenericCollection](../../com.aspose.slides/igenericcollection). |
| [iterator()](#iterator--) | يعيد Enumerator يتجول عبر المجموعة. |
| [iteratorJava()](#iteratorJava--) | يعيد java iterator للمجموعة بأكملها. |
| [getSlide()](#getSlide--) | يعيد الشريحة الأم لمجموعة الفقرات. |
| [getPresentation()](#getPresentation--) | يعيد العرض التقديمي الأم لمجموعة الفقرات. |
| [addFromHtml(String text)](#addFromHtml-java.lang.String-) | يضيف نصًا من سلسلة HTML محددة إلى المجموعة. |
| [addFromHtml(String text, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | يضيف نصًا من سلسلة HTML محددة إلى المجموعة. |
| [exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)](#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-) | يحوّل الفقرات المحددة إلى HTML ويعيدها ككائن String. |

### getCount() {#getCount--}
```
public final int getCount()
```

يحصل على عدد العناصر الفعلية الموجودة في المجموعة. int للقراءة فقط.

**الإرجاع:**  
int

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

يحصل على قيمة تشير إلى ما إذا كان [IGenericCollection](../../com.aspose.slides/igenericcollection) للقراءة فقط. boolean للقراءة فقط.

**الإرجاع:**  
boolean - true إذا كان [IGenericCollection](../../com.aspose.slides/igenericcollection) للقراءة فقط؛ وإلا false.

### get_Item(int index) {#get-Item-int-}
```
public final IParagraph get_Item(int index)
```

يحصل على العنصر عند الفهرس المحدد.

**الوسائط:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**الإرجاع:**  
[IParagraph](../../com.aspose.slides/iparagraph)

### add(IParagraph value) {#add-com.aspose.slides.IParagraph-}
```
public final void add(IParagraph value)
```

يضيف Paragraph إلى نهاية المجموعة.

**الوسائط:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | Paragraph الذي سيُضاف إلى نهاية المجموعة. |

### add(IParagraphCollection value) {#add-com.aspose.slides.IParagraphCollection-}
```
public final int add(IParagraphCollection value)
```

يضيف محتوى ParagraphCollection إلى نهاية المجموعة.

**الوسائط:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | ParagraphCollection الذي سيُضاف إلى نهاية المجموعة. |

**الإرجاع:**  
int - الفهرس الذي أُضيف إليه Paragraph أو -1 إذا لم يكن هناك ما يُضاف.

### indexOf(IParagraph item) {#indexOf-com.aspose.slides.IParagraph-}
```
public final int indexOf(IParagraph item)
```

يحدد الفهرس لعنصر محدد في List.

**الوسائط:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | الكائن الذي يُحدَّد موقعه في List. |

**الإرجاع:**  
int - فهرس العنصر إذا وُجد في القائمة؛ وإلا -1.

### insert(int index, IParagraph value) {#insert-int-com.aspose.slides.IParagraph-}
```
public final void insert(int index, IParagraph value)
```

يدخل Paragraph في المجموعة عند الفهرس المحدد.

**الوسائط:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | الفهرس الصفري الذي سيُدخل عنده Paragraph. |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | Paragraph الذي سيُدخل. |

### insert(int index, IParagraphCollection value) {#insert-int-com.aspose.slides.IParagraphCollection-}
```
public final void insert(int index, IParagraphCollection value)
```

يدخل محتوى ParagraphCollection في المجموعة عند الفهرس المحدد.

**الوسائط:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | الفهرس الصفري الذي ستُدخل عنده الفقرات. |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | الفقرات التي ستُدخل. |

### clear() {#clear--}
```
public final void clear()
```

يزيل جميع العناصر من المجموعة.

### contains(IParagraph item) {#contains-com.aspose.slides.IParagraph-}
```
public final boolean contains(IParagraph item)
```

يحدد ما إذا كان [IGenericCollection](../../com.aspose.slides/igenericcollection) يحتوي على قيمة محددة.

**الوسائط:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | الكائن الذي يُحدَّد موقعه في [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**الإرجاع:**  
boolean - true إذا وُجد العنصر في [IGenericCollection](../../com.aspose.slides/igenericcollection)؛ وإلا false.

### copyTo(IParagraph[] array, int arrayIndex) {#copyTo-com.aspose.slides.IParagraph---int-}
```
public final void copyTo(IParagraph[] array, int arrayIndex)
```

ينسخ عناصر [IGenericCollection](../../com.aspose.slides/igenericcollection) إلى مصفوفة، بدءًا من فهرس مصفوفة معين.

**الوسائط:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | [IParagraph\[\]](../../com.aspose.slides/iparagraph) | المصفوفة أحادية البُعد التي هي وجهة العناصر المنسوخة من [IGenericCollection](../../com.aspose.slides/igenericcollection). يجب أن تكون المصفوفة ذات فهرست صفري. |
| arrayIndex | int | الفهرس الصفري في المصفوفة الذي يبدأ النسخ عنده. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

يزيل العنصر عند الفهرس المحدد في المجموعة.

**الوسائط:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | الفهرس الصفري للعنصر الذي سيُزال. |

### remove(IParagraph item) {#remove-com.aspose.slides.IParagraph-}
```
public final boolean remove(IParagraph item)
```

يزيل أول ظهور لكائن محدد من [IGenericCollection](../../com.aspose.slides/igenericcollection).

**الوسائط:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | الكائن الذي سيُزال من [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**الإرجاع:**  
boolean - true إذا تم إزالة العنصر بنجاح من [IGenericCollection](../../com.aspose.slides/igenericcollection)؛ وإلا false. تُعيد هذه الطريقة false أيضًا إذا لم يُعثر على العنصر في [IGenericCollection](../../com.aspose.slides/igenericcollection) الأصلي.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IParagraph> iterator()
```

يعيد Enumerator يتجول عبر المجموعة.

**الإرجاع:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IParagraph> - IGenericEnumerator يمكن استعماله للتجول عبر المجموعة.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IParagraph> iteratorJava()
```

يعيد java iterator للمجموعة بأكملها.

**الإرجاع:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IParagraph> - java.util.Iterator للمجموعة بأكملها.

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

يعيد الشريحة الأم لمجموعة الفقرات. [BaseSlide](../../com.aspose.slides/baseslide) للقراءة فقط.

**الإرجاع:**  
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

يعيد العرض التقديمي الأم لمجموعة الفقرات. [IPresentation](../../com.aspose.slides/ipresentation) للقراءة فقط.

**الإرجاع:**  
[IPresentation](../../com.aspose.slides/ipresentation)

### addFromHtml(String text) {#addFromHtml-java.lang.String-}
```
public final void addFromHtml(String text)
```

يضيف نصًا من سلسلة HTML محددة إلى المجموعة.

**الوسائط:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | نص HTML. |

### addFromHtml(String text, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final void addFromHtml(String text, IExternalResourceResolver resolver, String uri)
```

يضيف نصًا من سلسلة HTML محددة إلى المجموعة.

**الوسائط:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | نص HTML. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | كائن رد نداء المقرر الذي يحل URI ويجلب الكائنات المرجعية. |
| uri | java.lang.String | URI لإضافة وثيقة HTML. يُستخدم لحل الروابط النسبية.

--------------------

يمكن أن يُدخل تحديد المحلِّل ثغرة أمنية محتملة. استخدمه بحذر. |

### exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options) {#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-}
```
public final String exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)
```

يحوّل الفقرات المحددة إلى HTML ويعيدها ككائن String.

**الوسائط:**
| Parameter | Type | Description |
| --- | --- | --- |
| firstParagraphIndex | int | فهرس الفقرة الأول int |
| paragraphsCount | int | عدد الفقرات int |
| options | [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) | خيارات التحويل [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) |

**الإرجاع:**  
java.lang.String - HTML المولد.