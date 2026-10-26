---
title: GetEffective()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Pobiera efektywne właściwości formatowania tabeli z uwzględnieniem dziedziczenia i zastosowanych stylów tabeli.
type: docs
weight: 40
url: /pl/aspose.slides/tableformat/geteffective/
---
## TableFormat::GetEffective() method

Pobiera efektywne właściwości formatowania tabeli z uwzględnieniem dziedziczenia i zastosowanych stylów tabeli.

```cpp
System::SharedPtr<ITableFormatEffectiveData> Aspose::Slides::TableFormat::GetEffective() override
```

### Wartość zwracana

Obiekt [ITableFormatEffectiveData](../../itableformateffectivedata/).

## Uwagi

Ten przykład demonstruje pobieranie efektywnego formatu wypełnienia dla różnych części logiki tabeli. Należy zauważyć, że formatowanie komórek zawsze ma wyższy priorytet niż formatowanie wierszy, wierszy – wyższy niż kolumn, kolumn – wyższy niż cała tabela. Ostatecznie właściwości CellFormatEffectiveData są zawsze używane do rysowania tabeli. Poniższy kod jest jedynie przykładem API. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto tbl = AsCast<Table>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto tableFillFormatEffective = tbl->get_TableFormat()->GetEffective()->get_FillFormat();
auto rowFillFormatEffective = tbl->get_Rows()->idx_get(0)->get_RowFormat()->GetEffective()->get_FillFormat();
auto columnFillFormatEffective = tbl->get_Columns()->idx_get(0)->get_ColumnFormat()->GetEffective()->get_FillFormat();
auto cellFillFormatEffective = tbl->idx_get(0, 0)->get_CellFormat()->GetEffective()->get_FillFormat();
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [ITableFormatEffectiveData](../../itableformateffectivedata/)
* Klasa [TableFormat](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)