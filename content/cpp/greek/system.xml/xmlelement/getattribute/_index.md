---
title: GetAttribute()
second_title: Aspose.Slides για C++ Αναφορά API
description: Επιστρέφει τη τιμή της ιδιότητας με το καθορισμένο όνομα.
type: docs
weight: 209
url: /el/system.xml/xmlelement/getattribute/
---
## XmlElement::GetAttribute(String) μέθοδος

Επιστρέφει την τιμή για την ιδιότητα με το καθορισμένο όνομα.

```cpp
virtual String System::Xml::XmlElement::GetAttribute(String name)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | Το όνομα της ιδιότητας που θα ανακτηθεί. Αυτό είναι ένα πλήρες όνομα. Συμφωνεί με την τιμή **get_Name** του αντίστοιχου κόμβου. |

### Return Value

Η τιμή της καθορισμένης ιδιότητας. Επιστρέφεται κενή συμβολοσειρά εάν δεν βρεθεί αντίστοιχη ιδιότητα ή εάν η ιδιότητα δεν έχει καθορισμένη ή προεπιλεγμένη τιμή.

## XmlElement::GetAttribute(String, String) μέθοδος

Επιστρέφει την τιμή για την ιδιότητα με το καθορισμένο τοπικό όνομα και το URI του χώρου ονομάτων.

```cpp
virtual String System::Xml::XmlElement::GetAttribute(String localName, String namespaceURI)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Το τοπικό όνομα της ιδιότητας που θα ανακτηθεί. |
| namespaceURI | [String](../../../system/string/) | Το URI του χώρου ονομάτων της ιδιότητας που θα ανακτηθεί. |

### Return Value

Η τιμή της καθορισμένης ιδιότητας. Επιστρέφεται κενή συμβολοσειρά εάν δεν βρεθεί αντίστοιχη ιδιότητα ή εάν η ιδιότητα δεν έχει καθορισμένη ή προεπιλεγμένη τιμή.

## See Also

* Κλάση [String](../../../system/string/)
* Κλάση [XmlElement](../)
* Χώρος ονομάτων [System::Xml](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)