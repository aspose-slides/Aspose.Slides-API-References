---
title: Item()
second_title: Aspose.Slides για C++ Αναφορά API
description: Ανακτά τον κόμβο στη συγκεκριμένη θέση δείκτη στο XmlNamedNodeMap.
type: docs
weight: 53
url: /el/system.xml/xmlnamednodemap/item/
---
## XmlNamedNodeMap::Item(int32_t) μέθοδος

Ανακτά τον κόμβο στη συγκεκριμένη θέση δείκτη στο [XmlNamedNodeMap](../).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::Item(int32_t index)
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | **int32_t** | Η θέση του δείκτη του κόμβου που θα ανακτηθεί από το [XmlNamedNodeMap](../). Ο δείκτης είναι μηδενικής βάσης· συνεπώς, ο δείκτης του πρώτου κόμβου είναι 0 και ο δείκτης του τελευταίου κόμβου είναι [XmlNamedNodeMap::get_Count](../get_count/) - 1. |

### Τιμή Επιστροφής

Το [XmlNode](../../xmlnode/) στη συγκεκριμένη θέση δείκτη. Αν το **index** είναι μικρότερο από 0 ή μεγαλύτερο ή ίσο με την τιμή [XmlNamedNodeMap::get_Count](../get_count/), επιστρέφεται **nullptr**.

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [XmlNode](../../xmlnode/)
* Κλάση [XmlNamedNodeMap](../)
* Ονομαχώρος [System::Xml](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)