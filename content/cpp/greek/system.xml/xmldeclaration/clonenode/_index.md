---
title: CloneNode()
second_title: Aspose.Slides για C++ API Αναφορά
description: Δημιουργεί ένα αντίγραφο αυτού του κόμβου.
type: docs
weight: 157
url: /el/system.xml/xmldeclaration/clonenode/
---
## XmlDeclaration::CloneNode(bool) μέθοδος


Δημιουργεί ένα αντίγραφο αυτού του κόμβου.

```cpp
SharedPtr<XmlNode> System::Xml::XmlDeclaration::CloneNode(bool deep) override
```


### Ορίσματα

| Parameter | Type | Description |
| --- | --- | --- |
| deep | **bool** | **true** για να κλωνοποιηθεί αναδρομικά το υποδέντρο κάτω από τον καθορισμένο κόμβο· **false** για να κλωνοποιηθεί μόνο ο ίδιος ο κόμβος. Επειδή οι κόμβοι [XmlDeclaration](../) δεν έχουν παιδιά, ο κλωνοποιημένος κόμβος περιλαμβάνει πάντα την τιμή δεδομένων, ανεξαρτήτως της ρύθμισης της παραμέτρου. |

### Τιμή επιστροφής

Ο κλωνοποιημένος κόμβος.

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlDeclaration](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)