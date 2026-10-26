---
title: GetEffective()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar effektiva formateringsegenskaper för tabellceller med arv och tabellstilar tillämpade.
type: docs
weight: 118
url: /sv/aspose.slides/cellformat/geteffective/
---
## CellFormat::GetEffective() metod


Hämtar effektiva formateringsegenskaper för tabellceller med arv och tabellstilar tillämpade.

```cpp
System::SharedPtr<ICellFormatEffectiveData> Aspose::Slides::CellFormat::GetEffective() override
```


### Returvärde

En [ICellFormatEffectiveData](../../icellformateffectivedata/).
## Anmärkningar


Detta exempel visar hur man får den effektiva fyllningsformaten för olika delar av tabellens logik. Observera att cellformatering alltid har högre prioritet än radformatering, rad - högre än kolumn, kolumn - högre än hela tabellen. Så slutligen används alltid CellFormatEffectiveData-egenskaper för att rita tabellen. Följande kod är endast ett exempel på API.
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto tbl = AsCast<Table>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto tableFillFormatEffective = tbl->get_TableFormat()->GetEffective()->get_FillFormat();
auto rowFillFormatEffective = tbl->get_Rows()->idx_get(0)->get_RowFormat()->GetEffective()->get_FillFormat();
auto columnFillFormatEffective = tbl->get_Columns()->idx_get(0)->get_ColumnFormat()->GetEffective()->get_FillFormat();
auto cellFillFormatEffective = tbl->idx_get(0, 0)->get_CellFormat()->GetEffective()->get_FillFormat();
// Utdata och jämförelse
```

## Se även

* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Klass [ICellFormatEffectiveData](../../icellformateffectivedata/)
* Klass [CellFormat](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)