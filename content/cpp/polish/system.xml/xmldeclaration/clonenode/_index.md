---
title: CloneNode()
second_title: Aspose.Slides dla C++ - Referencja API
description: Tworzy duplikat tego węzła.
type: docs
weight: 157
url: /pl/system.xml/xmldeclaration/clonenode/
---
## XmlDeclaration::CloneNode(bool) metoda

Tworzy duplikat tego węzła.

```cpp
SharedPtr<XmlNode> System::Xml::XmlDeclaration::CloneNode(bool deep) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| deep | **bool** | **true** aby rekurencyjnie sklonować poddrzewo pod określonym węzłem; **false** aby sklonować tylko sam węzeł. Ponieważ węzły [XmlDeclaration](../) nie mają potomków, sklonowany węzeł zawsze zawiera wartość danych, niezależnie od ustawienia parametru. |

### Wartość zwracana

Sklonowany węzeł.

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [XmlNode](../../xmlnode/)
* Klasa [XmlDeclaration](../)
* Przestrzeń nazw [System::Xml](../../)
* Biblioteka [Aspose.Slides](../../../)