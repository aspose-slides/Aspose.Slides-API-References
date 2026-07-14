---
title: TableFormat
second_title: Aspose.Slides لنظام Android عبر مرجع واجهة برمجة التطبيقات Java
description: يمثل تنسيق جدول.
type: docs
url: /ar/com.aspose.slides/tableformat/
---
**الوراثة:**
java.lang.Object, com.aspose.slides.DomObject

**جميع الواجهات المنفذة:**
[com.aspose.slides.ITableFormat](../../com.aspose.slides/itableformat), com.aspose.slides.IPVIObject
```
public final class TableFormat extends DomObject<Table> implements ITableFormat, IPVIObject
```

يمثل تنسيق جدول.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | إرجاع كائن خصائص تعبئة الجدول. |
| [getTransparency()](#getTransparency--) | الحصول على شفافية لون التعبئة أو تعيينها. |
| [setTransparency(float value)](#setTransparency-float-) | الحصول على شفافية لون التعبئة أو تعيينها. |
| [getEffective()](#getEffective--) | الحصول على خصائص تنسيق الجدول الفعّالة مع تطبيق الوراثة وأنماط الجدول. |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```

إرجاع كائن خصائص تعبئة الجدول. للقراءة فقط [IFillFormat](../../com.aspose.slides/ifillformat).

**الإرجاع:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getTransparency() {#getTransparency--}
```
public final float getTransparency()
```

الحصول على شفافية لون التعبئة أو تعيينها. قراءة/كتابة  float .

**الإرجاع:**
float
### setTransparency(float value) {#setTransparency-float-}
```
public final void setTransparency(float value)
```

الحصول على شفافية لون التعبئة أو تعيينها. قراءة/كتابة  float .

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | float |  |
### getEffective() {#getEffective--}
```
public final ITableFormatEffectiveData getEffective()
```

الحصول على خصائص تنسيق الجدول الفعّالة مع تطبيق الوراثة وأنماط الجدول.

--------------------

> ```
> يوضح هذا المثال الحصول على تنسيق تعبئة فعال لأجزاء من منطق الجدول المختلفة.
>  يرجى ملاحظة أن تنسيق الخلية دائمًا له أولوية أعلى من تنسيق الصف، والصف أعلى من العمود، والعمود أعلى من الجدول الكامل.
>  لذا تُستخدم خصائص CellFormatEffectiveData في النهاية دائمًا لرسم الجدول. الشيفرة التالية مجرد مثال على واجهة برمجة التطبيقات.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>      ITable tbl = (Table)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IFillFormatEffectiveData tableFillFormatEffective = tbl.getTableFormat().getEffective().getFillFormat();
>      IFillFormatEffectiveData rowFillFormatEffective = tbl.getRows().get_Item(0).getRowFormat().getEffective().getFillFormat();
>      IFillFormatEffectiveData columnFillFormatEffective = tbl.getColumns().get_Item(0).getColumnFormat().getEffective().getFillFormat();
>      IFillFormatEffectiveData cellFillFormatEffective = tbl.get_Item(0, 0).getCellFormat().getEffective().getFillFormat();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**الإرجاع:**
[ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata) - كائن من النوع [ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata).
### getVersion() {#getVersion--}
```
public final long getVersion()
```

الإصدار. للقراءة فقط long.

**الإرجاع:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

إرجاع العنصر الأب IPresentationComponent. للقراءة فقط [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**الإرجاع:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)