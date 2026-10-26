---
title: idx_get()
second_title: Aspose.Slides για C++ API Αναφορά
description: Επιστρέφει το XmlSchema που σχετίζεται με το δοσμένο URI του χώρου ονομάτων.
type: docs
weight: 53
url: /el/system.xml.schema/xmlschemacollection/idx_get/
---
## XmlSchemaCollection::idx_get(const String\&) μέθοδος

Επιστρέφει το [XmlSchema](../../xmlschema/) που σχετίζεται με το δοσμένο URI του χώρου ονομάτων.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::idx_get(const String &ns)
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| ns | const [String](../../../system/string/)\& | Το URI του χώρου ονομάτων που σχετίζεται με το σχήμα που θέλετε να επιστρέψετε. Συνήθως θα είναι το **targetNamespace** του σχήματος. |

### Τιμή Επιστροφής

Το [XmlSchema](../../xmlschema/) που σχετίζεται με το URI του χώρου ονομάτων· **nullptr** εάν δεν υπάρχει φορτωμένο σχήμα που σχετίζεται με το δοσμένο χώρο ονομάτων ή εάν ο χώρος ονομάτων σχετίζεται με σχήμα XDR.

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [XmlSchema](../../xmlschema/)
* Κλάση [String](../../../system/string/)
* Κλάση [XmlSchemaCollection](../)
* Χώρος ονομάτων [System::Xml::Schema](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)