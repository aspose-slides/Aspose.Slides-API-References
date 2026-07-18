---
title: Schemas()
second_title: Aspose.Slides για C++ Αναφορά API
description: Επιστρέφει μια συλλογή όλων των σχημάτων γλώσσας ορισμού XML Schema (XSD) στο XmlSchemaSet.
type: docs
weight: 248
url: /el/system.xml.schema/xmlschemaset/schemas/
---
## XmlSchemaSet::Schemas() μέθοδος

Επιστρέφει μια συλλογή όλων των σχημάτων XML [Schema](../../) γλώσσας ορισμού (XSD) στο [XmlSchemaSet](../).

```cpp
SharedPtr<Collections::Generic::IList<SharedPtr<XmlSchema>>> System::Xml::Schema::XmlSchemaSet::Schemas()
```

### Τιμή Επιστροφής

Ένα αντικείμενο IList που περιέχει όλα τα σχήματα που έχουν προστεθεί στο [XmlSchemaSet](../). Εάν δεν έχουν προστεθεί σχήματα στο [XmlSchemaSet](../), επιστρέφεται μια κενή συλλογή.

## XmlSchemaSet::Schemas(String) μέθοδος

Επιστρέφει μια συλλογή όλων των σχημάτων XML [Schema](../../) γλώσσας ορισμού (XSD) στο [XmlSchemaSet](../) που ανήκουν στο συγκεκριμένο χώρο ονομάτων.

```cpp
SharedPtr<Collections::Generic::List<SharedPtr<XmlSchema>>> System::Xml::Schema::XmlSchemaSet::Schemas(String targetNamespace)
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| targetNamespace | [String](../../../system/string/) | Η ιδιότητα **targetNamespace** του σχήματος. |

### Τιμή Επιστροφής

Ένα αντικείμενο IList που περιέχει όλα τα σχήματα που έχουν προστεθεί στο [XmlSchemaSet](../) που ανήκουν στο συγκεκριμένο χώρο ονομάτων. Εάν δεν έχουν προστεθεί σχήματα στο [XmlSchemaSet](../), επιστρέφεται μια κενή συλλογή.

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IList](../../../system.collections.generic/ilist/)
* Κλάση [XmlSchema](../../xmlschema/)
* Κλάση [XmlSchemaSet](../)
* Κλάση [List](../../../system.collections.generic/list/)
* Κλάση [String](../../../system/string/)
* Χώρος ονομάτων [System::Xml::Schema](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)