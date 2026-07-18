---
title: Contains()
second_title: Αναφορά API Aspose.Slides για C++
description: Δηλώνει εάν ένα σχήμα XML Schema definition language (XSD) με το καθορισμένο URI του target namespace βρίσκεται στο XmlSchemaSet.
type: docs
weight: 196
url: /el/system.xml.schema/xmlschemaset/contains/
---
## XmlSchemaSet::Contains(String) μέθοδος


Δηλώνει εάν ένα σχήμα XML [Schema](../../) definition language (XSD) με το καθορισμένο URI του target namespace βρίσκεται στο [XmlSchemaSet](../).

```cpp
bool System::Xml::Schema::XmlSchemaSet::Contains(String targetNamespace)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| targetNamespace | [String](../../../system/string/) | Η ιδιότητα **targetNamespace** του σχήματος. |

### Τιμή Επιστροφής

**true** εάν ένα σχήμα με το καθορισμένο URI του target namespace βρίσκεται στο [XmlSchemaSet](../)· διαφορετικά, **false**.

## XmlSchemaSet::Contains(const SharedPtr\<XmlSchema\>\&) μέθοδος


Δηλώνει εάν το καθορισμένο αντικείμενο XML [Schema](../../) definition language (XSD) [XmlSchema](../../xmlschema/) βρίσκεται στο [XmlSchemaSet](../).

```cpp
bool System::Xml::Schema::XmlSchemaSet::Contains(const SharedPtr<XmlSchema> &schema)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | Το αντικείμενο [XmlSchema](../../xmlschema/). |

### Τιμή Επιστροφής

**true** εάν το αντικείμενο [XmlSchema](../../xmlschema/) βρίσκεται στο [XmlSchemaSet](../)· διαφορετικά, **false**.

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [String](../../../system/string/)
* Κλάση [XmlSchemaSet](../)
* Κλάση [XmlSchema](../../xmlschema/)
* Χώρος ονομάτων [System::Xml::Schema](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)