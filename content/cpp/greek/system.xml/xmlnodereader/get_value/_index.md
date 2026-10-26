---
title: get_Value()
second_title: Aspose.Slides για C++ API Αναφορά
description: Επιστρέφει την τιμή κειμένου του τρέχοντος κόμβου.
type: docs
weight: 79
url: /el/system.xml/xmlnodereader/get_value/
---
## XmlNodeReader::get_Value() μέθοδος

Returns the text value of the current node.

```cpp
String System::Xml::XmlNodeReader::get_Value() override
```

### Τιμή Επιστροφής

The value returned depends on the [XmlNodeReader::get_NodeType](../get_nodetype/) of the node.

## Παρατηρήσεις

The following table lists node types that have a value to return. All other node types return [String::Empty](../../../system/string/empty/). 

| Node Type | Value |
| --- | --- |
| [Attribute](../../../system/attribute/)| Η τιμή του χαρακτηριστικού. |
| CDATA| Το περιεχόμενο της ενότητας CDATA. |
| Comment| Το περιεχόμενο του σχολίου. |
| DocumentType| Το εσωτερικό υποσύνολο. |
| ProcessingInstruction| Ολόκληρο το περιεχόμενο, εξαιρώντας τον προορισμό. |
| SignificantWhitespace| Το λευκό διάστημα μεταξύ σήμανσης σε μοντέλο μικτής περιεχομένου. |
| [Text](../../../system.text/)| Το περιεχόμενο του κόμβου κειμένου. |
| Whitespace| Το λευκό διάστημα μεταξύ σήμανσης. |
| [XmlDeclaration](../../xmldeclaration/)| Το περιεχόμενο της δήλωσης. |

## Δείτε Επίσης

* Κλάση [String](../../../system/string/)
* Κλάση [XmlNodeReader](../)
* Χώρος ονομάτων [System::Xml](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)