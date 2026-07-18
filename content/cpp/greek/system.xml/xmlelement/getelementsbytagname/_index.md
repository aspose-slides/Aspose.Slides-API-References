---
title: GetElementsByTagName()
second_title: Αναφορά API Aspose.Slides για C++
description: "Επιστρέφει ένα XmlNodeList που περιέχει μια λίστα με όλα τα απογόμενα στοιχεία που ταιριάζουν με το καθορισμένο XmlElement::get_Name."
type: docs
weight: 287
url: /el/system.xml/xmlelement/getelementsbytagname/
---
## XmlElement::GetElementsByTagName(String) μέθοδος

Επιστρέφει ένα [XmlNodeList](../../xmlnodelist/) που περιέχει μια λίστα με όλα τα απογόμενα στοιχεία που ταιριάζουν με το καθορισμένο [XmlElement::get_Name](../get_name/).

```cpp
virtual SharedPtr<XmlNodeList> System::Xml::XmlElement::GetElementsByTagName(String name)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | [String](../../../system/string/) | Το όνομα ετικέτας για αντιστοίχηση. Αυτό είναι ένα πλήρως προσδιορισμένο όνομα. Συμφωνεί με την τιμή **get_Name** του αντιστοιχισμένου κόμβου. Το αστερίσκο (*) είναι μια ειδική τιμή που ταιριάζει με όλες τις ετικέτες. |

### Τιμή Επιστροφής

Ένα [XmlNodeList](../../xmlnodelist/) που περιέχει μια λίστα με όλους τους αντιστοιχούμενους κόμβους. Η λίστα είναι κενή εάν δεν υπάρχουν αντιστοιχούμενοι κόμβοι.

## XmlElement::GetElementsByTagName(String, String) μέθοδος

Επιστρέφει ένα [XmlNodeList](../../xmlnodelist/) που περιέχει μια λίστα με όλα τα απογόμενα στοιχεία που ταιριάζουν με τις καθορισμένες τιμές [XmlElement::get_LocalName](../get_localname/) και [XmlElement::get_NamespaceURI](../get_namespaceuri/).

```cpp
virtual SharedPtr<XmlNodeList> System::Xml::XmlElement::GetElementsByTagName(String localName, String namespaceURI)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Το τοπικό όνομα για αντιστοίχιση. Το αστερίσκος (*) είναι μια ειδική τιμή που ταιριάζει με όλες τις ετικέτες. |
| namespaceURI | [String](../../../system/string/) | Το URI του χώρου ονομάτων για αντιστοίχιση. |

### Τιμή Επιστροφής

Ένα [XmlNodeList](../../xmlnodelist/) που περιέχει μια λίστα με όλους τους αντιστοιχούμενους κόμβους. Η λίστα είναι κενή εάν δεν υπάρχουν αντιστοιχούμενοι κόμβοι.

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNodeList](../../xmlnodelist/)
* Class [String](../../../system/string/)
* Class [XmlElement](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)