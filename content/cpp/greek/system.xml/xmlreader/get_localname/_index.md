---
title: get_LocalName()
second_title: Aspose.Slides για C++ Αναφορά API
description: Όταν αντικαθίσταται σε υποκλάση, επιστρέφει το τοπικό όνομα του τρέχοντος κόμβου.
type: docs
weight: 40
url: /el/system.xml/xmlreader/get_localname/
---
## XmlReader::get_LocalName() μέθοδος

Όταν αντικαθίσταται σε υποκλάση, επιστρέφει το τοπικό όνομα του τρέχοντος κόμβου.

```cpp
virtual String System::Xml::XmlReader::get_LocalName()=0
```

### Τιμή επιστροφής

Το όνομα του τρέχοντος κόμβου με το πρόθεμα αφαιρεμένο. Για παράδειγμα, **LocalName** είναι **book** για το στοιχείο **<bk:book>**. Για τύπους κόμβων που δεν έχουν όνομα (όπως **[Text](../../../system.text/)**, **Comment**, κ.λπ.), αυτή η μέθοδος επιστρέφει [String::Empty](../../../system/string/empty/).

## Δείτε επίσης

* Κλάση [String](../../../system/string/)
* Κλάση [XmlReader](../)
* Χώρος ονομάτων [System::Xml](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)