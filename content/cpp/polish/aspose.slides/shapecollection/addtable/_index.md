---
title: AddTable()
second_title: Aspose.Slides - odniesienie API dla C++
description: Tworzy nową tabelę i dodaje ją na koniec kolekcji kształtów.
type: docs
weight: 469
url: /pl/aspose.slides/shapecollection/addtable/
---
## ShapeCollection::AddTable(float, float, System::ArrayPtr\<double\>, System::ArrayPtr\<double\>) metoda


Tworzy nową tabelę i dodaje ją na koniec kolekcji kształtów.

```cpp
System::SharedPtr<ITable> Aspose::Slides::ShapeCollection::AddTable(float x, float y, System::ArrayPtr<double> columnWidths, System::ArrayPtr<double> rowHeights) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| x | **float** | Współrzędna x tabeli, w punktach. |
| y | **float** | Współrzędna y tabeli, w punktach. |
| columnWidths | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | Tablica liczb zmiennoprzecinkowych reprezentująca szerokości kolumn tabeli\\u2019s, w punktach. |
| rowHeights | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | Tablica liczb zmiennoprzecinkowych reprezentująca wysokości wierszy tabeli\\u2019s, w punktach. |

### Wartość zwracana

Nowo utworzony [ITable](../../itable/).
## Uwagi



Poniższy przykład pokazuje, jak dodać tabelę w programie PowerPoint [Presentation](../../presentation/). 
```cpp
// Utwórz obiekt klasy Presentation reprezentujący plik PPTX
auto pres = System::MakeObject<Presentation>();
// Uzyskaj dostęp do pierwszego slajdu
auto slide = pres->get_Slides()->idx_get(0);
// Zdefiniuj kolumny z szerokościami i wiersze z wysokościami
System::ArrayPtr<double> dblCols = System::MakeArray<double>({50, 50, 50});
System::ArrayPtr<double> dblRows = System::MakeArray<double>({50, 30, 30, 30, 30});
// Dodaj kształt tabeli do slajdu
System::SharedPtr<ITable> table = slide->get_Shapes()->AddTable(100.0f, 50.0f, dblCols, dblRows);
// Ustaw format obramowania dla każdej komórki
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

// Scal komórki 1 i 2 w wierszu 1
table->MergeCells(table->get_Rows()->idx_get(0)->idx_get(0), table->get_Rows()->idx_get(1)->idx_get(1), false);
// Dodaj tekst do scalonej komórki
table->get_Rows()->idx_get(0)->idx_get(0)->get_TextFrame()->set_Text(u"Merged Cells");
// Zapisz PPTX na dysk
pres->Save(u"table.pptx", SaveFormat::Pptx);
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasa [ITable](../../itable/)
* Klasa [ShapeCollection](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)