---
title: TableFormat
second_title: مرجع واجهة برمجة تطبيقات Aspose.Slides للجاوا
description: يمثل تنسيق جدول.
type: docs
url: /ar/com.aspose.slides/tableformat/
---
**الوراثة:**  
java.lang.Object, com.aspose.slides.DomObject

**جميع الواجهات المُنفذة:**  
[com.aspose.slides.ITableFormat](../../com.aspose.slides/itableformat), com.aspose.slides.IPVIObject  
```
public final class TableFormat extends DomObject<Table> implements ITableFormat, IPVIObject
```

يمثل تنسيق جدول.

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | يرجع كائن خصائص تعبئة الجدول. |
| [getTransparency()](#getTransparency--) | يحصل أو يضبط شفافية لون التعبئة. |
| [setTransparency(float value)](#setTransparency-float-) | يحصل أو يضبط شفافية لون التعبئة. |
| [getEffective()](#getEffective--) | يحصل على خصائص تنسيق الجدول الفعّالة مع تطبيق الوراثة وأنماط الجدول. |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |

### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```

يرجع كائن خصائص تعبئة الجدول. قراءة فقط [IFillFormat](../../com.aspose.slides/ifillformat).

**القيمة المرجعة:**  
[IFillFormat](../../com.aspose.slides/ifillformat)

### getTransparency() {#getTransparency--}
```
public final float getTransparency()
```

يحصل أو يضبط شفافية لون التعبئة. قراءة/كتابة  float .

**القيمة المرجعة:**  
float

### setTransparency(float value) {#setTransparency-float-}
```
public final void setTransparency(float value)
```

يحصل أو يضبط شفافية لون التعبئة. قراءة/كتابة  float .

**المعلمات:**
| المُعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getEffective() {#getEffective--}
```
public final ITableFormatEffectiveData getEffective()
```

يحصل على خصائص تنسيق الجدول الفعّالة مع تطبيق الوراثة وأنماط الجدول.

--------------------

> ```
> هذا المثال يوضح الحصول على تنسيق التعبئة الفعّال لأجزاء منطق الجدول المختلفة.
>  يرجى ملاحظة أن تنسيق الخلية له دائمًا أولوية أعلى من تنسيق الصف، والصف أعلى من العمود، والعمود أعلى من الجدول بأكمله.
>  لذا في النهاية تُستخدم خصائص CellFormatEffectiveData دائمًا لرسم الجدول. الكود التالي هو مجرد مثال على واجهة برمجة التطبيقات.
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


**القيمة المرجعة:**  
[ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata) - [ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata).

### getVersion() {#getVersion--}
```
public final long getVersion()
```

الإصدار. قراءة فقط long.

**القيمة المرجعة:**  
long

### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

يرجع العنصر الأب IPresentationComponent. قراءة فقط [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**القيمة المرجعة:**  
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)