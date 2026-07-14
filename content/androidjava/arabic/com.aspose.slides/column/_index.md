---
title: Column
second_title: Aspose.Slides لنظام Android عبر مرجع واجهة برمجة التطبيقات لجافا
description: يمثل عمودًا في جدول.
type: docs
url: /ar/com.aspose.slides/column/
---
**الوراثة:**
java.lang.Object, [com.aspose.slides.CellCollection](../../com.aspose.slides/cellcollection)

**جميع الواجهات المُنفذة:**
[com.aspose.slides.IColumn](../../com.aspose.slides/icolumn)
```
public final class Column extends CellCollection implements IColumn
```

يمثل عمودًا في جدول.
## الطرق

| Method | Description |
| --- | --- |
| [getWidth()](#getWidth--) | إرجاع أو تعيين عرض العمود. |
| [setWidth(double value)](#setWidth-double-) | إرجاع أو تعيين عرض العمود. |
| [setTextFormat(IPortionFormat source)](#setTextFormat-com.aspose.slides.IPortionFormat-) | يعيّن خصائص تنسيق الجزء المعرفة إلى جميع أجزاء خلايا العمود. |
| [setTextFormat(IParagraphFormat source)](#setTextFormat-com.aspose.slides.IParagraphFormat-) | يعيّن خصائص تنسيق الفقرة المعرفة إلى جميع فقرات خلايا العمود. |
| [setTextFormat(ITextFrameFormat source)](#setTextFormat-com.aspose.slides.ITextFrameFormat-) | يعيّن خصائص تنسيق إطار النص المعرفة إلى جميع إطارات نص خلايا العمود. |
| [getColumnFormat()](#getColumnFormat--) | إرجاع كائن ColumnFormat الذي يحتوي على خصائص التنسيق لهذا العمود. |

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
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | double |  |

### setTextFormat(IPortionFormat source) {#setTextFormat-com.aspose.slides.IPortionFormat-}
```
public final void setTextFormat(IPortionFormat source)
```

يعيّن خصائص تنسيق الجزء المعرفة إلى جميع أجزاء خلايا العمود.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| source | [IPortionFormat](../../com.aspose.slides/iportionformat) | كائن IPortionFormat مع تعيين الخصائص اللازمة. |

### setTextFormat(IParagraphFormat source) {#setTextFormat-com.aspose.slides.IParagraphFormat-}
```
public final void setTextFormat(IParagraphFormat source)
```

يعيّن خصائص تنسيق الفقرة المعرفة إلى جميع فقرات خلايا العمود.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| source | [IParagraphFormat](../../com.aspose.slides/iparagraphformat) | كائن IParagraphFormat مع تعيين الخصائص اللازمة. |

### setTextFormat(ITextFrameFormat source) {#setTextFormat-com.aspose.slides.ITextFrameFormat-}
```
public final void setTextFormat(ITextFrameFormat source)
```

يعيّن خصائص تنسيق إطار النص المعرفة إلى جميع إطارات نص خلايا العمود.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| source | [ITextFrameFormat](../../com.aspose.slides/itextframeformat) | كائن ITextFrameFormat مع تعيين الخصائص اللازمة. |

### getColumnFormat() {#getColumnFormat--}
```
public final IColumnFormat getColumnFormat()
```

إرجاع كائن ColumnFormat الذي يحتوي على خصائص التنسيق لهذا العمود. للقراءة فقط [IColumnFormat](../../com.aspose.slides/icolumnformat).

**الإرجاع:**
[IColumnFormat](../../com.aspose.slides/icolumnformat)