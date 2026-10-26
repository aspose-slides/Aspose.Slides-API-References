---
title: WriteDocType()
second_title: Αναφορά API Aspose.Slides για C++
description: Όταν αντικαθίσταται σε μια παράγωγη κλάση, γράφει τη δήλωση DOCTYPE με το καθορισμένο όνομα και προαιρετικά χαρακτηριστικά.
type: docs
weight: 79
url: /el/system.xml/xmlwriter/writedoctype/
---
## XmlWriter::WriteDocType(const String\&, const String\&, const String\&, const String\&) μέθοδος

Όταν αντικαθίσταται σε μια παράγωγη κλάση, γράφει τη δήλωση DOCTYPE με το καθορισμένο όνομα και προαιρετικά χαρακτηριστικά.

```cpp
virtual void System::Xml::XmlWriter::WriteDocType(const String &name, const String &pubid, const String &sysid, const String &subset)=0
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Το όνομα του DOCTYPE. Πρέπει να μην είναι κενό. |
| pubid | const [String](../../../system/string/)\& | Αν δεν είναι μηδενικό, γράφει επίσης PUBLIC "pubid" "sysid" όπου **pubid** και **sysid** αντικαθίστανται με την τιμή των δοσμένων επιχειρημάτων. |
| sysid | const [String](../../../system/string/)\& | Αν **pubid** είναι **nullptr** και **sysid** δεν είναι μηδενικό, γράφει SYSTEM "sysid" όπου **sysid** αντικαθίσταται με την τιμή αυτού του επιχειρήματος. |
| subset | const [String](../../../system/string/)\& | Αν δεν είναι μηδενικό, γράφει [subset] όπου το subset αντικαθίσταται με την τιμή αυτού του επιχειρήματος. |

## Δείτε επίσης

* Κλάση [String](../../../system/string/)
* Κλάση [XmlWriter](../)
* Χώρος ονομάτων [System::Xml](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)