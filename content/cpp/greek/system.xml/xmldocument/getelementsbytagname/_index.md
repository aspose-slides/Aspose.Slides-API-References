---
title: GetElementsByTagName()
second_title: Αναφορά API του Aspose.Slides για C++
description: Επιστρέφει ένα XmlNodeList που περιέχει μια λίστα με όλα τα απογώμενα στοιχεία που ταιριάζουν με το καθορισμένο όνομα.
type: docs
weight: 443
url: /el/system.xml/xmldocument/getelementsbytagname/
---
## XmlDocument::GetElementsByTagName(String) method

Επιστρέφει ένα [XmlNodeList](../../xmlnodelist/) που περιέχει μια λίστα με όλα τα απογώμενα στοιχεία που ταιριάζουν με το καθορισμένο όνομα.

```cpp
virtual SharedPtr<XmlNodeList> System::Xml::XmlDocument::GetElementsByTagName(String name)
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | Το πλήρως καθορισμένο όνομα προς αντιστοίχιση. Συμφωνεί με την τιμή **get_Name** του αντίστοιχου κόμβου. Η ειδική τιμή **"*"** ταιριάζει με όλες τις ετικέτες. |

### Τιμή Επιστροφής

Ένα [XmlNodeList](../../xmlnodelist/) που περιέχει μια λίστα με όλους τους κόμβους που ταιριάζουν. Εάν κανένας κόμβος δεν ταιριάζει με το **name**, η επιστρεφόμενη συλλογή θα είναι κενή.

## XmlDocument::GetElementsByTagName(String, String) method

Επιστρέφει ένα [XmlNodeList](../../xmlnodelist/) που περιέχει μια λίστα με όλα τα απογώμενα στοιχεία που ταιριάζουν με τα καθορισμένα [XmlDocument::get_LocalName](../get_localname/) και [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
virtual SharedPtr<XmlNodeList> System::Xml::XmlDocument::GetElementsByTagName(String localName, String namespaceURI)
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Το LocalName προς αντιστοίχιση. Η ειδική τιμή **"*"** ταιριάζει με όλες τις ετικέτες. |
| namespaceURI | [String](../../../system/string/) | NamespaceURI προς αντιστοίχιση. |

### Τιμή Επιστροφής

Ένα [XmlNodeList](../../xmlnodelist/) που περιέχει μια λίστα με όλους τους κόμβους που ταιριάζουν. Εάν κανένας κόμβος δεν ταιριάζει με τα καθορισμένα **localName** και **namespaceURI**, η επιστρεφόμενη συλλογή θα είναι κενή.

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNodeList](../../xmlnodelist/)
* Class [String](../../../system/string/)
* Class [XmlDocument](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)