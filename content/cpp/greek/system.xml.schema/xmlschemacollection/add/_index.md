---
title: Add()
second_title: Aspose.Slides για C++ API Αναφορά
description: Προσθέτει το σχήμα που βρίσκεται στη δεδομένη διεύθυνση URL στη συλλογή σχήματος.
type: docs
weight: 40
url: /el/system.xml.schema/xmlschemacollection/add/
---
## XmlSchemaCollection::Add(const String\&, const String\&) μέθοδος

Προσθέτει το σχήμα που βρίσκεται στη δεδομένη διεύθυνση URL στη συλλογή σχήματος.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const String &ns, const String &uri)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| ns | const [String](../../../system/string/)\& | Το URI του χώρου ονομάτων που σχετίζεται με το σχήμα. Για XML Schemas, αυτό συνήθως είναι το **targetNamespace**. |
| uri | const [String](../../../system/string/)\& | Η διεύθυνση URL που καθορίζει το σχήμα προς φόρτωση. |

### Τιμή Επιστροφής

Το [XmlSchema](../../xmlschema/) προστέθηκε στη συλλογή σχήματος· **nullptr** εάν το σχήμα που προστίθεται είναι σχήμα XDR ή αν υπάρχουν σφάλματα μεταγλώττισης στο σχήμα.

## XmlSchemaCollection::Add(const String\&, const SharedPtr\<XmlReader\>\&) μέθοδος

Προσθέτει το σχήμα που περιέχεται στο [XmlReader](../../../system.xml/xmlreader/) στη συλλογή σχήματος.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const String &ns, const SharedPtr<XmlReader> &reader)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| ns | const [String](../../../system/string/)\& | Το URI του χώρου ονομάτων που σχετίζεται με το σχήμα. Για XML Schemas, αυτό συνήθως είναι το **targetNamespace**. |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | [XmlReader](../../../system.xml/xmlreader/) που περιέχει το σχήμα προς προσθήκη. |

### Τιμή Επιστροφής

Το [XmlSchema](../../xmlschema/) προστέθηκε στη συλλογή σχήματος· **nullptr** εάν το σχήμα που προστίθεται είναι σχήμα XDR ή αν υπάρχουν σφάλματα μεταγλώττισης στο σχήμα.

## XmlSchemaCollection::Add(const String\&, const SharedPtr\<XmlReader\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) μέθοδος

Προσθέτει το σχήμα που περιέχεται στο [XmlReader](../../../system.xml/xmlreader/) στη συλλογή σχήματος. Η καθορισμένη [XmlResolver](../../../system.xml/xmlresolver/) χρησιμοποιείται για την επίλυση τυχόν εξωτερικών πόρων.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const String &ns, const SharedPtr<XmlReader> &reader, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| ns | const [String](../../../system/string/)\& | Το URI του χώρου ονομάτων που σχετίζεται με το σχήμα. Για XML Schemas, αυτό συνήθως είναι το **targetNamespace**. |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | [XmlReader](../../../system.xml/xmlreader/) που περιέχει το σχήμα προς προσθήκη. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | Το [XmlResolver](../../../system.xml/xmlresolver/) που χρησιμοποιείται για την επίλυση χώρων ονομάτων που αναφέρονται σε στοιχεία **include** και **import** ή στην ιδιότητα **x-schema** (σχήματα XDR). Εάν είναι **nullptr**, οι εξωτερικές αναφορές δεν επιλύονται. |

### Τιμή Επιστροφής

Το [XmlSchema](../../xmlschema/) προστέθηκε στη συλλογή σχήματος· **nullptr** εάν το σχήμα που προστίθεται είναι σχήμα XDR ή αν υπάρχουν σφάλματα μεταγλώττισης στο σχήμα.

## XmlSchemaCollection::Add(const SharedPtr\<XmlSchema\>\&) μέθοδος

Προσθέτει το [XmlSchema](../../xmlschema/) στη συλλογή.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const SharedPtr<XmlSchema> &schema)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | Το [XmlSchema](../../xmlschema/) προς προσθήκη στη συλλογή. |

### Τιμή Επιστροφής

Το αντικείμενο [XmlSchema](../../xmlschema/).

## XmlSchemaCollection::Add(const SharedPtr\<XmlSchema\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) μέθοδος

Προσθέτει το [XmlSchema](../../xmlschema/) στη συλλογή. Η καθορισμένη [XmlResolver](../../../system.xml/xmlresolver/) χρησιμοποιείται για την επίλυση τυχόν εξωτερικών αναφορών.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const SharedPtr<XmlSchema> &schema, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | Το [XmlSchema](../../xmlschema/) προς προσθήκη στη συλλογή. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | Το [XmlResolver](../../../system.xml/xmlresolver/) που χρησιμοποιείται για την επίλυση χώρων ονομάτων που αναφέρονται σε στοιχεία **include** και **import**. Εάν είναι **nullptr**, οι εξωτερικές αναφορές δεν επιλύονται. |

### Τιμή Επιστροφής

Το [XmlSchema](../../xmlschema/) προστέθηκε στη συλλογή σχήματος.

## XmlSchemaCollection::Add(const SharedPtr\<XmlSchemaCollection\>\&) μέθοδος

Προσθέτει όλους τους χώρους ονομάτων που ορίζονται στην δεδομένη συλλογή (συμπεριλαμβανομένων των σχετικών σχημάτων) σε αυτήν τη συλλογή.

```cpp
void System::Xml::Schema::XmlSchemaCollection::Add(const SharedPtr<XmlSchemaCollection> &schema)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaCollection](../)\>\& | Το [XmlSchemaCollection](../) που θέλετε να προσθέσετε σε αυτή τη συλλογή. |

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchema](../../xmlschema/)
* Class [String](../../../system/string/)
* Class [XmlSchemaCollection](../)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)