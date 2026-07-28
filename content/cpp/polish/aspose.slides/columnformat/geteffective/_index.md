---
title: GetEffective()
second_title: Referencja API Aspose.Slides dla C++
description: Pobiera efektywne właściwości formatowania kolumny tabeli z uwzględnieniem dziedziczenia i zastosowanych stylów tabeli.
type: docs
weight: 1
url: /pl/aspose.slides/columnformat/geteffective/
---
## ColumnFormat::GetEffective() metoda

Pobiera efektywne właściwości formatowania kolumny tabeli z uwzględnieniem dziedziczenia i zastosowanych stylów tabeli.

```cpp
System::SharedPtr<IColumnFormatEffectiveData> Aspose::Slides::ColumnFormat::GetEffective() override
```

### Return Value

Obiekt [IColumnFormatEffectiveData](../../icolumnformateffectivedata/).

## Uwagi

Ten przykład demonstruje pobieranie efektywnego formatu wypełnienia dla różnych części logiki tabeli. Należy zauważyć, że formatowanie komórek zawsze ma wyższy priorytet niż formatowanie wierszy, formatowanie wierszy – wyższy niż kolumn, kolumn – wyższy niż cała tabela. W rezultacie właściwości CellFormatEffectiveData są zawsze używane do rysowania tabeli. Poniższy kod jest jedynie przykładem użycia API. 
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
* Klasa [IColumnFormatEffectiveData](../../icolumnformateffectivedata/)
* Klasa [ColumnFormat](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)