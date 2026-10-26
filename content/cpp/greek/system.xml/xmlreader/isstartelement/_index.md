---
title: IsStartElement()
second_title: Aspose.Slides για C++ API Αναφορά
description: "Καλεί XmlReader::MoveToContent και ελέγχει εάν ο τρέχων κόμβος περιεχομένου είναι μια ετικέτα έναρξης ή μια κενή ετικέτα στοιχείου."
type: docs
weight: 885
url: /el/system.xml/xmlreader/isstartelement/
---
## XmlReader::IsStartElement() μέθοδος

Καλεί [XmlReader::MoveToContent](../movetocontent/) και ελέγχει αν ο τρέχων κόμβος περιεχομένου είναι μια ετικέτα έναρξης ή μια κενή ετικέτα στοιχείου.

```cpp
virtual bool System::Xml::XmlReader::IsStartElement()
```

### Τιμή Επιστροφής

**true** αν [XmlReader::MoveToContent](../movetocontent/) βρίσκει μια ετικέτα έναρξης ή μια κενή ετικέτα στοιχείου· **false** αν βρέθηκε ένας τύπος κόμβου διαφορετικός από [XmlNodeType::Element](../../xmlnodetype/).

## XmlReader::IsStartElement(String) μέθοδος

Καλεί [XmlReader::MoveToContent](../movetocontent/) και ελέγχει αν ο τρέχων κόμβος περιεχομένου είναι μια ετικέτα έναρξης ή μια κενή ετικέτα στοιχείου και αν η τιμή [XmlReader::get_Name](../get_name/) του ευρεθέντος στοιχείου ταιριάζει με το δοσμένο όρισμα.

```cpp
virtual bool System::Xml::XmlReader::IsStartElement(String name)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | [String](../../../system/string/) | Η συμβολοσειρά που ταιριάζει με την τιμή **Name** του ευρεθέντος στοιχείου. |

### Τιμή Επιστροφής

**true** αν ο τελικός κόμβος είναι ένα στοιχείο και η τιμή **Name** ταιριάζει με τη δοσμένη συμβολοσειρά. **false** αν βρέθηκε ένας τύπος κόμβου διαφορετικός από [XmlNodeType::Element](../../xmlnodetype/) ή αν η τιμή **Name** του στοιχείου δεν ταιριάζει με τη δοσμένη συμβολοσειρά.

## XmlReader::IsStartElement(String, String) μέθοδος

Καλεί [XmlReader::MoveToContent](../movetocontent/) και ελέγχει αν ο τρέχων κόμβος περιεχομένου είναι μια ετικέτα έναρξης ή μια κενή ετικέτα στοιχείου και αν οι τιμές [XmlReader::get_LocalName](../get_localname/) και [XmlReader::get_NamespaceURI](../get_namespaceuri/) του ευρεθέντος στοιχείου ταιριάζουν με τις δοσμένες συμβολοσειρές.

```cpp
virtual bool System::Xml::XmlReader::IsStartElement(String localname, String ns)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| localname | [String](../../../system/string/) | Η συμβολοσειρά που ταιριάζει με την τιμή **LocalName** του ευρεθέντος στοιχείου. |
| ns | [String](../../../system/string/) | Η συμβολοσειρά που ταιριάζει με την τιμή **NamespaceURI** του ευρεθέντος στοιχείου. |

### Τιμή Επιστροφής

**true** αν ο τελικός κόμβος είναι ένα στοιχείο. **false** αν βρέθηκε ένας τύπος κόμβου διαφορετικός από [XmlNodeType::Element](../../xmlnodetype/) ή αν οι τιμές **LocalName** και **NamespaceURI** του στοιχείου δεν ταιριάζουν με τις δοσμένες συμβολοσειρές.

## Δείτε επίσης

* Κλάση [XmlReader](../)
* Κλάση [String](../../../system/string/)
* Χώρος ονομάτων [System::Xml](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)