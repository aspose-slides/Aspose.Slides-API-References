---
title: GetEffective()
second_title: Aspose.Slides pro C++ API Reference
description: Získá efektivní vlastnosti formátování buněk tabulky s aplikovaným děděním a styly tabulky.
type: docs
weight: 118
url: /cs/aspose.slides/cellformat/geteffective/
---
## CellFormat::GetEffective() metoda


Získá efektivní vlastnosti formátování buněk tabulky s aplikovaným děděním a styly tabulky.

```cpp
System::SharedPtr<ICellFormatEffectiveData> Aspose::Slides::CellFormat::GetEffective() override
```


### Návratová hodnota

A [ICellFormatEffectiveData](../../icellformateffectivedata/).
## Poznámky



Tento příklad ukazuje získání efektivního formátu výplně pro různé logické části tabulky. Všimněte si, že formátování buňky má vždy vyšší prioritu než formátování řádku, řádek – vyšší než sloupec, sloupec – vyšší než celá tabulka. Nakonec se vlastnosti CellFormatEffectiveData vždy používají k vykreslení tabulky. Následující kód je pouze příkladem API. 
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
* Třída [ICellFormatEffectiveData](../../icellformateffectivedata/)
* Třída [CellFormat](../)
* Jmenný prostor [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)