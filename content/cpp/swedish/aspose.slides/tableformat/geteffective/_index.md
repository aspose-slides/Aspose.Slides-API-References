---
title: GetEffective()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar effektiva tabellformateringsegenskaper med arv och tillämpade tabellstilar.
type: docs
weight: 40
url: /sv/aspose.slides/tableformat/geteffective/
---
## TableFormat::GetEffective() metod


Hämtar effektiva tabellformateringsegenskaper med arv och tillämpade tabellstilar.

```cpp
System::SharedPtr<ITableFormatEffectiveData> Aspose::Slides::TableFormat::GetEffective() override
```


### Returvärde

En [ITableFormatEffectiveData](../../itableformateffectivedata/).
## Anmärkningar



Det här exemplet demonstrerar hur man hämtar effektiv fyllningsformat för olika delar av tabellens logik. Observera att cellformatering alltid har högre prioritet än radformatering, rad - högre än kolumn, kolumn - högre än hela tabellen. Så slutligen används alltid CellFormatEffectiveData-egenskaperna för att rita tabellen. Följande kod är bara ett exempel på API. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto tbl = AsCast<Table>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto tableFillFormatEffective = tbl->get_TableFormat()->GetEffective()->get_FillFormat();
auto rowFillFormatEffective = tbl->get_Rows()->idx_get(0)->get_RowFormat()->GetEffective()->get_FillFormat();
auto columnFillFormatEffective = tbl->get_Columns()->idx_get(0)->get_ColumnFormat()->GetEffective()->get_FillFormat();
auto cellFillFormatEffective = tbl->idx_get(0, 0)->get_CellFormat()->GetEffective()->get_FillFormat();
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [ITableFormatEffectiveData](../../itableformateffectivedata/)
* Klass [TableFormat](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)