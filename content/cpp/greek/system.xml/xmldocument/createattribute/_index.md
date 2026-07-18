---
title: CreateAttribute()
second_title: Aspose.Slides για C++ API Αναφορά
description: Δημιουργεί ένα XmlAttribute με το καθορισμένο όνομα.
type: docs
weight: 274
url: /el/system.xml/xmldocument/createattribute/
---
## XmlDocument::CreateAttribute(const String\&) μέθοδος


Δημιουργεί ένα [XmlAttribute](../../xmlattribute/) με το καθορισμένο όνομα.

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlDocument::CreateAttribute(const String &name)
```


### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Το πλήρες όνομα του χαρακτηριστικού. Εάν το όνομα περιέχει άνω-κάτω τελεία, η τιμή [XmlNode::get_Prefix](../../xmlnode/get_prefix/) αντανακλά το τμήμα του ονόματος που προηγείται της πρώτης άνω-κάτω τελείας και η τιμή [XmlDocument::get_LocalName](../get_localname/) αντανακλά το τμήμα του ονόματος που ακολουθεί την πρώτη άνω-κάτω τελεία. Η τιμή [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/) παραμένει κενή εκτός εάν το πρόθεμα είναι ένα αναγνωρισμένο ενσωματωμένο πρόθεμα όπως **xmlns**. Σε αυτήν την περίπτωση η get_NamespaceURI έχει τιμή [http://www.w3.org/2000/xmlns/](http://www.w3.org/2000/xmlns/). |

### Τιμή επιστροφής

Το νέο [XmlAttribute](../../xmlattribute/).

## XmlDocument::CreateAttribute(const String\&, const String\&) μέθοδος


Δημιουργεί ένα [XmlAttribute](../../xmlattribute/) με το καθορισμένο πλήρες όνομα και [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlDocument::CreateAttribute(const String &qualifiedName, const String &namespaceURI)
```


### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| qualifiedName | const [String](../../../system/string/)\& | Το πλήρες όνομα του χαρακτηριστικού. Εάν το όνομα περιέχει άνω-κάτω τελεία, η τιμή [XmlNode::get_Prefix](../../xmlnode/get_prefix/) αντανακλά το τμήμα του ονόματος που προηγείται της άνω-κάτω τελείας και η τιμή [XmlDocument::get_LocalName](../get_localname/) αντανακλά το τμήμα του ονόματος που ακολουθεί την άνω-κάτω τελεία. |
| namespaceURI | const [String](../../../system/string/)\& | Το namespaceURI του χαρακτηριστικού. Εάν το πλήρες όνομα περιλαμβάνει πρόθεμα **xmlns**, τότε αυτή η παράμετρος πρέπει να είναι [http://www.w3.org/2000/xmlns/](http://www.w3.org/2000/xmlns/). |

### Τιμή επιστροφής

Το νέο [XmlAttribute](../../xmlattribute/).

## XmlDocument::CreateAttribute(const String\&, const String\&, const String\&) μέθοδος


Δημιουργεί ένα [XmlAttribute](../../xmlattribute/) με το καθορισμένο [XmlNode::get_Prefix](../../xmlnode/get_prefix/), [XmlDocument::get_LocalName](../get_localname/) και [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlDocument::CreateAttribute(const String &prefix, const String &localName, const String &namespaceURI)
```


### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | Το πρόθεμα του χαρακτηριστικού (εάν υπάρχει). [String::Empty](../../../system/string/empty/) και **nullptr** είναι ισοδύναμα. |
| localName | const [String](../../../system/string/)\& | Το τοπικό όνομα του χαρακτηριστικού. |
| namespaceURI | const [String](../../../system/string/)\& | Το namespace URI του χαρακτηριστικού (εάν υπάρχει). [String::Empty](../../../system/string/empty/) και **nullptr** είναι ισοδύναμα. Εάν το **prefix** είναι **xmlns**, τότε αυτή η παράμετρος πρέπει να είναι [http://www.w3.org/2000/xmlns/;](http://www.w3.org/2000/xmlns/;) διαφορετικά θα προκληθεί εξαίρεση. |

### Τιμή επιστροφής

Το νέο [XmlAttribute](../../xmlattribute/).

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [XmlAttribute](../../xmlattribute/)
* Κλάση [String](../../../system/string/)
* Κλάση [XmlDocument](../)
* Χώρος ονομάτων [System::Xml](../../)
* Library [Aspose.Slides](../../../)