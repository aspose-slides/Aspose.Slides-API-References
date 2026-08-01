---
title: ValidateElement()
second_title: Aspose.Slides voor C++ API-referentie
description: Valideert het element in de huidige context.
type: docs
weight: 131
url: /nl/system.xml.schema/xmlschemavalidator/validateelement/
---
## XmlSchemaValidator::ValidateElement(const String\&, const String\&, const SharedPtr\<XmlSchemaInfo\>\&) method

Valideert het element in de huidige context.

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateElement(const String &localName, const String &namespaceUri, const SharedPtr<XmlSchemaInfo> &schemaInfo)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | De lokale naam van het te valideren element. |
| namespaceUri | const [String](../../../system/string/)\& | De namespace-URI van het te valideren element. |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | Een [XmlSchemaInfo](../../xmlschemainfo/) object waarvan de eigenschappen worden ingesteld bij succesvolle validatie van de naam van het element. Deze parameter kan **nullptr** zijn. |

## XmlSchemaValidator::ValidateElement(const String\&, const String\&, const SharedPtr\<XmlSchemaInfo\>\&, const String\&, const String\&, const String\&, const String\&) method

Valideert het element in de huidige context met de opgegeven attribuutwaarden **xsi:Type**, **xsi:Nil**, **xsi:SchemaLocation** en **xsi:NoNamespaceSchemaLocation**.

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateElement(const String &localName, const String &namespaceUri, const SharedPtr<XmlSchemaInfo> &schemaInfo, const String &xsiType, const String &xsiNil, const String &xsiSchemaLocation, const String &xsiNoNamespaceSchemaLocation)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | De lokale naam van het te valideren element. |
| namespaceUri | const [String](../../../system/string/)\& | De namespace-URI van het te valideren element. |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | Een [XmlSchemaInfo](../../xmlschemainfo/) object waarvan de eigenschappen worden ingesteld bij succesvolle validatie van de naam van het element. Deze parameter kan **nullptr** zijn. |
| xsiType | const [String](../../../system/string/)\& | De **xsi:Type** attribuutwaarde van het element. Deze parameter kan **nullptr** zijn. |
| xsiNil | const [String](../../../system/string/)\& | De **xsi:Nil** attribuutwaarde van het element. Deze parameter kan **nullptr** zijn. |
| xsiSchemaLocation | const [String](../../../system/string/)\& | De **xsi:SchemaLocation** attribuutwaarde van het element. Deze parameter kan **nullptr** zijn. |
| xsiNoNamespaceSchemaLocation | const [String](../../../system/string/)\& | De **xsi:NoNamespaceSchemaLocation** attribuutwaarde van het element. Deze parameter kan **nullptr** zijn. |

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [XmlSchemaInfo](../../xmlschemainfo/)
* Class [XmlSchemaValidator](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)