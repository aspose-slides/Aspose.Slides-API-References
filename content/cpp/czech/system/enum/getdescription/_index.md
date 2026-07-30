---
title: GetDescription()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Vrací název konstanty výčtu, která má zadanou hodnotu.
type: docs
weight: 53
url: /cs/system/enum/getdescription/
---
## Enum::GetDescription(T) metoda

Vrací název konstanty výčtu, která má zadanou hodnotu.

```cpp
template<class T> static std::enable_if<std::is_same<T, E>::value||std::is_convertible<T, UnderlyingType>::value, String>::type System::Enum<E, Guard>::GetDescription(T value)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | T | Hodnota konstanty výčtu, jejíž název má být vrácen |

### Návratová hodnota

Název zadané konstanty výčtu

## Viz také

* Typedef [UnderlyingType](../underlyingtype/)
* Třída [String](../../string/)
* Struct [Enum](../)
* Jmenný prostor [System](../../)
* Library [Aspose.Slides](../../../)