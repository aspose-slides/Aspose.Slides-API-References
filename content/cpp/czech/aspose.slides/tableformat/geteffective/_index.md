---
title: GetEffective()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Získá účinné vlastnosti formátování tabulky s použitím dědičnosti a stylů tabulky.
type: docs
weight: 40
url: /cs/aspose.slides/tableformat/geteffective/
---
## TableFormat::GetEffective() metoda

Získá účinné vlastnosti formátování tabulky s použitím dědičnosti a stylů tabulky.

```cpp
System::SharedPtr<ITableFormatEffectiveData> Aspose::Slides::TableFormat::GetEffective() override
```

### Návratová hodnota

A [ITableFormatEffectiveData](../../itableformateffectivedata/).

## Poznámky

Tento příklad ukazuje získání účinného formátu výplně pro různé logické části tabulky. Všimněte si, že formátování buněk má vždy vyšší prioritu než formátování řádků, řádků – vyšší než sloupců, sloupců – vyšší než celé tabulky. Nakonec se vlastnosti CellFormatEffectiveData vždy používají k vykreslení tabulky. Následující kód je pouze příkladem API. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto tbl = AsCast<Table>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto tableFillFormatEffective = tbl->get_TableFormat()->GetEffective()->get_FillFormat();
auto rowFillFormatEffective = tbl->get_Rows()->idx_get(0)->get_RowFormat()->GetEffective()->get_FillFormat();
auto columnFillFormatEffective = tbl->get_Columns()->idx_get(0)->get_ColumnFormat()->GetEffective()->get_FillFormat();
auto cellFillFormatEffective = tbl->idx_get(0, 0)->get_CellFormat()->GetEffective()->get_FillFormat();
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [ITableFormatEffectiveData](../../itableformateffectivedata/)
* Třída [TableFormat](../)
* Jmenný prostor [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)