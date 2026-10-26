---
title: GetEffective()
second_title: Aspose.Slides C++ API hivatkozás
description: Lekéri a hatékony táblasor formázási tulajdonságokat öröklődéssel és a táblastílusok alkalmazásával.
type: docs
weight: 1
url: /hu/aspose.slides/rowformat/geteffective/
---
## RowFormat::GetEffective() metódus


Lekéri a hatékony táblasor formázási tulajdonságokat öröklődéssel és a táblastílusok alkalmazásával.

```cpp
System::SharedPtr<IRowFormatEffectiveData> Aspose::Slides::RowFormat::GetEffective() override
```


### Visszatérési érték

A [IRowFormatEffectiveData](../../irowformateffectivedata/).
## Megjegyzések



Ez a példa bemutatja a hatékony kitöltés formátumának lekérését a táblázat különböző logikai részeinél. Kérjük, vegye figyelembe, hogy a cella formázás mindig nagyobb prioritással bír, mint a sor formázása, a sor nagyobb, mint az oszlop, az oszlop nagyobb, mint az egész táblázat. Így végül a CellFormatEffectiveData tulajdonságok mindig a táblázat kirajzolásához használatosak. A következő kód csak egy API-példa. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto tbl = AsCast<Table>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto tableFillFormatEffective = tbl->get_TableFormat()->GetEffective()->get_FillFormat();
auto rowFillFormatEffective = tbl->get_Rows()->idx_get(0)->get_RowFormat()->GetEffective()->get_FillFormat();
auto columnFillFormatEffective = tbl->get_Columns()->idx_get(0)->get_ColumnFormat()->GetEffective()->get_FillFormat();
auto cellFillFormatEffective = tbl->idx_get(0, 0)->get_CellFormat()->GetEffective()->get_FillFormat();
// Kimenet és összehasonlítás
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IRowFormatEffectiveData](../../irowformateffectivedata/)
* Osztály [RowFormat](../)
* Névterület [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)