---
title: SetAttribute()
second_title: Aspose.Slides για την Αναφορά API του C++
description: Ορίζει την τιμή της ιδιότητας με το συγκεκριμένο όνομα.
type: docs
weight: 222
url: /el/system.xml/xmlelement/setattribute/
---
## XmlElement::SetAttribute(String, String) μέθοδος

Ορίζει την τιμή της ιδιότητας με το συγκεκριμένο όνομα.

```cpp
virtual void System::Xml::XmlElement::SetAttribute(String name, String value)
```

### Παράμετρα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | [String](../../../system/string/) | Το όνομα της ιδιότητας που θα δημιουργηθεί ή θα τροποποιηθεί. Αυτό είναι ένα πλήρες όνομα. Εάν το όνομα περιέχει άνω-κάτω τελεία, διαχωρίζεται σε πρόθεση και τοπικό όνομα. |
| value | [String](../../../system/string/) | Η τιμή που θα οριστεί για την ιδιότητα. |

## XmlElement::SetAttribute(String, String, String) μέθοδος

Ορίζει την τιμή της ιδιότητας με το συγκεκριμένο τοπικό όνομα και το URI του χώρου ονομάτων.

```cpp
virtual String System::Xml::XmlElement::SetAttribute(String localName, String namespaceURI, String value)
```

### Παράμετρα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Το τοπικό όνομα της ιδιότητας. |
| namespaceURI | [String](../../../system/string/) | Το URI του χώρου ονομάτων της ιδιότητας. |
| value | [String](../../../system/string/) | Η τιμή που θα οριστεί για την ιδιότητα. |

### Τιμή Επιστροφής

Τιμή της ιδιότητας.

## Δες επίσης

* Κλάση [String](../../../system/string/)
* Κλάση [XmlElement](../)
* Χώρος ονομάτων [System::Xml](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)