---
title: MoveToAttribute()
second_title: Aspose.Slides für C++ API-Referenz
description: Bewegt zum Attribut mit dem angegebenen Namen.
type: docs
weight: 300
url: /de/system.xml/xmlnodereader/movetoattribute/
---
## XmlNodeReader::MoveToAttribute(String) Methode

Bewegt zum Attribut mit dem angegebenen Namen.

```cpp
bool System::Xml::XmlNodeReader::MoveToAttribute(String name) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | [String](../../../system/string/) | Der qualifizierte Name des Attributs. |

### Rückgabewert

**true** wenn das Attribut gefunden wurde; andernfalls **false**. Wenn **false**, ändert sich die Position des Readers nicht.

## XmlNodeReader::MoveToAttribute(String, String) Methode

Bewegt zum Attribut mit dem angegebenen lokalen Namen und dem Namespace-URI.

```cpp
bool System::Xml::XmlNodeReader::MoveToAttribute(String name, String namespaceURI) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | [String](../../../system/string/) | Der lokale Name des Attributs. |
| namespaceURI | [String](../../../system/string/) | Der Namespace-URI des Attributs. |

### Rückgabewert

**true** wenn das Attribut gefunden wurde; andernfalls **false**. Wenn **false**, ändert sich die Position des Readers nicht.

## XmlNodeReader::MoveToAttribute(int32_t) Methode

Bewegt zum Attribut mit dem angegebenen Index.

```cpp
void System::Xml::XmlNodeReader::MoveToAttribute(int32_t attributeIndex) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| attributeIndex | **int32_t** | Der Index des Attributs. |

## Siehe auch

* Klasse [String](../../../system/string/)
* Klasse [XmlNodeReader](../)
* Namensraum [System::Xml](../../)
* Bibliothek [Aspose.Slides](../../../)