---
title: Initialize()
second_title: Aspose.Slides för C++ API-referens
description: Initierar tillståndet för XmlSchemaValidator-objektet.
type: docs
weight: 118
url: /sv/system.xml.schema/xmlschemavalidator/initialize/
---
## XmlSchemaValidator::Initialize() metod

Initierar tillståndet för objektet [XmlSchemaValidator](../).

```cpp
void System::Xml::Schema::XmlSchemaValidator::Initialize()
```

## XmlSchemaValidator::Initialize(const SharedPtr\<XmlSchemaObject\>\&) metod

Initierar tillståndet för objektet [XmlSchemaValidator](../) med den [XmlSchemaObject](../../xmlschemaobject/) som anges för partiell validering.

```cpp
void System::Xml::Schema::XmlSchemaValidator::Initialize(const SharedPtr<XmlSchemaObject> &partialValidationType)
```

### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| partialValidationType | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaObject](../../xmlschemaobject/)\>\& | Ett [XmlSchemaElement](../../xmlschemaelement/), [XmlSchemaAttribute](../../xmlschemaattribute/) eller [XmlSchemaType](../../xmlschematype/)-objekt som används för att initiera valideringskontexten för [XmlSchemaValidator](../)-objektet för partiell validering. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [XmlSchemaValidator](../)
* Klass [XmlSchemaObject](../../xmlschemaobject/)
* Namnrymd [System::Xml::Schema](../../)
* Bibliotek [Aspose.Slides](../../../)