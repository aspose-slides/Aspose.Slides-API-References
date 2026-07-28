---
title: CloneNode()
second_title: Aspose.Slides dla C++ Dokumentacja API
description: Tworzy duplikat tego węzła.
type: docs
weight: 53
url: /pl/system.xml/xmlcdatasection/clonenode/
---
## XmlCDataSection::CloneNode(bool) metoda

Tworzy duplikat tego węzła.

```cpp
SharedPtr<XmlNode> System::Xml::XmlCDataSection::CloneNode(bool deep) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| deep | **bool** | **true** aby rekurencyjnie sklonować poddrzewo pod określonym węzłem; **false** aby sklonować tylko sam węzeł. Ponieważ węzły CDATA nie mają dzieci, niezależnie od ustawienia parametru, sklonowany węzeł zawsze będzie zawierał treść danych. |

### Wartość zwracana

Sklonowany węzeł.

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [XmlNode](../../xmlnode/)
* Klasa [XmlCDataSection](../)
* Przestrzeń nazw [System::Xml](../../)
* Biblioteka [Aspose.Slides](../../../)