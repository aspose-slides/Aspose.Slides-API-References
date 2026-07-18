---
title: ValidateElement()
second_title: Aspose.Slides για C++ - Αναφορά API
description: Επικυρώνει το στοιχείο στο τρέχον πλαίσιο.
type: docs
weight: 131
url: /el/system.xml.schema/xmlschemavalidator/validateelement/
---
## XmlSchemaValidator::ValidateElement(const String\&, const String\&, const SharedPtr\<XmlSchemaInfo\>\&) μέθοδος

Επικυρώνει το στοιχείο στο τρέχον πλαίσιο.

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateElement(const String &localName, const String &namespaceUri, const SharedPtr<XmlSchemaInfo> &schemaInfo)
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | Το τοπικό όνομα του στοιχείου για επικύρωση. |
| namespaceUri | const [String](../../../system/string/)\& | Το URI του ονόματος χώρου του στοιχείου για επικύρωση. |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | Ένα αντικείμενο [XmlSchemaInfo](../../xmlschemainfo/) των οποίων οι ιδιότητες ορίζονται μετά από επιτυχημένη επικύρωση του ονόματος του στοιχείου. Αυτή η παράμετρος μπορεί να είναι **nullptr**. |

## XmlSchemaValidator::ValidateElement(const String\&, const String\&, const SharedPtr\<XmlSchemaInfo\>\&, const String\&, const String\&, const String\&, const String\&) μέθοδος

Επικυρώνει το στοιχείο στο τρέχον πλαίσιο με τις καθορισμένες τιμές χαρακτηριστικών **xsi:Type**, **xsi:Nil**, **xsi:SchemaLocation** και **xsi:NoNamespaceSchemaLocation**.

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateElement(const String &localName, const String &namespaceUri, const SharedPtr<XmlSchemaInfo> &schemaInfo, const String &xsiType, const String &xsiNil, const String &xsiSchemaLocation, const String &xsiNoNamespaceSchemaLocation)
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | Το τοπικό όνομα του στοιχείου για επικύρωση. |
| namespaceUri | const [String](../../../system/string/)\& | Το URI του ονόματος χώρου του στοιχείου για επικύρωση. |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | Ένα αντικείμενο [XmlSchemaInfo](../../xmlschemainfo/) των οποίων οι ιδιότητες ορίζονται μετά από επιτυχημένη επικύρωση του ονόματος του στοιχείου. Αυτή η παράμετρος μπορεί να είναι **nullptr**. |
| xsiType | const [String](../../../system/string/)\& | Η τιμή του χαρακτηριστικού **xsi:Type** του στοιχείου. Αυτή η παράμετρος μπορεί να είναι **nullptr**. |
| xsiNil | const [String](../../../system/string/)\& | Η τιμή του χαρακτηριστικού **xsi:Nil** του στοιχείου. Αυτή η παράμετρος μπορεί να είναι **nullptr**. |
| xsiSchemaLocation | const [String](../../../system/string/)\& | Η τιμή του χαρακτηριστικού **xsi:SchemaLocation** του στοιχείου. Αυτή η παράμετρος μπορεί να είναι **nullptr**. |
| xsiNoNamespaceSchemaLocation | const [String](../../../system/string/)\& | Η τιμή του χαρακτηριστικού **xsi:NoNamespaceSchemaLocation** του στοιχείου. Αυτή η παράμετρος μπορεί να είναι **nullptr**. |

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [String](../../../system/string/)
* Κλάση [XmlSchemaInfo](../../xmlschemainfo/)
* Κλάση [XmlSchemaValidator](../)
* Χώρος ονομάτων [System::Xml::Schema](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)