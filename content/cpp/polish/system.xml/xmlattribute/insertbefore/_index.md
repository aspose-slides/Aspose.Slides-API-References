---
title: InsertBefore()
second_title: Aspose.Slides for C++ – odniesienie API
description: Wstawia określony węzeł bezpośrednio przed określonym węzłem odniesienia.
type: docs
weight: 209
url: /pl/system.xml/xmlattribute/insertbefore/
---
## XmlAttribute::InsertBefore(SharedPtr\<XmlNode\>, SharedPtr\<XmlNode\>) metoda

Wstawia określony węzeł bezpośrednio przed określonym węzłem odniesienia.

```cpp
SharedPtr<XmlNode> System::Xml::XmlAttribute::InsertBefore(SharedPtr<XmlNode> newChild, SharedPtr<XmlNode> refChild) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | Obiekt [XmlNode](../../xmlnode/) do wstawienia. |
| refChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | [XmlNode](../../xmlnode/) będący węzłem odniesienia. **newChild** jest umieszczany przed tym węzłem. |

### Wartość zwracana

Wstawiono [XmlNode](../../xmlnode/).

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [XmlNode](../../xmlnode/)
* Klasa [XmlAttribute](../)
* Przestrzeń nazw [System::Xml](../../)
* Biblioteka [Aspose.Slides](../../../)