---
title: GetEffective()
second_title: Aspose.Slides dla C++ - referencja API
description: Pobiera efektywne właściwości formatowania wiersza tabeli z uwzględnieniem dziedziczenia i zastosowanych stylów tabeli.
type: docs
weight: 1
url: /pl/aspose.slides/rowformat/geteffective/
---
## RowFormat::GetEffective() metoda


Pobiera efektywne właściwości formatowania wiersza tabeli z uwzględnieniem dziedziczenia i zastosowanych stylów tabeli.

```cpp
System::SharedPtr<IRowFormatEffectiveData> Aspose::Slides::RowFormat::GetEffective() override
```


### Wartość zwracana

Obiekt [IRowFormatEffectiveData](../../irowformateffectivedata/).
## Uwagi



Ten przykład demonstruje pobieranie efektywnego formatu wypełnienia dla różnych części logiki tabeli. Należy zauważyć, że formatowanie komórek zawsze ma wyższy priorytet niż formatowanie wierszy, wiersz - wyższy niż kolumna, kolumna - wyższy niż cała tabela. Dlatego ostatecznie właściwości CellFormatEffectiveData są zawsze używane do rysowania tabeli. Poniższy kod jest jedynie przykładem API. 
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
* Class [IRowFormatEffectiveData](../../irowformateffectivedata/)
* Class [RowFormat](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)