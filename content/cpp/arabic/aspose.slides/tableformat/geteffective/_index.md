---
title: GetEffective()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يحصل على خصائص تنسيق الجدول الفعّالة مع تطبيق الوراثة وأنماط الجدول.
type: docs
weight: 40
url: /ar/aspose.slides/tableformat/geteffective/
---
## TableFormat::GetEffective() طريقة


يحصل على خصائص تنسيق الجدول الفعّالة مع تطبيق الوراثة وأنماط الجدول.

```cpp
System::SharedPtr<ITableFormatEffectiveData> Aspose::Slides::TableFormat::GetEffective() override
```


### قيمة الإرجاع

A [ITableFormatEffectiveData](../../itableformateffectivedata/).
## ملاحظات



يوضح هذا المثال الحصول على تنسيق التعبئة الفعّال لأجزاء منطق الجدول المختلفة. يرجى ملاحظة أن تنسيق الخلية له أولوية أعلى دائماً من تنسيق الصف، والصف أعلى من العمود، والعمود أعلى من الجدول بأكمله. لذلك في النهاية تُستخدم خصائص CellFormatEffectiveData دائمًا لرسم الجدول. الشيفرة التالية هي مجرد مثال على API. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto tbl = AsCast<Table>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto tableFillFormatEffective = tbl->get_TableFormat()->GetEffective()->get_FillFormat();
auto rowFillFormatEffective = tbl->get_Rows()->idx_get(0)->get_RowFormat()->GetEffective()->get_FillFormat();
auto columnFillFormatEffective = tbl->get_Columns()->idx_get(0)->get_ColumnFormat()->GetEffective()->get_FillFormat();
auto cellFillFormatEffective = tbl->idx_get(0, 0)->get_CellFormat()->GetEffective()->get_FillFormat();
```

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ITableFormatEffectiveData](../../itableformateffectivedata/)
* Class [TableFormat](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)