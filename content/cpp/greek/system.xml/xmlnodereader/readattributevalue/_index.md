---
title: ReadAttributeValue()
second_title: Aspose.Slides για C++ API Αναφορά
description: Αναλύει την τιμή του χαρακτηριστικού σε έναν ή περισσότερους Text, EntityReference ή EndEntity κόμβους.
type: docs
weight: 430
url: /el/system.xml/xmlnodereader/readattributevalue/
---
## XmlNodeReader::ReadAttributeValue() μέθοδος


Αναλύει την τιμή του χαρακτηριστικού σε έναν ή περισσότερους **[Text](../../../system.text/)**, **EntityReference**, ή **EndEntity** κόμβους.

```cpp
bool System::Xml::XmlNodeReader::ReadAttributeValue() override
```


### Τιμή Επιστροφής

**true** εάν υπάρχουν κόμβοι προς επιστροφή. **false** εάν ο αναγνώστης δεν είναι τοποθετημένος σε κόμβο χαρακτηριστικού όταν γίνεται η αρχική κλήση ή εάν έχουν διαβαστεί όλες οι τιμές των χαρακτηριστικών. Ένα κενό χαρακτηριστικό, όπως **misc=\"\"**, επιστρέφει **true** με έναν μοναδικό κόμβο με τιμή [String::Empty](../../../system/string/empty/).

## Δείτε επίσης

* Κλάση [XmlNodeReader](../)
* Χώρος ονομάτων [System::Xml](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)