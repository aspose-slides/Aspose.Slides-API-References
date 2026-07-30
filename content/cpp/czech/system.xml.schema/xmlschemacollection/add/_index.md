---
title: Add()
second_title: Aspose.Slides pro C++ API Reference
description: Přidá schéma umístěné pomocí zadané URL do kolekce schémat.
type: docs
weight: 40
url: /cs/system.xml.schema/xmlschemacollection/add/
---
## XmlSchemaCollection::Add(const String\&, const String\&) metoda

Přidá schéma umístěné pomocí zadané URL do kolekce schémat.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const String &ns, const String &uri)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| ns | const [String](../../../system/string/)\& | URI jmenného prostoru přiřazené ke schématu. Pro XML Schemas bude typicky **targetNamespace**. |
| uri | const [String](../../../system/string/)\& | URL, která určuje schéma ke načtení. |

### Návratová hodnota

Objekt [XmlSchema](../../xmlschema/) přidaný do kolekce schémat; **nullptr**, pokud je přidávané schéma XDR schéma nebo pokud v schématu jsou chyby při kompilaci.

## XmlSchemaCollection::Add(const String\&, const SharedPtr\<XmlReader\>\&) metoda

Přidá schéma obsažené v [XmlReader](../../../system.xml/xmlreader/) do kolekce schémat.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const String &ns, const SharedPtr<XmlReader> &reader)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| ns | const [String](../../../system/string/)\& | URI jmenného prostoru přiřazené ke schématu. Pro XML Schemas bude typicky **targetNamespace**. |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | [XmlReader](../../../system.xml/xmlreader/) obsahující schéma k přidání. |

### Návratová hodnota

Objekt [XmlSchema](../../xmlschema/) přidaný do kolekce schémat; **nullptr**, pokud je přidávané schéma XDR schéma nebo pokud v schématu jsou chyby při kompilaci.

## XmlSchemaCollection::Add(const String\&, const SharedPtr\<XmlReader\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) metoda

Přidá schéma obsažené v [XmlReader](../../../system.xml/xmlreader/) do kolekce schémat. Zadaný [XmlResolver](../../../system.xml/xmlresolver/) se používá k řešení všech externích zdrojů.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const String &ns, const SharedPtr<XmlReader> &reader, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| ns | const [String](../../../system/string/)\& | URI jmenného prostoru přiřazené ke schématu. Pro XML Schemas bude typicky **targetNamespace**. |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | [XmlReader](../../../system.xml/xmlreader/) obsahující schéma k přidání. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) použité k řešení jmenných prostorů odkazovaných v prvcích **include** a **import** nebo atributu **x-schema** (XDR schémata). Pokud je **nullptr**, externí reference nejsou řešeny. |

### Návratová hodnota

Objekt [XmlSchema](../../xmlschema/) přidaný do kolekce schémat; **nullptr**, pokud je přidávané schéma XDR schéma nebo pokud v schématu jsou chyby při kompilaci.

## XmlSchemaCollection::Add(const SharedPtr\<XmlSchema\>\&) metoda

Přidá [XmlSchema](../../xmlschema/) do kolekce.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const SharedPtr<XmlSchema> &schema)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | [XmlSchema](../../xmlschema/) k přidání do kolekce. |

### Návratová hodnota

Objekt [XmlSchema](../../xmlschema/).

## XmlSchemaCollection::Add(const SharedPtr\<XmlSchema\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) metoda

Přidá [XmlSchema](../../xmlschema/) do kolekce. Zadaný [XmlResolver](../../../system.xml/xmlresolver/) se používá k řešení všech externích referencí.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const SharedPtr<XmlSchema> &schema, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | [XmlSchema](../../xmlschema/) k přidání do kolekce. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) použité k řešení jmenných prostorů odkazovaných v prvcích **include** a **import**. Pokud je **nullptr**, externí reference nejsou řešeny. |

### Návratová hodnota

Objekt [XmlSchema](../../xmlschema/) přidaný do kolekce schémat.

## XmlSchemaCollection::Add(const SharedPtr\<XmlSchemaCollection\>\&) metoda

Přidá všechny jmenné prostory definované v zadané kolekci (včetně jejich souvisejících schémat) do této kolekce.

```cpp
void System::Xml::Schema::XmlSchemaCollection::Add(const SharedPtr<XmlSchemaCollection> &schema)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaCollection](../)\>\& | [XmlSchemaCollection](../) který chcete přidat do této kolekce. |

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchema](../../xmlschema/)
* Class [String](../../../system/string/)
* Class [XmlSchemaCollection](../)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)