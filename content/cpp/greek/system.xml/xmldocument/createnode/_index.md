---
title: CreateNode()
second_title: Aspose.Slides για την Αναφορά API του C++
description: "Δημιουργεί ένα XmlNode με το καθορισμένο XmlNodeType, XmlNode::get_Prefix, XmlDocument::get_Name και XmlNode::get_NamespaceURI."
type: docs
weight: 482
url: /el/system.xml/xmldocument/createnode/
---
## XmlDocument::CreateNode(XmlNodeType, const String\&, const String\&, const String\&) μέθοδος

Δημιουργεί ένα [XmlNode](../../xmlnode/) με το καθορισμένο XmlNodeType, [XmlNode::get_Prefix](../../xmlnode/get_prefix/), [XmlDocument::get_Name](../get_name/) και [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlDocument::CreateNode(XmlNodeType type, const String &prefix, const String &name, const String &namespaceURI)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| type | [XmlNodeType](../../xmlnodetype/) | Το XmlNodeType του νέου κόμβου. |
| prefix | const [String](../../../system/string/)\& | Το πρόθεμα του νέου κόμβου. |
| name | const [String](../../../system/string/)\& | Το τοπικό όνομα του νέου κόμβου. |
| namespaceURI | const [String](../../../system/string/)\& | Το URI του χώρου ονομάτων του νέου κόμβου. |

### Τιμή Επιστροφής

Το νέο [XmlNode](../../xmlnode/).

## XmlDocument::CreateNode(const String\&, const String\&, const String\&) μέθοδος

Δημιουργεί ένα [XmlNode](../../xmlnode/) με τον καθορισμένο τύπο κόμβου, [XmlDocument::get_Name](../get_name/) και [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlDocument::CreateNode(const String &nodeTypeString, const String &name, const String &namespaceURI)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| nodeTypeString | const [String](../../../system/string/)\& | [String](../../../system/string/) έκδοση του XmlNodeType του νέου κόμβου. Αυτό το όρισμα πρέπει να είναι μία από τις τιμές που εμφανίζονται στον παρακάτω πίνακα. |
| name | const [String](../../../system/string/)\& | Το πλήρες όνομα του νέου κόμβου. Εάν το όνομα περιέχει άνω τελεία, αναλύεται σε στοιχεία [XmlNode::get_Prefix](../../xmlnode/get_prefix/) και [XmlDocument::get_LocalName](../get_localname/). |
| namespaceURI | const [String](../../../system/string/)\& | Το URI του χώρου ονομάτων του νέου κόμβου. |

### Τιμή Επιστροφής

Το νέο [XmlNode](../../xmlnode/).

## Παρατηρήσεις

Η παράμετρος **nodeTypeString** είναι ευαίσθητη στις κεφαλαίες και πρέπει να είναι μία από τις τιμές στον παρακάτω πίνακα:

| nodeTypeString| XmlNodeType |
| --- | --- |
| attribute| [Attribute](../../../system/attribute/)|
| cdatasection| CDATA |
| comment| Comment |
| document| Document |
| documentfragment| DocumentFragment |
| documenttype| DocumentType |
| element| Element |
| entityreference| EntityReference |
| processinginstruction| ProcessingInstruction |
| significantwhitespace| SignificantWhitespace |
| text| [Text](../../../system.text/)|
| whitespace| Whitespace |

## XmlDocument::CreateNode(XmlNodeType, const String\&, const String\&) μέθοδος

Δημιουργεί ένα [XmlNode](../../xmlnode/) με το καθορισμένο XmlNodeType, [XmlDocument::get_Name](../get_name/) και [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlDocument::CreateNode(XmlNodeType type, const String &name, const String &namespaceURI)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| type | [XmlNodeType](../../xmlnodetype/) | Το XmlNodeType του νέου κόμβου. |
| name | const [String](../../../system/string/)\& | Το πλήρες όνομα του νέου κόμβου. Εάν το όνομα περιέχει άνω τελεία, τότε αναλύεται σε στοιχεία [XmlNode::get_Prefix](../../xmlnode/get_prefix/) και [XmlDocument::get_LocalName](../get_localname/). |
| namespaceURI | const [String](../../../system/string/)\& | Το URI του χώρου ονομάτων του νέου κόμβου. |

### Τιμή Επιστροφής

Το νέο [XmlNode](../../xmlnode/).

## Δείτε επίσης

* Enum [XmlNodeType](../../xmlnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [String](../../../system/string/)
* Class [XmlDocument](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)