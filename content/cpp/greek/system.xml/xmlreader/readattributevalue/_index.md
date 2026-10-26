---
title: ReadAttributeValue()
second_title: Aspose.Slides για C++ API Αναφορά
description: Όταν αντικαθίσταται σε μια παράγωγη κλάση, αναλύει την τιμή του χαρακτηριστικού σε έναν ή περισσότερους Text, EntityReference ή EndEntity κόμβους.
type: docs
weight: 677
url: /el/system.xml/xmlreader/readattributevalue/
---
## XmlReader::ReadAttributeValue() μέθοδος


Όταν αντικαθίσταται σε μια παράγωγη κλάση, αναλύει την τιμή του χαρακτηριστικού σε ένα ή περισσότερα **[Text](../../../system.text/)**, **EntityReference**, ή **EndEntity** κόμβους.

```cpp
virtual bool System::Xml::XmlReader::ReadAttributeValue()=0
```


### Τιμή Επιστροφής

**true** εάν υπάρχουν κόμβοι προς επιστροφή. **false** εάν ο αναγνώστης δεν βρίσκεται σε κόμβο χαρακτηριστικού όταν γίνεται η αρχική κλήση ή εάν όλες οι τιμές του χαρακτηριστικού έχουν διαβαστεί. Ένα κενό χαρακτηριστικό, όπως **misc=\"\"**, επιστρέφει **true** με έναν μόνο κόμβο με τιμή [String::Empty](../../../system/string/empty/).

## Δείτε επίσης

* Κλάση [XmlReader](../)
* Χώρος ονομάτων [System::Xml](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)