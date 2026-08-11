---
title: GetEffective()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يحصل على خصائص تنسيق خلايا الجدول الفعالة مع تطبيق الوراثة وأنماط الجدول.
type: docs
weight: 118
url: /ar/aspose.slides/cellformat/geteffective/
---
## CellFormat::GetEffective() طريقة

يحصل على خصائص تنسيق خلايا الجدول الفعالة مع وراثة وتطبيق أنماط الجدول.

```cpp
System::SharedPtr<ICellFormatEffectiveData> Aspose::Slides::CellFormat::GetEffective() override
```

### قيمة الإرجاع

[ICellFormatEffectiveData](../../icellformateffectivedata/).

## ملاحظات

يوضح هذا المثال الحصول على تنسيق الملء الفعال لأجزاء منطقية مختلفة في الجدول. يرجى ملاحظة أن تنسيق الخلية دائمًا له أولوية أعلى من تنسيق الصف، والصف أعلى من العمود، والعمود أعلى من كامل الجدول. لذا في النهاية تُستخدم خصائص CellFormatEffectiveData دائمًا لرسم الجدول. الكود التالي هو مجرد مثال على API.
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto tbl = AsCast<Table>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto tableFillFormatEffective = tbl->get_TableFormat()->GetEffective()->get_FillFormat();
auto rowFillFormatEffective = tbl->get_Rows()->idx_get(0)->get_RowFormat()->GetEffective()->get_FillFormat();
auto columnFillFormatEffective = tbl->get_Columns()->idx_get(0)->get_ColumnFormat()->GetEffective()->get_FillFormat();
auto cellFillFormatEffective = tbl->idx_get(0, 0)->get_CellFormat()->GetEffective()->get_FillFormat();
// إخراج ومقارنة
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [ICellFormatEffectiveData](../../icellformateffectivedata/)
* فئة [CellFormat](../)
* مساحة اسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)