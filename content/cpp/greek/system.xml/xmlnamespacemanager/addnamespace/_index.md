---
title: AddNamespace()
second_title: Αναφορά API Aspose.Slides για C++
description: Προσθέτει το δεδομένο namespace στη συλλογή.
type: docs
weight: 66
url: /el/system.xml/xmlnamespacemanager/addnamespace/
---
## XmlNamespaceManager::AddNamespace(String, String) μέθοδος

Προσθέτει το δεδομένο namespace στη συλλογή.

```cpp
virtual void System::Xml::XmlNamespaceManager::AddNamespace(String prefix, String uri)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | Το πρόθεμα για συσχέτιση με το namespace που προστίθεται. Χρησιμοποιήστε [String::Empty](../../../system/string/empty/) για να προσθέσετε προεπιλεγμένο namespace. Εάν το [XmlNamespaceManager](../) θα χρησιμοποιηθεί για την επίλυση namespaces σε μια έκφραση XML Path Language ([XPath](../../../system.xml.xpath/)), πρέπει να οριστεί πρόθεμα. Εάν μια έκφραση [XPath](../../../system.xml.xpath/) δεν περιλαμβάνει πρόθεμα, θεωρείται ότι το Uniform Resource Identifier (URI) του namespace είναι το κενό namespace. Για περισσότερες πληροφορίες σχετικά με τις εκφράσεις [XPath](../../../system.xml.xpath/) και το [XmlNamespaceManager](../), ανατρέξτε στις μεθόδους XmlNode::SelectNodes(String) και XPathExpression::SetContext(SharedPtr<XmlNamespaceManager>) μεθόδους. |
| uri | [String](../../../system/string/) | Το namespace προς προσθήκη. |

## Δείτε επίσης

* Κλάση [String](../../../system/string/)
* Κλάση [XmlNamespaceManager](../)
* Χώρος ονομάτων [System::Xml](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)