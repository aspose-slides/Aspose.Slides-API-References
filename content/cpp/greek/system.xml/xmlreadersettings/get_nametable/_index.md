---
title: get_NameTable()
second_title: Aspose.Slides για C++ Αναφορά API
description: Επιστρέφει το XmlNameTable που χρησιμοποιείται για συγκρίσεις ατομικών συμβολοσειρών.
type: docs
weight: 1
url: /el/system.xml/xmlreadersettings/get_nametable/
---
## XmlReaderSettings::get_NameTable() μέθοδος

Επιστρέφει το [XmlNameTable](../../xmlnametable/) που χρησιμοποιείται για συγκρίσεις ατομικών συμβολοσειρών.

```cpp
SharedPtr<XmlNameTable> System::Xml::XmlReaderSettings::get_NameTable()
```

### Τιμή επιστροφής

Το [XmlNameTable](../../xmlnametable/) που αποθηκεύει όλες τις ατομικές συμβολοσειρές που χρησιμοποιούνται από όλες τις [XmlReader](../../xmlreader/) εμφανίσεις που δημιουργήθηκαν με αυτό το αντικείμενο [XmlReaderSettings](../). Η προεπιλογή είναι **nullptr**. Η δημιουργημένη [XmlReader](../../xmlreader/) εμφάνιση θα χρησιμοποιήσει ένα νέο κενό [NameTable](../../nametable/) εάν αυτή η τιμή είναι **nullptr**.

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [XmlNameTable](../../xmlnametable/)
* Κλάση [XmlReaderSettings](../)
* Χώρος ονομάτων [System::Xml](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)