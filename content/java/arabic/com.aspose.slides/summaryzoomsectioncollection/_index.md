---
title: SummaryZoomSectionCollection
second_title: مرجع API لـ Aspose.Slides للغة Java
description: يمثل مجموعة من كائنات Summary Zoom Section.
type: docs
url: /ar/com.aspose.slides/summaryzoomsectioncollection/
---
**الوراثة:**
java.lang.Object, com.aspose.slides.DomObject

**جميع الواجهات المنفذة:**
[com.aspose.slides.ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection)
```
public final class SummaryZoomSectionCollection extends DomObject<SummaryZoomFrame> implements ISummaryZoomSectionCollection
```

يمثل مجموعة من كائنات Summary Zoom Section.

## الأساليب

| الطريقة | الوصف |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | يحصل على العنصر في الفهرس المحدد. |
| [addSummaryZoomSection(ISection section)](#addSummaryZoomSection-com.aspose.slides.ISection-) | ينشئ كائن Summary Zoom Section جديد ويضيفه إلى المجموعة. |
| [size()](#size--) | يحصل على عدد العناصر الفعلي الموجودة في المجموعة. |
| [indexOf(ISummaryZoomSection summaryZoomSection)](#indexOf-com.aspose.slides.ISummaryZoomSection-) | يعيد فهرس كائن SummaryZoomSection المحدد. |
| [removeSummaryZoomSection(ISection section)](#removeSummaryZoomSection-com.aspose.slides.ISection-) | إزالة كائن Summary Zoom Section من المجموعة. |
| [getSummarySection(ISection section)](#getSummarySection-com.aspose.slides.ISection-) | يعيد عنصر Summary Zoom Section للقسم المعطى. |
| [clear()](#clear--) | يزيل جميع كائنات SummaryZoomSection من المجموعة. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | ينسخ المجموعة بالكامل إلى المصفوفة المحددة. |
| [isSynchronized()](#isSynchronized--) | يعيد قيمة تشير إلى ما إذا كان الوصول إلى المجموعة متزامنًا (آمن للتهيئة المتعددة). |
| [getSyncRoot()](#getSyncRoot--) | يعيد جذر التزامن. |
| [iterator()](#iterator--) | يعيد كائن تعداد يتنقل عبر المجموعة. |
| [iteratorJava()](#iteratorJava--) | يعيد مؤشر java للمجموعة بأكملها. |

### get_Item(int index) {#get-Item-int-}
```
public final ISummaryZoomSection get_Item(int index)
```

يحصل على العنصر في الفهرس المحدد. قراءة فقط [ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection).

--------------------

> ```
> The example demonstrates getting Summary Zoom Section element by index:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame)pres.getSlides().get_Item(1).getShapes().get_Item(0);
>       ISummaryZoomSectionCollection collection = zoomFrame.getSummaryZoomCollection();
>       ISummaryZoomSection zoomSection = collection.get_Item(1);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int |  |

**القيمة المرجعة:**
[ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection)

### addSummaryZoomSection(ISection section) {#addSummaryZoomSection-com.aspose.slides.ISection-}
```
public final ISummaryZoomSection addSummaryZoomSection(ISection section)
```

ينشئ كائن Summary Zoom Section جديد ويضيفه إلى المجموعة.

--------------------

> ```
> The example demonstrates getting Summary Zoom Section element by index:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame)pres.getSlides().get_Item(1).getShapes().get_Item(0);
>       ISummaryZoomSectionCollection collection = zoomFrame.getSummaryZoomCollection();
>       ISummaryZoomSection newZoomSection = collection.addSummaryZoomSection(pres.getSections().get_Item(3));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | القسم لعنصر Summary Zoom Section جديد [ISection](../../com.aspose.slides/isection) |

إذا كان هناك عنصر لهذا القسم موجود بالفعل في المجموعة، يتم إرجاع العنصر الموجود.

**القيمة المرجعة:**
[ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection) - تم إضافة عنصر [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe)

### size() {#size--}
```
public final int size()
```

يحصل على عدد العناصر الفعلي الموجودة في المجموعة. قراءة فقط int.

**القيمة المرجعة:**
int

### indexOf(ISummaryZoomSection summaryZoomSection) {#indexOf-com.aspose.slides.ISummaryZoomSection-}
```
public final int indexOf(ISummaryZoomSection summaryZoomSection)
```

يعيد فهرس كائن SummaryZoomSection المحدد.

--------------------

> ```
> The example demonstrates getting Summary Zoom Section element by index:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame)pres.getSlides().get_Item(1).getShapes().get_Item(0);
>       ISummaryZoomSectionCollection collection = zoomFrame.getSummaryZoomCollection();
>       ISummaryZoomSection selectedObject = collection.getSummarySection(pres.getSections().get_Item(2));
>       int idx = collection.indexOf(selectedObject);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| summaryZoomSection | [ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection) | كائن SummaryZoomSection للعثور عليه [ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection). |

**القيمة المرجعة:**
int - فهرس كائن SummaryZoomSection أو -1 إذا لم يكن كائن SummaryZoomSection من هذه المجموعة.

### removeSummaryZoomSection(ISection section) {#removeSummaryZoomSection-com.aspose.slides.ISection-}
```
public final void removeSummaryZoomSection(ISection section)
```

إزالة كائن Summary Zoom Section من المجموعة.

--------------------

> ```
> The example demonstrates getting Summary Zoom Section element by index:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame)pres.getSlides().get_Item(1).getShapes().get_Item(0);
>       ISummaryZoomSectionCollection collection = zoomFrame.getSummaryZoomCollection();
>       collection.removeSummaryZoomSection(pres.getSections().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | القسم الذي يجب إزالة عنصر Summary Zoom Section منه [ISection](../../com.aspose.slides/isection). |

### getSummarySection(ISection section) {#getSummarySection-com.aspose.slides.ISection-}
```
public final ISummaryZoomSection getSummarySection(ISection section)
```

يعيد عنصر Summary Zoom Section للقسم المعطى.

--------------------

> ```
> The example demonstrates getting Summary Zoom Section element by index:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame)pres.getSlides().get_Item(1).getShapes().get_Item(0);
>       ISummaryZoomSectionCollection collection = zoomFrame.getSummaryZoomCollection();
>       ISummaryZoomSection selectedObject = collection.getSummarySection(pres.getSections().get_Item(2));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | القسم للعثور عليه [ISection](../../com.aspose.slides/isection) |

**القيمة المرجعة:**
[ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection) - [ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection) أو null إذا لم تحتوي المجموعة عنصراً للقسم.

### clear() {#clear--}
```
public final void clear()
```

يزيل جميع كائنات SummaryZoomSection من المجموعة.

--------------------

> ```
> The example demonstrates getting Summary Zoom Section element by index:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame)pres.getSlides().get_Item(1).getShapes().get_Item(0);
>       ISummaryZoomSectionCollection collection = zoomFrame.getSummaryZoomCollection();
>       collection.clear();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

ينسخ المجموعة بالكامل إلى المصفوفة المحددة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | المصفوفة الهدف |
| index | int | الفهرس في المصفوفة الهدف. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

يعيد قيمة تشير إلى ما إذا كان الوصول إلى المجموعة متزامنًا (آمن للتهيئة المتعددة). قراءة فقط boolean.

**القيمة المرجعة:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

يعيد جذر التزامن. قراءة فقط Object.

**القيمة المرجعة:**
java.lang.Object

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISummaryZoomSection> iterator()
```

يعيد كائن تعداد يتنقل عبر المجموعة.

**القيمة المرجعة:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISummaryZoomSection> - A IGenericEnumerator that can be used to iterate through the collection.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISummaryZoomSection> iteratorJava()
```

يعيد مؤشر java للمجموعة بأكملها.

**القيمة المرجعة:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISummaryZoomSection> - An java.util.Iterator for the entire collection.