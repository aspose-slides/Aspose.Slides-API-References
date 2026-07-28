---
title: CloneNode()
second_title: Aspose.Slides dla odwołania API C++
description: Tworzy duplikat tego węzła. Węzły encji nie mogą być klonowane. Wywołanie tej metody na obiekcie XmlEntity powoduje wyrzucenie wyjątku.
type: docs
weight: 170
url: /pl/system.xml/xmlentity/clonenode/
---
## XmlEntity::CloneNode(bool) metoda

Tworzy duplikat tego węzła. Węzły encji nie mogą być klonowane. Wywołanie tej metody na obiekcie [XmlEntity](../) rzuca wyjątek.

```cpp
SharedPtr<XmlNode> System::Xml::XmlEntity::CloneNode(bool deep) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| deep | **bool** | **true**, aby rekurencyjnie sklonować poddrzewo pod określonym węzłem; **false**, aby sklonować tylko sam węzeł. |

### Wartość zwracana

Kopia [XmlNode](../../xmlnode/), z którego wywołano metodę.

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [XmlNode](../../xmlnode/)
* Klasa [XmlEntity](../)
* Przestrzeń nazw [System::Xml](../../)
* Biblioteka [Aspose.Slides](../../../)