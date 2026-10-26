---
title: Compile()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Kompiluje model XML SchemaObject (SOM) do informacji o schemacie w celu walidacji. Służy do sprawdzania struktury syntaktycznej i semantycznej programowo budowanego SOM. Sprawdzanie walidacji semantycznej odbywa się podczas kompilacji.
type: docs
weight: 352
url: /pl/system.xml.schema/xmlschema/compile/
---
## XmlSchema::Compile(ValidationEventHandler) metoda


Kompiluje model XML [Schema](../../)[Object](../../../system/object/) (SOM) do informacji o schemacie w celu walidacji. Używany do sprawdzania struktury syntaktycznej i semantycznej programowo zbudowanego SOM. Sprawdzanie walidacji semantycznej jest wykonywane podczas kompilacji.

```cpp
void System::Xml::Schema::XmlSchema::Compile(ValidationEventHandler validationEventHandler)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| validationEventHandler | [ValidationEventHandler](../../validationeventhandler/) | Obsługa zdarzeń walidacji, która otrzymuje informacje o błędach walidacji XML [Schema](../../). |

## XmlSchema::Compile(ValidationEventHandler, const SharedPtr\<XmlResolver\>\&) metoda


Kompiluje model XML [Schema](../../)[Object](../../../system/object/) (SOM) do informacji o schemacie w celu walidacji. Używany do sprawdzania struktury syntaktycznej i semantycznej programowo zbudowanego SOM. Sprawdzanie walidacji semantycznej jest wykonywane podczas kompilacji.

```cpp
void System::Xml::Schema::XmlSchema::Compile(ValidationEventHandler validationEventHandler, const SharedPtr<XmlResolver> &resolver)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| validationEventHandler | [ValidationEventHandler](../../validationeventhandler/) | Obsługa zdarzeń walidacji, która otrzymuje informacje o błędach walidacji XML [Schema](../../). |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) używany do rozwiązywania przestrzeni nazw odwoływanych w elementach **include** i **import**. |

## Zobacz także

* Typedef [ValidationEventHandler](../../validationeventhandler/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchema](../)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)