---
title: AddTable()
second_title: Aspose.Slides C++ API referencia
description: Új táblát hoz létre, és a alakzatgyűjtemény végéhez adja hozzá.
type: docs
weight: 469
url: /hu/aspose.slides/shapecollection/addtable/
---
## ShapeCollection::AddTable(float, float, System::ArrayPtr\<double\>, System::ArrayPtr\<double\>) metódus


Új táblát hoz létre, és hozzáadja a alakzatgyűjtemény végéhez.

```cpp
System::SharedPtr<ITable> Aspose::Slides::ShapeCollection::AddTable(float x, float y, System::ArrayPtr<double> columnWidths, System::ArrayPtr<double> rowHeights) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | **float** | A tábla x-koordinátája pontban. |
| y | **float** | A tábla y-koordinátája pontban. |
| columnWidths | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | A tábla oszlopainak szélességét pontban megadó double típusú tömb. |
| rowHeights | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | A tábla sorainak magasságát pontban megadó double típusú tömb. |

### Visszatérési érték

Az újonnan létrehozott [ITable](../../itable/).
## Megjegyzés



A következő példák bemutatják, hogyan lehet táblát hozzáadni a PowerPoint [Presentation](../../presentation/)-ban. 
```cpp
// Példányosítja a PPTX fájlt képviselő Presentation osztályt
auto pres = System::MakeObject<Presentation>();
// Az első diát eléri
auto slide = pres->get_Slides()->idx_get(0);
// Meghatározza az oszlopok szélességét és a sorok magasságát
System::ArrayPtr<double> dblCols = System::MakeArray<double>({50, 50, 50});
System::ArrayPtr<double> dblRows = System::MakeArray<double>({50, 30, 30, 30, 30});
// Táblát alakzattá ad hozzá a diához
System::SharedPtr<ITable> table = slide->get_Shapes()->AddTable(100.0f, 50.0f, dblCols, dblRows);
// Beállítja a keret formátumát minden cellához
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

// Összevonja az 1. sor 1. és 2. celláját
table->MergeCells(table->get_Rows()->idx_get(0)->idx_get(0), table->get_Rows()->idx_get(1)->idx_get(1), false);
// Szöveget ad a összevont cellához
table->get_Rows()->idx_get(0)->idx_get(0)->get_TextFrame()->set_Text(u"Merged Cells");
// Elmenti a PPTX fájlt a lemezre
pres->Save(u"table.pptx", SaveFormat::Pptx);
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Osztály [ITable](../../itable/)
* Osztály [ShapeCollection](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)