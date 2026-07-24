---
title: GetEffective()
second_title: Aspose.Slides für C++ API Referenz
description: Liefert die wirksamen Tabellenzeilenformatierungseigenschaften unter Berücksichtigung von Vererbung und angewandten Tabellenstilen.
type: docs
weight: 1
url: /de/aspose.slides/rowformat/geteffective/
---
## RowFormat::GetEffective() Methode

Liefert die wirksamen Tabellenzeilenformatierungseigenschaften mit angewandter Vererbung und Tabellenstilen.

```cpp
System::SharedPtr<IRowFormatEffectiveData> Aspose::Slides::RowFormat::GetEffective() override
```

### Rückgabewert

Ein [IRowFormatEffectiveData](../../irowformateffectivedata/).

## Bemerkungen

Dieses Beispiel demonstriert das Abrufen des wirksamen Füllformats für verschiedene logische Tabellenteile. Bitte beachten Sie, dass die Zellformatierung immer höhere Priorität hat als die Zeilenformatierung, Zeilen höher als Spalten, Spalten höher als die gesamte Tabelle. Daher werden schließlich die Eigenschaften von CellFormatEffectiveData immer zum Zeichnen der Tabelle verwendet. Der folgende Code ist nur ein Beispiel für die API. 
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
* Klasse [IRowFormatEffectiveData](../../irowformateffectivedata/)
* Klasse [RowFormat](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)