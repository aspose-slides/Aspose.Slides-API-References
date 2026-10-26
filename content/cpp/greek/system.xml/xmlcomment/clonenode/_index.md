---
title: CloneNode()
second_title: Αναφορά API Aspose.Slides για C++
description: Δημιουργεί ένα αντίγραφο αυτού του κόμβου.
type: docs
weight: 40
url: /el/system.xml/xmlcomment/clonenode/
---
## XmlComment::CloneNode(bool) μέθοδος

Δημιουργεί ένα αντίγραφο αυτού του κόμβου.

```cpp
SharedPtr<XmlNode> System::Xml::XmlComment::CloneNode(bool deep) override
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| deep | **bool** | **true** για να αντιγράψετε αναδρομικά το υποδέντρο κάτω από τον καθορισμένο κόμβο· **false** για να αντιγράψετε μόνο τον ίδιο τον κόμβο. Επειδή οι κόμβοι σχολίων δεν έχουν παιδιά, ο κλώνος του κόμβου περιλαμβάνει πάντα το περιεχόμενο κειμένου, ανεξάρτητα από τη ρύθμιση της παραμέτρου. |

### Τιμή Επιστροφής

Ο κλώνος του κόμβου.

## Δείτε επίσης

* Τύπος [SharedPtr](../../../system/sharedptr/)
* Κλάση [XmlNode](../../xmlnode/)
* Κλάση [XmlComment](../)
* Χώρος ονομάτων [System::Xml](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)