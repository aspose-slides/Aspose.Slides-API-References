---
title: GetEffective()
second_title: Aspose.Slides voor C++ API-referentie
description: Haalt de effectieve opmaak-eigenschappen van tabelcellen op met overerving en toegepaste tabelstijlen.
type: docs
weight: 118
url: /nl/aspose.slides/cellformat/geteffective/
---
## CellFormat::GetEffective() methode

Haalt de effectieve opmaak-eigenschappen van tabelcellen op met overerving en tabelstijlen toegepast.

```cpp
System::SharedPtr<ICellFormatEffectiveData> Aspose::Slides::CellFormat::GetEffective() override
```

### Retourwaarde

Een [ICellFormatEffectiveData](../../icellformateffectivedata/).

## Opmerkingen

Dit voorbeeld demonstreert het verkrijgen van het effectieve opvulformaat voor verschillende logische delen van de tabel. Merk op dat celopmaak altijd een hogere prioriteit heeft dan rijopmaak, rij - hoger dan kolom, kolom - hoger dan de hele tabel. Dus uiteindelijk worden de CellFormatEffectiveData-eigenschappen altijd gebruikt om de tabel te tekenen. De volgende code is slechts een voorbeeld van de API.
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto tbl = AsCast<Table>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto tableFillFormatEffective = tbl->get_TableFormat()->GetEffective()->get_FillFormat();
auto rowFillFormatEffective = tbl->get_Rows()->idx_get(0)->get_RowFormat()->GetEffective()->get_FillFormat();
auto columnFillFormatEffective = tbl->get_Columns()->idx_get(0)->get_ColumnFormat()->GetEffective()->get_FillFormat();
auto cellFillFormatEffective = tbl->idx_get(0, 0)->get_CellFormat()->GetEffective()->get_FillFormat();
// Uitvoer en vergelijking
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [ICellFormatEffectiveData](../../icellformateffectivedata/)
* Klasse [CellFormat](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)