---
title: Equals()
second_title: Aspose.Slides για C++ API Αναφορά
description: Καθορίζει εάν η καθορισμένη περιοχή είναι ταυτόσημη με την περιοχή που αντιπροσωπεύεται από το τρέχον αντικείμενο στην καθορισμένη επιφάνεια σχεδίασης.
type: docs
weight: 157
url: /el/system.drawing/region/equals/
---
## Region::Equals(const SharedPtr\<Region\>\&, const SharedPtr\<Graphics\>\&) μέθοδος

Determines whether the specified region is identical to the region represented by the current object on the specified drawing surface.

```cpp
bool System::Drawing::Region::Equals(const SharedPtr<Region> &r, const SharedPtr<Graphics> &g)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| r | const [SharedPtr](../../../system/sharedptr/)\<[Region](../)\>\& | Η περιοχή για σύγκριση με αυτήν την περιοχή |
| g | const [SharedPtr](../../../system/sharedptr/)\<[Graphics](../../graphics/)\>\& | Μια επιφάνεια σχεδίασης |

### Τιμή επιστροφής

Αληθές εάν το εσωτερικό της καθορισμένης περιοχής είναι ίδιο με το εσωτερικό της περιοχής που αντιπροσωπεύεται από το τρέχον αντικείμενο όταν εφαρμόζεται η μετασχηματισμός που σχετίζεται με την παράμετρο **g**· διαφορετικά - ψευδές

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [Region](../)
* Κλάση [Graphics](../../graphics/)
* Χώρος ονομάτων [System::Drawing](../../)
* Library [Aspose.Slides](../../../)