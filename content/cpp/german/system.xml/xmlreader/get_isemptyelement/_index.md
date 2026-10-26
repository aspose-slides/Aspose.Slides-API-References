---
title: get_IsEmptyElement()
second_title: Aspose.Slides für C++ API-Referenz
description: Wenn sie in einer abgeleiteten Klasse überschrieben wird, gibt sie einen Wert zurück, der angibt, ob der aktuelle Knoten ein leeres Element ist (zum Beispiel <MyElement/>).
type: docs
weight: 131
url: /de/system.xml/xmlreader/get_isemptyelement/
---
## XmlReader::get_IsEmptyElement() Methode

Wenn sie in einer abgeleiteten Klasse überschrieben wird, liefert sie einen Wert, der angibt, ob das aktuelle Knoten ein leeres Element ist (zum Beispiel **<MyElement/>**).

```cpp
virtual bool System::Xml::XmlReader::get_IsEmptyElement()=0
```

### Rückgabewert

**true**, wenn das aktuelle Knoten ein Element ([XmlReader::get_NodeType](../get_nodetype/) ist gleich [XmlNodeType::Element](../../xmlnodetype/)) ist, das mit **/>** endet; andernfalls **false**.

## Siehe auch

* Klasse [XmlReader](../)
* Namensraum [System::Xml](../../)
* Bibliothek [Aspose.Slides](../../../)