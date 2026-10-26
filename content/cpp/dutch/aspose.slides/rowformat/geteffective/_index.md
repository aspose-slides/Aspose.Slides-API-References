---
title: GetEffective()
second_title: Aspose.Slides voor C++ API-referentie
description: Haalt de effectieve tabelrij-opmaakeigenschappen op met erfelijkheid en toegepaste tabelstijlen.
type: docs
weight: 1
url: /nl/aspose.slides/rowformat/geteffective/
---
## RowFormat::GetEffective() methode


Haalt de effectieve tabelrij-opmaakeigenschappen op met erfelijkheid en toegepaste tabelstijlen.

```cpp
System::SharedPtr<IRowFormatEffectiveData> Aspose::Slides::RowFormat::GetEffective() override
```


### Retourwaarde

A [IRowFormatEffectiveData](../../irowformateffectivedata/).
## Opmerkingen



Dit voorbeeld laat zien hoe de effectieve opvullingsindeling wordt verkregen voor verschillende logische delen van de tabel. Houd er rekening mee dat celopmaak altijd een hogere prioriteit heeft dan rij-opmaak, rij hoger dan kolom, kolom hoger dan de gehele tabel. Uiteindelijk worden de eigenschappen van CellFormatEffectiveData altijd gebruikt om de tabel te tekenen. De volgende code is slechts een voorbeeld van de API. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto tbl = AsCast<Table>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto tableFillFormatEffective = tbl->get_TableFormat()->GetEffective()->get_FillFormat();
auto rowFillFormatEffective = tbl->get_Rows()->idx_get(0)->get_RowFormat()->GetEffective()->get_FillFormat();
auto columnFillFormatEffective = tbl->get_Columns()->idx_get(0)->get_ColumnFormat()->GetEffective()->get_FillFormat();
auto cellFillFormatEffective = tbl->idx_get(0, 0)->get_CellFormat()->GetEffective()->get_FillFormat();
// Output and comparison
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IRowFormatEffectiveData](../../irowformateffectivedata/)
* Klasse [RowFormat](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)