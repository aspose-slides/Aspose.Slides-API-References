---
title: MoveToContent()
second_title: Aspose.Slides για C++ Αναφορά API
description: "Ελέγχει εάν ο τρέχων κόμβος είναι κόμβος περιεχομένου (κείμενο χωρίς λευκό διάστημα, CDATA, Element, EndElement, EntityReference ή EndEntity). Εάν ο κόμβος δεν είναι κόμβος περιεχομένου, ο αναγνώστης προχωρά στον επόμενο κόμβο περιεχομένου ή στο τέλος του αρχείου. Παραλείπει κόμβους του ακόλουθου τύπου: ProcessingInstruction, DocumentType, Comment, Whitespace ή SignificantWhitespace."
type: docs
weight: 833
url: /el/system.xml/xmlreader/movetocontent/
---
## XmlReader::MoveToContent() method

Ελέγχει εάν ο τρέχων κόμβος είναι ένας κόμβος περιεχομένου (κείμενο χωρίς λευκά διάστημα, **CDATA**, **Element**, **EndElement**, **EntityReference**, ή **EndEntity**). Εάν ο κόμβος δεν είναι κόμβος περιεχομένου, ο αναγνώστης προχωράει στον επόμενο κόμβο περιεχομένου ή στο τέλος του αρχείου. Παραλείπει κόμβους του ακόλουθου τύπου: **ProcessingInstruction**, **DocumentType**, **Comment**, **Whitespace**, ή **SignificantWhitespace**.

```cpp
virtual XmlNodeType System::Xml::XmlReader::MoveToContent()
```

### Τιμή Επιστροφής

Η [XmlReader::get_NodeType](../get_nodetype/) τιμή του τρέχοντος κόμβου που βρέθηκε από τη μέθοδο ή [XmlNodeType::None](../../xmlnodetype/) εάν ο αναγνώστης έχει φτάσει στο τέλος της ροής εισόδου.

## Δείτε επίσης

* Enum [XmlNodeType](../../xmlnodetype/)
* Κλάση [XmlReader](../)
* Χώρος ονομάτων [System::Xml](../../)
* Library [Aspose.Slides](../../../)