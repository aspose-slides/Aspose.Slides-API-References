---
title: AddTable()
second_title: Aspose.Slides برای C++ مرجع API
description: یک جدول جدید ایجاد می‌کند و آن را به انتهای مجموعهٔ اشکال اضافه می‌نماید.
type: docs
weight: 469
url: /fa/aspose.slides/shapecollection/addtable/
---
## ShapeCollection::AddTable(float, float, System::ArrayPtr\<double\>, System::ArrayPtr\<double\>) متد

یک جدول جدید ایجاد می‌کند و آن را به انتهای مجموعهٔ اشکال اضافه می‌نماید.

```cpp
System::SharedPtr<ITable> Aspose::Slides::ShapeCollection::AddTable(float x, float y, System::ArrayPtr<double> columnWidths, System::ArrayPtr<double> rowHeights) override
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | **float** | مختصات x جدول، به نقطه. |
| y | **float** | مختصات y جدول، به نقطه. |
| columnWidths | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | یک آرایه از double که عرض ستون‌های جدول را نشان می‌دهد، به نقطه. |
| rowHeights | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | یک آرایه از double که ارتفاع سطرهای جدول را نشان می‌دهد، به نقطه. |

### مقدار بازگشتی

[ITable](../../itable/) جدید ایجاد شده.

## نکات

مثال‌های زیر نشان می‌دهند چگونه جدول را در PowerPoint [Presentation](../../presentation/) اضافه کرد.
```cpp
// یک شی از کلاس Presentation که نمایانگر فایل PPTX است را ایجاد می‌کند
auto pres = System::MakeObject<Presentation>();
// به اولین اسلاید دسترسی پیدا می‌کند
auto slide = pres->get_Slides()->idx_get(0);
// ستون‌ها را با عرض‌ها و سطرها را با ارتفاع‌ها تعریف می‌کند
System::ArrayPtr<double> dblCols = System::MakeArray<double>({50, 50, 50});
System::ArrayPtr<double> dblRows = System::MakeArray<double>({50, 30, 30, 30, 30});
// شکل جدول را به اسلاید اضافه می‌کند
System::SharedPtr<ITable> table = slide->get_Shapes()->AddTable(100.0f, 50.0f, dblCols, dblRows);
// فرمت حاشیه را برای هر سلول تنظیم می‌کند
for (int32_t row = 0; row < table->get_Rows()->get_Count(); row++)
{
    auto currentRow = table->get_Rows()->idx_get(row);
    for (int32_t col = 0; col < currentRow->get_Count(); col++)
    {
        auto cell = currentRow->idx_get(col);
        auto cellFormat = cell->get_CellFormat();
        cellFormat->get_BorderTop()->get_FillFormat()->set_FillType(FillType::Solid);
        cellFormat->get_BorderTop()->get_FillFormat()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Red());
        cellFormat->get_BorderTop()->set_Width(5);
        cellFormat->get_BorderBottom()->get_FillFormat()->set_FillType(FillType::Solid);
        cellFormat->get_BorderBottom()->get_FillFormat()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Red());
        cellFormat->get_BorderBottom()->set_Width(5);
        cellFormat->get_BorderLeft()->get_FillFormat()->set_FillType(FillType::Solid);
        cellFormat->get_BorderLeft()->get_FillFormat()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Red());
        cellFormat->get_BorderLeft()->set_Width(5);
        cellFormat->get_BorderRight()->get_FillFormat()->set_FillType(FillType::Solid);
        cellFormat->get_BorderRight()->get_FillFormat()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Red());
        cellFormat->get_BorderRight()->set_Width(5);
    }
}

// ترکیب سلول‌های 1 و 2 از سطر 1
table->MergeCells(table->get_Rows()->idx_get(0)->idx_get(0), table->get_Rows()->idx_get(1)->idx_get(1), false);
// متن را به سلول ترکیب‌شده اضافه می‌کند
table->get_Rows()->idx_get(0)->idx_get(0)->get_TextFrame()->set_Text(u"Merged Cells");
// ذخیره PPTX بر روی دیسک
pres->Save(u"table.pptx", SaveFormat::Pptx);
```

## همچنین ببینید

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* کلاس [ITable](../../itable/)
* کلاس [ShapeCollection](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)