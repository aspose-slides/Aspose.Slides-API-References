---
title: ValidateElement()
second_title: Aspose.Slides C++ API referencia
description: Érvényesíti az elemet a jelenlegi kontextusban.
type: docs
weight: 131
url: /hu/system.xml.schema/xmlschemavalidator/validateelement/
---
## XmlSchemaValidator::ValidateElement(const String\&, const String\&, const SharedPtr\<XmlSchemaInfo\>\&) metódus

Érvényesíti az elemet a jelenlegi kontextusban.

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateElement(const String &localName, const String &namespaceUri, const SharedPtr<XmlSchemaInfo> &schemaInfo)
```

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | Az érvényesítendő elem helyi neve. |
| namespaceUri | const [String](../../../system/string/)\& | Az érvényesítendő elem névtér-URI-ja. |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | Egy [XmlSchemaInfo](../../xmlschemainfo/) objektum, amelynek tulajdonságai a elem nevének sikeres érvényesítésekor kerülnek beállításra. Ez a paraméter lehet **nullptr**. |

## XmlSchemaValidator::ValidateElement(const String\&, const String\&, const SharedPtr\<XmlSchemaInfo\>\&, const String\&, const String\&, const String\&, const String\&) metódus

Érvényesíti az elemet a jelenlegi kontextusban a megadott **xsi:Type**, **xsi:Nil**, **xsi:SchemaLocation** és **xsi:NoNamespaceSchemaLocation** attribútumértékekkel.

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateElement(const String &localName, const String &namespaceUri, const SharedPtr<XmlSchemaInfo> &schemaInfo, const String &xsiType, const String &xsiNil, const String &xsiSchemaLocation, const String &xsiNoNamespaceSchemaLocation)
```

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | Az érvényesítendő elem helyi neve. |
| namespaceUri | const [String](../../../system/string/)\& | Az érvényesítendő elem névtér-URI-ja. |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | Egy [XmlSchemaInfo](../../xmlschemainfo/) objektum, amelynek tulajdonságai a elem nevének sikeres érvényesítésekor kerülnek beállításra. Ez a paraméter lehet **nullptr**. |
| xsiType | const [String](../../../system/string/)\& | Az elem **xsi:Type** attribútumértéke. Ez a paraméter lehet **nullptr**. |
| xsiNil | const [String](../../../system/string/)\& | Az elem **xsi:Nil** attribútumértéke. Ez a paraméter lehet **nullptr**. |
| xsiSchemaLocation | const [String](../../../system/string/)\& | Az elem **xsi:SchemaLocation** attribútumértéke. Ez a paraméter lehet **nullptr**. |
| xsiNoNamespaceSchemaLocation | const [String](../../../system/string/)\& | Az elem **xsi:NoNamespaceSchemaLocation** attribútumértéke. Ez a paraméter lehet **nullptr**. |

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [String](../../../system/string/)
* Osztály [XmlSchemaInfo](../../xmlschemainfo/)
* Osztály [XmlSchemaValidator](../)
* Névtér [System::Xml::Schema](../../)
* Könyvtár [Aspose.Slides](../../../)