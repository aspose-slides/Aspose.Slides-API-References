---
title: get_Value()
second_title: Aspose.Slides για C++ API Αναφορά
description: Επιστρέφει την κειμενική τιμή του τρέχοντος κόμβου.
type: docs
weight: 79
url: /el/system.xml/xmlvalidatingreader/get_value/
---
## XmlValidatingReader::get_Value() μέθοδος

Επιστρέφει την κειμενική τιμή του τρέχοντος κόμβου.

```cpp
String System::Xml::XmlValidatingReader::get_Value() override
```

### Τιμή Επιστροφής

Η επιστρεφόμενη τιμή εξαρτάται από το XmlValidatingReader::NodeType του κόμβου.

## Παρατηρήσεις



Ο ακόλουθος πίνακας παραθέτει τύπους κόμβων που έχουν τιμή για επιστροφή. Όλοι οι άλλοι τύποι κόμβων επιστρέφουν [String::Empty](../../../system/string/empty/). 

| Τύπος Κόμβου | Τιμή |
| --- | --- |
| [Attribute](../../../system/attribute/)| Η τιμή του χαρακτηριστικού. |
| CDATA| Το περιεχόμενο της ενότητας CDATA. |
| Comment| Το περιεχόμενο του σχολίου. |
| DocumentType| Το εσωτερικό υποσύνολο. |
| ProcessingInstruction| Ολόκληρο το περιεχόμενο, χωρίς τον προορισμό. |
| SignificantWhitespace| Το λευκό διάστημα μεταξύ σημάνσεων σε ένα μοντέλο μικτής περιεχομένου. |
| [Text](../../../system.text/)| Το περιεχόμενο του κόμβου κειμένου. |
| Whitespace| Το λευκό διάστημα μεταξύ σημάνσεων. |
| [XmlDeclaration](../../xmldeclaration/)| Το περιεχόμενο της δήλωσης. |

## Δείτε επίσης

* Κλάση [String](../../../system/string/)
* Κλάση [XmlValidatingReader](../)
* Χώρος ονομάτων [System::Xml](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)