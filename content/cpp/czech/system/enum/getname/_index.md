---
title: GetName()
second_title: Aspose.Slides pro C++ API Reference
description: Vrací název konstanty výčtu, která má zadanou hodnotu.
type: docs
weight: 40
url: /cs/system/enum/getname/
---
## Enum::GetName(T) metoda

Vrací název konstanty výčtu, která má zadanou hodnotu.

```cpp
template<class T> static std::enable_if<std::is_same<T, E>::value||std::is_convertible<T, UnderlyingType>::value, String>::type System::Enum<E, Guard>::GetName(T value)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | T | Hodnota konstanty výčtu, jejíž název se má vrátit |

### Návratová hodnota

Název zadané konstanty výčtu

## Viz také

* Typedef [UnderlyingType](../underlyingtype/)
* Class [String](../../string/)
* Struct [Enum](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)