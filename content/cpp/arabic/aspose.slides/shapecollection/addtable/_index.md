---
title: AddTable()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: ينشئ جدولًا جديدًا ويضيفه إلى نهاية مجموعة الأشكال.
type: docs
weight: 469
url: /ar/aspose.slides/shapecollection/addtable/
---
## ShapeCollection::AddTable(float, float, System::ArrayPtr\<double\>, System::ArrayPtr\<double\>) طريقة

Creates a new table and adds it to the end of the shape collection.

```cpp
System::SharedPtr<ITable> Aspose::Slides::ShapeCollection::AddTable(float x, float y, System::ArrayPtr<double> columnWidths, System::ArrayPtr<double> rowHeights) override
```

### الوسائط

| معامل | نوع | الوصف |
| --- | --- | --- |
| x | **float** | الإحداثي السيني للجدول، بالنقاط. |
| y | **float** | الإحداثي الصادي للجدول، بالنقاط. |
| columnWidths | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | مصفوفة من double تمثل عرض أعمدة الجدول، بالنقاط. |
| rowHeights | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | مصفوفة من double تمثل ارتفاع صفوف الجدول، بالنقاط. |

### قيمة الإرجاع

الـ [ITable](../../itable/) الذي تم إنشاؤه حديثًا.

## ملاحظات

توضح الأمثلة التالية كيفية إضافة جدول في PowerPoint [Presentation](../../presentation/).
```cpp
// إنشاء كائن من فئة Presentation التي تمثل ملف PPTX
auto pres = System::MakeObject<Presentation>();
// الوصول إلى الشريحة الأولى
auto slide = pres->get_Slides()->idx_get(0);
// تعريف الأعمدة بعرضها والصفوف بطولها
System::ArrayPtr<double> dblCols = System::MakeArray<double>({50, 50, 50});
System::ArrayPtr<double> dblRows = System::MakeArray<double>({50, 30, 30, 30, 30});
// إضافة شكل جدول إلى الشريحة
System::SharedPtr<ITable> table = slide->get_Shapes()->AddTable(100.0f, 50.0f, dblCols, dblRows);
// تعيين تنسيق الحدود لكل خلية
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

// دمج الخلايا 1 & 2 في الصف 1
table->MergeCells(table->get_Rows()->idx_get(0)->idx_get(0), table->get_Rows()->idx_get(1)->idx_get(1), false);
// إضافة نص إلى الخلية المدمجة
table->get_Rows()->idx_get(0)->idx_get(0)->get_TextFrame()->set_Text(u"Merged Cells");
// حفظ PPTX إلى القرص
pres->Save(u"table.pptx", SaveFormat::Pptx);
```

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ITable](../../itable/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)