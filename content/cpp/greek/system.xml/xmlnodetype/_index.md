---
title: XmlNodeType
second_title: Aspose.Slides για C++ API Αναφορά
description: Καθορίζει τον τύπο του κόμβου.
type: docs
weight: 833
url: /el/system.xml/xmlnodetype/
---
## XmlNodeType enum

Καθορίζει τον τύπο του κόμβου.

```cpp
enum class XmlNodeType
```

### Τιμές

| Name | Value | Description |
| --- | --- | --- |
| None | 0 | Αυτή επιστρέφεται από το [XmlReader](../xmlreader/) εάν δεν έχει κληθεί η μέθοδος **Read**. |
| Element | 1 | Ένα στοιχείο (για παράδειγμα, **<item>**). |
| Attribute | 2 | Ένα χαρακτηριστικό (για παράδειγμα, **id='123'**). |
| Text | 3 | Το κειμενικό περιεχόμενο ενός κόμβου. Ένας κόμβος [XmlNodeType::Text](./) δεν μπορεί να έχει παιδικούς κόμβους. Μπορεί να εμφανιστεί ως παιδικός κόμβος των κόμβων [XmlNodeType::Attribute](./), [XmlNodeType::DocumentFragment](./), [XmlNodeType::Element](./) και [XmlNodeType::EntityReference](./). |
| CDATA | 4 | Ένα τμήμα CDATA (για παράδειγμα, **my escaped text**). |
| EntityReference | 5 | Μία αναφορά σε οντότητα (για παράδειγμα, **&num;**). |
| Entity | 6 | Μια δήλωση οντότητας (για παράδειγμα, **<!ENTITY...>**). |
| ProcessingInstruction | 7 | Μία οδηγία επεξεργασίας (για παράδειγμα, **<?pi test?>**). |
| Comment | 8 | Ένα σχόλιο (για παράδειγμα, ****). |
| Document | 9 | Ένα αντικείμενο εγγράφου που, ως ρίζα του δένδρου εγγράφου, παρέχει πρόσβαση σε ολόκληρο το έγγραφο XML. |
| DocumentType | 10 | Η δήλωση τύπου εγγράφου, η οποία υποδεικνύεται από την ακόλουθη ετικέτα (για παράδειγμα, **<!DOCTYPE...>**). |
| DocumentFragment | 11 | Ένα τμήμα εγγράφου. |
| Notation | 12 | Μια σημειογραφία στη δήλωση τύπου εγγράφου (για παράδειγμα, **<!NOTATION...>**). |
| Whitespace | 13 | Κενό διάστημα μεταξύ σήμανσης. |
| SignificantWhitespace | 14 | Κενό διάστημα μεταξύ σήμανσης σε ένα μοντέλο μικτής περιεχομένου ή κενό διάστημα εντός του πεδίου **xml:space=\"preserve\"**. |
| EndElement | 15 | Μια ετικέτα τέλους στοιχείου (για παράδειγμα, ****). |
| EndEntity | 16 | Επιστρέφεται όταν το [XmlReader](../xmlreader/) φθάνει στο τέλος της αντικατάστασης οντότητας ως αποτέλεσμα κλήσης του [XmlReader::ResolveEntity](../xmlreader/resolveentity/). |
| XmlDeclaration | 17 | Η δήλωση XML (για παράδειγμα, **<?xml version='1.0'?>**). Ο κόμβος [XmlNodeType::XmlDeclaration](./) πρέπει να είναι ο πρώτος κόμβος στο έγγραφο. Δεν μπορεί να έχει παιδιά. Είναι παιδί του κόμβου [XmlNodeType::Document](./). Μπορεί να έχει χαρακτηριστικά που παρέχουν πληροφορίες έκδοσης και κωδικοποίησης. |

## Δείτε επίσης

* Χώρος ονομάτων [System::Xml](../)
* Βιβλιοθήκη [Aspose.Slides](../../)