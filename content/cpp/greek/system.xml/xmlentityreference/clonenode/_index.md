---
title: CloneNode()
second_title: Aspose.Slides για C++ – Αναφορά API
description: Δημιουργεί ένα αντίγραφο αυτού του κόμβου.
type: docs
weight: 92
url: /el/system.xml/xmlentityreference/clonenode/
---
## XmlEntityReference::CloneNode(bool) μέθοδος

Δημιουργεί ένα αντίγραφο αυτού του κόμβου.

```cpp
SharedPtr<XmlNode> System::Xml::XmlEntityReference::CloneNode(bool deep) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| deep | **bool** | **true** για αναδρομική κλωνοποίηση του υποδέντρου κάτω από τον καθορισμένο κόμβο· **false** για κλωνοποίηση μόνο του ίδιου κόμβου. Για [XmlEntityReference](../) κόμβους, αυτή η μέθοδος επιστρέφει πάντα έναν κόμβο αναφοράς οντότητας χωρίς παιδιά. Το κείμενο αντικατάστασης ορίζεται όταν ο κόμβος εισάγεται σε έναν γονικό. |

### Τιμή Επιστροφής

Ο κλωνοποιημένος κόμβος.

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [XmlNode](../../xmlnode/)
* Κλάση [XmlEntityReference](../)
* Χώρος ονομάτων [System::Xml](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)