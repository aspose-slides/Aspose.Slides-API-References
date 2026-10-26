---
title: MoveToAttribute()
second_title: Aspose.Slides für C++ API Referenz
description: Wechselt zum Attribut mit dem angegebenen Namen.
type: docs
weight: 456
url: /de/system.xml/xmlvalidatingreader/movetoattribute/
---
## XmlValidatingReader::MoveToAttribute(String) Methode

Wechselt zum Attribut mit dem angegebenen Namen.

```cpp
bool System::Xml::XmlValidatingReader::MoveToAttribute(String name) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | [String](../../../system/string/) | Der qualifizierte Name des Attributs. |

### Rückgabewert

**true** if the attribute is found; otherwise, **false**. If **false**, the position of the reader does not change.

## XmlValidatingReader::MoveToAttribute(String, String) Methode

Wechselt zum Attribut mit dem angegebenen lokalen Namen und dem Namespace Uniform Resource Identifier (URI).

```cpp
bool System::Xml::XmlValidatingReader::MoveToAttribute(String localName, String namespaceURI) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Der lokale Name des Attributs. |
| namespaceURI | [String](../../../system/string/) | Der Namespace-URI des Attributs. |

### Rückgabewert

**true** if the attribute is found; otherwise, **false**. If **false**, the position of the reader does not change.

## XmlValidatingReader::MoveToAttribute(int32_t) Methode

Wechselt zum Attribut mit dem angegebenen Index.

```cpp
void System::Xml::XmlValidatingReader::MoveToAttribute(int32_t i) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| i | **int32_t** | Der Index des Attributs. |

## Siehe auch

* Klasse [String](../../../system/string/)
* Klasse [XmlValidatingReader](../)
* Namensraum [System::Xml](../../)
* Bibliothek [Aspose.Slides](../../../)