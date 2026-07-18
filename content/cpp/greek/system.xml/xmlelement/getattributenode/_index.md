---
title: GetAttributeNode()
second_title: Aspose.Slides για C++ Αναφορά API
description: Επιστρέφει το XmlAttribute με το καθορισμένο όνομα.
type: docs
weight: 248
url: /el/system.xml/xmlelement/getattributenode/
---
## XmlElement::GetAttributeNode(String) μέθοδος


Επιστρέφει το [XmlAttribute](../../xmlattribute/) με το καθορισμένο όνομα.

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::GetAttributeNode(String name)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | [String](../../../system/string/) | Το όνομα του χαρακτηριστικού για ανάκτηση. Αυτό είναι ένα πλήρως προσδιορισμένο όνομα. Ταιριάζει με την τιμή **get_Name** του αντίστοιχου κόμβου. |

### Τιμή Επιστροφής

Το συγκεκριμένο [XmlAttribute](../../xmlattribute/) ή **nullptr** εάν δεν βρεθεί αντίστοιχο χαρακτηριστικό.

## XmlElement::GetAttributeNode(String, String) μέθοδος


Επιστρέφει το [XmlAttribute](../../xmlattribute/) με το καθορισμένο τοπικό όνομα και το URI ονομαχώρου.

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::GetAttributeNode(String localName, String namespaceURI)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Το τοπικό όνομα του χαρακτηριστικού. |
| namespaceURI | [String](../../../system/string/) | Το URI ονομαχώρου του χαρακτηριστικού. |

### Τιμή Επιστροφής

Το συγκεκριμένο [XmlAttribute](../../xmlattribute/) ή **nullptr** εάν δεν βρεθεί αντίστοιχο χαρακτηριστικό.

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [XmlAttribute](../../xmlattribute/)
* Κλάση [String](../../../system/string/)
* Κλάση [XmlElement](../)
* Χώρος ονομάτων [System::Xml](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)