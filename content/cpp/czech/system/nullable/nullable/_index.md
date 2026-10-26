---
title: Nullable()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Vytvoří instanci, která představuje nulovou hodnotu.
type: docs
weight: 1
url: /cs/system/nullable/nullable/
---
## Nullable::Nullable() konstruktor

Vytvoří instanci, která představuje nulovou hodnotu.

```cpp
System::Nullable<T>::Nullable()
```

## Nullable::Nullable(std::nullptr_t) konstruktor

Vytvoří instanci, která představuje null.

```cpp
System::Nullable<T>::Nullable(std::nullptr_t)
```

## Nullable::Nullable(const T1\&) konstruktor

Vytvoří instanci třídy [Nullable](../), která představuje zadanou hodnotu převedenou (pokud je to nutné) na hodnotu základního typu T.

```cpp
template<typename T1> System::Nullable<T>::Nullable(const T1 &value)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T1 | Typ zadané hodnoty |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const T1\& | Konstantní reference na hodnotu, která má být představena nově vytvořeným objektem [Nullable](../) |

## Nullable::Nullable(const Nullable\<T1\>\&) konstruktor

Vytvoří instanci, která představuje hodnotu, jež je reprezentována zadaným objektem [Nullable](../). Zadaný nullable objekt může představovat hodnotu jiného typu než základní typ vytvářené instance, v takovém případě je představovaná hodnota převedena na hodnotu typu T.

```cpp
template<typename T1> System::Nullable<T>::Nullable(const Nullable<T1> &value)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T1 | Typ hodnoty reprezentované zadaným objektem [Nullable](../) |

## Viz také

* Třída [Nullable](../)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)