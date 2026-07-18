---
title: IsDerivedFrom()
second_title: Αναφορά API Aspose.Slides για C++
description: Επιστρέφει μια τιμή που υποδεικνύει εάν ο καθορισμένος παράγωγος τύπος σχήματος προέρχεται από τον καθορισμένο βασικό τύπο σχήματος.
type: docs
weight: 209
url: /el/system.xml.schema/xmlschematype/isderivedfrom/
---
## XmlSchemaType::IsDerivedFrom(SharedPtr\<XmlSchemaType\>, const SharedPtr\<XmlSchemaType\>\&, XmlSchemaDerivationMethod) method

Επιστρέφει μια τιμή που υποδεικνύει εάν ο ορισμένος παράγωγος τύπος σχήματος προέρχεται από τον ορισμένο βασικό τύπο σχήματος.

```cpp
static bool System::Xml::Schema::XmlSchemaType::IsDerivedFrom(SharedPtr<XmlSchemaType> derivedType, const SharedPtr<XmlSchemaType> &baseType, XmlSchemaDerivationMethod except)
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| derivedType | [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaType](../)\> | Το παράγωγο [XmlSchemaType](../) για δοκιμή. |
| baseType | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaType](../)\>\& | Το βασικό [XmlSchemaType](../) για τη δοκιμή του παράγωγου [XmlSchemaType](../). |
| except | [XmlSchemaDerivationMethod](../../xmlschemaderivationmethod/) | Μία από τις τιμές XmlSchemaDerivationMethod που αντιπροσωπεύει μια μέθοδο απόδοσης τύπου που πρέπει να αποκλειστεί από τη δοκιμή. |

### Τιμή επιστροφής

**true** εάν ο παράγωγος τύπος προέρχεται από τον βασικό τύπο· διαφορετικά, **false**.

## Δείτε επίσης

* Enum [XmlSchemaDerivationMethod](../../xmlschemaderivationmethod/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [XmlSchemaType](../)
* Χώρος ονομάτων [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)