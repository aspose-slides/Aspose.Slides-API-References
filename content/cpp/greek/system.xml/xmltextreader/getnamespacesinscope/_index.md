---
title: GetNamespacesInScope()
second_title: Aspose.Slides για C++ API Αναφορά
description: Επιστρέφει μια συλλογή που περιέχει όλους τους χώρους ονομάτων που είναι αυτή τη στιγμή εντός εμβέλειας.
type: docs
weight: 716
url: /el/system.xml/xmltextreader/getnamespacesinscope/
---
## XmlTextReader::GetNamespacesInScope(XmlNamespaceScope) μέθοδος

Επιστρέφει μια συλλογή που περιέχει όλους τους χώρους ονομάτων που είναι αυτή τη στιγμή εντός εμβέλειας.

```cpp
SharedPtr<Collections::Generic::IDictionary<String, String>> System::Xml::XmlTextReader::GetNamespacesInScope(XmlNamespaceScope scope) override
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| scope | [XmlNamespaceScope](../../xmlnamespacescope/) | Μια τιμή XmlNamespaceScope που καθορίζει τον τύπο των κόμβων χώρου ονομάτων που θα επιστραφούν. |

### Τιμή επιστροφής

Ένα αντικείμενο IDictionary που περιέχει όλους τους τρέχοντες χώρους ονομάτων εντός εμβέλειας. Εάν ο αναγνώστης δεν είναι τοποθετημένος σε στοιχείο, επιστρέφεται ένα κενό λεξικό (χωρίς χώρους ονομάτων).

## Δείτε επίσης

* Enum [XmlNamespaceScope](../../xmlnamespacescope/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IDictionary](../../../system.collections.generic/idictionary/)
* Κλάση [String](../../../system/string/)
* Κλάση [XmlTextReader](../)
* Χώρος ονομάτων [System::Xml](../../)
* Library [Aspose.Slides](../../../)