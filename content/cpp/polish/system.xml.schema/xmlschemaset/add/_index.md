---
title: Add()
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Dodaje schemat języka definicji XML Schema (XSD) pod podanym adresem URL do XmlSchemaSet.
type: docs
weight: 157
url: /pl/system.xml.schema/xmlschemaset/add/
---
## XmlSchemaSet::Add(String, const String\&) metoda

Dodaje schemat języka definicji XML [Schema](../../) (XSD) pod podanym adresem URL do [XmlSchemaSet](../).

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Add(String targetNamespace, const String &schemaUri)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| targetNamespace | [String](../../../system/string/) | Wartość **targetNamespace** schematu lub **nullptr**, aby użyć **targetNamespace** określonego w schemacie. |
| schemaUri | const [String](../../../system/string/)\& | Adres URL określający schemat do załadowania. |

### Wartość zwracana

Obiekt [XmlSchema](../../xmlschema/) jeśli schemat jest prawidłowy. Jeśli schemat nie jest prawidłowy i określono ValidationEventHandler, wtedy zwracane jest **nullptr** i podnoszone jest odpowiednie zdarzenie walidacji. W przeciwnym razie zgłaszany jest XmlSchemaException.

## XmlSchemaSet::Add(String, const SharedPtr\<XmlReader\>\&) metoda

Dodaje schemat języka definicji XML [Schema](../../) (XSD) zawarty w [XmlReader](../../../system.xml/xmlreader/) do [XmlSchemaSet](../).

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Add(String targetNamespace, const SharedPtr<XmlReader> &schemaDocument)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| targetNamespace | [String](../../../system/string/) | Wartość **targetNamespace** schematu lub **nullptr**, aby użyć **targetNamespace** określonego w schemacie. |
| schemaDocument | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Obiekt [XmlReader](../../../system.xml/xmlreader/). |

### Wartość zwracana

Obiekt [XmlSchema](../../xmlschema/) jeśli schemat jest prawidłowy. Jeśli schemat nie jest prawidłowy i określono ValidationEventHandler, wtedy zwracane jest **nullptr** i podnoszone jest odpowiednie zdarzenie walidacji. W przeciwnym razie zgłaszany jest XmlSchemaException.

## XmlSchemaSet::Add(const SharedPtr\<XmlSchemaSet\>\&) metoda

Dodaje wszystkie schematy języka definicji XML [Schema](../../) (XSD) zawarte w podanym [XmlSchemaSet](../) do [XmlSchemaSet](../).

```cpp
void System::Xml::Schema::XmlSchemaSet::Add(const SharedPtr<XmlSchemaSet> &schemas)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| schemas | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaSet](../)\>\& | Obiekt [XmlSchemaSet](../). |

## XmlSchemaSet::Add(const SharedPtr\<XmlSchema\>\&) metoda

Dodaje podany [XmlSchema](../../xmlschema/) do [XmlSchemaSet](../).

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Add(const SharedPtr<XmlSchema> &schema)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | Obiekt [XmlSchema](../../xmlschema/) do dodania do [XmlSchemaSet](../). |

### Wartość zwracana

Obiekt [XmlSchema](../../xmlschema/) jeśli schemat jest prawidłowy. Jeśli schemat nie jest prawidłowy i określono ValidationEventHandler, wtedy zwracane jest **nullptr** i podnoszone jest odpowiednie zdarzenie walidacji. W przeciwnym razie zgłaszany jest XmlSchemaException.

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [XmlSchema](../../xmlschema/)
* Klasa [String](../../../system/string/)
* Klasa [XmlSchemaSet](../)
* Klasa [XmlReader](../../../system.xml/xmlreader/)
* Przestrzeń nazw [System::Xml::Schema](../../)
* Biblioteka [Aspose.Slides](../../../)