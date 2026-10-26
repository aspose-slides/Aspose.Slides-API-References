---
title: Add()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Přidá schéma jazyka XML Schema definition (XSD) na zadané URL do XmlSchemaSet.
type: docs
weight: 157
url: /cs/system.xml.schema/xmlschemaset/add/
---
## XmlSchemaSet::Add(String, const String\&) metoda

Přidá XML [Schema](../../) schéma definice jazyka (XSD) na zadané URL do [XmlSchemaSet](../).

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Add(String targetNamespace, const String &schemaUri)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| targetNamespace | [String](../../../system/string/) | Hodnota **targetNamespace** schématu, nebo **nullptr** pro použití **targetNamespace** určeného ve schématu. |
| schemaUri | const [String](../../../system/string/)\& | URL, který určuje schéma k načtení. |

### Návratová hodnota

Objekt [XmlSchema](../../xmlschema/), pokud je schéma platné. Pokud schéma není platné a je zadán ValidationEventHandler, vrátí se **nullptr** a bude vyvolána příslušná validační událost. V opačném případě je vyhozena výjimka XmlSchemaException.

## XmlSchemaSet::Add(String, const SharedPtr\<XmlReader\>\&) metoda

Přidá XML [Schema](../../) schéma definice jazyka (XSD) obsažené v [XmlReader](../../../system.xml/xmlreader/) do [XmlSchemaSet](../).

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Add(String targetNamespace, const SharedPtr<XmlReader> &schemaDocument)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| targetNamespace | [String](../../../system/string/) | Hodnota **targetNamespace** schématu, nebo **nullptr** pro použití **targetNamespace** určeného ve schématu. |
| schemaDocument | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Objekt [XmlReader](../../../system.xml/xmlreader/). |

### Návratová hodnota

Objekt [XmlSchema](../../xmlschema/), pokud je schéma platné. Pokud schéma není platné a je zadán ValidationEventHandler, vrátí se **nullptr** a bude vyvolána příslušná validační událost. V opačném případě je vyhozena výjimka XmlSchemaException.

## XmlSchemaSet::Add(const SharedPtr\<XmlSchemaSet\>\&) metoda

Přidá všechna XML [Schema](../../) schémata definice jazyka (XSD) v daném [XmlSchemaSet](../) do [XmlSchemaSet](../).

```cpp
void System::Xml::Schema::XmlSchemaSet::Add(const SharedPtr<XmlSchemaSet> &schemas)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| schemas | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaSet](../)\>\& | Objekt [XmlSchemaSet](../). |

## XmlSchemaSet::Add(const SharedPtr\<XmlSchema\>\&) metoda

Přidá daný [XmlSchema](../../xmlschema/) do [XmlSchemaSet](../).

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Add(const SharedPtr<XmlSchema> &schema)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | Objekt [XmlSchema](../../xmlschema/) k přidání do [XmlSchemaSet](../). |

### Návratová hodnota

Objekt [XmlSchema](../../xmlschema/), pokud je schéma platné. Pokud schéma není platné a je zadán ValidationEventHandler, vrátí se **nullptr** a bude vyvolána příslušná validační událost. V opačném případě je vyhozena výjimka XmlSchemaException.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [XmlSchema](../../xmlschema/)
* Třída [String](../../../system/string/)
* Třída [XmlSchemaSet](../)
* Třída [XmlReader](../../../system.xml/xmlreader/)
* Jmenný prostor [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)