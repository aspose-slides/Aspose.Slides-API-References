---
title: get_Name()
second_title: Aspose.Slides για C++ API Αναφορά
description: Επιστρέφει το πλήρες όνομα του κόμβου, όταν επανυλοποιείται σε μια παράγωγη κλάση.
type: docs
weight: 1
url: /el/system.xml/xmlnode/get_name/
---
## XmlNode::get_Name() μέθοδος


Επιστρέφει το πλήρες όνομα του κόμβου, όταν επανυλοποιείται σε μια παράγωγη κλάση.

```cpp
virtual String System::Xml::XmlNode::get_Name()=0
```


### Τιμή Επιστροφής

Το πλήρες όνομα του κόμβου.
## Παρατηρήσεις



Το όνομα που επιστρέφεται εξαρτάται από το [XmlNode::get_NodeType](../get_nodetype/) του κόμβου: 

| Type | Name |
| --- | --- |
| [Attribute](../../../system/attribute/)| Το πλήρες όνομα του χαρακτηριστικού. |
| CDATA | #cdata-section |
| Comment | #comment |
| Document | #document |
| DocumentFragment | #document-fragment |
| DocumentType | Το όνομα τύπου του εγγράφου. |
| Element | Το πλήρες όνομα του στοιχείου. |
| Entity | Το όνομα της οντότητας. |
| EntityReference | Το όνομα της αναφερόμενης οντότητας. |
| Notation | Το όνομα της σημειογραφίας. |
| ProcessingInstruction | Ο προορισμός της εντολής επεξεργασίας. |
| [Text](../../../system.text/)| #text |
| Whitespace | #whitespace |
| SignificantWhitespace | #significant-whitespace |
| [XmlDeclaration](../../xmldeclaration/)| #xml-declaration |


## Δείτε επίσης

* Κλάση [String](../../../system/string/)
* Κλάση [XmlNode](../)
* Χώρος ονομάτων [System::Xml](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)