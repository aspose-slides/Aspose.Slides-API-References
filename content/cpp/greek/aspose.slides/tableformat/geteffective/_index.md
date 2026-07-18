---
title: GetEffective()
second_title: Aspose.Slides για C++ Αναφορά API
description: Λαμβάνει τις αποτελεσματικές ιδιότητες μορφοποίησης πίνακα με κληρονομικότητα και εφαρμοσμένα στυλ πίνακα.
type: docs
weight: 40
url: /el/aspose.slides/tableformat/geteffective/
---
## TableFormat::GetEffective() μέθοδος

Λαμβάνει τις αποτελεσματικές ιδιότητες μορφοποίησης πίνακα με κληρονομικότητα και εφαρμοσμένα στυλ πίνακα.

```cpp
System::SharedPtr<ITableFormatEffectiveData> Aspose::Slides::TableFormat::GetEffective() override
```

### Τιμή Επιστροφής

Ένα [ITableFormatEffectiveData](../../itableformateffectivedata/).

## Σχόλια

Αυτό το παράδειγμα επιδεικνύει τη λήψη του αποτελεσματικού μορφώματος γεμίσματος για διαφορετικά λογικά μέρη του πίνακα. Παρακαλούμε σημειώστε ότι η μορφοποίηση κελιού έχει πάντα υψηλότερη προτεραιότητα από τη μορφοποίηση γραμμής, η μορφοποίηση γραμμής υψηλότερη από τη στήλη, η στήλη υψηλότερη από ολόκληρο τον πίνακα. Έτσι τελικά οι ιδιότητες του CellFormatEffectiveData χρησιμοποιούνται πάντα για τη σχεδίαση του πίνακα. Ο παρακάτω κώδικας είναι μόνο ένα παράδειγμα του API. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto tbl = AsCast<Table>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto tableFillFormatEffective = tbl->get_TableFormat()->GetEffective()->get_FillFormat();
auto rowFillFormatEffective = tbl->get_Rows()->idx_get(0)->get_RowFormat()->GetEffective()->get_FillFormat();
auto columnFillFormatEffective = tbl->get_Columns()->idx_get(0)->get_ColumnFormat()->GetEffective()->get_FillFormat();
auto cellFillFormatEffective = tbl->idx_get(0, 0)->get_CellFormat()->GetEffective()->get_FillFormat();
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [ITableFormatEffectiveData](../../itableformateffectivedata/)
* Κλάση [TableFormat](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)