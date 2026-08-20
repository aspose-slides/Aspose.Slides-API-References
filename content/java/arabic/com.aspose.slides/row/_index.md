---
title: Row
second_title: مرجع API لـ Aspose.Slides للـ Java
description: يمثل صفًا في جدول.
type: docs
url: /ar/com.aspose.slides/row/
---
**الوراثة:**
java.lang.Object, [com.aspose.slides.CellCollection](../../com.aspose.slides/cellcollection)

**جميع الواجهات المنفذة:**
[com.aspose.slides.IRow](../../com.aspose.slides/irow)
```
public final class Row extends CellCollection implements IRow
```

يمثل صفًا في جدول.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getHeight()](#getHeight--) | يرجع ارتفاع الصف. |
| [getMinimalHeight()](#getMinimalHeight--) | يرجع أو يعين الحد الأدنى الممكن لارتفاع الصف. |
| [setMinimalHeight(double value)](#setMinimalHeight-double-) | يرجع أو يعين الحد الأدنى الممكن لارتفاع الصف. |
| [setTextFormat(IPortionFormat source)](#setTextFormat-com.aspose.slides.IPortionFormat-) | يضبط خصائص تنسيق الجزء المحددة لجميع أجزاء خلايا الصف. |
| [setTextFormat(IParagraphFormat source)](#setTextFormat-com.aspose.slides.IParagraphFormat-) | يضبط خصائص تنسيق الفقرة المحددة لجميع فقرات خلايا الصف. |
| [setTextFormat(ITextFrameFormat source)](#setTextFormat-com.aspose.slides.ITextFrameFormat-) | يضبط خصائص تنسيق إطار النص المحددة لجميع إطارات نص خلايا الصف. |
| [getRowFormat()](#getRowFormat--) | يرجع كائن RowFormat التي تحتوي على خصائص التنسيق لهذا الصف. |
### getHeight() {#getHeight--}
```
public final double getHeight()
```


يرجع ارتفاع الصف. للقراءة فقط double.

**الإرجاع:**
double
### getMinimalHeight() {#getMinimalHeight--}
```
public final double getMinimalHeight()
```


يرجع أو يعين الحد الأدنى الممكن لارتفاع الصف. قابل للقراءة والكتابة double.

**الإرجاع:**
double
### setMinimalHeight(double value) {#setMinimalHeight-double-}
```
public final void setMinimalHeight(double value)
```


يرجع أو يعين الحد الأدنى الممكن لارتفاع الصف. قابل للقراءة والكتابة double.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | double |  |

### setTextFormat(IPortionFormat source) {#setTextFormat-com.aspose.slides.IPortionFormat-}
```
public final void setTextFormat(IPortionFormat source)
```


يضبط خصائص تنسيق الجزء المحددة لجميع أجزاء خلايا الصف.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| source | [IPortionFormat](../../com.aspose.slides/iportionformat) | كائن IPortionFormat مع الخصائص الضرورية محددة. |

### setTextFormat(IParagraphFormat source) {#setTextFormat-com.aspose.slides.IParagraphFormat-}
```
public final void setTextFormat(IParagraphFormat source)
```


يضبط خصائص تنسيق الفقرة المحددة لجميع فقرات خلايا الصف.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| source | [IParagraphFormat](../../com.aspose.slides/iparagraphformat) | كائن IParagraphFormat مع الخصائص الضرورية محددة. |

### setTextFormat(ITextFrameFormat source) {#setTextFormat-com.aspose.slides.ITextFrameFormat-}
```
public final void setTextFormat(ITextFrameFormat source)
```


يضبط خصائص تنسيق إطار النص المحددة لجميع إطارات نص خلايا الصف.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| source | [ITextFrameFormat](../../com.aspose.slides/itextframeformat) | كائن ITextFrameFormat مع الخصائص الضرورية محددة. |

### getRowFormat() {#getRowFormat--}
```
public final IRowFormat getRowFormat()
```


يرجع كائن RowFormat الذي يحتوي على خصائص التنسيق لهذا الصف. للقراءة فقط [IRowFormat](../../com.aspose.slides/irowformat).

**الإرجاع:**
[IRowFormat](../../com.aspose.slides/irowformat)