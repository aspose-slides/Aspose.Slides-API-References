---
title: GetEffective()
second_title: Aspose.Slides for C++ API referenciája
description: Lekérdezi a hatékony táblacella formázási tulajdonságokat öröklődéssel és a táblastílusok alkalmazásával.
type: docs
weight: 118
url: /hu/aspose.slides/cellformat/geteffective/
---
## CellFormat::GetEffective() metódus


Lekérdezi a hatékony táblacellák formázási tulajdonságait öröklődéssel és a táblastílusok alkalmazásával.

```cpp
System::SharedPtr<ICellFormatEffectiveData> Aspose::Slides::CellFormat::GetEffective() override
```


### Visszatérési érték

A [ICellFormatEffectiveData](../../icellformateffectivedata/).
## Megjegyzések



Ez a példa bemutatja a hatékony kitöltési formátum lekérését a táblázat különböző logikai részeinél. Kérjük, vegye figyelembe, hogy a cellaformázás mindig magasabb prioritással bír, mint a sorformázás, a sor – magasabb, mint az oszlop, az oszlop – magasabb, mint az egész táblázat. Így végül a CellFormatEffectiveData tulajdonságait mindig a táblázat rajzolásához használják. Az alábbi kód csak egy API példát mutat. 
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
* Osztály [ICellFormatEffectiveData](../../icellformateffectivedata/)
* Osztály [CellFormat](../)
* Névterület [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)