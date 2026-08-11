---
title: GetEffective()
second_title: مرجع API Aspose.Slides برای C++
description: ویژگی‌های قالب‌بندی مؤثر ستون جدول را با وراثت و سبک‌های جدول اعمال‌شده دریافت می‌کند.
type: docs
weight: 1
url: /fa/aspose.slides/columnformat/geteffective/
---
## ColumnFormat::GetEffective() متد

ویژگی‌های قالب‌بندی مؤثر ستون جدول را با وراثت و سبک‌های جدول اعمال‌شده دریافت می‌کند.

```cpp
System::SharedPtr<IColumnFormatEffectiveData> Aspose::Slides::ColumnFormat::GetEffective() override
```

### مقدار بازگشت

یک [IColumnFormatEffectiveData](../../icolumnformateffectivedata/).
## توضیحات

این مثال نحوه دریافت قالب پر کردن مؤثر برای بخش‌های مختلف منطق جدول را نشان می‌دهد. لطفاً توجه داشته باشید که قالب‌بندی سلول همیشه دارای اولویت بالاتری نسبت به قالب‌بندی ردیف است، ردیف بیش از ستون، ستون بیش از کل جدول. بنابراین در نهایت ویژگی‌های CellFormatEffectiveData همیشه برای رسم جدول استفاده می‌شوند. کد زیر صرفاً یک مثال از API است.
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto tbl = AsCast<Table>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto tableFillFormatEffective = tbl->get_TableFormat()->GetEffective()->get_FillFormat();
auto rowFillFormatEffective = tbl->get_Rows()->idx_get(0)->get_RowFormat()->GetEffective()->get_FillFormat();
auto columnFillFormatEffective = tbl->get_Columns()->idx_get(0)->get_ColumnFormat()->GetEffective()->get_FillFormat();
auto cellFillFormatEffective = tbl->idx_get(0, 0)->get_CellFormat()->GetEffective()->get_FillFormat();
// خروجی و مقایسه
```

## همچنین

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IColumnFormatEffectiveData](../../icolumnformateffectivedata/)
* کلاس [ColumnFormat](../)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)