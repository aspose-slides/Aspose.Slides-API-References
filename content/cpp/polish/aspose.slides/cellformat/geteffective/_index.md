---
title: GetEffective()
second_title: Aspose.Slides dla C++ Odniesienie API
description: Pobiera efektywne właściwości formatowania komórek tabeli z uwzględnieniem dziedziczenia i zastosowanych stylów tabeli.
type: docs
weight: 118
url: /pl/aspose.slides/cellformat/geteffective/
---
## CellFormat::GetEffective() metoda

Pobiera efektywne właściwości formatowania komórek tabeli z uwzględnieniem dziedziczenia i zastosowanych stylów tabel.

```cpp
System::SharedPtr<ICellFormatEffectiveData> Aspose::Slides::CellFormat::GetEffective() override
```

### Wartość zwracana

Obiekt [ICellFormatEffectiveData](../../icellformateffectivedata/).

## Uwagi

Ten przykład demonstruje pobieranie efektywnego formatu wypełnienia dla różnych części logiki tabeli. Należy zauważyć, że formatowanie komórek zawsze ma wyższy priorytet niż formatowanie wierszy, wiersze – wyższy niż kolumny, kolumny – wyższy niż cała tabela. Dlatego ostatecznie właściwości CellFormatEffectiveData są zawsze używane do rysowania tabeli. Poniższy kod jest jedynie przykładem użycia API. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto tbl = AsCast<Table>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto tableFillFormatEffective = tbl->get_TableFormat()->GetEffective()->get_FillFormat();
auto rowFillFormatEffective = tbl->get_Rows()->idx_get(0)->get_RowFormat()->GetEffective()->get_FillFormat();
auto columnFillFormatEffective = tbl->get_Columns()->idx_get(0)->get_ColumnFormat()->GetEffective()->get_FillFormat();
auto cellFillFormatEffective = tbl->idx_get(0, 0)->get_CellFormat()->GetEffective()->get_FillFormat();
// Wyjście i porównanie
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [ICellFormatEffectiveData](../../icellformateffectivedata/)
* Klasa [CellFormat](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)