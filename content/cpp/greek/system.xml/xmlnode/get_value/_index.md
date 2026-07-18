---
title: get_Value()
second_title: Αναφορά API του Aspose.Slides για C++
description: Επιστρέφει την τιμή του κόμβου.
type: docs
weight: 14
url: /el/system.xml/xmlnode/get_value/
---
## XmlNode::get_Value() μέθοδος

Επιστρέφει την τιμή του κόμβου.

```cpp
virtual String System::Xml::XmlNode::get_Value()
```

### Τιμή Επιστροφής

Η τιμή που επιστρέφεται εξαρτάται από το [XmlNode::get_NodeType](../get_nodetype/) του κόμβου: 

| Τύπος | Τιμή |
| --- | --- |
| [Attribute](../../../system/attribute/)| Η τιμή της ιδιότητας. |
| CDATASection | Το περιεχόμενο της ενότητας CDATA. |
| Comment | Το περιεχόμενο του σχολίου. |
| Document | `nullptr`. |
| DocumentFragment | `nullptr`. |
| DocumentType | `nullptr`. |
| Element | `nullptr`. Μπορείτε να χρησιμοποιήσετε τις τιμές XmlElement::InnerText ή [XmlElement::get_InnerXml](../../xmlelement/get_innerxml/) για να αποκτήσετε πρόσβαση στην τιμή του κόμβου στοιχείου. |
| Entity | `nullptr`. |
| EntityReference | `nullptr`. |
| Notation | `nullptr`. |
| ProcessingInstruction | Όλο το περιεχόμενο εκτός του προορισμού. |
| [Text](../../../system.text/)| Το περιεχόμενο του κόμβου κειμένου. |
| SignificantWhitespace | Οι χαρακτήρες λευκού διαστήματος. Το λευκό διάστημα μπορεί να αποτελείται από έναν ή περισσότερους χαρακτήρες διαστήματος, επιστροφές carriage, αλλαγές γραμμής ή καρτέλες. |
| Whitespace | Οι χαρακτήρες λευκού διαστήματος. Το λευκό διάστημα μπορεί να αποτελείται από έναν ή περισσότερους χαρακτήρες διαστήματος, επιστροφές carriage, αλλαγές γραμμής ή καρτέλες. |
| [XmlDeclaration](../../xmldeclaration/)| Το περιεχόμενο της δήλωσης (δηλαδή, όλα μεταξύ `<?xml and ?>`). |

## Δείτε επίσης

* Κλάση [String](../../../system/string/)
* Κλάση [XmlNode](../)
* Χώρος ονομάτων [System::Xml](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)