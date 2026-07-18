---
title: ValidateEndElement()
second_title: Aspose.Slides για C++ API Αναφορά
description: Επιβεβαιώνει εάν το κειμενικό περιεχόμενο του στοιχείου είναι έγκυρο σύμφωνα με τον τύπο δεδομένων του για στοιχεία με απλό περιεχόμενο, και επιβεβαιώνει εάν το περιεχόμενο του τρέχοντος στοιχείου είναι πλήρες για στοιχεία με σύνθετο περιεχόμενο.
type: docs
weight: 209
url: /el/system.xml.schema/xmlschemavalidator/validateendelement/
---
## XmlSchemaValidator::ValidateEndElement(const SharedPtr\<XmlSchemaInfo\>\&) μέθοδος

Επαληθεύει εάν το κείμενο του στοιχείου είναι έγκυρο σύμφωνα με τον τύπο δεδομένων του για στοιχεία με απλό περιεχόμενο, και επαληθεύει εάν το περιεχόμενο του τρέχοντος στοιχείου είναι πλήρες για στοιχεία με σύνθετο περιεχόμενο.

```cpp
SharedPtr<Object> System::Xml::Schema::XmlSchemaValidator::ValidateEndElement(const SharedPtr<XmlSchemaInfo> &schemaInfo)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | Ένα αντικείμενο [XmlSchemaInfo](../../xmlschemainfo/) του οποίου οι ιδιότητες ορίζονται μετά από επιτυχημένη επικύρωση του στοιχείου. Αυτή η παράμετρος μπορεί να είναι **nullptr**. |

### Τιμή Επιστροφής

Η αναλυμένη, τυποποιημένη τιμή κειμένου του στοιχείου εάν το στοιχείο έχει απλό περιεχόμενο.

## XmlSchemaValidator::ValidateEndElement(const SharedPtr\<XmlSchemaInfo\>\&, const SharedPtr\<Object\>\&) μέθοδος

Επαληθεύει εάν το κείμενο του καθορισμένου στοιχείου είναι έγκυρο σύμφωνα με τον τύπο δεδομένων του.

```cpp
SharedPtr<Object> System::Xml::Schema::XmlSchemaValidator::ValidateEndElement(const SharedPtr<XmlSchemaInfo> &schemaInfo, const SharedPtr<Object> &typedValue)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | Ένα αντικείμενο [XmlSchemaInfo](../../xmlschemainfo/) του οποίου οι ιδιότητες ορίζονται μετά από επιτυχημένη επικύρωση του κειμενικού περιεχομένου του στοιχείου. Αυτή η παράμετρος μπορεί να είναι **nullptr**. |
| typedValue | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Το τυποποιημένο κειμενικό περιεχόμενο του στοιχείου. |

### Τιμή Επιστροφής

Η αναλυμένη, τυποποιημένη απλή τιμή περιεχομένου του στοιχείου.

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Τάξη [Object](../../../system/object/)
* Τάξη [XmlSchemaInfo](../../xmlschemainfo/)
* Τάξη [XmlSchemaValidator](../)
* Χώρος ονομάτων [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)