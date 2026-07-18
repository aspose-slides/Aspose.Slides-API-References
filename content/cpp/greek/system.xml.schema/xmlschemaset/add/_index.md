---
title: Add()
second_title: Aspose.Slides για C++ API Αναφορά
description: Προσθέτει το σχήμα XML Schema definition language (XSD) στη διεύθυνση URL που καθορίζεται στο XmlSchemaSet.
type: docs
weight: 157
url: /el/system.xml.schema/xmlschemaset/add/
---
## XmlSchemaSet::Add(String, const String\&) μέθοδος


Προσθέτει το σχήμα XML [Schema](../../) γλώσσα ορισμού (XSD) στη διεύθυνση URL που ορίζεται στο [XmlSchemaSet](../).

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Add(String targetNamespace, const String &schemaUri)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| targetNamespace | [String](../../../system/string/) | Η τιμή **targetNamespace** του σχήματος, ή **nullptr** για χρήση του **targetNamespace** που ορίζεται στο σχήμα. |
| schemaUri | const [String](../../../system/string/)\& | Η URL που καθορίζει το σχήμα προς φόρτωση. |

### Τιμή Επιστροφής

Ένα αντικείμενο [XmlSchema](../../xmlschema/) εάν το σχήμα είναι έγκυρο. Εάν το σχήμα δεν είναι έγκυρο και έχει καθοριστεί ValidationEventHandler, τότε επιστρέφεται **nullptr** και ενεργοποιείται το αντίστοιχο συμβάν επικύρωσης. Διαφορετικά, η XmlSchemaException ρίχνεται.

## XmlSchemaSet::Add(String, const SharedPtr\<XmlReader\>\&) μέθοδος


Προσθέτει το σχήμα XML [Schema](../../) γλώσσα ορισμού (XSD) που περιέχεται στο [XmlReader](../../../system.xml/xmlreader/) στο [XmlSchemaSet](../).

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Add(String targetNamespace, const SharedPtr<XmlReader> &schemaDocument)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| targetNamespace | [String](../../../system/string/) | Η τιμή **targetNamespace** του σχήματος, ή **nullptr** για χρήση του **targetNamespace** που ορίζεται στο σχήμα. |
| schemaDocument | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Το αντικείμενο [XmlReader](../../../system.xml/xmlreader/). |

### Τιμή Επιστροφής

Ένα αντικείμενο [XmlSchema](../../xmlschema/) εάν το σχήμα είναι έγκυρο. Εάν το σχήμα δεν είναι έγκυρο και έχει καθοριστεί ValidationEventHandler, τότε επιστρέφεται **nullptr** και ενεργοποιείται το αντίστοιχο συμβάν επικύρωσης. Διαφορετικά, η XmlSchemaException ρίχνεται.

## XmlSchemaSet::Add(const SharedPtr\<XmlSchemaSet\>\&) μέθοδος


Προσθέτει όλα τα σχήματα XML [Schema](../../) γλώσσα ορισμού (XSD) στο δοσμένο [XmlSchemaSet](../) στο [XmlSchemaSet](../).

```cpp
void System::Xml::Schema::XmlSchemaSet::Add(const SharedPtr<XmlSchemaSet> &schemas)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| schemas | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaSet](../)\>\& | Το αντικείμενο [XmlSchemaSet](../). |

## XmlSchemaSet::Add(const SharedPtr\<XmlSchema\>\&) μέθοδος


Προσθέτει το δεδομένο [XmlSchema](../../xmlschema/) στο [XmlSchemaSet](../).

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Add(const SharedPtr<XmlSchema> &schema)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | Το αντικείμενο [XmlSchema](../../xmlschema/) προς προσθήκη στο [XmlSchemaSet](../). |

### Τιμή Επιστροφής

Ένα αντικείμενο [XmlSchema](../../xmlschema/) εάν το σχήμα είναι έγκυρο. Εάν το σχήμα δεν είναι έγκυρο και έχει καθοριστεί ValidationEventHandler, τότε επιστρέφεται **nullptr** και ενεργοποιείται το αντίστοιχο συμβάν επικύρωσης. Διαφορετικά, η XmlSchemaException ρίχνεται.

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchema](../../xmlschema/)
* Class [String](../../../system/string/)
* Class [XmlSchemaSet](../)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)