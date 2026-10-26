---
title: GetEffective()
second_title: Aspose.Slides C++ API-referencia
description: Lekéri a hatékony táblázat oszlopformázási tulajdonságokat, figyelembe véve az öröklődést és a táblázatstílusok alkalmazását.
type: docs
weight: 1
url: /hu/aspose.slides/columnformat/geteffective/
---
## ColumnFormat::GetEffective() metódus

Lekéri a táblázat oszlopformázási tulajdonságait, figyelembe véve az öröklődést és a táblázatstílusok alkalmazását.

```cpp
System::SharedPtr<IColumnFormatEffectiveData> Aspose::Slides::ColumnFormat::GetEffective() override
```

### Visszatérési érték

A [IColumnFormatEffectiveData](../../icolumnformateffectivedata/).

## Megjegyzés

Ez a példa bemutatja, hogyan lehet lekérni a hatékony kitöltési formátumot a táblázat különböző logikai részeire. Kérjük, vegye figyelembe, hogy a cellaformázás mindig magasabb prioritással bír, mint a sorformázás, a sor magasabb, mint az oszlop, az oszlop pedig magasabb, mint az egész táblázat. Így végül a CellFormatEffectiveData tulajdonságait használják a táblázat megjelenítéséhez. A következő kód csak egy API-példa.
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
* Osztály [IColumnFormatEffectiveData](../../icolumnformateffectivedata/)
* Osztály [ColumnFormat](../)
* Névtér [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)