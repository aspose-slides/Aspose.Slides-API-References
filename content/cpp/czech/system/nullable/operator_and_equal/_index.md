---
title: operator&=()
second_title: Aspose.Slides pro C++ – reference API
description: Použije operátor&=() na hodnotu představovanou aktuálním objektem s použitím zadané hodnoty jako argumentu na pravé straně.
type: docs
weight: 274
url: /cs/system/nullable/operator_and_equal/
---
## Nullable::operator&=(bool) metoda

Použije [operator&=()](./) na hodnotu, kterou představuje aktuální objekt, s použitím zadané hodnoty jako argumentu na pravé straně.

```cpp
template<typename T1> std::enable_if<std::is_same<T1, bool>::value, Nullable<T>>::type System::Nullable<T>::operator&=(bool other)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T1 | Parametr šablony, který umožňuje fungování SFINAE. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| other | **bool** | Booleovská hodnota, která se používá jako pravá hodnota [operator&=()](./) aplikovaná na hodnotu představovanou aktuálním objektem. |

### Návratová hodnota

Odkaz na sebe.

## Viz také

* Třída [Nullable](../)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)