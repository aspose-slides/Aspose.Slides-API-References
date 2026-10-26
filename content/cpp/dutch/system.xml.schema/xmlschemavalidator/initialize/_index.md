---
title: Initialize()
second_title: Aspose.Slides voor C++ API-referentie
description: Initialiseert de staat van het XmlSchemaValidator object.
type: docs
weight: 118
url: /nl/system.xml.schema/xmlschemavalidator/initialize/
---
## XmlSchemaValidator::Initialize() methode


Initialiseert de staat van het [XmlSchemaValidator](../) object.

```cpp
void System::Xml::Schema::XmlSchemaValidator::Initialize()
```


## XmlSchemaValidator::Initialize(const SharedPtr\<XmlSchemaObject\>\&) methode


Initialiseert de staat van het [XmlSchemaValidator](../) object met behulp van de [XmlSchemaObject](../../xmlschemaobject/) die is opgegeven voor gedeeltelijke validatie.

```cpp
void System::Xml::Schema::XmlSchemaValidator::Initialize(const SharedPtr<XmlSchemaObject> &partialValidationType)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| partialValidationType | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaObject](../../xmlschemaobject/)\>\& | Een [XmlSchemaElement](../../xmlschemaelement/), [XmlSchemaAttribute](../../xmlschemaattribute/) of [XmlSchemaType](../../xmlschematype/) object dat wordt gebruikt om de validatie-context van het [XmlSchemaValidator](../) object te initialiseren voor gedeeltelijke validatie. |

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XmlSchemaValidator](../)
* Klasse [XmlSchemaObject](../../xmlschemaobject/)
* Naamruimte [System::Xml::Schema](../../)
* Bibliotheek [Aspose.Slides](../../../)