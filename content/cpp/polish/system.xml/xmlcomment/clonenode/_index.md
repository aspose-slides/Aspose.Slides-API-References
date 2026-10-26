---
title: CloneNode()
second_title: Aspose.Slides dla C++ - Dokumentacja API
description: Tworzy duplikat tego węzła.
type: docs
weight: 40
url: /pl/system.xml/xmlcomment/clonenode/
---
## XmlComment::CloneNode(bool) metoda


Tworzy duplikat tego węzła.

```cpp
SharedPtr<XmlNode> System::Xml::XmlComment::CloneNode(bool deep) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| deep | **bool** | **true** aby rekurencyjnie sklonować poddrzewo pod określonym węzłem; **false** aby sklonować tylko sam węzeł. Ponieważ węzły komentarzy nie mają dzieci, sklonowany węzeł zawsze zawiera treść tekstową, bez względu na ustawienie parametru. |

### Wartość zwracana

Sklonowany węzeł.

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [XmlNode](../../xmlnode/)
* Klasa [XmlComment](../)
* Przestrzeń nazw [System::Xml](../../)
* Biblioteka [Aspose.Slides](../../../)