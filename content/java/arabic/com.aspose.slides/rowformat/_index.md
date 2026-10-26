---
title: RowFormat
second_title: Aspose.Slides لمرجع API جافا
description: يمثل تنسيق صف جدول.
type: docs
url: /ar/com.aspose.slides/rowformat/
---
**الوراثة:**  
java.lang.Object, com.aspose.slides.DomObject

**جميع الواجهات المطبقة:**  
[com.aspose.slides.IRowFormat](../../com.aspose.slides/irowformat), com.aspose.slides.IPVIObject  
```
public final class RowFormat extends DomObject<Row> implements IRowFormat, IPVIObject
```

يمثل تنسيق صف جدول.

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getEffective()](#getEffective--) | يحصل على خصائص تنسيق صف الجدول الفعّالة مع تطبيق الوراثة وأنماط الجدول. |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |

### getEffective() {#getEffective--}
```
public final IRowFormatEffectiveData getEffective()
```

يحصل على خصائص تنسيق صف الجدول الفعّالة مع تطبيق الوراثة وأنماط الجدول.

--------------------

> ```
> يوضح هذا المثال كيفية الحصول على تنسيق الملء الفعّال لأجزاء المنطق المختلفة للجدول.
>  يرجى ملاحظة أن تنسيق الخلية له أولوية أعلى دائمًا من تنسيق الصف، والصف أعلى من العمود، والعمود أعلى من الجدول بالكامل.
>  لذا في النهاية يتم دائمًا استخدام خصائص CellFormatEffectiveData لرسم الجدول. الشيفرة التالية مجرد مثال على API.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>      ITable tbl = (ITable)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IFillFormatEffectiveData tableFillFormatEffective = tbl.getTableFormat().getEffective().getFillFormat();
>      IFillFormatEffectiveData rowFillFormatEffective = tbl.getRows().get_Item(0).getRowFormat().getEffective().getFillFormat();
>      IFillFormatEffectiveData columnFillFormatEffective = tbl.getColumns().get_Item(0).getColumnFormat().getEffective().getFillFormat();
>      IFillFormatEffectiveData cellFillFormatEffective = tbl.get_Item(0, 0).getCellFormat().getEffective().getFillFormat();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**الإرجاع:**  
[IRowFormatEffectiveData](../../com.aspose.slides/irowformateffectivedata) - ‏[IRowFormatEffectiveData](../../com.aspose.slides/irowformateffectivedata).

### getVersion() {#getVersion--}
```
public final long getVersion()
```

الإصدار. قراءة فقط من النوع long.

**الإرجاع:**  
long

### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

يرجع الوالد IPresentationComponent. قراءة فقط [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**الإرجاع:**  
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)