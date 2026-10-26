---
title: AddTable()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat tabel baru dan menambahkannya ke akhir koleksi shape.
type: docs
weight: 469
url: /id/aspose.slides/shapecollection/addtable/
---
## ShapeCollection::AddTable(float, float, System::ArrayPtr\<double\>, System::ArrayPtr\<double\>) method

Creates a new table and adds it to the end of the shape collection.

```cpp
System::SharedPtr<ITable> Aspose::Slides::ShapeCollection::AddTable(float x, float y, System::ArrayPtr<double> columnWidths, System::ArrayPtr<double> rowHeights) override
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | Koordinat x tabel, dalam poin. |
| y | **float** | Koordinat y tabel, dalam poin. |
| columnWidths | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | Array double yang mewakili lebar kolom tabel, dalam poin. |
| rowHeights | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | Array double yang mewakili tinggi baris tabel, dalam poin. |

### Return Value

[ITable](../../itable/) yang baru dibuat.
## Remarks

Contoh berikut menunjukkan cara menambahkan tabel dalam PowerPoint [Presentation](../../presentation/).
```cpp
// Membuat instance kelas Presentation yang mewakili file PPTX
auto pres = System::MakeObject<Presentation>();
// Mengakses slide pertama
auto slide = pres->get_Slides()->idx_get(0);
// Mendefinisikan kolom dengan lebar dan baris dengan tinggi
System::ArrayPtr<double> dblCols = System::MakeArray<double>({50, 50, 50});
System::ArrayPtr<double> dblRows = System::MakeArray<double>({50, 30, 30, 30, 30});
// Menambahkan bentuk tabel ke slide
System::SharedPtr<ITable> table = slide->get_Shapes()->AddTable(100.0f, 50.0f, dblCols, dblRows);
// Mengatur format border untuk setiap sel
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

// Menggabungkan sel 1 & 2 pada baris 1
table->MergeCells(table->get_Rows()->idx_get(0)->idx_get(0), table->get_Rows()->idx_get(1)->idx_get(1), false);
// Menambahkan teks ke sel yang digabungkan
table->get_Rows()->idx_get(0)->idx_get(0)->get_TextFrame()->set_Text(u"Merged Cells");
// Menyimpan PPTX ke Disk
pres->Save(u"table.pptx", SaveFormat::Pptx);
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ITable](../../itable/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)