---
title: ReadStartElement()
second_title: Aspose.Slides για C++ – Αναφορά API
description: Ελέγχει ότι ο τρέχων κόμβος είναι ένα στοιχείο και προχωρά τον αναγνώστη στον επόμενο κόμβο.
type: docs
weight: 846
url: /el/system.xml/xmlreader/readstartelement/
---
## XmlReader::ReadStartElement() μέθοδος

Ελέγχει ότι ο τρέχων κόμβος είναι ένα στοιχείο και προχωρά τον αναγνώστη στον επόμενο κόμβο.

```cpp
virtual void System::Xml::XmlReader::ReadStartElement()
```

## XmlReader::ReadStartElement(String) μέθοδος

Ελέγχει ότι ο τρέχων κόμβος περιεχομένου είναι ένα στοιχείο με την δεδομένη τιμή [XmlReader::get_Name](../get_name/) και προχωρά τον αναγνώστη στον επόμενο κόμβο.

```cpp
virtual void System::Xml::XmlReader::ReadStartElement(String name)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | [String](../../../system/string/) | Το πλήρες όνομα του στοιχείου. |

## XmlReader::ReadStartElement(String, String) μέθοδος

Ελέγχει ότι ο τρέχων κόμβος περιεχομένου είναι ένα στοιχείο με τις δεδομένες τιμές [XmlReader::get_LocalName](../get_localname/) και [XmlReader::get_NamespaceURI](../get_namespaceuri/) και προχωρά τον αναγνώστη στον επόμενο κόμβο.

```cpp
virtual void System::Xml::XmlReader::ReadStartElement(String localname, String ns)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| localname | [String](../../../system/string/) | Το τοπικό όνομα του στοιχείου. |
| ns | [String](../../../system/string/) | Το URI του χώρου ονομάτων του στοιχείου. |

## Δείτε επίσης

* Κλάση [XmlReader](../)
* Κλάση [String](../../../system/string/)
* Χώρος ονομάτων [System::Xml](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)