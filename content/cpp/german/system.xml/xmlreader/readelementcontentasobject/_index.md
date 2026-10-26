---
title: ReadElementContentAsObject()
second_title: Aspose.Slides für C++ API Referenz
description: Liest das aktuelle Element und gibt den Inhalt als ein Objekt zurück.
type: docs
weight: 469
url: /de/system.xml/xmlreader/readelementcontentasobject/
---
## XmlReader::ReadElementContentAsObject() Methode

Liest das aktuelle Element und gibt den Inhalt als ein [Object](../../../system/object/) zurück.

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadElementContentAsObject()
```

### Rückgabewert

Ein verpacktes Objekt des am besten geeigneten Typs. Der [XmlReader::get_ValueType](../get_valuetype/)-Wert bestimmt den geeigneten Typ. Wenn der Inhalt als Listentyp typisiert ist, gibt diese Methode ein Array von verpackten Objekten des geeigneten Typs zurück.

## XmlReader::ReadElementContentAsObject(String, String) Methode

Prüft, ob der angegebene lokale Name und die Namespace-URI mit denen des aktuellen Elements übereinstimmen, liest dann das aktuelle Element und gibt den Inhalt als ein [Object](../../../system/object/) zurück.

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadElementContentAsObject(String localName, String namespaceURI)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Der lokale Name des Elements. |
| namespaceURI | [String](../../../system/string/) | Die Namespace-URI des Elements. |

### Rückgabewert

Ein verpacktes Objekt des am besten geeigneten Typs. Der [XmlReader::get_ValueType](../get_valuetype/)-Wert bestimmt den geeigneten Typ. Wenn der Inhalt als Listentyp typisiert ist, gibt diese Methode ein Array von verpackten Objekten des geeigneten Typs zurück.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Object](../../../system/object/)
* Klasse [XmlReader](../)
* Klasse [String](../../../system/string/)
* Namensraum [System::Xml](../../)
* Library [Aspose.Slides](../../../)