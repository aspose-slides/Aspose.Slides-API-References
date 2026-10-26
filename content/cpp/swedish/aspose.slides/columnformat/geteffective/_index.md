---
title: GetEffective()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar effektiva formateringsegenskaper för tabellkolumn med arv och tillämpade tabellstilar.
type: docs
weight: 1
url: /sv/aspose.slides/columnformat/geteffective/
---
## ColumnFormat::GetEffective() metod


Hämtar effektiva formateringsegenskaper för tabellkolumn med arv och tabellstilar tillämpade.

```cpp
System::SharedPtr<IColumnFormatEffectiveData> Aspose::Slides::ColumnFormat::GetEffective() override
```


### Returvärde

A [IColumnFormatEffectiveData](../../icolumnformateffectivedata/).
## Anmärkningar



Det här exemplet visar hur man hämtar effektiv fyllningsformat för olika tabelllogikdelar. Observera att cellformatering alltid har högre prioritet än radformatering, rad - högre än kolumn, kolumn - högre än hela tabellen. Så till slut används alltid CellFormatEffectiveData-egenskaper för att rita tabellen. Följande kod är bara ett exempel på API. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto tbl = AsCast<Table>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto tableFillFormatEffective = tbl->get_TableFormat()->GetEffective()->get_FillFormat();
auto rowFillFormatEffective = tbl->get_Rows()->idx_get(0)->get_RowFormat()->GetEffective()->get_FillFormat();
auto columnFillFormatEffective = tbl->get_Columns()->idx_get(0)->get_ColumnFormat()->GetEffective()->get_FillFormat();
auto cellFillFormatEffective = tbl->idx_get(0, 0)->get_CellFormat()->GetEffective()->get_FillFormat();
// Utskrift och jämförelse
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IColumnFormatEffectiveData](../../icolumnformateffectivedata/)
* Klass [ColumnFormat](../)
* Namnområde [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)