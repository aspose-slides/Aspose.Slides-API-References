---
title: IsBoxable
second_title: Aspose.Slides för C++ API-referens
description: Mallpredikat som kontrollerar om inkapsling av den angivna typen stöds.
type: docs
weight: 1665
url: /sv/system/isboxable/
---
## IsBoxable struct


Mallpredikat som kontrollerar om inkapsling av den angivna typen stöds.

```cpp
template<typename T>class IsBoxable : public std::integral_constant<bool, std::is_base_of<Details::BoxableObjectBase, T>::value||std::is_arithmetic<T>::value||std::is_enum<T>::value>
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen att kontrollera |

## Se även

* Namnrymd [System](../)
* Bibliotek [Aspose.Slides](../../)