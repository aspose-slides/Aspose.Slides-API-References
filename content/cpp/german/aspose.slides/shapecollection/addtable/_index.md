---
title: AddTable()
second_title: Aspose.Slides für C++ API Referenz
description: Erstellt eine neue Tabelle und fügt sie am Ende der ShapeCollection hinzu.
type: docs
weight: 469
url: /de/aspose.slides/shapecollection/addtable/
---
## ShapeCollection::AddTable(float, float, System::ArrayPtr\<double\>, System::ArrayPtr\<double\>) Methode

Erstellt eine neue Tabelle und fügt sie am Ende der ShapeCollection hinzu.

```cpp
System::SharedPtr<ITable> Aspose::Slides::ShapeCollection::AddTable(float x, float y, System::ArrayPtr<double> columnWidths, System::ArrayPtr<double> rowHeights) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | **float** | Die x-Koordinate der Tabelle, in Punkten. |
| y | **float** | Die y-Koordinate der Tabelle, in Punkten. |
| columnWidths | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | Ein Array von double-Werten, das die Breiten der Tabellenspalten in Punkten darstellt. |
| rowHeights | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | Ein Array von double-Werten, das die Höhen der Tabellenzeilen in Punkten darstellt. |

### Rückgabewert

Das neu erstellte [ITable](../../itable/).
## Hinweise



Das folgende Beispiel zeigt, wie man in PowerPoint [Presentation](../../presentation/) eine Tabelle hinzufügt.
```cpp
// Instanzieren der Presentation-Klasse, die eine PPTX-Datei darstellt
auto pres = System::MakeObject<Presentation>();
// Greift auf die erste Folie zu
auto slide = pres->get_Slides()->idx_get(0);
// Definieren Sie Spalten mit Breiten und Zeilen mit Höhen
System::ArrayPtr<double> dblCols = System::MakeArray<double>({50, 50, 50});
System::ArrayPtr<double> dblRows = System::MakeArray<double>({50, 30, 30, 30, 30});
// Tabellenshape zur Folie hinzufügen
System::SharedPtr<ITable> table = slide->get_Shapes()->AddTable(100.0f, 50.0f, dblCols, dblRows);
// Setzt das Rahmenformat für jede Zelle
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

// Führt Zellen 1 und 2 der Zeile 1 zusammen
table->MergeCells(table->get_Rows()->idx_get(0)->idx_get(0), table->get_Rows()->idx_get(1)->idx_get(1), false);
// Text zur zusammengeführten Zelle hinzufügen
table->get_Rows()->idx_get(0)->idx_get(0)->get_TextFrame()->set_Text(u"Merged Cells");
// Speichert PPTX auf die Festplatte
pres->Save(u"table.pptx", SaveFormat::Pptx);
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ITable](../../itable/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)