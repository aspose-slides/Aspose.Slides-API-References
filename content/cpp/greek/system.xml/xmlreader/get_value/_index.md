---
title: get_Value()
second_title: Aspose.Slides για C++ Αναφορά API
description: Όταν αντικαθίσταται σε παράγωγη κλάση, λαμβάνει την τιμή κειμένου του τρέχοντος κόμβου.
type: docs
weight: 92
url: /el/system.xml/xmlreader/get_value/
---
## XmlReader::get_Value() μέθοδος

Όταν αντικαθίσταται σε παράγωγη κλάση, επιστρέφει την τιμή κειμένου του τρέχοντος κόμβου.

```cpp
virtual String System::Xml::XmlReader::get_Value()=0
```

### Τιμή Επιστροφής

Η τιμή που επιστρέφεται εξαρτάται από την τιμή [XmlReader::get_NodeType](../get_nodetype/) του κόμβου.

## Παρατηρήσεις

Ο ακόλουθος πίνακας καταγράφει τους τύπους κόμβων που έχουν τιμή προς επιστροφή. Όλοι οι άλλοι τύποι κόμβων επιστρέφουν [String::Empty](../../../system/string/empty/).

| Node type | Value |
| --- | --- |
| `[Attribute](../../../system/attribute/)`| Η τιμή του χαρακτηριστικού. |
| `CDATA`| Το περιεχόμενο της ενότητας CDATA. |
| `Comment`| Το περιεχόμενο του σχολίου. |
| `DocumentType`| Το εσωτερικό υποσύνολο. |
| `ProcessingInstruction`| Ολόκληρο το περιεχόμενο, χωρίς τον προορισμό. |
| `SignificantWhitespace`| Το λευκό διάστημα μεταξύ σήμανσης σε μοντέλο μικτής δομής. |
| `[Text](../../../system.text/)`| Το περιεχόμενο του κόμβου κειμένου. |
| `Whitespace`| Το λευκό διάστημα μεταξύ σήμανσης. |
| [XmlDeclaration](../../xmldeclaration/)| Το περιεχόμενο της δήλωσης. |

## Δείτε επίσης

* Κλάση [String](../../../system/string/)
* Κλάση [XmlReader](../)
* Χώρος ονομάτων [System::Xml](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)