---
title: GetDescription()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar namnet på uppräkningkonstanten som har det specificerade värdet.
type: docs
weight: 53
url: /sv/system/enum/getdescription/
---
## Enum::GetDescription(T) metod


Returnerar namnet på uppräkningkonstanten som har det specificerade värdet.

```cpp
template<class T> static std::enable_if<std::is_same<T, E>::value||std::is_convertible<T, UnderlyingType>::value, String>::type System::Enum<E, Guard>::GetDescription(T value)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | T | Värdet på enum-konstanten vars namn ska returneras |

### Returvärde

Namnet på den specificerade enum-konstanten

## Se även

* Typedef [UnderlyingType](../underlyingtype/)
* Klass [String](../../string/)
* Struktur [Enum](../)
* Namnutrymme [System](../../)
* Bibliotek [Aspose.Slides](../../../)