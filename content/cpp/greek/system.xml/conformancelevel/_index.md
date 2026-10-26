---
title: ConformanceLevel
second_title: Aspose.Slides για C++ Αναφορά API
description: Καθορίζει το ποσό ελέγχου εισόδου ή εξόδου που εκτελούν τα αντικείμενα XmlReader και XmlWriter.
type: docs
weight: 625
url: /el/system.xml/conformancelevel/
---
## ConformanceLevel enum

Specifies the amount of input or output checking that [XmlReader](../xmlreader/) and [XmlWriter](../xmlwriter/) objects perform.

```cpp
enum class ConformanceLevel
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Auto | 0 | Το αντικείμενο [XmlReader](../xmlreader/) ή [XmlWriter](../xmlwriter/) ανιχνεύει αυτόματα αν πρέπει να γίνει έλεγχος επιπέδου εγγράφου ή επιπέδου τμήματος και εκτελεί τον αντίστοιχο έλεγχο. Εάν τυλίγετε ένα άλλο αντικείμενο [XmlReader](../xmlreader/) ή [XmlWriter](../xmlwriter/), το εξωτερικό αντικείμενο δεν κάνει κανέναν πρόσθετο έλεγχο συμμόρφωσης. Ο έλεγχος συμμόρφωσης αφήνεται στο υποκείμενο αντικείμενο. |
| Fragment | 1 | Τα XML δεδομένα είναι ένα [well-formed XML fragment](https://www.w3.org/TR/2006/REC-xml-20060816/#wf-entities), όπως ορίζεται από το W3C. Αυτό το επίπεδο συμμόρφωσης αντιπροσωπεύει ένα XML έγγραφο που ενδέχεται να μην έχει στοιχείο ρίζας αλλά είναι κατά τα άλλα καλά δομημένο. Αυτό το επίπεδο ελέγχου διασφαλίζει ότι η ροή που διαβάζεται ή γράφεται μπορεί να καταναλωθεί από οποιονδήποτε επεξεργαστή ως ένα [XML 1.0 external parsed entity](https://www.w3.org/TR/2006/REC-xml-20060816/#wf-entities). |
| Document | 2 | Τα XML δεδομένα συμμορφώνονται με τους κανόνες για ένα καλά δομημένο [XML 1.0 document](https://www.w3.org/TR/2006/REC-xml-20060816/#sec-well-formed), όπως ορίζεται από το W3C. Αυτό το επίπεδο ελέγχου διασφαλίζει ότι η ροή που διαβάζεται ή γράφεται μπορεί να καταναλωθεί από οποιονδήποτε επεξεργαστή ως ένα [XML 1.0 document](https://www.w3.org/TR/2006/REC-xml-20060816/#sec-well-formed). |

## Δείτε επίσης

* Χώρος ονομάτων [System::Xml](../)
* Βιβλιοθήκη [Aspose.Slides](../../)