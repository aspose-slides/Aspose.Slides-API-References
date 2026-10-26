---
title: MoveToAttribute()
second_title: Aspose.Slides für C++ API Referenz
description: Bewegt zum Attribut mit dem angegebenen Namen.
type: docs
weight: 508
url: /de/system.xml/xmltextreader/movetoattribute/
---
## XmlTextReader::MoveToAttribute(String) Methode

Bewegt zum Attribut mit dem angegebenen Namen.

```cpp
bool System::Xml::XmlTextReader::MoveToAttribute(String name) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | [String](../../../system/string/) | Der qualifizierte Name des Attributs. |

### Rückgabewert

**true** wenn das Attribut gefunden wird; andernfalls **false**. Wenn **false**, ändert sich die Position des Readers nicht.

## XmlTextReader::MoveToAttribute(String, String) Methode

Bewegt zum Attribut mit dem angegebenen lokalen Namen und dem Namespace-URI.

```cpp
bool System::Xml::XmlTextReader::MoveToAttribute(String localName, String namespaceURI) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Der lokale Name des Attributs. |
| namespaceURI | [String](../../../system/string/) | Der Namespace-URI des Attributs. |

### Rückgabewert

**true** wenn das Attribut gefunden wird; andernfalls **false**. Wenn **false**, ändert sich die Position des Readers nicht.

## XmlTextReader::MoveToAttribute(int32_t) Methode

Bewegt zum Attribut mit dem angegebenen Index.

```cpp
void System::Xml::XmlTextReader::MoveToAttribute(int32_t i) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| i | **int32_t** | Der Index des Attributs. |

## Siehe auch

* Klasse [String](../../../system/string/)
* Klasse [XmlTextReader](../)
* Namensraum [System::Xml](../../)
* Bibliothek [Aspose.Slides](../../../)