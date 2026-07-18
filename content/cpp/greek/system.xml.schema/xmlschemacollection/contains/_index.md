---
title: Contains()
second_title: Aspose.Slides για C++ Αναφορά API
description: Επιστρέφει μια τιμή που υποδεικνύει εάν το targetNamespace του καθορισμένου XmlSchema βρίσκεται στη συλλογή.
type: docs
weight: 66
url: /el/system.xml.schema/xmlschemacollection/contains/
---
## XmlSchemaCollection::Contains(const SharedPtr\<XmlSchema\>\&) μέθοδος

Επιστρέφει μια τιμή που υποδεικνύει εάν το **targetNamespace** του καθορισμένου [XmlSchema](../../xmlschema/) βρίσκεται στη συλλογή.

```cpp
bool System::Xml::Schema::XmlSchemaCollection::Contains(const SharedPtr<XmlSchema> &schema)
```

### Arguments

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | Το αντικείμενο [XmlSchema](../../xmlschema/). |

### Τιμή επιστροφής

**true** εάν υπάρχει ένα σχήμα στη συλλογή με το ίδιο **targetNamespace**· διαφορετικά, **false**.

## XmlSchemaCollection::Contains(const String\&) μέθοδος

Επιστρέφει μια τιμή που υποδεικνύει εάν ένα σχήμα με το καθορισμένο χώρο ονομάτων βρίσκεται στη συλλογή.

```cpp
bool System::Xml::Schema::XmlSchemaCollection::Contains(const String &ns)
```

### Arguments

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| ns | const [String](../../../system/string/)\& | Το URI του χώρου ονομάτων που συσχετίζεται με το σχήμα. Για XML Schemas, αυτό συνήθως είναι το target namespace. |

### Τιμή επιστροφής

**true** εάν ένα σχήμα με το καθορισμένο χώρο ονομάτων βρίσκεται στη συλλογή· διαφορετικά, **false**.

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [XmlSchema](../../xmlschema/)
* Κλάση [XmlSchemaCollection](../)
* Κλάση [String](../../../system/string/)
* Χώρος ονομάτων [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)