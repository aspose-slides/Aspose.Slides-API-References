---
title: ValidateAttribute()
second_title: Aspose.Slides for C++ API Referencia
description: Érvényesíti az attribútum nevét, a névtér URI-ját és az értékét az aktuális elemkörnyezetben.
type: docs
weight: 144
url: /hu/system.xml.schema/xmlschemavalidator/validateattribute/
---
## XmlSchemaValidator::ValidateAttribute(const String\&, const String\&, const String\&, const SharedPtr\<XmlSchemaInfo\>\&) metódus

Érvényesíti az attribútum nevét, névtér URI-ját és értékét az aktuális elemkörnyezetben.

```cpp
SharedPtr<Object> System::Xml::Schema::XmlSchemaValidator::ValidateAttribute(const String &localName, const String &namespaceUri, const String &attributeValue, const SharedPtr<XmlSchemaInfo> &schemaInfo)
```

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | Az attribútum helyi neve, amelyet érvényesíteni kell. |
| namespaceUri | const [String](../../../system/string/)\& | Az attribútum névtér URI-ja, amelyet érvényesíteni kell. |
| attributeValue | const [String](../../../system/string/)\& | Az attribútum értéke, amelyet érvényesíteni kell. |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | Egy [XmlSchemaInfo](../../xmlschemainfo/) objektum, amelynek tulajdonságai az attribútum sikeres érvényesítésekor kerülnek beállításra. Ez a paraméter **nullptr** is lehet. |

### Visszatérési érték

Az érvényesített attribútum értéke.

## XmlSchemaValidator::ValidateAttribute(const String\&, const String\&, XmlValueGetter, const SharedPtr\<XmlSchemaInfo\>\&) metódus

Érvényesíti az attribútum nevét, névtér URI-ját és értékét az aktuális elemkörnyezetben.

```cpp
SharedPtr<Object> System::Xml::Schema::XmlSchemaValidator::ValidateAttribute(const String &localName, const String &namespaceUri, XmlValueGetter attributeValue, const SharedPtr<XmlSchemaInfo> &schemaInfo)
```

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | Az attribútum helyi neve, amelyet érvényesíteni kell. |
| namespaceUri | const [String](../../../system/string/)\& | Az attribútum névtér URI-ja, amelyet érvényesíteni kell. |
| attributeValue | [XmlValueGetter](../../xmlvaluegetter/) | Egy XmlValueGetter visszahívás, amelyet az attribútum értékének átadására használnak egy olyan típusként, amely kompatibilis az attribútum XML [Schema](../../) Definition Language (XSD) típusával. |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | Egy [XmlSchemaInfo](../../xmlschemainfo/) objektum, amelynek tulajdonságai az attribútum sikeres érvényesítésekor kerülnek beállításra. Ez a paraméter **nullptr** is lehet. |

### Visszatérési érték

Az érvényesített attribútum értéke.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [XmlValueGetter](../../xmlvaluegetter/)
* Class [Object](../../../system/object/)
* Class [String](../../../system/string/)
* Class [XmlSchemaInfo](../../xmlschemainfo/)
* Class [XmlSchemaValidator](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)