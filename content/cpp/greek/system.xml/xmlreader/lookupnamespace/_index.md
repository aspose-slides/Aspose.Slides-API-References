---
title: LookupNamespace()
second_title: Aspose.Slides για την αναφορά API του C++
description: Όταν επικαλείται σε παράγωγη κλάση, επιλύει ένα πρόθεμα ονόματος χώρου στο πεδίο ισχύος του τρέχοντος στοιχείου.
type: docs
weight: 729
url: /el/system.xml/xmlreader/lookupnamespace/
---
## XmlReader::LookupNamespace(const String\&) μέθοδος

When overridden in a derived class, resolves a namespace prefix in the current element's scope.

```cpp
virtual String System::Xml::XmlReader::LookupNamespace(const String &prefix)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | Το prefix του οποίου το namespace URI θέλετε να επιλύσετε. Για να ταιριάξετε το προεπιλεγμένο namespace, περάστε μια κενή συμβολοσειρά. |

### Τιμή Επιστροφής

Το namespace URI στο οποίο αντιστοιχεί το prefix ή **nullptr** εάν δεν βρεθεί αντιστοίχιση προθέματος.

## Δείτε επίσης

* Κλάση [String](../../../system/string/)
* Κλάση [XmlReader](../)
* Χώρος ονομάτων [System::Xml](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)