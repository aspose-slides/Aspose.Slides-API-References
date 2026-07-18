---
title: PrependChild()
second_title: Aspose.Slides για C++ Αναφορά API
description: Προσθέτει τον καθορισμένο κόμβο στην αρχή της λίστας των παιδικών κόμβων για αυτόν τον κόμβο.
type: docs
weight: 261
url: /el/system.xml/xmlattribute/prependchild/
---
## XmlAttribute::PrependChild(SharedPtr\<XmlNode\>) μέθοδος

Προσθέτει τον καθορισμένο κόμβο στην αρχή της λίστας των παιδικών κόμβων για αυτόν τον κόμβο.

```cpp
SharedPtr<XmlNode> System::Xml::XmlAttribute::PrependChild(SharedPtr<XmlNode> newChild) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | Το [XmlNode](../../xmlnode/) προς προσθήκη. Αν είναι ένα [XmlDocumentFragment](../../xmldocumentfragment/), το πλήρες περιεχόμενο του τμήματος εγγράφου μετακινείται στη λίστα παιδικών κόμβων αυτού του κόμβου. |

### Τιμή Επιστροφής

Το [XmlNode](../../xmlnode/) που προστέθηκε.

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [XmlNode](../../xmlnode/)
* Κλάση [XmlAttribute](../)
* Χώρος ονομάτων [System::Xml](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)