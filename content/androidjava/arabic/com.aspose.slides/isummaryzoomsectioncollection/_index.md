---
title: ISummaryZoomSectionCollection
second_title: Aspose.Slides لـ Android عبر مرجع API لجافا
description: يمثل مجموعة من كائنات Summary Zoom Section.
type: docs
url: /ar/com.aspose.slides/isummaryzoomsectioncollection/
---
**جميع الواجهات المنفذة:**
com.aspose.slides.IGenericCollection
```
public interface ISummaryZoomSectionCollection extends IGenericCollection<ISummaryZoomSection>
```

يمثل مجموعة من كائنات Summary Zoom Section.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | يحصل على العنصر في الفهرس المحدد. |
| [addSummaryZoomSection(ISection section)](#addSummaryZoomSection-com.aspose.slides.ISection-) | ينشئ كائن Summary Zoom Section جديد ويضيفه إلى المجموعة |
| [getSummarySection(ISection section)](#getSummarySection-com.aspose.slides.ISection-) | يعيد عنصر Summary Zoom Section للفقرة المحددة. |
| [removeSummaryZoomSection(ISection section)](#removeSummaryZoomSection-com.aspose.slides.ISection-) | يزيل كائن Summary Zoom Section من المجموعة. |
| [indexOf(ISummaryZoomSection summaryZoomSection)](#indexOf-com.aspose.slides.ISummaryZoomSection-) | يعيد فهرس الكائن SummaryZoomSection المحدد. |
| [clear()](#clear--) | يزيل جميع كائنات SummaryZoomSection من المجموعة. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ISummaryZoomSection get_Item(int index)
```

يحصل على العنصر في الفهرس المحدد. للقراءة فقط [ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection).

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
| معامل | نوع | وصف |
| --- | --- | --- |
| index | int |  |

**القيمة المرجعة:**
[ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection)
### addSummaryZoomSection(ISection section) {#addSummaryZoomSection-com.aspose.slides.ISection-}
```
public abstract ISummaryZoomSection addSummaryZoomSection(ISection section)
```

ينشئ كائن Summary Zoom Section جديد ويضيفه إلى المجموعة

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
| معامل | نوع | وصف |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | الفقرة للعنصر Summary Zoom Section الجديد [ISection](../../com.aspose.slides/isection)

--------------------

إذا كان هناك عنصر لهذا القسم موجود بالفعل في المجموعة، يتم إرجاع العنصر الموجود. |

**القيمة المرجعة:**
[ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection) - العنصر المضاف [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe)
### getSummarySection(ISection section) {#getSummarySection-com.aspose.slides.ISection-}
```
public abstract ISummaryZoomSection getSummarySection(ISection section)
```

يعيد عنصر Summary Zoom Section للفقرة المحددة.

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
| معامل | نوع | وصف |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | القسم للبحث [ISection](../../com.aspose.slides/isection) |

**القيمة المرجعة:**
[ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection) - [ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection) أو null إذا لم تحتوي المجموعة على عنصر للقسم.
### removeSummaryZoomSection(ISection section) {#removeSummaryZoomSection-com.aspose.slides.ISection-}
```
public abstract void removeSummaryZoomSection(ISection section)
```

يزيل كائن Summary Zoom Section من المجموعة.

--------------------

> ```
> يوضح المثال كيفية الحصول على عنصر Summary Zoom Section عن طريق الفهرس:
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
| معامل | نوع | وصف |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | القسم الذي سيتم إزالة عنصر Summary Zoom Section منه [ISection](../../com.aspose.slides/isection). |

### indexOf(ISummaryZoomSection summaryZoomSection) {#indexOf-com.aspose.slides.ISummaryZoomSection-}
```
public abstract int indexOf(ISummaryZoomSection summaryZoomSection)
```

يعيد فهرس الكائن SummaryZoomSection المحدد.

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
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**المعاملات:**
| معامل | نوع | وصف |
| --- | --- | --- |
| summaryZoomSection | [ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection) | كائن SummaryZoomSection للبحث عنه [ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection). |

**القيمة المرجعة:**
int - فهرس كائن SummaryZoomSection أو -1 إذا كان كائن SummaryZoomSection ليس من هذه المجموعة.
### clear() {#clear--}
```
public abstract void clear()
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
