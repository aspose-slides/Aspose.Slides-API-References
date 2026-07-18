---
title: CloneNode()
second_title: Aspose.Slides για την Αναφορά API C++
description: Δημιουργεί ένα αντίγραφο αυτού του κόμβου.
type: docs
weight: 53
url: /el/system.xml/xmlcdatasection/clonenode/
---
## XmlCDataSection::CloneNode(bool) μέθοδος

Δημιουργεί ένα αντίγραφο αυτού του κόμβου.

```cpp
SharedPtr<XmlNode> System::Xml::XmlCDataSection::CloneNode(bool deep) override
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| deep | **bool** | **true** για να κλωνοποιήσει αναδρομικά το υποδέντρο κάτω από τον καθορισμένο κόμβο· **false** για να κλωνοποιήσει μόνο τον ίδιο τον κόμβο. Επειδή οι κόμβοι CDATA δεν έχουν παιδιά, ανεξάρτητα από τη ρύθμιση της παραμέτρου, ο κλωνοποιημένος κόμβος θα περιλαμβάνει πάντα το περιεχόμενο των δεδομένων. |

### Τιμή επιστροφής

Ο κλωνοποιημένος κόμβος.

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [XmlNode](../../xmlnode/)
* Κλάση [XmlCDataSection](../)
* Χώρος ονομάτων [System::Xml](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)