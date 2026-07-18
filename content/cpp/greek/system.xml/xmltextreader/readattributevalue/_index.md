---
title: ReadAttributeValue()
second_title: Αναφορά API του Aspose.Slides για C++
description: Αναλύει την τιμή του χαρακτηριστικού σε έναν ή περισσότερους Text, EntityReference ή EndEntity κόμβους.
type: docs
weight: 560
url: /el/system.xml/xmltextreader/readattributevalue/
---
## XmlTextReader::ReadAttributeValue() μέθοδος

Αναλύει την τιμή του χαρακτηριστικού σε έναν ή περισσότερους **[Text](../../../system.text/)**, **EntityReference**, ή **EndEntity** κόμβους.

```cpp
bool System::Xml::XmlTextReader::ReadAttributeValue() override
```

### Τιμή Επιστροφής

**true** αν υπάρχουν κόμβοι προς επιστροφή. **false** αν ο αναγνώστης δεν βρίσκεται σε κόμβο χαρακτηριστικού όταν γίνεται η αρχική κλήση ή αν όλες οι τιμές χαρακτηριστικού έχουν διαβαστεί. Ένα κενό χαρακτηριστικό, όπως **misc=\"\"**, επιστρέφει **true** με έναν μόνο κόμβο με τιμή [String::Empty](../../../system/string/empty/).

## Δείτε επίσης

* Κλάση [XmlTextReader](../)
* Χώρος ονομάτων [System::Xml](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)