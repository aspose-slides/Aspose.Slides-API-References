---
title: idx_get()
second_title: Aspose.Slides für C++ API-Referenz
description: Wenn in einer abgeleiteten Klasse überschrieben, gibt den Wert des Attributs mit dem angegebenen Index zurück.
type: docs
weight: 612
url: /de/system.xml/xmlreader/idx_get/
---
## XmlReader::idx_get(int32_t) Methode

Wenn in einer abgeleiteten Klasse überschrieben, gibt den Wert des Attributs mit dem angegebenen Index zurück.

```cpp
virtual String System::Xml::XmlReader::idx_get(int32_t i)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| i | **int32_t** | Der Index des Attributs. |

### Rückgabewert

Der Wert des angegebenen Attributs.

## XmlReader::idx_get(String) Methode

Wenn in einer abgeleiteten Klasse überschrieben, gibt den Wert des Attributs mit dem angegebenen [XmlReader::get_Name](../get_name/)-Wert zurück.

```cpp
virtual String System::Xml::XmlReader::idx_get(String name)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | [String](../../../system/string/) | Der qualifizierte Name des Attributs. |

### Rückgabewert

Der Wert des angegebenen Attributs. Falls das Attribut nicht gefunden wird, wird **nullptr** zurückgegeben.

## XmlReader::idx_get(String, String) Methode

Wenn in einer abgeleiteten Klasse überschrieben, gibt den Wert des Attributs mit den angegebenen [XmlReader::get_LocalName](../get_localname/)- und [XmlReader::get_NamespaceURI](../get_namespaceuri/)-Werten zurück.

```cpp
virtual String System::Xml::XmlReader::idx_get(String name, String namespaceURI)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | [String](../../../system/string/) | Der lokale Name des Attributs. |
| namespaceURI | [String](../../../system/string/) | Der Namespace-URI des Attributs. |

### Rückgabewert

Der Wert des angegebenen Attributs. Falls das Attribut nicht gefunden wird, wird **nullptr** zurückgegeben.

## Siehe auch

* Klasse [String](../../../system/string/)
* Klasse [XmlReader](../)
* Namensraum [System::Xml](../../)
* Bibliothek [Aspose.Slides](../../../)