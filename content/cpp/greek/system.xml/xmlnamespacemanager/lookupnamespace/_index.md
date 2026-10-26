---
title: LookupNamespace()
second_title: Αναφορά API Aspose.Slides για C++
description: Επιστρέφει το URI του χώρου ονομάτων για το καθορισμένο πρόθεμα.
type: docs
weight: 118
url: /el/system.xml/xmlnamespacemanager/lookupnamespace/
---
## XmlNamespaceManager::LookupNamespace(const String\&) μέθοδος

Επιστρέφει το URI του χώρου ονομάτων για το καθορισμένο πρόθεμα.

```cpp
String System::Xml::XmlNamespaceManager::LookupNamespace(const String &prefix) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | Το πρόθεμα του οποίου το URI του χώρου ονομάτων θέλετε να επιλύσετε. Για να ταιριάξετε με το προεπιλεγμένο χώρο ονομάτων, περάστε [String::Empty](../../../system/string/empty/). |

### Τιμή επιστροφής

Το URI του χώρου ονομάτων για **prefix** ή **nullptr** αν δεν υπάρχει αντιστοιχισμένο χώρο ονομάτων. Η επιστρεφόμενη συμβολοσειρά είναι ατομική. Για περισσότερες πληροφορίες σχετικά με τις ατομικές συμβολοσειρές, δείτε την κλάση [XmlNameTable](../../xmlnametable/).

## Δείτε επίσης

* Κλάση [String](../../../system/string/)
* Κλάση [XmlNamespaceManager](../)
* Χώρος ονομάτων [System::Xml](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)