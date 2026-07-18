---
title: GetEffective()
second_title: Aspose.Slides για την Αναφορά API C++
description: Λαμβάνει τις αποτελεσματικές ιδιότητες μορφοποίησης γραμμής πίνακα με κληρονομικότητα και εφαρμοσμένα στυλ πίνακα.
type: docs
weight: 1
url: /el/aspose.slides/rowformat/geteffective/
---
## RowFormat::GetEffective() μέθοδος

Λαμβάνει τις αποτελεσματικές ιδιότητες μορφοποίησης γραμμής πίνακα με κληρονομικότητα και εφαρμόζοντας στυλ πίνακα.

```cpp
System::SharedPtr<IRowFormatEffectiveData> Aspose::Slides::RowFormat::GetEffective() override
```

### Τιμή Επιστροφής

Ένα [IRowFormatEffectiveData](../../irowformateffectivedata/).
## Παρατηρήσεις

Αυτό το παράδειγμα δείχνει την απόκτηση του αποτελεσματικού μορφοτύπου γεμίσματος για διαφορετικά λογικά τμήματα του πίνακα. Παρακαλώ σημειώστε ότι η μορφοποίηση cell έχει πάντα υψηλότερη προτεραιότητα από τη μορφοποίηση row, η row – υψηλότερη από τη column, η column – υψηλότερη από ολόκληρο τον table. Έτσι τελικά οι ιδιότητες CellFormatEffectiveData χρησιμοποιούνται πάντα για τη σχεδίαση του πίνακα. Ο ακόλουθος κώδικας είναι μόνο ένα παράδειγμα του API. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto tbl = AsCast<Table>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto tableFillFormatEffective = tbl->get_TableFormat()->GetEffective()->get_FillFormat();
auto rowFillFormatEffective = tbl->get_Rows()->idx_get(0)->get_RowFormat()->GetEffective()->get_FillFormat();
auto columnFillFormatEffective = tbl->get_Columns()->idx_get(0)->get_ColumnFormat()->GetEffective()->get_FillFormat();
auto cellFillFormatEffective = tbl->idx_get(0, 0)->get_CellFormat()->GetEffective()->get_FillFormat();
// Έξοδος και σύγκριση
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IRowFormatEffectiveData](../../irowformateffectivedata/)
* Κλάση [RowFormat](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)