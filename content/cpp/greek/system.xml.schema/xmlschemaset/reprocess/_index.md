---
title: Reprocess()
second_title: Aspose.Slides για C++ - Αναφορά API
description: Επεξεργάζεται ξανά ένα σχήμα γλώσσας ορισμού XML Schema (XSD) που ήδη υπάρχει στο XmlSchemaSet.
type: docs
weight: 222
url: /el/system.xml.schema/xmlschemaset/reprocess/
---
## XmlSchemaSet::Reprocess(SharedPtr\<XmlSchema\>) μέθοδος


Επεξεργάζεται ξανά ένα σχήμα γλώσσας ορισμού XML [Schema](../../) (XSD) που υπάρχει ήδη στο [XmlSchemaSet](../).

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Reprocess(SharedPtr<XmlSchema> schema)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| schema | [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\> | Το σχήμα που θα επεξεργαστεί ξανά. |

### Τιμή Επιστροφής

Ένα αντικείμενο [XmlSchema](../../xmlschema/) εάν το σχήμα είναι έγκυρο. Εάν το σχήμα δεν είναι έγκυρο και ορίζεται ValidationEventHandler, **nullptr** επιστρέφεται και ενεργοποιείται το κατάλληλο συμβάν επικύρωσης. Διαφορετικά, ρίχνεται ένα XmlSchemaException.

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [XmlSchema](../../xmlschema/)
* Κλάση [XmlSchemaSet](../)
* Χώρος ονομάτων [System::Xml::Schema](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)