---
title: Initialize()
second_title: Aspose.Slides für C++ API-Referenz
description: Initialisiert den Zustand des XmlSchemaValidator-Objekts.
type: docs
weight: 118
url: /de/system.xml.schema/xmlschemavalidator/initialize/
---
## XmlSchemaValidator::Initialize() Methode


Initialisiert den Zustand des [XmlSchemaValidator](../)-Objekts.

```cpp
void System::Xml::Schema::XmlSchemaValidator::Initialize()
```


## XmlSchemaValidator::Initialize(const SharedPtr\<XmlSchemaObject\>\&) Methode


Initialisiert den Zustand des [XmlSchemaValidator](../)-Objekts unter Verwendung des [XmlSchemaObject](../../xmlschemaobject/)-Parameters, der für die partielle Validierung angegeben ist.

```cpp
void System::Xml::Schema::XmlSchemaValidator::Initialize(const SharedPtr<XmlSchemaObject> &partialValidationType)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| partialValidationType | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaObject](../../xmlschemaobject/)\>\& | Ein [XmlSchemaElement](../../xmlschemaelement/), [XmlSchemaAttribute](../../xmlschemaattribute/) oder [XmlSchemaType](../../xmlschematype/)-Objekt, das verwendet wird, um den Validierungskontext des [XmlSchemaValidator](../)-Objekts für die partielle Validierung zu initialisieren. |

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XmlSchemaValidator](../)
* Klasse [XmlSchemaObject](../../xmlschemaobject/)
* Namensraum [System::Xml::Schema](../../)
* Bibliothek [Aspose.Slides](../../../)