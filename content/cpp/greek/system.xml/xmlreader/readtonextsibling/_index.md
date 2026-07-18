---
title: ReadToNextSibling()
second_title: Αναφορά API Aspose.Slides για C++
description: Μετακινεί τον XmlReader στο επόμενο αδελφό στοιχείο με το καθορισμένο πλήρες όνομα.
type: docs
weight: 924
url: /el/system.xml/xmlreader/readtonextsibling/
---
## XmlReader::ReadToNextSibling(String) μέθοδος

Προχωρά το [XmlReader](../) στο επόμενο αδελφό στοιχείο με το καθορισμένο πλήρες όνομα.

```cpp
virtual bool System::Xml::XmlReader::ReadToNextSibling(String name)
```

### Παραμέτρους

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | [String](../../../system/string/) | Το πλήρες όνομα του αδελφού στοιχείου στο οποίο θέλετε να μετακινηθείτε. |

### Τιμή Επιστροφής

**true** αν βρεθεί ένα αντίστοιχο αδελφό στοιχείο· διαφορετικά **false**. Αν δεν βρεθεί ένα αντίστοιχο αδελφό στοιχείο, το [XmlReader](../) τοποθετείται στην ετικέτα κλεισίματος (η τιμή [XmlReader::get_NodeType](../get_nodetype/) είναι [XmlNodeType::EndElement](../../xmlnodetype/)) του γονικού στοιχείου.

## XmlReader::ReadToNextSibling(String, String) μέθοδος

Προχωρά το [XmlReader](../) στο επόμενο αδελφό στοιχείο με το καθορισμένο τοπικό όνομα και το URI του namespace.

```cpp
virtual bool System::Xml::XmlReader::ReadToNextSibling(String localName, String namespaceURI)
```

### Παραμέτρους

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Το τοπικό όνομα του αδελφού στοιχείου στο οποίο θέλετε να μετακινηθείτε. |
| namespaceURI | [String](../../../system/string/) | Το URI του namespace του αδελφού στοιχείου στο οποίο θέλετε να μετακινηθείτε. |

### Τιμή Επιστροφής

**true** αν βρεθεί ένα αντίστοιχο αδελφό στοιχείο· διαφορετικά **false**. Αν δεν βρεθεί ένα αντίστοιχο αδελφό στοιχείο, το [XmlReader](../) τοποθετείται στην ετικέτα κλεισίματος (η τιμή [XmlReader::get_NodeType](../get_nodetype/) είναι [XmlNodeType::EndElement](../../xmlnodetype/)) του γονικού στοιχείου.

## Δείτε επίσης

* Κλάση [String](../../../system/string/)
* Κλάση [XmlReader](../)
* Χώρος ονομάτων [System::Xml](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)