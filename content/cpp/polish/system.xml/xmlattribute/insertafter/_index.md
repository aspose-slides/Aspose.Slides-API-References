---
title: InsertAfter()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Wstawia określony węzeł bezpośrednio po wskazanym węźle referencyjnym.
type: docs
weight: 222
url: /pl/system.xml/xmlattribute/insertafter/
---
## XmlAttribute::InsertAfter(SharedPtr\<XmlNode\>, SharedPtr\<XmlNode\>) metoda

Wstawia określony węzeł bezpośrednio po wskazanym węźle referencyjnym.

```cpp
SharedPtr<XmlNode> System::Xml::XmlAttribute::InsertAfter(SharedPtr<XmlNode> newChild, SharedPtr<XmlNode> refChild) override
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | [XmlNode](../../xmlnode/) do wstawienia. |
| refChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | [XmlNode](../../xmlnode/) będący węzłem referencyjnym. **newChild** jest umieszczany po **refChild**. |

### Wartość zwracana

Wstawiony [XmlNode](../../xmlnode/).

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [XmlNode](../../xmlnode/)
* Klasa [XmlAttribute](../)
* Przestrzeń nazw [System::Xml](../../)
* Library [Aspose.Slides](../../../)