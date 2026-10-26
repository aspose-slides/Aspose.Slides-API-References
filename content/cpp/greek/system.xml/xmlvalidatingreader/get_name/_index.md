---
title: get_Name()
second_title: Aspose.Slides για C++ – Αναφορά API
description: Επιστρέφει το πλήρες όνομα του τρέχοντος κόμβου.
type: docs
weight: 14
url: /el/system.xml/xmlvalidatingreader/get_name/
---
## XmlValidatingReader::get_Name() μέθοδος


Επιστρέφει το πλήρες όνομα του τρέχοντος κόμβου.

```cpp
String System::Xml::XmlValidatingReader::get_Name() override
```


### Τιμή Επιστροφής

Το πλήρες όνομα του τρέχοντος κόμβου. Για παράδειγμα, **Name** είναι **bk:book** για το στοιχείο **<bk:book>**.
## Σχόλια



Το επιστρεφόμενο όνομα εξαρτάται από το XmlValidatingReader::NodeType του κόμβου. Οι ακόλουθοι τύποι κόμβων επιστρέφουν τις αναγραφόμενες τιμές. Όλοι οι άλλοι τύποι κόμβων επιστρέφουν μια κενή συμβολοσειρά. 

| Τύπος Κόμβου | Όνομα |
| --- | --- |
| [Attribute](../../../system/attribute/)| Το όνομα του χαρακτηριστικού. |
| DocumentType| Το όνομα τύπου εγγράφου. |
| Element| Το όνομα ετικέτας. |
| EntityReference| Το όνομα της αναφερόμενης οντότητας. |
| ProcessingInstruction| Ο προορισμός της οδηγίας επεξεργασίας. |
| [XmlDeclaration](../../xmldeclaration/)| Η κυριολεκτική συμβολοσειρά `xml`. |


## Δείτε επίσης

* Κλάση [String](../../../system/string/)
* Κλάση [XmlValidatingReader](../)
* Χώρος ονομάτων [System::Xml](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)