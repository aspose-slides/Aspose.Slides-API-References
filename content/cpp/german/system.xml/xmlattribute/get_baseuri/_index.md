---
title: get_BaseURI()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt den Basis-Uniform-Resource-Identifier (URI) des Knotens zurück.
type: docs
weight: 183
url: /de/system.xml/xmlattribute/get_baseuri/
---
## XmlAttribute::get_BaseURI() Methode

Gibt den Basis Uniform Resource Identifier (URI) des Knotens zurück.

```cpp
String System::Xml::XmlAttribute::get_BaseURI() override
```

### Rückgabewert

Der Speicherort, von dem der Knoten geladen wurde, oder [String::Empty](../../../system/string/empty/) falls der Knoten keinen Basis-URI hat. [Attribute](../../../system/attribute/) Knoten haben denselben Basis-URI wie ihr übergeordnetes Element. Wenn ein Attributknoten kein übergeordnetes Element hat, gibt get_BaseURI [String::Empty](../../../system/string/empty/) zurück.

## Siehe auch

* Klasse [String](../../../system/string/)
* Klasse [XmlAttribute](../)
* Namensraum [System::Xml](../../)
* Library [Aspose.Slides](../../../)