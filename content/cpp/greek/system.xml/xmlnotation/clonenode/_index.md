---
title: CloneNode()
second_title: Aspose.Slides για C++ API Αναφορά
description: Δημιουργεί ένα αντίγραφο αυτού του κόμβου. Οι κόμβοι σημειώσεων δεν μπορούν να κλωνοποιηθούν. Η κλήση αυτής της μεθόδου σε ένα αντικείμενο XmlNotation προκαλεί εξαίρεση.
type: docs
weight: 118
url: /el/system.xml/xmlnotation/clonenode/
---
## XmlNotation::CloneNode(bool) method

Δημιουργεί ένα αντίγραφο αυτού του κόμβου. Οι κόμβοι σημειώσεων δεν μπορούν να κλωνοποιηθούν. Η κλήση αυτής της μεθόδου σε ένα αντικείμενο [XmlNotation](../) προκαλεί εξαίρεση.

```cpp
SharedPtr<XmlNode> System::Xml::XmlNotation::CloneNode(bool deep) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| deep | **bool** | **true** για αναδρομική κλωνοποίηση του υποδένδρου κάτω από τον καθορισμένο κόμβο· **false** για κλωνοποίηση μόνο του κόμβου. |

### Τιμή Επιστροφής

Ένα [XmlNode](../../xmlnode/) αντίγραφο του κόμβου από τον οποίο κλήθηκε η μέθοδος.

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [XmlNode](../../xmlnode/)
* Κλάση [XmlNotation](../)
* Χώρος ονομάτων [System::Xml](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)