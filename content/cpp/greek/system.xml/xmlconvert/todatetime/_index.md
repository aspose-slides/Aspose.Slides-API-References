---
title: ToDateTime()
second_title: Aspose.Slides για C++ API Αναφορά
description: Μετατρέπει το String σε ένα ισοδύναμο DateTime.
type: docs
weight: 417
url: /el/system.xml/xmlconvert/todatetime/
---
## XmlConvert::ToDateTime(const String\&) μέθοδος

Μετατρέπει το [String](../../../system/string/) σε ένα ισοδύναμο [DateTime](../../../system/datetime/).

```cpp
static DateTime System::Xml::XmlConvert::ToDateTime(const String &s)
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | Η συμβολοσειρά για μετατροπή. |

### Τιμή επιστροφής

Ένα ισοδύναμο [DateTime](../../../system/datetime/) της συμβολοσειράς.

## XmlConvert::ToDateTime(const String\&, const String\&) μέθοδος

Μετατρέπει το [String](../../../system/string/) σε ένα ισοδύναμο [DateTime](../../../system/datetime/).

```cpp
static DateTime System::Xml::XmlConvert::ToDateTime(const String &s, const String &format)
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | Η συμβολοσειρά για μετατροπή. |
| format | const [String](../../../system/string/)\& | Η δομή μορφής που θα εφαρμοστεί στο μετατρεπόμενο [DateTime](../../../system/datetime/). Έγκυρες μορφές περιλαμβάνουν "yyyy-MM-ddTHH:mm:sszzzzzz" και τα υποσύνολά της. Η συμβολοσειρά επαληθεύεται έναντι αυτής της μορφής. |

### Τιμή επιστροφής

Ένα ισοδύναμο [DateTime](../../../system/datetime/) της συμβολοσειράς.

## XmlConvert::ToDateTime(const String\&, const ArrayPtr\<String\>\&) μέθοδος

Μετατρέπει το [String](../../../system/string/) σε ένα ισοδύναμο [DateTime](../../../system/datetime/).

```cpp
static DateTime System::Xml::XmlConvert::ToDateTime(const String &s, const ArrayPtr<String> &formats)
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | Η συμβολοσειρά για μετατροπή. |
| formats | const [ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\>\& | Ένας πίνακας που περιέχει τις δομές μορφής που θα εφαρμοστούν στο μετατρεπόμενο [DateTime](../../../system/datetime/). Έγκυρες μορφές περιλαμβάνουν "yyyy-MM-ddTHH:mm:sszzzzzz" και τα υποσύνολά της. |

### Τιμή επιστροφής

Ένα ισοδύναμο [DateTime](../../../system/datetime/) της συμβολοσειράς.

## XmlConvert::ToDateTime(const String\&, XmlDateTimeSerializationMode) μέθοδος

Μετατρέπει το [String](../../../system/string/) σε ένα [DateTime](../../../system/datetime/) χρησιμοποιώντας το καθορισμένο XmlDateTimeSerializationMode.

```cpp
static DateTime System::Xml::XmlConvert::ToDateTime(const String &s, XmlDateTimeSerializationMode dateTimeOption)
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | Η [String](../../../system/string/) τιμή για μετατροπή. |
| dateTimeOption | [XmlDateTimeSerializationMode](../../xmldatetimeserializationmode/) | Μία από τις τιμές της απαρίθμησης που καθορίζει εάν η ημερομηνία πρέπει να μετατραπεί σε τοπική ώρα ή να διατηρηθεί ως Συντονισμένος Παγκόσμιος Χρόνος (UTC), εάν είναι ημερομηνία UTC. |

### Τιμή επιστροφής

Ένα ισοδύναμο [DateTime](../../../system/datetime/) του [String](../../../system/string/).

## Δείτε επίσης

* Απαρίθμηση [XmlDateTimeSerializationMode](../../xmldatetimeserializationmode/)
* Τύπος [ArrayPtr](../../../system/arrayptr/)
* Κλάση [DateTime](../../../system/datetime/)
* Κλάση [String](../../../system/string/)
* Κλάση [XmlConvert](../)
* Χώρος ονομάτων [System::Xml](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)