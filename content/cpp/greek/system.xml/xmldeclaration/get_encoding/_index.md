---
title: get_Encoding()
second_title: Aspose.Slides για την Αναφορά API C++
description: Επιστρέφει το επίπεδο κωδικοποίησης του εγγράφου XML.
type: docs
weight: 14
url: /el/system.xml/xmldeclaration/get_encoding/
---
## XmlDeclaration::get_Encoding() μέθοδος

Επιστρέφει το επίπεδο κωδικοποίησης του εγγράφου XML.

```cpp
String System::Xml::XmlDeclaration::get_Encoding()
```

### Τιμή Επιστροφής

Το έγκυρο όνομα κωδικοποίησης χαρακτήρων.

## Παρατηρήσεις

Τα πιο συχνά υποστηριζόμενα ονόματα κωδικοποίησης χαρακτήρων για XML είναι τα ακόλουθα:

| Κατηγορία | Ονόματα κωδικοποίησης |
| --- | --- |
| Unicode | UTF-8, UTF-16 |
| ISO 10646 | ISO-10646-UCS-2, ISO-10646-UCS-4 |
| ISO 8859 | ISO-8859-n (where "n" is a digit from 1 to 9) |
| JIS X-0208-1997 | ISO-2022-JP, Shift_JIS, EUC-JP |

Αυτή η τιμή είναι προαιρετική. Αν δεν έχει οριστεί τιμή, αυτή η μέθοδος επιστρέφει [String::Empty](../../../system/string/empty/). Αν δεν περιλαμβάνεται χαρακτηριστικό κωδικοποίησης, θεωρείται κωδικοποίηση UTF-8 όταν το έγγραφο γράφεται ή αποθηκεύεται.

## Δείτε επίσης

* Κλάση [String](../../../system/string/)
* Κλάση [XmlDeclaration](../)
* Χώρος ονομάτων [System::Xml](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)