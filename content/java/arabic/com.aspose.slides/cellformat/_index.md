---
title: CellFormat
second_title: مرجع واجهة برمجة تطبيقات Aspose.Slides لجافا
description: يمثل تنسيق خلية جدول.
type: docs
url: /ar/com.aspose.slides/cellformat/
---
**الوراثة:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**جميع الواجهات المنفذة:**
[com.aspose.slides.ICellFormat](../../com.aspose.slides/icellformat)
```
public final class CellFormat extends PVIObject implements ICellFormat
```

يمثّل تنسيق خلية جدول.
## الطرق

| Method | Description |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getFillFormat()](#getFillFormat--) | يعيد كائن خصائص تعبئة الخلية. |
| [getBorderLeft()](#getBorderLeft--) | يعيد كائن خصائص خط الحد الأيسر. |
| [getBorderTop()](#getBorderTop--) | يعيد كائن خصائص خط الحد العلوي. |
| [getBorderRight()](#getBorderRight--) | يعيد كائن خصائص خط الحد الأيمن. |
| [getBorderBottom()](#getBorderBottom--) | يعيد كائن خصائص خط الحد السفلي. |
| [getBorderDiagonalDown()](#getBorderDiagonalDown--) | يعيد كائن خصائص الخط القطري من أعلى اليسار إلى أسفل اليمين. |
| [getBorderDiagonalUp()](#getBorderDiagonalUp--) | يعيد كائن خصائص الخط القطري من أسفل اليسار إلى أعلى اليمين. |
| [getEffective()](#getEffective--) | يحصل على خصائص تنسيق خلية الجدول الفعّالة مع تطبيق الوراثة وأنماط الجدول. |
| [getTransparency()](#getTransparency--) | يحصل أو يعيّن شفافية لون التعبئة. |
| [setTransparency(float value)](#setTransparency-float-) | يحصل أو يعيّن شفافية لون التعبئة. |
### getVersion() {#getVersion--}
```
public long getVersion()
```


الإصدار. قراءة فقط long.

**الإرجاع:**
long
### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```


يعيد كائن خصائص تعبئة الخلية. قراءة فقط [IFillFormat](../../com.aspose.slides/ifillformat).

**الإرجاع:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getBorderLeft() {#getBorderLeft--}
```
public final ILineFormat getBorderLeft()
```


يعيد كائن خصائص خط الحد الأيسر. قراءة فقط [ILineFormat](../../com.aspose.slides/ilineformat).

**الإرجاع:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderTop() {#getBorderTop--}
```
public final ILineFormat getBorderTop()
```


يعيد كائن خصائص خط الحد العلوي. قراءة فقط [ILineFormat](../../com.aspose.slides/ilineformat).

**الإرجاع:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderRight() {#getBorderRight--}
```
public final ILineFormat getBorderRight()
```


يعيد كائن خصائص خط الحد الأيمن. قراءة فقط [ILineFormat](../../com.aspose.slides/ilineformat).

**الإرجاع:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderBottom() {#getBorderBottom--}
```
public final ILineFormat getBorderBottom()
```


يعيد كائن خصائص خط الحد السفلي. قراءة فقط [ILineFormat](../../com.aspose.slides/ilineformat).

**الإرجاع:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderDiagonalDown() {#getBorderDiagonalDown--}
```
public final ILineFormat getBorderDiagonalDown()
```


يعيد كائن خصائص الخط القطري من أعلى اليسار إلى أسفل اليمين. قراءة فقط [ILineFormat](../../com.aspose.slides/ilineformat).

**الإرجاع:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderDiagonalUp() {#getBorderDiagonalUp--}
```
public final ILineFormat getBorderDiagonalUp()
```


يعيد كائن خصائص الخط القطري من أسفل اليسار إلى أعلى اليمين. قراءة فقط [ILineFormat](../../com.aspose.slides/ilineformat).

**الإرجاع:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getEffective() {#getEffective--}
```
public final ICellFormatEffectiveData getEffective()
```


يحصل على خصائص تنسيق خلية الجدول الفعّالة مع تطبيق الوراثة وأنماط الجدول.

--------------------

> ```
> هذا المثال يوضح الحصول على تنسيق التعبئة الفعّال لأجزاء منطق الجدول المختلفة.
>  يرجى ملاحظة أن تنسيق الخلية له أولوية أعلى دائمًا من تنسيق الصف، والصف أعلى من العمود، والعمود أعلى من الجدول بأكمله.
>  وبالتالي تُستخدم خصائص CellFormatEffectiveData دائمًا لرسم الجدول. الشفرة التالية هي مجرد مثال على API.
>  
>  Presentation pres = new Presentation(@"MyPresentation.pptx");
>  try
>  {
>      ITable tbl = (ITable) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IFillFormatEffectiveData tableFillFormatEffective = tbl.getTableFormat().getEffective().getFillFormat();
>      IFillFormatEffectiveData rowFillFormatEffective = tbl.getRows().get_Item(0).RowFormat.GetEffective().getFillFormat();
>      IFillFormatEffectiveData columnFillFormatEffective = tbl.getColumns().get_Item(0).getColumnFormat().getEffective().getFillFormat();
>      IFillFormatEffectiveData cellFillFormatEffective = tbl.get_Item(0, 0).getCellFormat().getEffective().getFillFormat();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**الإرجاع:**
[ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata) - [ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata).
### getTransparency() {#getTransparency--}
```
public final float getTransparency()
```


يحصل أو يعيّن شفافية لون التعبئة. قراءة/كتابة float .

**الإرجاع:**
float
### setTransparency(float value) {#setTransparency-float-}
```
public final void setTransparency(float value)
```


يحصل أو يعيّن شفافية لون التعبئة. قراءة/كتابة float .

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |