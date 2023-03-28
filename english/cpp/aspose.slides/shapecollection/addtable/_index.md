---
title: AddTable()
second_title: Aspose.Slides for C++ API Reference
description: Creates a new Table and adds it to the end of the collection.
type: docs
weight: 469
url: /cpp/aspose.slides/shapecollection/addtable/
---
## ShapeCollection::AddTable(**float**, **float**, [System::ArrayPtr](../../../system/arrayptr/)\<**double**\>, [System::ArrayPtr](../../../system/arrayptr/)\<**double**\>) method


Creates a new [Table](../../table/) and adds it to the end of the collection.

```cpp
System::SharedPtr<ITable> Aspose::Slides::ShapeCollection::AddTable(float x, float y, System::ArrayPtr<double> columnWidths, System::ArrayPtr<double> rowHeights) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | The X-coordinate for a left side of shape's frame. |
| y | **float** | The Y-coordinate for a top side of shape's frame. |
| columnWidths | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | Array of doubles which represents widths of columns in the table. |
| rowHeights | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | Array of doubles which represents heights of rows in the table. |

### Return Value

Created [Table](../../table/) object.
## Remarks



The following examples shows how to add table in PowerPoint [Presentation](../../presentation/). 
```cpp
// Instantiate Presentation class that represents PPTX file
auto pres = System::MakeObject<Presentation>();
// Access first slide
auto slide = pres->get_Slides()->idx_get(0);
// Define columns with widths and rows with heights
System::ArrayPtr<double> dblCols = System::MakeArray<double>({50, 50, 50});
System::ArrayPtr<double> dblRows = System::MakeArray<double>({50, 30, 30, 30, 30});
// Add table shape to slide
System::SharedPtr<ITable> table = slide->get_Shapes()->AddTable(100.0f, 50.0f, dblCols, dblRows);
// Set border format for each cell
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

// Merge cells 1 & 2 of row 1
table->MergeCells(table->get_Rows()->idx_get(0)->idx_get(0), table->get_Rows()->idx_get(1)->idx_get(1), false);
// Add text to the merged cell
table->get_Rows()->idx_get(0)->idx_get(0)->get_TextFrame()->set_Text(u"Merged Cells");
// Save PPTX to Disk
pres->Save(u"table.pptx", SaveFormat::Pptx);
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ITable](../../itable/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
