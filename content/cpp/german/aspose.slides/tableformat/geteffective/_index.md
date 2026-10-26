---
title: GetEffective()
second_title: Aspose.Slides für C++ API-Referenz
description: Ruft die wirksamen Tabellformatierungseigenschaften ab, wobei Vererbung und Tabellenvorlagen angewendet werden.
type: docs
weight: 40
url: /de/aspose.slides/tableformat/geteffective/
---
## TableFormat::GetEffective() Methode

Ruft die wirksamen Tabellformatierungseigenschaften ab, wobei Vererbung und Tabellenvorlagen angewendet werden.

```cpp
System::SharedPtr<ITableFormatEffectiveData> Aspose::Slides::TableFormat::GetEffective() override
```

### Rückgabewert

Ein [ITableFormatEffectiveData](../../itableformateffectivedata/).
## Bemerkungen

Dieses Beispiel zeigt, wie das wirksame Füllformat für verschiedene logische Tabellenteile abgerufen wird. Bitte beachten Sie, dass die Zellformatierung immer Vorrang vor der Zeilenformatierung hat, die Zeilenformatierung Vorrang vor der Spaltenformatierung hat und die Spaltenformatierung Vorrang vor der gesamten Tabelle hat. Daher werden letztlich die Eigenschaften von CellFormatEffectiveData immer zum Zeichnen der Tabelle verwendet. Der folgende Code ist lediglich ein API-Beispiel.
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto tbl = AsCast<Table>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto tableFillFormatEffective = tbl->get_TableFormat()->GetEffective()->get_FillFormat();
auto rowFillFormatEffective = tbl->get_Rows()->idx_get(0)->get_RowFormat()->GetEffective()->get_FillFormat();
auto columnFillFormatEffective = tbl->get_Columns()->idx_get(0)->get_ColumnFormat()->GetEffective()->get_FillFormat();
auto cellFillFormatEffective = tbl->idx_get(0, 0)->get_CellFormat()->GetEffective()->get_FillFormat();
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [ITableFormatEffectiveData](../../itableformateffectivedata/)
* Klasse [TableFormat](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)