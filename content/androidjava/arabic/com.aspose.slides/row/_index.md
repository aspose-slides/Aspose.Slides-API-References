---
title: Row
second_title: Aspose.Slides لنظام Android عبر مرجع API Java
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
| [getHeight()](#getHeight--) | يعيد ارتفاع الصف. |
| [getMinimalHeight()](#getMinimalHeight--) | يعيد أو يضبط الحد الأدنى الممكن لارتفاع الصف. |
| [setMinimalHeight(double value)](#setMinimalHeight-double-) | يعيد أو يضبط الحد الأدنى الممكن لارتفاع الصف. |
| [setTextFormat(IPortionFormat source)](#setTextFormat-com.aspose.slides.IPortionFormat-) | يضبط خصائص تنسيق الجزء المحدد لجميع أجزاء خلايا الصف. |
| [setTextFormat(IParagraphFormat source)](#setTextFormat-com.aspose.slides.IParagraphFormat-) | يضبط خصائص تنسيق الفقرة المحددة لجميع فقرات خلايا الصف. |
| [setTextFormat(ITextFrameFormat source)](#setTextFormat-com.aspose.slides.ITextFrameFormat-) | يضبط خصائص تنسيق إطار النص المحددة لجميع إطارات نص خلايا الصف. |
| [getRowFormat()](#getRowFormat--) | يعيد كائن RowFormat الذي يحتوي على خصائص التنسيق لهذا الصف. |

### getHeight() {#getHeight--}
```
public final double getHeight()
```

يعيد ارتفاع صف. double للقراءة فقط.

**الإرجاع:**
double

### getMinimalHeight() {#getMinimalHeight--}
```
public final double getMinimalHeight()
```

يعيد أو يضبط الحد الأدنى الممكن لارتفاع صف. double للقراءة والكتابة.

**الإرجاع:**
double

### setMinimalHeight(double value) {#setMinimalHeight-double-}
```
public final void setMinimalHeight(double value)
```

يعيد أو يضبط الحد الأدنى الممكن لارتفاع صف. double للقراءة والكتابة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | double |  |

### setTextFormat(IPortionFormat source) {#setTextFormat-com.aspose.slides.IPortionFormat-}
```
public final void setTextFormat(IPortionFormat source)
```

يضبط خصائص تنسيق الجزء المحدد لجميع أجزاء خلايا الصف.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| source | [IPortionFormat](../../com.aspose.slides/iportionformat) | كائن IPortionFormat مع الخصائص الضرورية مضبوطة. |

### setTextFormat(IParagraphFormat source) {#setTextFormat-com.aspose.slides.IParagraphFormat-}
```
public final void setTextFormat(IParagraphFormat source)
```

يضبط خصائص تنسيق الفقرة المحددة لجميع فقرات خلايا الصف.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| source | [IParagraphFormat](../../com.aspose.slides/iparagraphformat) | كائن IParagraphFormat مع الخصائص الضرورية مضبوطة. |

### setTextFormat(ITextFrameFormat source) {#setTextFormat-com.aspose.slides.ITextFrameFormat-}
```
public final void setTextFormat(ITextFrameFormat source)
```

يضبط خصائص تنسيق إطار النص المحددة لجميع إطارات نص خلايا الصف.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| source | [ITextFrameFormat](../../com.aspose.slides/itextframeformat) | كائن ITextFrameFormat مع الخصائص الضرورية مضبوطة. |

### getRowFormat() {#getRowFormat--}
```
public final IRowFormat getRowFormat()
```

يعيد كائن RowFormat الذي يحتوي على خصائص التنسيق لهذا الصف. للقراءة فقط [IRowFormat](../../com.aspose.slides/irowformat).

**الإرجاع:**
[IRowFormat](../../com.aspose.slides/irowformat)