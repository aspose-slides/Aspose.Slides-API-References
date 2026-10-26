---
title: GetEffective()
second_title: مرجع Aspose.Slides API للغة C++
description: يحصل على خصائص تنسيق أعمدة الجدول الفعّالة مع تطبيق الوراثة وأنماط الجدول.
type: docs
weight: 1
url: /ar/aspose.slides/columnformat/geteffective/
---
## ColumnFormat::GetEffective() method

يحصل على خصائص تنسيق أعمدة الجدول الفعّالة مع تطبيق الوراثة وأنماط الجدول.
```cpp
System::SharedPtr<IColumnFormatEffectiveData> Aspose::Slides::ColumnFormat::GetEffective() override
```

### قيمة الإرجاع

[IColumnFormatEffectiveData](../../icolumnformateffectivedata/).
## ملاحظات

يوضح هذا المثال كيفية الحصول على تنسيق التعبئة الفعّال لأجزاء منطقية مختلفة في الجدول. يرجى ملاحظة أن تنسيق الخلية له أولوية أعلى دائمًا من تنسيق الصف، والصف أعلى من العمود، والعمود أعلى من الجدول بأكمله. لذلك في النهاية تُستخدم خصائص CellFormatEffectiveData دائمًا لرسم الجدول. الشيفرة التالية مجرد مثال على API.
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
* فئة [IColumnFormatEffectiveData](../../icolumnformateffectivedata/)
* فئة [ColumnFormat](../)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)