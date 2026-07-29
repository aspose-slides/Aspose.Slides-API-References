---
title: AddTable()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en ny tabell och lägger till den i slutet av shape-samlingen.
type: docs
weight: 469
url: /sv/aspose.slides/shapecollection/addtable/
---
## ShapeCollection::AddTable(float, float, System::ArrayPtr\<double\>, System::ArrayPtr\<double\>) metod

Skapar en ny tabell och lägger till den i slutet av shape-samlingen.

```cpp
System::SharedPtr<ITable> Aspose::Slides::ShapeCollection::AddTable(float x, float y, System::ArrayPtr<double> columnWidths, System::ArrayPtr<double> rowHeights) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | **float** | x-koordinaten för tabellen, i punkter. |
| y | **float** | y-koordinaten för tabellen, i punkter. |
| columnWidths | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | En array av double-värden som representerar bredden på tabellens kolumner, i punkter. |
| rowHeights | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | En array av double-värden som representerar höjden på tabellens rader, i punkter. |

### Returvärde

Den nyss skapade [ITable](../../itable/).

## Anmärkningar

Följande exempel visar hur man lägger till en tabell i PowerPoint [Presentation](../../presentation/).
```cpp
// Instansiera Presentation-klassen som representerar PPTX-filen
auto pres = System::MakeObject<Presentation>();
// Hämta första bilden
auto slide = pres->get_Slides()->idx_get(0);
// Definiera kolumner med bredder och rader med höjder
System::ArrayPtr<double> dblCols = System::MakeArray<double>({50, 50, 50});
System::ArrayPtr<double> dblRows = System::MakeArray<double>({50, 30, 30, 30, 30});
// Lägg till tabellform till bilden
System::SharedPtr<ITable> table = slide->get_Shapes()->AddTable(100.0f, 50.0f, dblCols, dblRows);
// Ange kantformat för varje cell
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

// Sammanfoga cellerna 1 och 2 i rad 1
table->MergeCells(table->get_Rows()->idx_get(0)->idx_get(0), table->get_Rows()->idx_get(1)->idx_get(1), false);
// Lägg till text i den sammanslagna cellen
table->get_Rows()->idx_get(0)->idx_get(0)->get_TextFrame()->set_Text(u"Merged Cells");
// Spara PPTX till disk
pres->Save(u"table.pptx", SaveFormat::Pptx);
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klass [ITable](../../itable/)
* Klass [ShapeCollection](../)
* Namnrymd [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)