---
title: get_Name()
second_title: Aspose.Slides για C++ API Αναφορά
description: Όταν παρακάμπτεται σε μια παράγωγη κλάση, επιστρέφει το πλήρες όνομα του τρέχοντος κόμβου.
type: docs
weight: 27
url: /el/system.xml/xmlreader/get_name/
---
## XmlReader::get_Name() μέθοδος


Όταν παρακάμπτεται σε μια παράγωγη κλάση, επιστρέφει το πλήρες όνομα του τρέχοντος κόμβου.

```cpp
virtual String System::Xml::XmlReader::get_Name()
```


### Return Value

Το πλήρες όνομα του τρέχοντος κόμβου. Για παράδειγμα, **Name** είναι **bk:book** για το στοιχείο **<bk:book>**.

## Remarks



Το όνομα που επιστρέφεται εξαρτάται από την τιμή [XmlReader::get_NodeType](../get_nodetype/) του κόμβου. Οι παρακάτω τύποι κόμβων επιστρέφουν τις αναγραφόμενες τιμές. Όλοι οι άλλοι τύποι κόμβων επιστρέφουν μια κενή συμβολοσειρά. 

| Τύπος κόμβου | Όνομα |
| --- | --- |
| `[Attribute](../../../system/attribute/)`| Το όνομα του χαρακτηριστικού. |
| `DocumentType`| Το όνομα του τύπου εγγράφου. |
| `Element`| Το όνομα της ετικέτας. |
| `EntityReference`| Το όνομα της αναφερόμενης οντότητας. |
| `ProcessingInstruction`| Ο προορισμός της οδηγίας επεξεργασίας. |
| [XmlDeclaration](../../xmldeclaration/)| Η κυριολεκτική συμβολοσειρά `xml`. |


## See Also

* Κλάση [String](../../../system/string/)
* Κλάση [XmlReader](../)
* Χώρος ονομάτων [System::Xml](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)