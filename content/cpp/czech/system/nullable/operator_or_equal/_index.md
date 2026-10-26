---
title: operator|=()
second_title: Aspose.Slides pro C++ API Reference
description: Použije operator|=() na hodnotu reprezentovanou aktuálním objektem pomocí zadané hodnoty jako pravého argumentu.
type: docs
weight: 261
url: /cs/system/nullable/operator_or_equal/
---
## Nullable::operator|=(bool) metoda


Použije [operator|=()](./) na hodnotu reprezentovanou aktuálním objektem pomocí zadané hodnoty jako pravého argumentu.

```cpp
template<typename T1> std::enable_if<std::is_same<T1, bool>::value, Nullable<T>>::type System::Nullable<T>::operator|=(bool other)
```


### Parametry šablony

| Parameter | Description |
| --- | --- |
| T1 | Parametr šablony, který umožňuje fungování SFINAE. |

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| other | **bool** | Bool hodnota, která se používá jako pravá hodnota [operator|=()](./) aplikovaná na hodnotu reprezentovanou aktuálním objektem. |

### Návratová hodnota

Reference na sebe.

## Viz také

* Třída [Nullable](../)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)