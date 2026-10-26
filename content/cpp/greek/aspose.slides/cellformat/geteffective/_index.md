---
title: GetEffective()
second_title: Αναφορά API του Aspose.Slides για C++
description: Λαμβάνει τις αποτελεσματικές ιδιότητες μορφοποίησης κελιών πίνακα με κληρονομικότητα και εφαρμοσμένα στυλ πίνακα.
type: docs
weight: 118
url: /el/aspose.slides/cellformat/geteffective/
---
## CellFormat::GetEffective() μέθοδος

Επιστρέφει τις αποτελεσματικές ιδιότητες μορφοποίησης κελιών πίνακα με κληρονομικότητα και εφαρμοσμένα στυλ πίνακα.

```cpp
System::SharedPtr<ICellFormatEffectiveData> Aspose::Slides::CellFormat::GetEffective() override
```

### Τιμή Επιστροφής

A [ICellFormatEffectiveData](../../icellformateffectivedata/).

## Παρατηρήσεις

Αυτό το παράδειγμα δείχνει πώς να ληφθεί η αποτελεσματική μορφή γεμίσματος για διαφορετικά λογικά μέρη του πίνακα. Παρακαλούμε σημειώστε ότι η μορφοποίηση κελιών έχει πάντα μεγαλύτερη προτεραιότητα από τη μορφοποίηση γραμμής, η μορφοποίηση γραμμής έχει μεγαλύτερη προτεραιότητα από τη στήλη, η στήλη από όλο τον πίνακα. Έτσι, τελικά οι ιδιότητες CellFormatEffectiveData χρησιμοποιούνται πάντα για τη σχεδίαση του πίνακα. Ο παρακάτω κώδικας είναι μόνο ένα παράδειγμα του API. 
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
* Class [ICellFormatEffectiveData](../../icellformateffectivedata/)
* Class [CellFormat](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)