---
title: ValidateAttribute()
second_title: Aspose.Slides för C++ API-referens
description: Validerar attributnamnet, namnrymdens URI och värdet i det aktuella elementets sammanhang.
type: docs
weight: 144
url: /sv/system.xml.schema/xmlschemavalidator/validateattribute/
---
## XmlSchemaValidator::ValidateAttribute(const String\&, const String\&, const String\&, const SharedPtr\<XmlSchemaInfo\>\&) metod

Validerar attributnamnet, namnrymdens URI och värdet i det aktuella elementets sammanhang.

```cpp
SharedPtr<Object> System::Xml::Schema::XmlSchemaValidator::ValidateAttribute(const String &localName, const String &namespaceUri, const String &attributeValue, const SharedPtr<XmlSchemaInfo> &schemaInfo)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | Det lokala namnet på attributet som ska valideras. |
| namespaceUri | const [String](../../../system/string/)\& | Namnområdets URI för attributet som ska valideras. |
| attributeValue | const [String](../../../system/string/)\& | Värdet på attributet som ska valideras. |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | Ett [XmlSchemaInfo](../../xmlschemainfo/)-objekt vars egenskaper sätts vid lyckad validering av attributet. Denna parameter kan vara **nullptr**. |

### Returvärde

Det validerade attributets värde.

## XmlSchemaValidator::ValidateAttribute(const String\&, const String\&, XmlValueGetter, const SharedPtr\<XmlSchemaInfo\>\&) metod

Validerar attributnamnet, namnrymdens URI och värdet i det aktuella elementets sammanhang.

```cpp
SharedPtr<Object> System::Xml::Schema::XmlSchemaValidator::ValidateAttribute(const String &localName, const String &namespaceUri, XmlValueGetter attributeValue, const SharedPtr<XmlSchemaInfo> &schemaInfo)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | Det lokala namnet på attributet som ska valideras. |
| namespaceUri | const [String](../../../system/string/)\& | Namnområdets URI för attributet som ska valideras. |
| attributeValue | [XmlValueGetter](../../xmlvaluegetter/) | En XmlValueGetter-callback som används för att överföra attributets värde som en typ som är kompatibel med XML [Schema](../../) Definition Language (XSD)-typen för attributet. |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | Ett [XmlSchemaInfo](../../xmlschemainfo/)-objekt vars egenskaper sätts vid lyckad validering av attributet. Denna parameter kan vara **nullptr**. |

### Returvärde

Det validerade attributets värde.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [XmlValueGetter](../../xmlvaluegetter/)
* Klass [Object](../../../system/object/)
* Klass [String](../../../system/string/)
* Klass [XmlSchemaInfo](../../xmlschemainfo/)
* Klass [XmlSchemaValidator](../)
* Namnrymd [System::Xml::Schema](../../)
* Bibliotek [Aspose.Slides](../../../)