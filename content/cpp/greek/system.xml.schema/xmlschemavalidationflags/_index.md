---
title: XmlSchemaValidationFlags
second_title: Aspose.Slides για C++ Αναφορά API
description: Καθορίζει τις επιλογές επικύρωσης σχήματος που χρησιμοποιούνται από τις κλάσεις XmlSchemaValidator και XmlReader.
type: docs
weight: 1054
url: /el/system.xml.schema/xmlschemavalidationflags/
---
## XmlSchemaValidationFlags enum

Καθορίζει τις επιλογές επικύρωσης σχήματος που χρησιμοποιούνται από τις κλάσεις [XmlSchemaValidator](../xmlschemavalidator/) και [XmlReader](../../system.xml/xmlreader/).

```cpp
enum class XmlSchemaValidationFlags
```

### Τιμές

| Όνομα | Τιμή | Περιγραφή |
| --- | --- | --- |
| None | 0 | Να μην επεξεργαστεί περιορισμούς ταυτότητας, ενσωματωμένα σχήματα, ενδείξεις θέσης σχήματος ή να αναφέρει προειδοποιήσεις επικύρωσης σχήματος. |
| ProcessInlineSchema | 1 | Επεξεργασία ενσωματωμένων σχημάτων που εντοπίζονται κατά την επικύρωση. |
| ProcessSchemaLocation | 2 | Επεξεργασία ενδείξεων θέσης σχήματος (**xsi:schemaLocation**, **xsi:noNamespaceSchemaLocation**) που εντοπίζονται κατά την επικύρωση. |
| ReportValidationWarnings | 4 | Αναφορά προειδοποιήσεων επικύρωσης σχήματος που εντοπίζονται κατά την επικύρωση. |
| ProcessIdentityConstraints | 8 | Επεξεργασία περιορισμών ταυτότητας (**xs:ID**, **xs:IDREF**, **xs:key**, **xs:keyref**, **xs:unique**) που εντοπίζονται κατά την επικύρωση. |
| AllowXmlAttributes | 16 | Να επιτραπεί η χρήση χαρακτηριστικών xml:* ακόμη και αν δεν ορίζονται στο σχήμα. Τα χαρακτηριστικά θα επικυρώνονται βάσει του τύπου δεδομένων τους. |

## Δείτε επίσης

* Χώρος ονομάτων [System::Xml::Schema](../)
* Βιβλιοθήκη [Aspose.Slides](../../)