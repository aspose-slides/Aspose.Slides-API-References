---
title: GetEffective()
second_title: مرجع API الخاص بـ Aspose.Slides للـ C++
description: يحصل على خصائص تنسيق صف الجدول الفعّالة مع تطبيق الوراثة وأنماط الجدول.
type: docs
weight: 1
url: /ar/aspose.slides/rowformat/geteffective/
---
## RowFormat::GetEffective() طريقة

يحصل على خصائص تنسيق صف الجدول الفعّالة مع تطبيق الوراثة وأنماط الجدول.

```cpp
System::SharedPtr<IRowFormatEffectiveData> Aspose::Slides::RowFormat::GetEffective() override
```

### قيمة الإرجاع

كائن [IRowFormatEffectiveData](../../irowformateffectivedata/).

## ملاحظات

يوضح هذا المثال الحصول على تنسيق التعبئة الفعّال لأجزاء منطقية مختلفة من الجدول. يرجى ملاحظة أن تنسيق الخلية دائمًا له أولوية أعلى من تنسيق الصف، والصف أعلى من العمود، والعمود أعلى من كامل الجدول. لذلك في النهاية تُستخدم خصائص CellFormatEffectiveData دائمًا لرسم الجدول. الشفرة التالية هي مجرد مثال على API. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto tbl = AsCast<Table>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto tableFillFormatEffective = tbl->get_TableFormat()->GetEffective()->get_FillFormat();
auto rowFillFormatEffective = tbl->get_Rows()->idx_get(0)->get_RowFormat()->GetEffective()->get_FillFormat();
auto columnFillFormatEffective = tbl->get_Columns()->idx_get(0)->get_ColumnFormat()->GetEffective()->get_FillFormat();
auto cellFillFormatEffective = tbl->idx_get(0, 0)->get_CellFormat()->GetEffective()->get_FillFormat();
// الإخراج والمقارنة
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IRowFormatEffectiveData](../../irowformateffectivedata/)
* فئة [RowFormat](../)
* مساحة اسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)