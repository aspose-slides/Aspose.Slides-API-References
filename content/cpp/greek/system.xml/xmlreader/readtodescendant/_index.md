---
title: ReadToDescendant()
second_title: Αναφορά API του Aspose.Slides για C++
description: Προωθεί το XmlReader στο επόμενο θυγατρικό στοιχείο με το καθορισμένο πλήρες όνομα.
type: docs
weight: 911
url: /el/system.xml/xmlreader/readtodescendant/
---
## XmlReader::ReadToDescendant(String) μέθοδος


Προωθεί το [XmlReader](../) στο επόμενο θυγατρικό στοιχείο με το καθορισμένο πλήρες όνομα.

```cpp
virtual bool System::Xml::XmlReader::ReadToDescendant(String name)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | [String](../../../system/string/) | Το πλήρες όνομα του στοιχείου στο οποίο θέλετε να μετακινηθείτε. |

### Τιμή Επιστροφής

**true** εάν βρεθεί ένα ταιριαστό θυγατρικό στοιχείο· διαφορετικά **false**. Εάν δεν βρεθεί ένα ταιριαστό παιδί-στοιχείο, το [XmlReader](../) τοποθετείται στο κλείσιμο (τιμή [XmlReader::get_NodeType](../get_nodetype/) είναι [XmlNodeType::EndElement](../../xmlnodetype/)) του στοιχείου. Εάν το [XmlReader](../) δεν είναι τοποθετημένο σε στοιχείο όταν κλήθηκε το [XmlReader::ReadToDescendant(String)](./), αυτή η μέθοδος επιστρέφει **false** και η θέση του [XmlReader](../) δεν αλλάζει.

## XmlReader::ReadToDescendant(String, String) μέθοδος


Προωθεί το [XmlReader](../) στο επόμενο θυγατρικό στοιχείο με το καθορισμένο τοπικό όνομα και το URI του ονοματοχώρου.

```cpp
virtual bool System::Xml::XmlReader::ReadToDescendant(String localName, String namespaceURI)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Το τοπικό όνομα του στοιχείου στο οποίο θέλετε να μετακινηθείτε. |
| namespaceURI | [String](../../../system/string/) | Το URI του ονοματοχώρου του στοιχείου στο οποίο θέλετε να μετακινηθείτε. |

### Τιμή Επιστροφής

**true** εάν βρεθεί ένα ταιριαστό θυγατρικό στοιχείο· διαφορετικά **false**. Εάν δεν βρεθεί ένα ταιριαστό παιδί-στοιχείο, το [XmlReader](../) τοποθετείται στο κλείσιμο (τιμή [XmlReader::get_NodeType](../get_nodetype/) είναι [XmlNodeType::EndElement](../../xmlnodetype/)) του στοιχείου. Εάν το [XmlReader](../) δεν είναι τοποθετημένο σε στοιχείο όταν κλήθηκε το [XmlReader::ReadToDescendant(String,String)](./), αυτή η μέθοδος επιστρέφει **false** και η θέση του [XmlReader](../) δεν αλλάζει.

## Δείτε επίσης

* Κλάση [String](../../../system/string/)
* Κλάση [XmlReader](../)
* Ονοματοχώρος [System::Xml](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)