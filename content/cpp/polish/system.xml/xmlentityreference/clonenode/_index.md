---
title: CloneNode()
second_title: Aspose.Slides dla C++ – referencja API
description: Tworzy duplikat tego węzła.
type: docs
weight: 92
url: /pl/system.xml/xmlentityreference/clonenode/
---
## XmlEntityReference::CloneNode(bool) metoda

Tworzy duplikat tego węzła.

```cpp
SharedPtr<XmlNode> System::Xml::XmlEntityReference::CloneNode(bool deep) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| deep | **bool** | **true**, aby rekurencyjnie sklonować poddrzewo pod określonym węzłem; **false**, aby sklonować tylko sam węzeł. Dla węzłów [XmlEntityReference](../) ta metoda zawsze zwraca węzeł referencji encji bez dzieci. Tekst zamienny jest ustawiany, gdy węzeł zostaje wstawiony do rodzica. |

### Wartość zwracana

Sklonowany węzeł.

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [XmlNode](../../xmlnode/)
* Klasa [XmlEntityReference](../)
* Przestrzeń nazw [System::Xml](../../)
* Biblioteka [Aspose.Slides](../../../)