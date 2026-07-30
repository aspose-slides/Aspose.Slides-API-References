---
title: GetEffective()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Získá efektivní vlastnosti formátování sloupce tabulky s děděním a aplikovanými styly tabulky.
type: docs
weight: 1
url: /cs/aspose.slides/columnformat/geteffective/
---
## ColumnFormat::GetEffective() method


Získá efektivní formátování sloupce tabulky s děděním a aplikovanými styly tabulky.

```cpp
System::SharedPtr<IColumnFormatEffectiveData> Aspose::Slides::ColumnFormat::GetEffective() override
```


### Návratová hodnota

A [IColumnFormatEffectiveData](../../icolumnformateffectivedata/).
## Poznámky



Tento příklad demonstruje získání efektivního formátu výplně pro různé logické části tabulky. Všimněte si, že formátování buňky má vždy vyšší prioritu než formátování řádku, řádek – vyšší než sloupec, sloupec – vyšší než celá tabulka. Nakonec jsou vlastnosti CellFormatEffectiveData vždy použity k vykreslení tabulky. Následující kód je jen ukázkou API. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto tbl = AsCast<Table>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto tableFillFormatEffective = tbl->get_TableFormat()->GetEffective()->get_FillFormat();
auto rowFillFormatEffective = tbl->get_Rows()->idx_get(0)->get_RowFormat()->GetEffective()->get_FillFormat();
auto columnFillFormatEffective = tbl->get_Columns()->idx_get(0)->get_ColumnFormat()->GetEffective()->get_FillFormat();
auto cellFillFormatEffective = tbl->idx_get(0, 0)->get_CellFormat()->GetEffective()->get_FillFormat();
// Výstup a porovnání
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IColumnFormatEffectiveData](../../icolumnformateffectivedata/)
* Třída [ColumnFormat](../)
* Jmenný prostor [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)