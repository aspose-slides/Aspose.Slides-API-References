---
title: ReadAttributeValue()
second_title: Aspose.Slides για C++ Αναφορά API
description: Αναλύει την τιμή του χαρακτηριστικού σε έναν ή περισσότερους κόμβους Text, EntityReference ή EndEntity.
type: docs
weight: 508
url: /el/system.xml/xmlvalidatingreader/readattributevalue/
---
## XmlValidatingReader::ReadAttributeValue() μέθοδος

Αναλύει την τιμή του χαρακτηριστικού σε έναν ή περισσότερους **[Text](../../../system.text/)**, **EntityReference**, ή **EndEntity** κόμβους.

```cpp
bool System::Xml::XmlValidatingReader::ReadAttributeValue() override
```

### Τιμή Επιστροφής

**true** εάν υπάρχουν κόμβοι προς επιστροφή. **false** εάν ο αναγνώστης δεν βρίσκεται σε κόμβο χαρακτηριστικού όταν γίνεται η αρχική κλήση ή εάν όλες οι τιμές χαρακτηριστικού έχουν διαβαστεί. Ένα κενό χαρακτηριστικό, όπως **misc=""**, επιστρέφει **true** με έναν μοναδικό κόμβο με τιμή [String::Empty](../../../system/string/empty/).

## Δείτε επίσης

* Κλάση [XmlValidatingReader](../)
* Χώρος ονομάτων [System::Xml](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)