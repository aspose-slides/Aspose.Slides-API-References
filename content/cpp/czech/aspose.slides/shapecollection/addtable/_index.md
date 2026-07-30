---
title: AddTable()
second_title: Aspose.Slides pro referenci API C++
description: Vytvoří novou tabulku a přidá ji na konec kolekce tvarů.
type: docs
weight: 469
url: /cs/aspose.slides/shapecollection/addtable/
---
## ShapeCollection::AddTable(float, float, System::ArrayPtr\<double\>, System::ArrayPtr\<double\>) metoda


Vytvoří novou tabulku a přidá ji na konec kolekce tvarů.

```cpp
System::SharedPtr<ITable> Aspose::Slides::ShapeCollection::AddTable(float x, float y, System::ArrayPtr<double> columnWidths, System::ArrayPtr<double> rowHeights) override
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | X-souřadnice tabulky v bodech. |
| y | **float** | Y-souřadnice tabulky v bodech. |
| columnWidths | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | Pole typu double představující šířky sloupců tabulky v bodech. |
| rowHeights | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | Pole typu double představující výšky řádků tabulky v bodech. |

### Návratová hodnota

Nově vytvořený [ITable](../../itable/).
## Poznámky



Následující **příklad** ukazuje, jak přidat tabulku v PowerPointu [Presentation](../../presentation/). 
```cpp
// Vytvořte instanci třídy Presentation, která představuje soubor PPTX
auto pres = System::MakeObject<Presentation>();
// Získejte první snímek
auto slide = pres->get_Slides()->idx_get(0);
// Definujte sloupce se šířkami a řádky s výškami
System::ArrayPtr<double> dblCols = System::MakeArray<double>({50, 50, 50});
System::ArrayPtr<double> dblRows = System::MakeArray<double>({50, 30, 30, 30, 30});
// Přidejte tvar tabulky na snímek
System::SharedPtr<ITable> table = slide->get_Shapes()->AddTable(100.0f, 50.0f, dblCols, dblRows);
// Nastavte formát ohraničení pro každou buňku
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

// Sloučte buňky 1 a 2 řádku 1
table->MergeCells(table->get_Rows()->idx_get(0)->idx_get(0), table->get_Rows()->idx_get(1)->idx_get(1), false);
// Přidejte text do sloučené buňky
table->get_Rows()->idx_get(0)->idx_get(0)->get_TextFrame()->set_Text(u"Merged Cells");
// Uložte PPTX na disk
pres->Save(u"table.pptx", SaveFormat::Pptx);
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Třída [ITable](../../itable/)
* Třída [ShapeCollection](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)