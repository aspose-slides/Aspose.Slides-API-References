---
title: ValidateAttribute()
second_title: Aspose.Slides για C++ Αναφορά API
description: Επικυρώνει το όνομα του χαρακτηριστικού, το URI του ονόματος χώρου και την τιμή στο τρέχον πλαίσιο στοιχείου.
type: docs
weight: 144
url: /el/system.xml.schema/xmlschemavalidator/validateattribute/
---
## XmlSchemaValidator::ValidateAttribute(const String\&, const String\&, const String\&, const SharedPtr\<XmlSchemaInfo\>\&) μέθοδος

Επικυρώνει το όνομα του χαρακτηριστικού, το URI του ονόματος χώρου και την τιμή στο τρέχον πλαίσιο στοιχείου.

```cpp
SharedPtr<Object> System::Xml::Schema::XmlSchemaValidator::ValidateAttribute(const String &localName, const String &namespaceUri, const String &attributeValue, const SharedPtr<XmlSchemaInfo> &schemaInfo)
```

### Arguments

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | Το τοπικό όνομα του χαρακτηριστικού που θα επικυρωθεί. |
| namespaceUri | const [String](../../../system/string/)\& | Το URI του ονόματος χώρου του χαρακτηριστικού που θα επικυρωθεί. |
| attributeValue | const [String](../../../system/string/)\& | Η τιμή του χαρακτηριστικού που θα επικυρωθεί. |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | Ένα αντικείμενο [XmlSchemaInfo](../../xmlschemainfo/) του οποίου οι ιδιότητες ορίζονται μετά την επιτυχή επικύρωση του χαρακτηριστικού. Αυτή η παράμετρος μπορεί να είναι **nullptr**. |

### Return Value

Η τιμή του επικυρωμένου χαρακτηριστικού.

## XmlSchemaValidator::ValidateAttribute(const String\&, const String\&, XmlValueGetter, const SharedPtr\<XmlSchemaInfo\>\&) μέθοδος

Επικυρώνει το όνομα του χαρακτηριστικού, το URI του ονόματος χώρου και την τιμή στο τρέχον πλαίσιο στοιχείου.

```cpp
SharedPtr<Object> System::Xml::Schema::XmlSchemaValidator::ValidateAttribute(const String &localName, const String &namespaceUri, XmlValueGetter attributeValue, const SharedPtr<XmlSchemaInfo> &schemaInfo)
```

### Arguments

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | Το τοπικό όνομα του χαρακτηριστικού που θα επικυρωθεί. |
| namespaceUri | const [String](../../../system/string/)\& | Το URI του ονόματος χώρου του χαρακτηριστικού που θα επικυρωθεί. |
| attributeValue | [XmlValueGetter](../../xmlvaluegetter/) | Μία κλήση XmlValueGetter που χρησιμοποιείται για τη μεταφορά της τιμής του χαρακτηριστικού ως τύπου συμβατού με τον τύπο XML [Schema](../../) Definition Language (XSD) του χαρακτηριστικού. |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | Ένα αντικείμενο [XmlSchemaInfo](../../xmlschemainfo/) του οποίου οι ιδιότητες ορίζονται μετά την επιτυχή επικύρωση του χαρακτηριστικού. Αυτή η παράμετρος μπορεί να είναι **nullptr**. |

### Return Value

Η τιμή του επικυρωμένου χαρακτηριστικού.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [XmlValueGetter](../../xmlvaluegetter/)
* Κλάση [Object](../../../system/object/)
* Κλάση [String](../../../system/string/)
* Κλάση [XmlSchemaInfo](../../xmlschemainfo/)
* Κλάση [XmlSchemaValidator](../)
* Χώρος ονομάτων [System::Xml::Schema](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)