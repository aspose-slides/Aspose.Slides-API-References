---
title: Column
second_title: مرجع API Aspose.Slides للـ Java
description: يمثِّل عمودًا في جدول.
type: docs
url: /ar/com.aspose.slides/column/
---
**الوراثة:**
java.lang.Object, [com.aspose.slides.CellCollection](../../com.aspose.slides/cellcollection)

**جميع الواجهات المنفذة:**
[com.aspose.slides.IColumn](../../com.aspose.slides/icolumn)
```
public final class Column extends CellCollection implements IColumn
```

يمثِّل عمودًا في جدول.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getWidth()](#getWidth--) | إرجاع أو تعيين عرض العمود. |
| [setWidth(double value)](#setWidth-double-) | إرجاع أو تعيين عرض العمود. |
| [setTextFormat(IPortionFormat source)](#setTextFormat-com.aspose.slides.IPortionFormat-) | تعيين خصائص تنسيق الجزء المحدد لجميع أجزاء خلايا العمود. |
| [setTextFormat(IParagraphFormat source)](#setTextFormat-com.aspose.slides.IParagraphFormat-) | تعيين خصائص تنسيق الفقرات المحددة لجميع فقرات خلايا العمود. |
| [setTextFormat(ITextFrameFormat source)](#setTextFormat-com.aspose.slides.ITextFrameFormat-) | تعيين خصائص تنسيق إطارات النص المحددة لجميع إطارات نص خلايا العمود. |
| [getColumnFormat()](#getColumnFormat--) | إرجاع كائن ColumnFormat الذي يحتوي على خصائص تنسيق لهذا العمود. |

### getWidth() {#getWidth--}
```
public final double getWidth()
```

إرجاع أو تعيين عرض العمود. قراءة/كتابة double.

**الإرجاع:**
double

### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```

إرجاع أو تعيين عرض العمود. قراءة/كتابة double.

**المعلمات:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| value | double |  |

### setTextFormat(IPortionFormat source) {#setTextFormat-com.aspose.slides.IPortionFormat-}
```
public final void setTextFormat(IPortionFormat source)
```

تعيين خصائص تنسيق الجزء المحدد لجميع أجزاء خلايا العمود.

**المعلمات:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| source | [IPortionFormat](../../com.aspose.slides/iportionformat) | كائن IPortionFormat مع الخصائص اللازمة مضبوطة. |

### setTextFormat(IParagraphFormat source) {#setTextFormat-com.aspose.slides.IParagraphFormat-}
```
public final void setTextFormat(IParagraphFormat source)
```

تعيين خصائص تنسيق الفقرات المحددة لجميع فقرات خلايا العمود.

**المعلمات:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| source | [IParagraphFormat](../../com.aspose.slides/iparagraphformat) | كائن IParagraphFormat مع الخصائص اللازمة مضبوطة. |

### setTextFormat(ITextFrameFormat source) {#setTextFormat-com.aspose.slides.ITextFrameFormat-}
```
public final void setTextFormat(ITextFrameFormat source)
```

تعيين خصائص تنسيق إطارات النص المحددة لجميع إطارات نص خلايا العمود.

**المعلمات:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| source | [ITextFrameFormat](../../com.aspose.slides/itextframeformat) | كائن ITextFrameFormat مع الخصائص اللازمة مضبوطة. |

### getColumnFormat() {#getColumnFormat--}
```
public final IColumnFormat getColumnFormat()
```

إرجاع كائن ColumnFormat الذي يحتوي على خصائص تنسيق لهذا العمود. قراءة فقط [IColumnFormat](../../com.aspose.slides/icolumnformat).

**الإرجاع:**
[IColumnFormat](../../com.aspose.slides/icolumnformat)