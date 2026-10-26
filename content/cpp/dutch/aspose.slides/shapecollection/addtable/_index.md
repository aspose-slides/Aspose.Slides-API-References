---
title: AddTable()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt een nieuwe tabel aan en voegt deze toe aan het einde van de shape-collectie.
type: docs
weight: 469
url: /nl/aspose.slides/shapecollection/addtable/
---
## ShapeCollection::AddTable(float, float, System::ArrayPtr\<double\>, System::ArrayPtr\<double\>) methode


Maakt een nieuwe tabel aan en voegt deze toe aan het einde van de shape-collectie.

```cpp
System::SharedPtr<ITable> Aspose::Slides::ShapeCollection::AddTable(float x, float y, System::ArrayPtr<double> columnWidths, System::ArrayPtr<double> rowHeights) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | **float** | De x-coördinaat van de tabel, in punten. |
| y | **float** | De y-coördinaat van de tabel, in punten. |
| columnWidths | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | Een array van doubles die de breedtes van de kolommen van de tabel vertegenwoordigt, in punten. |
| rowHeights | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | Een array van doubles die de hoogtes van de rijen van de tabel vertegenwoordigt, in punten. |

### Retourwaarde

De nieuw aangemaakte [ITable](../../itable/).
## Opmerkingen



De volgende voorbeelden laten zien hoe je een tabel toevoegt in PowerPoint [Presentation](../../presentation/). 
```cpp
// Instantieer Presentation-klasse die PPTX-bestand vertegenwoordigt
auto pres = System::MakeObject<Presentation>();
// Toegang tot eerste dia
auto slide = pres->get_Slides()->idx_get(0);
// Definieer kolommen met breedtes en rijen met hoogtes
System::ArrayPtr<double> dblCols = System::MakeArray<double>({50, 50, 50});
System::ArrayPtr<double> dblRows = System::MakeArray<double>({50, 30, 30, 30, 30});
// Voeg tabelvorm toe aan dia
System::SharedPtr<ITable> table = slide->get_Shapes()->AddTable(100.0f, 50.0f, dblCols, dblRows);
// Stel randformaat in voor elke cel
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

// Voeg cellen 1 en 2 van rij 1 samen
table->MergeCells(table->get_Rows()->idx_get(0)->idx_get(0), table->get_Rows()->idx_get(1)->idx_get(1), false);
// Voeg tekst toe aan de samengevoegde cel
table->get_Rows()->idx_get(0)->idx_get(0)->get_TextFrame()->set_Text(u"Merged Cells");
// Sla PPTX op naar schijf
pres->Save(u"table.pptx", SaveFormat::Pptx);
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [ITable](../../itable/)
* Klasse [ShapeCollection](../)
* Naamruimte [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)