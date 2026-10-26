---
title: GetAttribute()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt den Wert des Attributs mit dem angegebenen Namen zurück.
type: docs
weight: 287
url: /de/system.xml/xmlnodereader/getattribute/
---
## XmlNodeReader::GetAttribute(String) Methode

Gibt den Wert des Attributs mit dem angegebenen Namen zurück.

```cpp
String System::Xml::XmlNodeReader::GetAttribute(String name) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | [String](../../../system/string/) | Der qualifizierte Name des Attributs. |

### Rückgabewert

Der Wert des angegebenen Attributs. Wenn das Attribut nicht gefunden wird, wird **nullptr** zurückgegeben.

## XmlNodeReader::GetAttribute(String, String) Methode

Gibt den Wert des Attributs mit dem angegebenen lokalen Namen und Namespace-URI zurück.

```cpp
String System::Xml::XmlNodeReader::GetAttribute(String name, String namespaceURI) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | [String](../../../system/string/) | Der lokale Name des Attributs. |
| namespaceURI | [String](../../../system/string/) | Der Namespace-URI des Attributs. |

### Rückgabewert

Der Wert des angegebenen Attributs. Wenn das Attribut nicht gefunden wird, wird **nullptr** zurückgegeben.

## XmlNodeReader::GetAttribute(int32_t) Methode

Gibt den Wert des Attributs mit dem angegebenen Index zurück.

```cpp
String System::Xml::XmlNodeReader::GetAttribute(int32_t attributeIndex) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| attributeIndex | **int32_t** | Der Index des Attributs. Der Index ist nullbasiert. (Das erste Attribut hat den Index 0.) |

### Rückgabewert

Der Wert des angegebenen Attributs.

## Siehe auch

* Klasse [String](../../../system/string/)
* Klasse [XmlNodeReader](../)
* Namensraum [System::Xml](../../)
* Bibliothek [Aspose.Slides](../../../)