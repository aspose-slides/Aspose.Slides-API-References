---
title: PrependChild()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Dodaje określony węzeł na początek listy węzłów potomnych tego węzła.
type: docs
weight: 261
url: /pl/system.xml/xmlattribute/prependchild/
---
## XmlAttribute::PrependChild(SharedPtr\<XmlNode\>) metoda

Dodaje określony węzeł na początek listy węzłów potomnych tego węzła.

```cpp
SharedPtr<XmlNode> System::Xml::XmlAttribute::PrependChild(SharedPtr<XmlNode> newChild) override
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | [XmlNode](../../xmlnode/) do dodania. Jeśli jest to [XmlDocumentFragment](../../xmldocumentfragment/), cała zawartość fragmentu dokumentu zostaje przeniesiona do listy potomków tego węzła. |

### Wartość zwracana

Dodany [XmlNode](../../xmlnode/).

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [XmlNode](../../xmlnode/)
* Klasa [XmlAttribute](../)
* Przestrzeń nazw [System::Xml](../../)
* Biblioteka [Aspose.Slides](../../../)