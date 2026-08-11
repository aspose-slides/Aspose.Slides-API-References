---
title: GetEffective()
second_title: Aspose.Slides برای C++ مرجع API
description: ویژگی‌های قالب‌بندی مؤثر سلول جدول را با ارث‌بری و اعمال سبک‌های جدول دریافت می‌کند.
type: docs
weight: 118
url: /fa/aspose.slides/cellformat/geteffective/
---
## CellFormat::GetEffective() متد


ویژگی‌های قالب‌بندی مؤثر سلول جدول را با ارث‌بری و اعمال سبک‌های جدول دریافت می‌کند.

```cpp
System::SharedPtr<ICellFormatEffectiveData> Aspose::Slides::CellFormat::GetEffective() override
```


### مقدار بازگشت

A [ICellFormatEffectiveData](../../icellformateffectivedata/).
## توضیحات



این مثال نحوه دریافت قالب پر کردن مؤثر برای بخش‌های مختلف منطقی جدول را نشان می‌دهد. لطفاً توجه داشته باشید که قالب‌بندی سلول همیشه اولویت بالاتری نسبت به قالب‌بندی سطر دارد، سطر بالاتر از ستون، ستون بالاتر از کل جدول. بنابراین در نهایت ویژگی‌های CellFormatEffectiveData همیشه برای رسم جدول استفاده می‌شوند. کد زیر تنها یک مثال از API است. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto tbl = AsCast<Table>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto tableFillFormatEffective = tbl->get_TableFormat()->GetEffective()->get_FillFormat();
auto rowFillFormatEffective = tbl->get_Rows()->idx_get(0)->get_RowFormat()->GetEffective()->get_FillFormat();
auto columnFillFormatEffective = tbl->get_Columns()->idx_get(0)->get_ColumnFormat()->GetEffective()->get_FillFormat();
auto cellFillFormatEffective = tbl->idx_get(0, 0)->get_CellFormat()->GetEffective()->get_FillFormat();
// خروجی و مقایسه
```

## همچنین ببینید

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [ICellFormatEffectiveData](../../icellformateffectivedata/)
* کلاس [CellFormat](../)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)