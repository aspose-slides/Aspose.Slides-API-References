---
title: GetDateTimeFormats()
second_title: Aspose.Slides για C++ – Αναφορά API
description: Επιστρέφει έναν πίνακα συμβολοσειρών όπου κάθε στοιχείο είναι η συμβολοσειρά που αντιπροσωπεύει το τρέχον αντικείμενο μορφοποιημένο με έναν από τους τυπικούς προσδιοριστές μορφής ημερομηνίας και ώρας.
type: docs
weight: 547
url: /el/system/datetime/getdatetimeformats/
---
## DateTime::GetDateTimeFormats() const μέθοδος


Επιστρέφει έναν πίνακα συμβολοσειρών όπου κάθε στοιχείο είναι η αναπαράσταση συμβολοσειράς του τρέχοντος αντικειμένου μορφοποιημένη με έναν από τους τυπικούς προσδιοριστές μορφής ημερομηνίας και ώρας.

```cpp
ArrayPtr<String> System::DateTime::GetDateTimeFormats() const
```

## DateTime::GetDateTimeFormats(char_t) const μέθοδος


Επιστρέφει έναν πίνακα συμβολοσειρών όπου κάθε στοιχείο είναι η αναπαράσταση συμβολοσειράς του τρέχοντος αντικειμένου μορφοποιημένη με τον καθορισμένο τυπικό προσδιοριστή μορφής ημερομηνίας και ώρας.

```cpp
ArrayPtr<String> System::DateTime::GetDateTimeFormats(char_t format) const
```


### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| format | char_t | Τυπικός προσδιοριστής μορφής ημερομηνίας και ώρας. |

## DateTime::GetDateTimeFormats(const SharedPtr\<IFormatProvider\>\&) const μέθοδος


Επιστρέφει έναν πίνακα συμβολοσειρών όπου κάθε στοιχείο είναι η αναπαράσταση συμβολοσειράς του τρέχοντος αντικειμένου μορφοποιημένη με έναν από τους τυπικούς προσδιοριστές μορφής ημερομηνίας και ώρας και τον καθορισμένο πάροχο μορφής.

```cpp
ArrayPtr<String> System::DateTime::GetDateTimeFormats(const SharedPtr<IFormatProvider> &provider) const
```


### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Πάροχος μορφής. |

## DateTime::GetDateTimeFormats(char_t, const SharedPtr\<IFormatProvider\>\&) const μέθοδος


Επιστρέφει έναν πίνακα συμβολοσειρών όπου κάθε στοιχείο είναι η αναπαράσταση συμβολοσειράς του τρέχοντος αντικειμένου μορφοποιημένη με τον καθορισμένο τυπικό προσδιοριστή μορφής ημερομηνίας και ώρας και τον καθορισμένο πάροχο μορφής.

```cpp
ArrayPtr<String> System::DateTime::GetDateTimeFormats(char_t format, const SharedPtr<IFormatProvider> &provider) const
```


### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| format | char_t | Τυπικός προσδιοριστής μορφής ημερομηνίας και ώρας. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Πάροχος μορφής. |

## Δείτε επίσης

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Κλάση [String](../../string/)
* Κλάση [DateTime](../)
* Κλάση [IFormatProvider](../../iformatprovider/)
* Χώρος ονομάτων [System](../../)
* Library [Aspose.Slides](../../../)