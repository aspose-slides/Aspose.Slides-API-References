---
title: get_ValidationFlags()
second_title: Aspose.Slides για C++ API Reference
description: "Επιστρέφει μια τιμή που υποδεικνύει τις ρυθμίσεις επαλήθευσης σχήματος. Αυτή η ρύθμιση εφαρμόζεται στα αντικείμενα XmlReader που επαληθεύουν σχήματα (η τιμή XmlReaderSettings::get_ValidationType είναι ValidationType::Schema)."
type: docs
weight: 378
url: /el/system.xml/xmlreadersettings/get_validationflags/
---
## XmlReaderSettings::get_ValidationFlags() μέθοδος

Επιστρέφει μια τιμή που υποδεικνύει τις ρυθμίσεις επαλήθευσης σχήματος. Αυτή η ρύθμιση εφαρμόζεται στα αντικείμενα [XmlReader](../../xmlreader/) που επαληθεύουν σχήματα (η τιμή [XmlReaderSettings::get_ValidationType](../get_validationtype/) είναι [ValidationType::Schema](../../validationtype/)).

```cpp
Schema::XmlSchemaValidationFlags System::Xml::XmlReaderSettings::get_ValidationFlags()
```

### Τιμή Επιστροφής

Μια συνδυαστική τιμή bitwise των τιμών της απαρίθμησης που καθορίζουν τις επιλογές επαλήθευσης. Τα XmlSchemaValidationFlags::ProcessIdentityConstraints και XmlSchemaValidationFlags::AllowXmlAttributes είναι ενεργοποιημένα από προεπιλογή. Τα XmlSchemaValidationFlags::ProcessInlineSchema, XmlSchemaValidationFlags::ProcessSchemaLocation και XmlSchemaValidationFlags::ReportValidationWarnings είναι απενεργοποιημένα από προεπιλογή.

## Δείτε επίσης

* Απαρίθμηση [XmlSchemaValidationFlags](../../../system.xml.schema/xmlschemavalidationflags/)
* Κλάση [XmlReaderSettings](../)
* Χώρος ονομάτων [System::Xml](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)