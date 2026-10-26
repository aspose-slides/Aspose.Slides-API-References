---
title: GetEffective()
second_title: Aspose.Slides برای مرجع API C++
description: ویژگی‌های قالب‌بندی مؤثر جدول را با اعمال وراثت و سبک‌های جدول دریافت می‌کند.
type: docs
weight: 40
url: /fa/aspose.slides/tableformat/geteffective/
---
## TableFormat::GetEffective() متد

ویژگی‌های قالب‌بندی مؤثر جدول را با به‌کارگیری وراثت و سبک‌های جدول دریافت می‌کند.

```cpp
System::SharedPtr<ITableFormatEffectiveData> Aspose::Slides::TableFormat::GetEffective() override
```

### مقدار بازگشت

یک [ITableFormatEffectiveData](../../itableformateffectivedata/).

## توضیحات

این مثال نحوه دریافت قالب پرشده مؤثر برای بخش‌های مختلف منطقی جدول را نشان می‌دهد. لطفاً توجه داشته باشید که قالب‌بندی سلول همیشه اولویت بالاتری نسبت به قالب‌بندی ردیف دارد، ردیف نسبت به ستون، ستون نسبت به کل جدول. بنابراین در نهایت ویژگی‌های CellFormatEffectiveData برای رسم جدول استفاده می‌شوند. کد زیر تنها نمونه‌ای از API است. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto tbl = AsCast<Table>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto tableFillFormatEffective = tbl->get_TableFormat()->GetEffective()->get_FillFormat();
auto rowFillFormatEffective = tbl->get_Rows()->idx_get(0)->get_RowFormat()->GetEffective()->get_FillFormat();
auto columnFillFormatEffective = tbl->get_Columns()->idx_get(0)->get_ColumnFormat()->GetEffective()->get_FillFormat();
auto cellFillFormatEffective = tbl->idx_get(0, 0)->get_CellFormat()->GetEffective()->get_FillFormat();
```

## مراجعه به

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ITableFormatEffectiveData](../../itableformateffectivedata/)
* Class [TableFormat](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)