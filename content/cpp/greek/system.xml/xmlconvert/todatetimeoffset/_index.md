---
title: ToDateTimeOffset()
second_title: Aspose.Slides για C++ API Αναφορά
description: Μετατρέπει τη δοθείσα String σε ένα ισοδύναμο DateTimeOffset.
type: docs
weight: 430
url: /el/system.xml/xmlconvert/todatetimeoffset/
---
## XmlConvert::ToDateTimeOffset(const String\&) μέθοδος


Μετατρέπει το παρεχόμενο [String](../../../system/string/) σε ένα ισοδύναμο [DateTimeOffset](../../../system/datetimeoffset/).

```cpp
static DateTimeOffset System::Xml::XmlConvert::ToDateTimeOffset(const String &s)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | Η συμβολοσειρά προς μετατροπή. Η συμβολοσειρά πρέπει να συμμορφώνεται με ένα υποσύνολο της Συστάσεως W3C για τον τύπο XML dateTime. Για περισσότερες πληροφορίες, δείτε την ενότητα [dateTime](https://www.w3.org/TR/xmlschema-2/#dateTime) του προτύπου XML [Schema](../../../system.xml.schema/). |

### Τιμή επιστροφής

Το ισοδύναμο [DateTimeOffset](../../../system/datetimeoffset/) της παρεχόμενης συμβολοσειράς.

## XmlConvert::ToDateTimeOffset(const String\&, const String\&) μέθοδος


Μετατρέπει το παρεχόμενο [String](../../../system/string/) σε ένα ισοδύναμο [DateTimeOffset](../../../system/datetimeoffset/).

```cpp
static DateTimeOffset System::Xml::XmlConvert::ToDateTimeOffset(const String &s, const String &format)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | Η συμβολοσειρά προς μετατροπή. |
| format | const [String](../../../system/string/)\& | Η μορφή από την οποία μετατρέπεται το **s**. Η παράμετρος format μπορεί να είναι οποιοδήποτε υποσύνολο της Συστάσεως W3C για τον τύπο XML dateTime. Για περισσότερες πληροφορίες, δείτε την ενότητα [dateTime](https://www.w3.org/TR/xmlschema-2/#dateTime) του προτύπου XML [Schema](../../../system.xml.schema/). Η συμβολοσειρά **s** επικυρώνεται έναντι αυτής της μορφής. |

### Τιμή επιστροφής

Το ισοδύναμο [DateTimeOffset](../../../system/datetimeoffset/) της παρεχόμενης συμβολοσειράς.

## XmlConvert::ToDateTimeOffset(const String\&, const ArrayPtr\<String\>\&) μέθοδος


Μετατρέπει το παρεχόμενο [String](../../../system/string/) σε ένα ισοδύναμο [DateTimeOffset](../../../system/datetimeoffset/).

```cpp
static DateTimeOffset System::Xml::XmlConvert::ToDateTimeOffset(const String &s, const ArrayPtr<String> &formats)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | Η συμβολοσειρά προς μετατροπή. |
| formats | const [ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\>\& | Ένας πίνακας μορφών από τις οποίες μπορεί να μετατραπεί το **s**. Κάθε μορφή στο **formats** μπορεί να είναι οποιοδήποτε υποσύνολο της Συστάσεως W3C για τον τύπο XML dateTime. Για περισσότερες πληροφορίες, δείτε την ενότητα [dateTime](https://www.w3.org/TR/xmlschema-2/#dateTime) του προτύπου XML [Schema](../../../system.xml.schema/). Η συμβολοσειρά **s** επικυρώνεται έναντι μιας από αυτές τις μορφές. |

### Τιμή επιστροφής

Το ισοδύναμο [DateTimeOffset](../../../system/datetimeoffset/) της παρεχόμενης συμβολοσειράς.

## Δείτε επίσης

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Κλάση [DateTimeOffset](../../../system/datetimeoffset/)
* Κλάση [String](../../../system/string/)
* Κλάση [XmlConvert](../)
* Χώρος ονομάτων [System::Xml](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)