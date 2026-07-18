---
title: CloneNode()
second_title: Aspose.Slides για C++ API Αναφορά
description: Δημιουργεί ένα αντίγραφο αυτού του κόμβου.
type: docs
weight: 118
url: /el/system.xml/xmldocumenttype/clonenode/
---
## XmlDocumentType::CloneNode(bool) μέθοδος


Δημιουργεί ένα αντίγραφο αυτού του κόμβου.

```cpp
SharedPtr<XmlNode> System::Xml::XmlDocumentType::CloneNode(bool deep) override
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| deep | **bool** | **true** για να κλωνοποιήσετε επαναληπτικά το υποδέντρο κάτω από τον καθορισμένο κόμβο· **false** για να κλωνοποιήσετε μόνο τον ίδιο τον κόμβο. Για κόμβους τύπου εγγράφου, ο κλωνοποιημένος κόμβος περιλαμβάνει πάντα το υποδέντρο, ανεξάρτητα από τη ρύθμιση της παραμέτρου. |

### Τιμή Επιστροφής

Ο κλωνοποιημένος κόμβος.

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlDocumentType](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)