---
title: get_Name()
second_title: Αναφορά API Aspose.Slides για C++
description: Επιστρέφει το πλήρες όνομα του τρέχοντος κόμβου.
type: docs
weight: 14
url: /el/system.xml/xmltextreader/get_name/
---
## XmlTextReader::get_Name() method

Επιστρέφει το πλήρες όνομα του τρέχοντος κόμβου.

```cpp
String System::Xml::XmlTextReader::get_Name() override
```

### Τιμή Επιστροφής

Το πλήρες όνομα του τρέχοντος κόμβου. Για παράδειγμα, **Name** είναι **bk:book** για το στοιχείο **<bk:book>**.

## Παρατηρήσεις

Το επιστρεφόμενο όνομα εξαρτάται από την τιμή [XmlTextReader::get_NodeType](../get_nodetype/) του κόμβου. Οι παρακάτω τύποι κόμβων επιστρέφουν τις αναγραφόμενες τιμές. Όλοι οι άλλοι τύποι κόμβων επιστρέφουν κενή συμβολοσειρά. 

| Τύπος Κόμβου | Όνομα |
| --- | --- |
| [Attribute](../../../system/attribute/)| Το όνομα του χαρακτηριστικού. |
| DocumentType| Το όνομα του τύπου εγγράφου. |
| Element| Το όνομα ετικέτας. |
| EntityReference| Το όνομα της αναφερόμενης οντότητας. |
| ProcessingInstruction| Ο προορισμός της οδηγίας επεξεργασίας. |
| [XmlDeclaration](../../xmldeclaration/)| Η κυριολεκτική συμβολοσειρά `xml`. |

## Δείτε επίσης

* Κλάση [String](../../../system/string/)
* Κλάση [XmlTextReader](../)
* Χώρος ονομάτων [System::Xml](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)