---
title: MoveToAttribute()
second_title: Aspose.Slides für C++ API-Referenz
description: "Wenn in einer abgeleiteten Klasse überschrieben, wechselt es zum Attribut mit dem angegebenen XmlReader::get_Name-Wert."
type: docs
weight: 625
url: /de/system.xml/xmlreader/movetoattribute/
---
## XmlReader::MoveToAttribute(String) Methode

Wenn in einer abgeleiteten Klasse überschrieben, wechselt es zum Attribut mit dem angegebenen [XmlReader::get_Name](../get_name/)-Wert.

```cpp
virtual bool System::Xml::XmlReader::MoveToAttribute(String name)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | [String](../../../system/string/) | Der qualifizierte Name des Attributs. |

### Rückgabewert

**true** wenn das Attribut gefunden wird; andernfalls **false**. Wenn **false**, ändert sich die Position des Lesers nicht.

## XmlReader::MoveToAttribute(String, String) Methode

Wenn in einer abgeleiteten Klasse überschrieben, wechselt es zum Attribut mit den angegebenen [XmlReader::get_LocalName](../get_localname/)- und [XmlReader::get_NamespaceURI](../get_namespaceuri/)-Werten.

```cpp
virtual bool System::Xml::XmlReader::MoveToAttribute(String name, String ns)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | [String](../../../system/string/) | Der lokale Name des Attributs. |
| ns | [String](../../../system/string/) | Der Namespace-URI des Attributs. |

### Rückgabewert

**true** wenn das Attribut gefunden wird; andernfalls **false**. Wenn **false**, ändert sich die Position des Lesers nicht.

## XmlReader::MoveToAttribute(int32_t) Methode

Wenn in einer abgeleiteten Klasse überschrieben, wechselt es zum Attribut mit dem angegebenen Index.

```cpp
virtual void System::Xml::XmlReader::MoveToAttribute(int32_t i)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| i | **int32_t** | Der Index des Attributs. |

## Siehe auch

* Klasse [String](../../../system/string/)
* Klasse [XmlReader](../)
* Namensraum [System::Xml](../../)
* Bibliothek [Aspose.Slides](../../../)