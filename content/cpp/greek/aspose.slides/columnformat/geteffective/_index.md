---
title: GetEffective()
second_title: Αναφορά API του Aspose.Slides για C++
description: Λαμβάνει τις αποτελεσματικές ιδιότητες μορφοποίησης στήλης πίνακα με κληρονομικότητα και εφαρμοσμένα στυλ πίνακα.
type: docs
weight: 1
url: /el/aspose.slides/columnformat/geteffective/
---
## ColumnFormat::GetEffective() μέθοδος


Λαμβάνει τις αποτελεσματικές ιδιότητες μορφοποίησης στήλης πίνακα με κληρονομικότητα και εφαρμόζονται στυλ πίνακα.

```cpp
System::SharedPtr<IColumnFormatEffectiveData> Aspose::Slides::ColumnFormat::GetEffective() override
```


### Τιμή Επιστροφής

Ένα [IColumnFormatEffectiveData](../../icolumnformateffectivedata/).
## Παρατηρήσεις



Αυτό το παράδειγμα δείχνει την λήψη της αποτελεσματικής μορφής γεμίσματος για διαφορετικά λογικά μέρη του πίνακα. Παρακαλώ σημειώστε ότι η μορφοποίηση κελιού έχει πάντα μεγαλύτερη προτεραιότητα από τη μορφοποίηση γραμμής, η γραμμή - μεγαλύτερη από τη στήλη, η στήλη - μεγαλύτερη από ολόκληρο τον πίνακα. Έτσι τελικά οι ιδιότητες CellFormatEffectiveData χρησιμοποιούνται πάντα για τη σχεδίαση του πίνακα. Ο παρακάτω κώδικας είναι μόνο ένα παράδειγμα του API. 
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
* Κλάση [IColumnFormatEffectiveData](../../icolumnformateffectivedata/)
* Κλάση [ColumnFormat](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)