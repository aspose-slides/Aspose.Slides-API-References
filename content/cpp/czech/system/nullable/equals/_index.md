---
title: Equals()
second_title: Aspose.Slides pro C++ – referenční dokumentace API
description: Určuje, zda je hodnota reprezentovaná aktuálním objektem rovna hodnotě reprezentované zadaným objektem Nullable.
type: docs
weight: 131
url: /cs/system/nullable/equals/
---
## Nullable::Equals(const T1\&) const metoda


Určuje, zda je hodnota reprezentovaná aktuálním objektem rovna hodnotě reprezentované zadaným objektem [Nullable](../).

```cpp
template<typename T1> std::enable_if<IsNullable<T1>::value, bool>::type System::Nullable<T>::Equals(const T1 &other) const
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T1 | Základní typ objektu [Nullable](../) pro porovnání |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| other | const T1\& | Konstantní reference na objekt [Nullable](../) pro porovnání |

### Návratová hodnota

True pokud je hodnota reprezentovaná aktuálním objektem rovna hodnotě reprezentované zadaným objektem [Nullable](../), jinak - false

## Viz také

* Class [Nullable](../)
* Struct [IsNullable](../../isnullable/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)