---
title: ValidateElement()
second_title: Aspose.Slides för C++ API-referens
description: Validerar elementet i det aktuella sammanhanget.
type: docs
weight: 131
url: /sv/system.xml.schema/xmlschemavalidator/validateelement/
---
## XmlSchemaValidator::ValidateElement(const String\&, const String\&, const SharedPtr\<XmlSchemaInfo\>\&) metod


Validerar elementet i det aktuella sammanhanget.

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateElement(const String &localName, const String &namespaceUri, const SharedPtr<XmlSchemaInfo> &schemaInfo)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | Det lokala namnet på elementet som ska valideras. |
| namespaceUri | const [String](../../../system/string/)\& | Namespace-URI:n för elementet som ska valideras. |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | Ett [XmlSchemaInfo](../../xmlschemainfo/)-objekt vars egenskaper sätts vid lyckad validering av elementets namn. Denna parameter kan vara **nullptr**. |

## XmlSchemaValidator::ValidateElement(const String\&, const String\&, const SharedPtr\<XmlSchemaInfo\>\&, const String\&, const String\&, const String\&, const String\&) metod


Validerar elementet i det aktuella sammanhanget med de angivna attributvärdena **xsi:Type**, **xsi:Nil**, **xsi:SchemaLocation** och **xsi:NoNamespaceSchemaLocation**.

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateElement(const String &localName, const String &namespaceUri, const SharedPtr<XmlSchemaInfo> &schemaInfo, const String &xsiType, const String &xsiNil, const String &xsiSchemaLocation, const String &xsiNoNamespaceSchemaLocation)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | Det lokala namnet på elementet som ska valideras. |
| namespaceUri | const [String](../../../system/string/)\& | Namespace-URI:n för elementet som ska valideras. |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | Ett [XmlSchemaInfo](../../xmlschemainfo/)-objekt vars egenskaper sätts vid lyckad validering av elementets namn. Denna parameter kan vara **nullptr**. |
| xsiType | const [String](../../../system/string/)\& | **xsi:Type**-attributvärdet för elementet. Denna parameter kan vara **nullptr**. |
| xsiNil | const [String](../../../system/string/)\& | **xsi:Nil**-attributvärdet för elementet. Denna parameter kan vara **nullptr**. |
| xsiSchemaLocation | const [String](../../../system/string/)\& | **xsi:SchemaLocation**-attributvärdet för elementet. Denna parameter kan vara **nullptr**. |
| xsiNoNamespaceSchemaLocation | const [String](../../../system/string/)\& | **xsi:NoNamespaceSchemaLocation**-attributvärdet för elementet. Denna parameter kan vara **nullptr**. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [String](../../../system/string/)
* Klass [XmlSchemaInfo](../../xmlschemainfo/)
* Klass [XmlSchemaValidator](../)
* Namnrymd [System::Xml::Schema](../../)
* Bibliotek [Aspose.Slides](../../../)