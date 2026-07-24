---
title: GetEffective()
second_title: Aspose.Slides für C++ API-Referenz
description: Ruft die wirksamen Tabellenspalten-Formatierungseigenschaften mit Vererbung und angewandten Tabellenstilen ab.
type: docs
weight: 1
url: /de/aspose.slides/columnformat/geteffective/
---
## ColumnFormat::GetEffective() Methode


Ruft die wirksamen Tabellenspalten-Formatierungseigenschaften mit Vererbung und angewandten Tabellenstilen ab.

```cpp
System::SharedPtr<IColumnFormatEffectiveData> Aspose::Slides::ColumnFormat::GetEffective() override
```


### Rückgabewert

A [IColumnFormatEffectiveData](../../icolumnformateffectivedata/).
## Hinweise



Dieses Beispiel zeigt, wie das wirksame Füllformat für verschiedene logische Tabellenteile ermittelt wird. Bitte beachten Sie, dass die Zellenformatierung immer eine höhere Priorität hat als die Zeilenformatierung, Zeilen - höher als Spalten, Spalten - höher als die gesamte Tabelle. Daher werden schließlich die Eigenschaften von CellFormatEffectiveData immer zum Zeichnen der Tabelle verwendet. Der folgende Code ist nur ein Beispiel für die API. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto tbl = AsCast<Table>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto tableFillFormatEffective = tbl->get_TableFormat()->GetEffective()->get_FillFormat();
auto rowFillFormatEffective = tbl->get_Rows()->idx_get(0)->get_RowFormat()->GetEffective()->get_FillFormat();
auto columnFillFormatEffective = tbl->get_Columns()->idx_get(0)->get_ColumnFormat()->GetEffective()->get_FillFormat();
auto cellFillFormatEffective = tbl->idx_get(0, 0)->get_CellFormat()->GetEffective()->get_FillFormat();
// Ausgabe und Vergleich
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IColumnFormatEffectiveData](../../icolumnformateffectivedata/)
* Klasse [ColumnFormat](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)