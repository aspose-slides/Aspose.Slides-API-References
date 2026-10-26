---
title: GetName()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar namnet på uppräkningskonstanten som har det angivna värdet.
type: docs
weight: 40
url: /sv/system/enum/getname/
---
## Enum::GetName(T) metod


Returnerar namnet på uppräkningskonstanten som har det angivna värdet.

```cpp
template<class T> static std::enable_if<std::is_same<T, E>::value||std::is_convertible<T, UnderlyingType>::value, String>::type System::Enum<E, Guard>::GetName(T value)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | T | Värdet på enum-konstanten vars namn ska returneras |

### Returvärde

Namnet på den angivna enum-konstanten

## Se även

* Typedef [UnderlyingType](../underlyingtype/)
* Klass [String](../../string/)
* Struktur [Enum](../)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)