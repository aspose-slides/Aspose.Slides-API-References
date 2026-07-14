---
title: ICellFormat
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يمثل تنسيق خلية جدول.
type: docs
url: /ar/com.aspose.slides/icellformat/
---```
public interface ICellFormat
```

يمثل تنسيق خلية جدول.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | يرجع كائن خصائص تعبئة الخلية. |
| [getBorderLeft()](#getBorderLeft--) | يرجع كائن خصائص خط الحد الأيسر. |
| [getBorderTop()](#getBorderTop--) | يرجع كائن خصائص خط الحد العلوي. |
| [getBorderRight()](#getBorderRight--) | يرجع كائن خصائص خط الحد الأيمن. |
| [getBorderBottom()](#getBorderBottom--) | يرجع كائن خصائص خط الحد السفلي. |
| [getBorderDiagonalDown()](#getBorderDiagonalDown--) | يرجع كائن خصائص الخط القطري من أعلى اليسار إلى أسفل اليمين. |
| [getBorderDiagonalUp()](#getBorderDiagonalUp--) | يرجع كائن خصائص الخط القطري من أسفل اليسار إلى أعلى اليمين. |
| [getTransparency()](#getTransparency--) | يحصل على أو يعيّن شفافية لون التعبئة. |
| [setTransparency(float value)](#setTransparency-float-) | يحصل على أو يعيّن شفافية لون التعبئة. |
| [getEffective()](#getEffective--) | يحصل على خصائص تنسيق خلية الجدول الفعّالة مع تطبيق الوراثة وأنماط الجدول. |
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

يرجع كائن خصائص تعبئة الخلية. قراءة فقط [IFillFormat](../../com.aspose.slides/ifillformat).

**القيمة المرجعة:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getBorderLeft() {#getBorderLeft--}
```
public abstract ILineFormat getBorderLeft()
```

يرجع كائن خصائص خط الحد الأيسر. قراءة فقط [ILineFormat](../../com.aspose.slides/ilineformat).

**القيمة المرجعة:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderTop() {#getBorderTop--}
```
public abstract ILineFormat getBorderTop()
```

يرجع كائن خصائص خط الحد العلوي. قراءة فقط [ILineFormat](../../com.aspose.slides/ilineformat).

**القيمة المرجعة:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderRight() {#getBorderRight--}
```
public abstract ILineFormat getBorderRight()
```

يرجع كائن خصائص خط الحد الأيمن. قراءة فقط [ILineFormat](../../com.aspose.slides/ilineformat).

**القيمة المرجعة:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderBottom() {#getBorderBottom--}
```
public abstract ILineFormat getBorderBottom()
```

يرجع كائن خصائص خط الحد السفلي. قراءة فقط [ILineFormat](../../com.aspose.slides/ilineformat).

**القيمة المرجعة:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderDiagonalDown() {#getBorderDiagonalDown--}
```
public abstract ILineFormat getBorderDiagonalDown()
```

يرجع كائن خصائص الخط القطري من أعلى اليسار إلى أسفل اليمين. قراءة فقط [ILineFormat](../../com.aspose.slides/ilineformat).

**القيمة المرجعة:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderDiagonalUp() {#getBorderDiagonalUp--}
```
public abstract ILineFormat getBorderDiagonalUp()
```

يرجع كائن خصائص الخط القطري من أسفل اليسار إلى أعلى اليمين. قراءة فقط [ILineFormat](../../com.aspose.slides/ilineformat).

**القيمة المرجعة:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getTransparency() {#getTransparency--}
```
public abstract float getTransparency()
```

يحصل على أو يعيّن شفافية لون التعبئة. قراءة/كتابة  float .

**القيمة المرجعة:**
float
### setTransparency(float value) {#setTransparency-float-}
```
public abstract void setTransparency(float value)
```

يحصل على أو يعيّن شفافية لون التعبئة. قراءة/كتابة  float .

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | float |  |
### getEffective() {#getEffective--}
```
public abstract ICellFormatEffectiveData getEffective()
```

يحصل على خصائص تنسيق خلية الجدول الفعّالة مع تطبيق الوراثة وأنماط الجدول.

**القيمة المرجعة:**
[ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata) - كائن [ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata).