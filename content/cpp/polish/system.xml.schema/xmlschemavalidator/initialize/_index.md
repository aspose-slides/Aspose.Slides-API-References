---
title: Initialize()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Inicjalizuje stan obiektu XmlSchemaValidator.
type: docs
weight: 118
url: /pl/system.xml.schema/xmlschemavalidator/initialize/
---
## XmlSchemaValidator::Initialize() metoda


Inicjalizuje stan obiektu [XmlSchemaValidator](../).

```cpp
void System::Xml::Schema::XmlSchemaValidator::Initialize()
```


## XmlSchemaValidator::Initialize(const SharedPtr\<XmlSchemaObject\>\&) metoda


Inicjalizuje stan obiektu [XmlSchemaValidator](../) używając [XmlSchemaObject](../../xmlschemaobject/) określonego dla częściowej walidacji.

```cpp
void System::Xml::Schema::XmlSchemaValidator::Initialize(const SharedPtr<XmlSchemaObject> &partialValidationType)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| partialValidationType | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaObject](../../xmlschemaobject/)\>\& | Obiekt [XmlSchemaElement](../../xmlschemaelement/), [XmlSchemaAttribute](../../xmlschemaattribute/) lub [XmlSchemaType](../../xmlschematype/) używany do zainicjowania kontekstu walidacji obiektu [XmlSchemaValidator](../) dla częściowej walidacji. |

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [XmlSchemaValidator](../)
* Klasa [XmlSchemaObject](../../xmlschemaobject/)
* Przestrzeń nazw [System::Xml::Schema](../../)
* Biblioteka [Aspose.Slides](../../../)