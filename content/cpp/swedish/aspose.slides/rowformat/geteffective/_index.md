---
title: GetEffective()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar effektiva formateringsegenskaper för tabellrad med arv och tillämpade tabellstilar.
type: docs
weight: 1
url: /sv/aspose.slides/rowformat/geteffective/
---
## RowFormat::GetEffective() metod


Hämtar effektiva formateringsegenskaper för tabellrad med arv och tabellstilar tillämpade.

```cpp
System::SharedPtr<IRowFormatEffectiveData> Aspose::Slides::RowFormat::GetEffective() override
```


### Returvärde

En [IRowFormatEffectiveData](../../irowformateffectivedata/).
## Anmärkningar



Detta exempel demonstrerar hur man får effektiv fyllningsformat för olika tabellens logikdelar. Observera att cellformatering alltid har högre prioritet än radformatering, rad - högre än kolumn, kolumn - högre än hela tabellen. Så slutligen används alltid CellFormatEffectiveData-egenskaper för att rita tabellen. Följande kod är bara ett exempel på API. 
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

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IRowFormatEffectiveData](../../irowformateffectivedata/)
* Klass [RowFormat](../)
* Namnutrymme [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)