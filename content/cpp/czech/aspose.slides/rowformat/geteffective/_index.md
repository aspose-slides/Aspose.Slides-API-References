---
title: GetEffective()
second_title: Aspose.Slides pro C++ - reference API
description: Získá efektivní vlastnosti formátování řádků tabulky s aplikovaným děděním a styly tabulky.
type: docs
weight: 1
url: /cs/aspose.slides/rowformat/geteffective/
---
## RowFormat::GetEffective() metoda


Získá efektivní vlastnosti formátování řádků tabulky s aplikovaným děděním a styly tabulky.

```cpp
System::SharedPtr<IRowFormatEffectiveData> Aspose::Slides::RowFormat::GetEffective() override
```


### Návratová hodnota

Objekt [IRowFormatEffectiveData](../../irowformateffectivedata/).
## Poznámky



Tento příklad ukazuje získávání efektivního formátu výplně pro různé logické části tabulky. Všimněte si, že formátování buňky má vždy vyšší prioritu než formátování řádku, řádek – vyšší než sloupec, sloupec – vyšší než celá tabulka. Nakonec se vždy použijí vlastnosti CellFormatEffectiveData k vykreslení tabulky. Následující kód je pouze příkladem API. 
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
* Třída [IRowFormatEffectiveData](../../irowformateffectivedata/)
* Třída [RowFormat](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)