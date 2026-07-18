---
title: get_LocalName()
second_title: Aspose.Slides για C++ API Αναφορά
description: Επιστρέφει το τοπικό όνομα του κόμβου, όταν αντικατασταθεί σε παράγωγη κλάση.
type: docs
weight: 209
url: /el/system.xml/xmlnode/get_localname/
---
## XmlNode::get_LocalName() μέθοδος


Επιστρέφει το τοπικό όνομα του κόμβου, όταν αντικατασταθεί σε παράγωγη κλάση.

```cpp
virtual String System::Xml::XmlNode::get_LocalName()=0
```


### Return Value

Το όνομα του κόμβου χωρίς το πρόθεμα. Για παράδειγμα, **LocalName** είναι **book** για το στοιχείο **<bk:book>**.

## Remarks

Το επιστρεφόμενο όνομα εξαρτάται από το [XmlNode::get_NodeType](../get_nodetype/) του κόμβου: 

| Τύπος | Όνομα |
| --- | --- |
| [Attribute](../../../system/attribute/)| Το τοπικό όνομα του χαρακτηριστικού. |
| CDATA | #cdata-section |
| Comment | #comment |
| Document | #document |
| DocumentFragment | #document-fragment |
| DocumentType | Το όνομα του τύπου εγγράφου. |
| Element | Το τοπικό όνομα του στοιχείου. |
| Entity | Το όνομα της οντότητας. |
| EntityReference | Το όνομα της αναφερόμενης οντότητας. |
| Notation | Το όνομα σημειογραφίας. |
| ProcessingInstruction | Ο προορισμός της οδηγίας επεξεργασίας. |
| [Text](../../../system.text/)| #text |
| Whitespace | #whitespace |
| SignificantWhitespace | #significant-whitespace |
| [XmlDeclaration](../../xmldeclaration/)| #xml-declaration |


## See Also

* Κλάση [String](../../../system/string/)
* Κλάση [XmlNode](../)
* Χώρος ονομάτων [System::Xml](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)