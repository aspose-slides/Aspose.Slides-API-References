---
title: ValidateElement()
second_title: Aspose.Slides für C++ API-Referenz
description: Validiert das Element im aktuellen Kontext.
type: docs
weight: 131
url: /de/system.xml.schema/xmlschemavalidator/validateelement/
---
## XmlSchemaValidator::ValidateElement(const String\&, const String\&, const SharedPtr\<XmlSchemaInfo\>\&) Methode


Validiert das Element im aktuellen Kontext.

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateElement(const String &localName, const String &namespaceUri, const SharedPtr<XmlSchemaInfo> &schemaInfo)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | Der lokale Name des zu validierenden Elements. |
| namespaceUri | const [String](../../../system/string/)\& | Der Namespace-URI des zu validierenden Elements. |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | Ein [XmlSchemaInfo](../../xmlschemainfo/)-Objekt, dessen Eigenschaften bei erfolgreicher Validierung des Elementnamens festgelegt werden. Dieser Parameter kann **nullptr** sein. |

## XmlSchemaValidator::ValidateElement(const String\&, const String\&, const SharedPtr\<XmlSchemaInfo\>\&, const String\&, const String\&, const String\&, const String\&) Methode


Validiert das Element im aktuellen Kontext mit den angegebenen Attributwerten **xsi:Type**, **xsi:Nil**, **xsi:SchemaLocation** und **xsi:NoNamespaceSchemaLocation**.

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateElement(const String &localName, const String &namespaceUri, const SharedPtr<XmlSchemaInfo> &schemaInfo, const String &xsiType, const String &xsiNil, const String &xsiSchemaLocation, const String &xsiNoNamespaceSchemaLocation)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | Der lokale Name des zu validierenden Elements. |
| namespaceUri | const [String](../../../system/string/)\& | Der Namespace-URI des zu validierenden Elements. |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | Ein [XmlSchemaInfo](../../xmlschemainfo/)-Objekt, dessen Eigenschaften bei erfolgreicher Validierung des Elementnamens festgelegt werden. Dieser Parameter kann **nullptr** sein. |
| xsiType | const [String](../../../system/string/)\& | Der Attributwert **xsi:Type** des Elements. Dieser Parameter kann **nullptr** sein. |
| xsiNil | const [String](../../../system/string/)\& | Der Attributwert **xsi:Nil** des Elements. Dieser Parameter kann **nullptr** sein. |
| xsiSchemaLocation | const [String](../../../system/string/)\& | Der Attributwert **xsi:SchemaLocation** des Elements. Dieser Parameter kann **nullptr** sein. |
| xsiNoNamespaceSchemaLocation | const [String](../../../system/string/)\& | Der Attributwert **xsi:NoNamespaceSchemaLocation** des Elements. Dieser Parameter kann **nullptr** sein. |

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [XmlSchemaInfo](../../xmlschemainfo/)
* Class [XmlSchemaValidator](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)