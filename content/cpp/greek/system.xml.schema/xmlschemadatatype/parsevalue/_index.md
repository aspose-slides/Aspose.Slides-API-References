---
title: ParseValue()
second_title: Aspose.Slides για C++ Αναφορά API
description: Όταν παρακαμφθεί σε μια παράγωγη κλάση, επαληθεύει το string που καθορίζεται έναντι ενός ενσωματωμένου ή προσαρμοσμένου απλού τύπου.
type: docs
weight: 53
url: /el/system.xml.schema/xmlschemadatatype/parsevalue/
---
## XmlSchemaDatatype::ParseValue(String, SharedPtr\<XmlNameTable\>, SharedPtr\<IXmlNamespaceResolver\>) μέθοδος

Όταν παρακαμφθεί σε μια παραγωγική κλάση, επαληθεύει το **string** που καθορίζεται έναντι ενός ενσωματωμένου ή προσαρμοσμένου απλού τύπου.

```cpp
virtual SharedPtr<Object> System::Xml::Schema::XmlSchemaDatatype::ParseValue(String s, SharedPtr<XmlNameTable> nameTable, SharedPtr<IXmlNamespaceResolver> nsmgr)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| s | [String](../../../system/string/) | Το **string** για επαλήθευση έναντι του απλού τύπου. |
| nameTable | [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../../system.xml/xmlnametable/)\> | Το [XmlNameTable](../../../system.xml/xmlnametable/) που θα χρησιμοποιηθεί για την ατομικοποίηση κατά την ανάλυση του **string** εάν αυτό το αντικείμενο [XmlSchemaDatatype](../) αντιπροσωπεύει τον τύπο **xs:NCName**. |
| nsmgr | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | Το αντικείμενο [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) που θα χρησιμοποιηθεί κατά την ανάλυση του **string** εάν αυτό το αντικείμενο [XmlSchemaDatatype](../) αντιπροσωπεύει τον τύπο **xs:QName**. |

### Τιμή Επιστροφής

Ένα [Object](../../../system/object/) που μπορεί να μετατραπεί με ασφάλεια στον τύπο που επιστρέφεται από την κλήση [XmlSchemaDatatype::get_ValueType](../get_valuetype/).

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [Object](../../../system/object/)
* Κλάση [String](../../../system/string/)
* Κλάση [XmlNameTable](../../../system.xml/xmlnametable/)
* Κλάση [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Κλάση [XmlSchemaDatatype](../)
* Χώρος ονομάτων [System::Xml::Schema](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)