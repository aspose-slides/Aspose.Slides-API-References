---
title: GetAttribute()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt den Wert des Attributs mit dem angegebenen Namen zurück.
type: docs
weight: 495
url: /de/system.xml/xmltextreader/getattribute/
---
## XmlTextReader::GetAttribute(String) Methode


Gibt den Wert des Attributs mit dem angegebenen Namen zurück.

```cpp
String System::Xml::XmlTextReader::GetAttribute(String name) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | [String](../../../system/string/) | Der voll qualifizierte Name des Attributs. |

### Rückgabewert

Der Wert des angegebenen Attributs. Wenn das Attribut nicht gefunden wird, wird **nullptr** zurückgegeben.

## XmlTextReader::GetAttribute(String, String) Methode


Gibt den Wert des Attributs mit dem angegebenen lokalen Namen und dem Namespace-URI zurück.

```cpp
String System::Xml::XmlTextReader::GetAttribute(String localName, String namespaceURI) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Der lokale Name des Attributs. |
| namespaceURI | [String](../../../system/string/) | Der Namespace-URI des Attributs. |

### Rückgabewert

Der Wert des angegebenen Attributs. Wenn das Attribut nicht gefunden wird, wird **nullptr** zurückgegeben. Diese Methode bewegt den Reader nicht.

## XmlTextReader::GetAttribute(int32_t) Methode


Gibt den Wert des Attributs mit dem angegebenen Index zurück.

```cpp
String System::Xml::XmlTextReader::GetAttribute(int32_t i) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| i | **int32_t** | Der Index des Attributs. Der Index ist nullbasiert. (Das erste Attribut hat den Index 0.) |

### Rückgabewert

Der Wert des angegebenen Attributs.

## Siehe auch

* Klasse [String](../../../system/string/)
* Klasse [XmlTextReader](../)
* Namensraum [System::Xml](../../)
* Bibliothek [Aspose.Slides](../../../)