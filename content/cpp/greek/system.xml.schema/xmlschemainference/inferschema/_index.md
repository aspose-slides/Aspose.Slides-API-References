---
title: InferSchema()
second_title: Aspose.Slides για C++ API Αναφορά
description: Παράγει ένα σχήμα XML Schema Definition Language (XSD) από το έγγραφο XML που περιέχεται στο αντικείμενο XmlReader που καθορίζεται.
type: docs
weight: 66
url: /el/system.xml.schema/xmlschemainference/inferschema/
---
## XmlSchemaInference::InferSchema(const SharedPtr\<XmlReader\>\&) μέθοδος

Παράγει ένα σχήμα XML [Schema](../../) Definition Language (XSD) από το έγγραφο XML που περιέχεται στο αντικείμενο [XmlReader](../../../system.xml/xmlreader/) που καθορίζεται.

```cpp
SharedPtr<XmlSchemaSet> System::Xml::Schema::XmlSchemaInference::InferSchema(const SharedPtr<XmlReader> &instanceDocument)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| instanceDocument | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Ένα αντικείμενο [XmlReader](../../../system.xml/xmlreader/) που περιέχει το έγγραφο XML από το οποίο θα προβλεφθεί ένα σχήμα. |

### Τιμή Επιστροφής

Ένα αντικείμενο [XmlSchemaSet](../../xmlschemaset/) που περιέχει τα προεγγραμμένα σχήματα.

## XmlSchemaInference::InferSchema(const SharedPtr\<XmlReader\>\&, SharedPtr\<XmlSchemaSet\>) μέθοδος

Παράγει ένα σχήμα XML [Schema](../../) Definition Language (XSD) από το έγγραφο XML που περιέχεται στο αντικείμενο [XmlReader](../../../system.xml/xmlreader/) που καθορίζεται, και βελτιώνει το προεγγραμμένο σχήμα χρησιμοποιώντας ένα υπάρχον σχήμα στο αντικείμενο [XmlSchemaSet](../../xmlschemaset/) με το ίδιο target namespace.

```cpp
SharedPtr<XmlSchemaSet> System::Xml::Schema::XmlSchemaInference::InferSchema(const SharedPtr<XmlReader> &instanceDocument, SharedPtr<XmlSchemaSet> schemas)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| instanceDocument | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Ένα αντικείμενο [XmlReader](../../../system.xml/xmlreader/) που περιέχει το έγγραφο XML από το οποίο θα προβλεφθεί ένα σχήμα. |
| schemas | [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaSet](../../xmlschemaset/)\> | Ένα αντικείμενο [XmlSchemaSet](../../xmlschemaset/) που περιέχει ένα υπάρχον σχήμα που χρησιμοποιείται για τη βελτίωση του προεγγραμμένου σχήματος. |

### Τιμή Επιστροφής

Ένα αντικείμενο [XmlSchemaSet](../../xmlschemaset/) που περιέχει τα προεγγραμμένα σχήματα.

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [XmlSchemaSet](../../xmlschemaset/)
* Κλάση [XmlReader](../../../system.xml/xmlreader/)
* Κλάση [XmlSchemaInference](../)
* Χώρος ονομάτων [System::Xml::Schema](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)