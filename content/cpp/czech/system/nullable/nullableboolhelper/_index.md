---
title: NullableBoolHelper()
second_title: Aspose.Slides pro C++ API Reference
description: Pomocná funkce pro kontrolu, zda jsou this a other oba nenulové, a v takovém případě zavolá lambda. Používá se v implementation.s.
type: docs
weight: 105
url: /cs/system/nullable/nullableboolhelper/
---
## Nullable::NullableBoolHelper(const T1\&, const std::function\<bool()>\&, bool) const metoda

Pomocná funkce, která kontroluje, zda **this** i **other** nejsou oba null a v takovém případě zavolá lambda. Používá se v implementation.s.

```cpp
template<typename T1> bool System::Nullable<T>::NullableBoolHelper(const T1 &other, const std::function<bool()> &f, bool default_if_both_are_null=false) const
```

### Parametry šablony

| Parameter | Description |
| --- | --- |
| T1 | Jiný nullable typ. |

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| other | const T1\& | Další nullable hodnota pro porovnání. |
| f | const std::function\<**bool**()>\& | Lambda, která se zavolá, pokud **this** a **other** nejsou null. |
| default_if_both_are_null | **bool** | Návratová hodnota, pokud jsou obě hodnoty null. |

### Návratová hodnota

false, pokud je **this** nebo **other** null; **default_if_both_are_null**, pokud jsou oba null; výsledek volání **f**, pokud jsou oba nenull.

## Viz také

* Třída [Nullable](../)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)