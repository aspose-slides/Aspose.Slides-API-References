---
title: WriteDocType()
second_title: Aspose.Slides για C++ Αναφορά API
description: Γράφει τη δήλωση DOCTYPE με το καθορισμένο όνομα και προαιρετικά χαρακτηριστικά.
type: docs
weight: 222
url: /el/system.xml/xmltextwriter/writedoctype/
---
## XmlTextWriter::WriteDocType(const String\&, const String\&, const String\&, const String\&) μέθοδος


Γράφει τη δήλωση DOCTYPE με το καθορισμένο όνομα και προαιρετικά χαρακτηριστικά.

```cpp
void System::Xml::XmlTextWriter::WriteDocType(const String &name, const String &pubid, const String &sysid, const String &subset) override
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Το όνομα του DOCTYPE. Πρέπει να μην είναι κενό. |
| pubid | const [String](../../../system/string/)\& | Εάν δεν είναι null, γράφει επίσης PUBLIC \"pubid\" \"sysid\" όπου **pubid** και **sysid** αντικαθίστανται με την τιμή των δεδομένων ορισμάτων. |
| sysid | const [String](../../../system/string/)\& | Εάν το **pubid** είναι null και το **sysid** δεν είναι null, γράφει SYSTEM \"sysid\" όπου **sysid** αντικαθίσταται με την τιμή αυτού του ορίσματος. |
| subset | const [String](../../../system/string/)\& | Εάν δεν είναι null, γράφει [subset] όπου το subset αντικαθίσταται με την τιμή αυτού του ορίσματος. |

## See Also

* Κλάση [String](../../../system/string/)
* Κλάση [XmlTextWriter](../)
* Χώρος ονομάτων [System::Xml](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)