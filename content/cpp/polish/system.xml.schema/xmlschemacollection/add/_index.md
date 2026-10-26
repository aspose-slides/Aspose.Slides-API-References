---
title: Add()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Dodaje schemat wskazany przez podany adres URL do kolekcji schematów.
type: docs
weight: 40
url: /pl/system.xml.schema/xmlschemacollection/add/
---
## XmlSchemaCollection::Add(const String\&, const String\&) method

Dodaje schemat znajdujący się pod podanym adresem URL do kolekcji schematów.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const String &ns, const String &uri)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| ns | const [String](../../../system/string/)\& | Adres URI przestrzeni nazw powiązany ze schematem. Dla schematów XML będzie to zazwyczaj **targetNamespace**. |
| uri | const [String](../../../system/string/)\& | Adres URL określający schemat do załadowania. |

### Wartość zwracana

Obiekt [XmlSchema](../../xmlschema/) dodany do kolekcji schematów; **nullptr**, jeśli dodawany schemat jest schematem XDR lub wystąpiły błędy kompilacji w schemacie.

## XmlSchemaCollection::Add(const String\&, const SharedPtr\<XmlReader\>\&) method

Dodaje schemat zawarty w [XmlReader](../../../system.xml/xmlreader/) do kolekcji schematów.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const String &ns, const SharedPtr<XmlReader> &reader)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| ns | const [String](../../../system/string/)\& | Adres URI przestrzeni nazw powiązany ze schematem. Dla schematów XML będzie to zazwyczaj **targetNamespace**. |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | [XmlReader](../../../system.xml/xmlreader/) zawierający schemat do dodania. |

### Wartość zwracana

Obiekt [XmlSchema](../../xmlschema/) dodany do kolekcji schematów; **nullptr**, jeśli dodawany schemat jest schematem XDR lub wystąpiły błędy kompilacji w schemacie.

## XmlSchemaCollection::Add(const String\&, const SharedPtr\<XmlReader\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method

Dodaje schemat zawarty w [XmlReader](../../../system.xml/xmlreader/) do kolekcji schematów. Określony [XmlResolver](../../../system.xml/xmlresolver/) jest używany do rozwiązywania wszelkich zewnętrznych zasobów.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const String &ns, const SharedPtr<XmlReader> &reader, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| ns | const [String](../../../system/string/)\& | Adres URI przestrzeni nazw powiązany ze schematem. Dla schematów XML będzie to zazwyczaj **targetNamespace**. |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | [XmlReader](../../../system.xml/xmlreader/) zawierający schemat do dodania. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) używany do rozwiązywania przestrzeni nazw odwoływanych w elementach **include** i **import** lub atrybucie **x-schema** (schematy XDR). Jeśli jest to **nullptr**, zewnętrzne odwołania nie są rozwiązywane. |

### Wartość zwracana

Obiekt [XmlSchema](../../xmlschema/) dodany do kolekcji schematów; **nullptr**, jeśli dodawany schemat jest schematem XDR lub wystąpiły błędy kompilacji w schemacie.

## XmlSchemaCollection::Add(const SharedPtr\<XmlSchema\>\&) method

Dodaje [XmlSchema](../../xmlschema/) do kolekcji.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const SharedPtr<XmlSchema> &schema)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | [XmlSchema](../../xmlschema/) do dodania do kolekcji. |

### Wartość zwracana

Obiekt [XmlSchema](../../xmlschema/).

## XmlSchemaCollection::Add(const SharedPtr\<XmlSchema\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method

Dodaje [XmlSchema](../../xmlschema/) do kolekcji. Określony [XmlResolver](../../../system.xml/xmlresolver/) jest używany do rozwiązywania wszelkich zewnętrznych odwołań.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const SharedPtr<XmlSchema> &schema, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | [XmlSchema](../../xmlschema/) do dodania do kolekcji. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) używany do rozwiązywania przestrzeni nazw odwoływanych w elementach **include** i **import**. Jeśli jest to **nullptr**, zewnętrzne odwołania nie są rozwiązywane. |

### Wartość zwracana

[XmlSchema](../../xmlschema/) dodany do kolekcji schematów.

## XmlSchemaCollection::Add(const SharedPtr\<XmlSchemaCollection\>\&) method

Dodaje wszystkie przestrzenie nazw zdefiniowane w podanej kolekcji (wraz z ich powiązanymi schematami) do tej kolekcji.

```cpp
void System::Xml::Schema::XmlSchemaCollection::Add(const SharedPtr<XmlSchemaCollection> &schema)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaCollection](../)\>\& | [XmlSchemaCollection](../) które chcesz dodać do tej kolekcji. |

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [XmlSchema](../../xmlschema/)
* Klasa [String](../../../system/string/)
* Klasa [XmlSchemaCollection](../)
* Klasa [XmlReader](../../../system.xml/xmlreader/)
* Klasa [XmlResolver](../../../system.xml/xmlresolver/)
* Przestrzeń nazw [System::Xml::Schema](../../)
* Biblioteka [Aspose.Slides](../../../)