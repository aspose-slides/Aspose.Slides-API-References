---
title: GetSensitivityLabels()
second_title: Αναφορά API Aspose.Slides για C++
description: Αποκτά έναν πίνακα ετικετών ευαισθησίας από τις προσαρμοσμένες ιδιότητες του εγγράφου (Microsoft Information Protection SDK Metadata).
type: docs
weight: 872
url: /el/aspose.slides/idocumentproperties/getsensitivitylabels/
---
## IDocumentProperties::GetSensitivityLabels() method

Παίρνει έναν πίνακα ετικετών ευαισθησίας από τις προσαρμοσμένες ιδιότητες του εγγράφου (Microsoft Information Protection SDK Metadata).

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISensitivityLabel>> Aspose::Slides::IDocumentProperties::GetSensitivityLabels()=0
```

## Σχόλια

Ο παρακάτω κώδικας δείχνει πώς να μετακινήσετε τις πληροφορίες ετικετών ευαισθησίας από τις προσαρμοσμένες ιδιότητες του εγγράφου στη σύγχρονη συλλογή SensitivityLabels: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"SomePresentation.pptx");

// Λάβετε ετικέτες ευαισθησίας από τις προσαρμοσμένες ιδιότητες του εγγράφου
auto mipSensitivityLabels = pres->get_DocumentProperties()->GetSensitivityLabels();

auto sensitivityLabels = pres->get_SensitivityLabels();
for (auto&& sensitivityLabel : mipSensitivityLabels)
{
    // Προσθέστε την ετικέτα στη συλλογή
    // Εδώ μπορείτε να προσθέσετε έναν έλεγχο για την εγκυρότητα των πληροφοριών της ετικέτας (η ετικέτα είναι διαθέσιμη, κ.λπ.)
    sensitivityLabels->Add(sensitivityLabel);
}

pres->Save(u"SensitivityLabel.pptx", SaveFormat::Pptx);
```

## Δείτε επίσης

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [ISensitivityLabel](../../isensitivitylabel/)
* Κλάση [IDocumentProperties](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)