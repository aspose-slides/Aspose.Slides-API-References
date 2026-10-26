---
title: get_Value()
second_title: Αναφορά API Aspose.Slides για C++
description: Επιστρέφει την κειμενική τιμή του τρέχοντος κόμβου.
type: docs
weight: 79
url: /el/system.xml/xmltextreader/get_value/
---
## XmlTextReader::get_Value() μέθοδος

Επιστρέφει την κειμενική τιμή του τρέχοντος κόμβου.

```cpp
String System::Xml::XmlTextReader::get_Value() override
```

### Τιμή επιστροφής

Η τιμή που επιστρέφεται εξαρτάται από την τιμή [XmlTextReader::get_NodeType](../get_nodetype/) του κόμβου.

## Παρατηρήσεις

Ο παρακάτω πίνακας παραθέτει τύπους κόμβων που έχουν τιμή προς επιστροφή. Όλοι οι άλλοι τύποι κόμβων επιστρέφουν [String::Empty](../../../system/string/empty/).

| Τύπος κόμβου | Τιμή |
| --- | --- |
| [Attribute](../../../system/attribute/)| Η τιμή της ιδιότητας. |
| CDATA| Το περιεχόμενο της ενότητας CDATA. |
| Comment| Το περιεχόμενο του σχολίου. |
| DocumentType| Το εσωτερικό υποσύνολο. |
| ProcessingInstruction| Ολόκληρο το περιεχόμενο, εξαιρουμένου του στόχου. |
| SignificantWhitespace| Τα λευκά διαστήματα μέσα σε πεδίο `xml:space='preserve'`. |
| [Text](../../../system.text/)| Το περιεχόμενο του κόμβου κειμένου. |
| Whitespace| Τα λευκά διαστήματα μεταξύ σήμανσης. |
| [XmlDeclaration](../../xmldeclaration/)| Το περιεχόμενο της δήλωσης. |

## Δείτε επίσης

* Κλάση [String](../../../system/string/)
* Κλάση [XmlTextReader](../)
* Χώρος ονομάτων [System::Xml](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)