---
title: CloneNode()
second_title: Aspose.Slides dla referencji API C++
description: Tworzy duplikat tego węzła.
type: docs
weight: 118
url: /pl/system.xml/xmldocumenttype/clonenode/
---
## XmlDocumentType::CloneNode(bool) method


Tworzy duplikat tego węzła.

```cpp
SharedPtr<XmlNode> System::Xml::XmlDocumentType::CloneNode(bool deep) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| deep | **bool** | **true** aby rekurencyjnie sklonować poddrzewo pod określonym węzłem; **false** aby sklonować tylko sam węzeł. Dla węzłów typu dokumentu sklonowany węzeł zawsze zawiera poddrzewo, niezależnie od ustawienia parametru. |

### Wartość zwracana

Sklonowany węzeł.

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [XmlNode](../../xmlnode/)
* Klasa [XmlDocumentType](../)
* Przestrzeń nazw [System::Xml](../../)
* Biblioteka [Aspose.Slides](../../../)