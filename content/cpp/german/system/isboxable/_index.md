---
title: IsBoxable
second_title: Aspose.Slides für C++ API-Referenz
description: Template-Prädikat, das prüft, ob das Boxen des angegebenen Typs unterstützt wird.
type: docs
weight: 1665
url: /de/system/isboxable/
---
## IsBoxable struct


Template-Prädikat, das prüft, ob das Boxen des angegebenen Typs unterstützt wird.

```cpp
template<typename T>class IsBoxable : public std::integral_constant<bool, std::is_base_of<Details::BoxableObjectBase, T>::value||std::is_arithmetic<T>::value||std::is_enum<T>::value>
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Der zu prüfende Typ |

## Siehe auch

* Namensraum [System](../)
* Bibliothek [Aspose.Slides](../../)