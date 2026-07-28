---
title: GetEffective()
second_title: Aspose.Slides for C++ API Referencia
description: Lekéri a hatékony táblázatformázási tulajdonságokat öröklődéssel és táblastílusok alkalmazásával.
type: docs
weight: 40
url: /hu/aspose.slides/tableformat/geteffective/
---
## TableFormat::GetEffective() metódus


Lekéri a hatékony táblázatformázási tulajdonságokat öröklődéssel és táblastílusok alkalmazásával.

```cpp
System::SharedPtr<ITableFormatEffectiveData> Aspose::Slides::TableFormat::GetEffective() override
```


### Visszatérési érték

Egy [ITableFormatEffectiveData](../../itableformateffectivedata/).
## Megjegyzések



Ez a példa bemutatja a hatékony kitöltési formátum lekérését a táblázat különböző logikai részeire. Kérjük, vegye figyelembe, hogy a cella formázása mindig nagyobb prioritással bír, mint a sor formázása, a sor nagyobb, mint az oszlop, az oszlop nagyobb, mint az egész táblázat. Így végül a CellFormatEffectiveData tulajdonságait mindig a táblázat kirajzolásához használják. A következő kód csak egy API példa. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto tbl = AsCast<Table>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto tableFillFormatEffective = tbl->get_TableFormat()->GetEffective()->get_FillFormat();
auto rowFillFormatEffective = tbl->get_Rows()->idx_get(0)->get_RowFormat()->GetEffective()->get_FillFormat();
auto columnFillFormatEffective = tbl->get_Columns()->idx_get(0)->get_ColumnFormat()->GetEffective()->get_FillFormat();
auto cellFillFormatEffective = tbl->idx_get(0, 0)->get_CellFormat()->GetEffective()->get_FillFormat();
```

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [ITableFormatEffectiveData](../../itableformateffectivedata/)
* Osztály [TableFormat](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)