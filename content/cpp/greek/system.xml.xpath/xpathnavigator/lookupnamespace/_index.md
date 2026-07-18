---
title: LookupNamespace()
second_title: Aspose.Slides για C++ API Αναφορά
description: Επιστρέφει το URI του χώρου ονομάτων για το καθορισμένο πρόθεμα.
type: docs
weight: 404
url: /el/system.xml.xpath/xpathnavigator/lookupnamespace/
---
## XPathNavigator::LookupNamespace(const String\&) μέθοδος

Επιστρέφει το URI του χώρου ονομάτων για το καθορισμένο πρόθεμα.

```cpp
String System::Xml::XPath::XPathNavigator::LookupNamespace(const String &prefix) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | Το πρόθεμα του οποίου το URI του χώρου ονομάτων θέλετε να επιλύσετε. Για να ταιριάξετε το προεπιλεγμένο namespace, περάστε [String::Empty](../../../system/string/empty/). |

### Τιμή Επιστροφής

Ένα [String](../../../system/string/) που περιέχει το URI του χώρου ονομάτων που έχει εκχωρηθεί στο καθορισμένο πρόθεμα χώρου ονομάτων· **nullptr** εάν δεν έχει εκχωρηθεί URI στο καθορισμένο πρόθεμα. Το [String](../../../system/string/) που επιστρέφεται είναι ατομικοποιημένο.

## Δείτε επίσης

* Κλάση [String](../../../system/string/)
* Κλάση [XPathNavigator](../)
* Χώρος ονομάτων [System::Xml::XPath](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)