---
title: CloneNode()
second_title: Aspose.Slides for C++ - dokumentacja API
description: Tworzy duplikat tego węzła. Węzły Notation nie mogą być klonowane. Wywołanie tej metody na obiekcie XmlNotation powoduje zgłoszenie wyjątku.
type: docs
weight: 118
url: /pl/system.xml/xmlnotation/clonenode/
---
## XmlNotation::CloneNode(bool) metoda

Tworzy duplikat tego węzła. Węzły Notation nie mogą być klonowane. Wywołanie tej metody na obiekcie [XmlNotation](../) powoduje zgłoszenie wyjątku.

```cpp
SharedPtr<XmlNode> System::Xml::XmlNotation::CloneNode(bool deep) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| deep | **bool** | **true** aby rekurencyjnie sklonować poddrzewo pod określonym węzłem; **false** aby sklonować tylko sam węzeł. |

### Wartość zwracana

Kopia [XmlNode](../../xmlnode/) węzła, z którego wywołano metodę.

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [XmlNode](../../xmlnode/)
* Klasa [XmlNotation](../)
* Przestrzeń nazw [System::Xml](../../)
* Biblioteka [Aspose.Slides](../../../)