---
title: GetAttribute()
second_title: Aspose.Slides für C++ API Referenz
description: "Wird in einer abgeleiteten Klasse überschrieben, gibt den Wert des Attributs mit dem angegebenen XmlReader::get_Name-Wert zurück."
type: docs
weight: 599
url: /de/system.xml/xmlreader/getattribute/
---
## XmlReader::GetAttribute(String) Methode


Wird in einer abgeleiteten Klasse überschrieben, gibt den Wert des Attributs mit dem angegebenen [XmlReader::get_Name](../get_name/)-Wert zurück.

```cpp
virtual String System::Xml::XmlReader::GetAttribute(String name)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | [String](../../../system/string/) | Der qualifizierte Name des Attributs. |

### Rückgabewert

Der Wert des angegebenen Attributs. Wenn das Attribut nicht gefunden wird oder der Wert [String::Empty](../../../system/string/empty/) ist, wird **nullptr** zurückgegeben.

## XmlReader::GetAttribute(String, String) Methode


Wird in einer abgeleiteten Klasse überschrieben, gibt den Wert des Attributs mit den angegebenen [XmlReader::get_LocalName](../get_localname/)- und [XmlReader::get_NamespaceURI](../get_namespaceuri/)-Werten zurück.

```cpp
virtual String System::Xml::XmlReader::GetAttribute(String name, String namespaceURI)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | [String](../../../system/string/) | Der lokale Name des Attributs. |
| namespaceURI | [String](../../../system/string/) | Der Namespace-URI des Attributs. |

### Rückgabewert

Der Wert des angegebenen Attributs. Wenn das Attribut nicht gefunden wird oder der Wert [String::Empty](../../../system/string/empty/) ist, wird **nullptr** zurückgegeben. Diese Methode verschiebt den Leser nicht.

## XmlReader::GetAttribute(int32_t) Methode


Wird in einer abgeleiteten Klasse überschrieben, gibt den Wert des Attributs mit dem angegebenen Index zurück.

```cpp
virtual String System::Xml::XmlReader::GetAttribute(int32_t i)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| i | **int32_t** | Der Index des Attributs. Der Index ist nullbasiert. (Das erste Attribut hat den Index 0.) |

### Rückgabewert

Der Wert des angegebenen Attributs. Diese Methode verschiebt den Leser nicht.

## Siehe auch

* Klasse [String](../../../system/string/)
* Klasse [XmlReader](../)
* Namensraum [System::Xml](../../)
* Bibliothek [Aspose.Slides](../../../)