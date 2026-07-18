---
title: CloneNode()
second_title: Aspose.Slides για C++ Αναφορά API
description: Δημιουργεί ένα αντίγραφο αυτού του κόμβου. Οι κόμβοι οντοτήτων δεν μπορούν να κλωνοποιηθούν. Η κλήση αυτής της μεθόδου σε ένα αντικείμενο XmlEntity προκαλεί εξαίρεση.
type: docs
weight: 170
url: /el/system.xml/xmlentity/clonenode/
---
## XmlEntity::CloneNode(bool) μέθοδος

Creates a duplicate of this node. Entity nodes cannot be cloned. Calling this method on an [XmlEntity](../) object throws an exception.

```cpp
SharedPtr<XmlNode> System::Xml::XmlEntity::CloneNode(bool deep) override
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| deep | **bool** | **true** για να αντιγράψετε αναδρομικά το υποδέντρο κάτω από τον καθορισμένο κόμβο· **false** για να αντιγράψετε μόνο τον ίδιο τον κόμβο. |

### Τιμή Επιστροφής

Μία αντίγραφο του [XmlNode](../../xmlnode/) από το οποίο κλήθηκε η μέθοδος.

## Δείτε επίσης

* Ορισμός τύπου [SharedPtr](../../../system/sharedptr/)
* Κλάση [XmlNode](../../xmlnode/)
* Κλάση [XmlEntity](../)
* Χώρος ονομάτων [System::Xml](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)