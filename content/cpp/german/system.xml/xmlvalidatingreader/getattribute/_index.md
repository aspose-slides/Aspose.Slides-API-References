---
title: GetAttribute()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt den Wert des Attributs mit dem angegebenen Namen zurück.
type: docs
weight: 443
url: /de/system.xml/xmlvalidatingreader/getattribute/
---
## XmlValidatingReader::GetAttribute(String) Methode

Gibt den Wert des Attributs mit dem angegebenen Namen zurück.

```cpp
String System::Xml::XmlValidatingReader::GetAttribute(String name) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | [String](../../../system/string/) | Der qualifizierte Name des Attributs. |

### Rückgabewert

Der Wert des angegebenen Attributs. Wenn das Attribut nicht gefunden wird, wird **nullptr** zurückgegeben.

## XmlValidatingReader::GetAttribute(String, String) Methode

Gibt den Wert des Attributs mit dem angegebenen lokalen Namen und dem Namespace-Uniform-Resource-Identifier (URI) zurück.

```cpp
String System::Xml::XmlValidatingReader::GetAttribute(String localName, String namespaceURI) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Der lokale Name des Attributs. |
| namespaceURI | [String](../../../system/string/) | Der Namespace-URI des Attributs. |

### Rückgabewert

Der Wert des angegebenen Attributs. Wenn das Attribut nicht gefunden wird, wird **nullptr** zurückgegeben. Diese Methode verschiebt den Reader nicht.

## XmlValidatingReader::GetAttribute(int32_t) Methode

Gibt den Wert des Attributs mit dem angegebenen Index zurück.

```cpp
String System::Xml::XmlValidatingReader::GetAttribute(int32_t i) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| i | **int32_t** | Der Index des Attributs. Der Index ist nullbasiert. (Das erste Attribut hat Index 0.) |

### Rückgabewert

Der Wert des angegebenen Attributs.

## Siehe auch

* Klasse [String](../../../system/string/)
* Klasse [XmlValidatingReader](../)
* Namensraum [System::Xml](../../)
* Bibliothek [Aspose.Slides](../../../)