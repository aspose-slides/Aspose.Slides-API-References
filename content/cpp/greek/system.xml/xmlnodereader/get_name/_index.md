---
title: get_Name()
second_title: Aspose.Slides για την αναφορά API σε C++
description: Επιστρέφει το πλήρες όνομα του τρέχοντος κόμβου.
type: docs
weight: 14
url: /el/system.xml/xmlnodereader/get_name/
---
## XmlNodeReader::get_Name() μέθοδος


Επιστρέφει το πλήρες όνομα του τρέχοντος κόμβου.

```cpp
String System::Xml::XmlNodeReader::get_Name() override
```


### Τιμή Επιστροφής

Το πλήρες όνομα του τρέχοντος κόμβου. Για παράδειγμα, **Name** είναι **bk:book** για το στοιχείο **<bk:book>**.
## Παρατηρήσεις



Το επιστρεφόμενο όνομα εξαρτάται από την τιμή [XmlNodeReader::get_NodeType](../get_nodetype/) του κόμβου. Οι ακόλουθοι τύποι κόμβων επιστρέφουν τις αναγραφόμενες τιμές. Όλοι οι άλλοι τύποι κόμβων επιστρέφουν κενό συμβολοσειρά. 

| Τύπος Κόμβου | Όνομα |
| --- | --- |
| [Attribute](../../../system/attribute/)| Το όνομα του χαρακτηριστικού. |
| DocumentType| Το όνομα του τύπου εγγράφου. |
| Element| Το όνομα της ετικέτας. |
| EntityReference| Το όνομα της αναφερόμενης οντότητας. |
| ProcessingInstruction| Ο στόχος της οδηγίας επεξεργασίας. |
| [XmlDeclaration](../../xmldeclaration/)| Η κυριολεκτική συμβολοσειρά `xml`. |


## Δείτε επίσης

* Κλάση [String](../../../system/string/)
* Κλάση [XmlNodeReader](../)
* Χώρος ονομάτων [System::Xml](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)