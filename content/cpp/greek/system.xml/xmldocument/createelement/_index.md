---
title: CreateElement()
second_title: Aspose.Slides για C++ API Reference
description: Δημιουργεί ένα στοιχείο με το καθορισμένο όνομα.
type: docs
weight: 339
url: /el/system.xml/xmldocument/createelement/
---
## XmlDocument::CreateElement(const String\&) μέθοδος

Δημιουργεί ένα στοιχείο με το καθορισμένο όνομα.

```cpp
SharedPtr<XmlElement> System::Xml::XmlDocument::CreateElement(const String &name)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Το πλήρες όνομα του στοιχείου. Εάν το όνομα περιέχει άνω-κάτω τελεία, τότε η τιμή [XmlNode::get_Prefix](../../xmlnode/get_prefix/) αντιπροσωπεύει το τμήμα του ονόματος πριν από την άνω-κάτω τελεία και η τιμή [XmlDocument::get_LocalName](../get_localname/) αντιπροσωπεύει το τμήμα του ονόματος μετά την άνω-κάτω τελεία. Το πλήρες όνομα δεν μπορεί να περιλαμβάνει πρόθεμα **xmlns**. |

### Τιμή Επιστροφής

Το νέο [XmlElement](../../xmlelement/).

## XmlDocument::CreateElement(const String\&, const String\&) μέθοδος

Δημιουργεί ένα [XmlElement](../../xmlelement/) με το πλήρες όνομα και [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
SharedPtr<XmlElement> System::Xml::XmlDocument::CreateElement(const String &qualifiedName, const String &namespaceURI)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| qualifiedName | const [String](../../../system/string/)\& | Το πλήρες όνομα του στοιχείου. Εάν το όνομα περιέχει άνω-κάτω τελεία, τότε η τιμή [XmlNode::get_Prefix](../../xmlnode/get_prefix/) θα αντικατοπτρίζει το τμήμα του ονόματος πριν από την άνω-κάτω τελεία και η τιμή [XmlDocument::get_LocalName](../get_localname/) θα αντικατοπτρίζει το τμήμα του ονόματος μετά την άνω-κάτω τελεία. Το πλήρες όνομα δεν μπορεί να περιλαμβάνει πρόθεμα **xmlns**. |
| namespaceURI | const [String](../../../system/string/)\& | Το URI του χώρου ονομάτων του στοιχείου. |

### Τιμή Επιστροφής

Το νέο [XmlElement](../../xmlelement/).

## XmlDocument::CreateElement(const String\&, const String\&, const String\&) μέθοδος

Δημιουργεί ένα στοιχείο με τα καθορισμένα [XmlNode::get_Prefix](../../xmlnode/get_prefix/), [XmlDocument::get_LocalName](../get_localname/) και [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
virtual SharedPtr<XmlElement> System::Xml::XmlDocument::CreateElement(const String &prefix, const String &localName, const String &namespaceURI)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | Το πρόθεμα του νέου στοιχείου (αν υπάρχει). [String::Empty](../../../system/string/empty/) και **nullptr** είναι ισοδύναμα. |
| localName | const [String](../../../system/string/)\& | Το τοπικό όνομα του νέου στοιχείου. |
| namespaceURI | const [String](../../../system/string/)\& | Το URI του χώρου ονομάτων του νέου στοιχείου (αν υπάρχει). [String::Empty](../../../system/string/empty/) και **nullptr** είναι ισοδύναμα. |

### Τιμή Επιστροφής

Το νέο [XmlElement](../../xmlelement/).

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [XmlElement](../../xmlelement/)
* Κλάση [String](../../../system/string/)
* Κλάση [XmlDocument](../)
* Χώρος ονομάτων [System::Xml](../../)
* Library [Aspose.Slides](../../../)