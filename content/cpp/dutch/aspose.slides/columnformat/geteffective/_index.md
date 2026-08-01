---
title: GetEffective()
second_title: Aspose.Slides voor C++ API-referentie
description: Haalt de effectieve opmaak-eigenschappen van een tabelkolom op met erfelijkheid en toegepaste tabelstijlen.
type: docs
weight: 1
url: /nl/aspose.slides/columnformat/geteffective/
---
## ColumnFormat::GetEffective() methode

Haalt de effectieve opmaak-eigenschappen van een tabelkolom op met erfelijkheid en toegepaste tabelstijlen.

```cpp
System::SharedPtr<IColumnFormatEffectiveData> Aspose::Slides::ColumnFormat::GetEffective() override
```

### Retourwaarde

Een [IColumnFormatEffectiveData](../../icolumnformateffectivedata/).

## Opmerkingen

Dit voorbeeld laat zien hoe het effectieve opvulformaat voor verschillende logische delen van een tabel wordt verkregen. Houd er rekening mee dat celopmaak altijd een hogere prioriteit heeft dan rij-opmaak, rij hoger dan kolom, kolom hoger dan de volledige tabel. Uiteindelijk worden de CellFormatEffectiveData-eigenschappen altijd gebruikt om de tabel te tekenen. De volgende code is slechts een voorbeeld van de API. 
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
* Klasse [IColumnFormatEffectiveData](../../icolumnformateffectivedata/)
* Klasse [ColumnFormat](../)
* Namespace [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)