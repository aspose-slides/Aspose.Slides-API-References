---
title: ReadElementContentAsObject()
second_title: Aspose.Slides για C++ API Αναφορά
description: Διαβάζει το τρέχον στοιχείο και επιστρέφει το περιεχόμενο ως Object.
type: docs
weight: 469
url: /el/system.xml/xmlreader/readelementcontentasobject/
---
## XmlReader::ReadElementContentAsObject() μέθοδος

Διαβάζει το τρέχον στοιχείο και επιστρέφει το περιεχόμενο ως [Object](../../../system/object/).

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadElementContentAsObject()
```

### Τιμή επιστροφής

Ένα boxed object του πιο κατάλληλου τύπου. Η τιμή [XmlReader::get_ValueType](../get_valuetype/) καθορίζει τον κατάλληλο τύπο. Εάν το περιεχόμενο είναι τύπου λίστας, αυτή η μέθοδος επιστρέφει έναν πίνακα boxed objects του κατάλληλου τύπου.

## XmlReader::ReadElementContentAsObject(String, String) μέθοδος

Ελέγχει ότι το καθορισμένο τοπικό όνομα και το URI του χώρου ονομάτων ταιριάζει με αυτό του τρέχοντος στοιχείου, κατόπιν διαβάζει το τρέχον στοιχείο και επιστρέφει το περιεχόμενο ως [Object](../../../system/object/).

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadElementContentAsObject(String localName, String namespaceURI)
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Το τοπικό όνομα του στοιχείου. |
| namespaceURI | [String](../../../system/string/) | Το URI του χώρου ονομάτων του στοιχείου. |

### Τιμή επιστροφής

Ένα boxed object του πιο κατάλληλου τύπου. Η τιμή [XmlReader::get_ValueType](../get_valuetype/) καθορίζει τον κατάλληλο τύπο. Εάν το περιεχόμενο είναι τύπου λίστας, αυτή η μέθοδος επιστρέφει έναν πίνακα boxed objects του κατάλληλου τύπου.

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [Object](../../../system/object/)
* Κλάση [XmlReader](../)
* Κλάση [String](../../../system/string/)
* Χώρος ονομάτων [System::Xml](../../)
* Library [Aspose.Slides](../../../)