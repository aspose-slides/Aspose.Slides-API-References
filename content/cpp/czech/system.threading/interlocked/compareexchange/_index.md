---
title: CompareExchange()
second_title: Aspose.Slides pro C++ API Reference
description: "Porovná a vymění hodnotu proměnné: kontroluje, zda je proměnná rovna konkrétní hodnotě, a uloží novou hodnotu pouze pokud se uložená hodnota shoduje s očekávanou."
type: docs
weight: 79
url: /cs/system.threading/interlocked/compareexchange/
---
## Interlocked::CompareExchange(T\&, T, T) metoda

Porovná a vymění hodnotu proměnné: kontroluje, zda je proměnná rovna specifické hodnotě, a uloží novou hodnotu pouze pokud se uložená hodnota shoduje s očekávanou.

```cpp
template<typename T> static std::enable_if<IsSupportedInt<T>, T>::type System::Threading::Interlocked::CompareExchange(T &location1, T value, T comparand)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ proměnné. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| location1 | T\& | Reference na proměnnou k změně. |
| value | T | Hodnota k uložení. |
| comparand | T | Hodnota, se kterou se před výměnou porovnává hodnota proměnné. |

### Návratová hodnota

Hodnota proměnné na začátku operace bez ohledu na to, zda byla změněna nebo ne.

## Interlocked::CompareExchange(T\&, T, T) metoda

Porovná a vymění hodnotu proměnné: kontroluje, zda je proměnná rovna specifické hodnotě, a uloží novou hodnotu pouze pokud se uložená hodnota shoduje s očekávanou. Not implemented.

```cpp
template<typename T> static std::enable_if<!IsSupportedInt<T>, T>::type System::Threading::Interlocked::CompareExchange(T &location1, T value, T comparand)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ proměnné. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| location1 | T\& | Reference na proměnnou k změně. |
| value | T | Hodnota k uložení. |
| comparand | T | Hodnota, se kterou se před výměnou porovnává hodnota proměnné. |

### Návratová hodnota

Hodnota proměnné na začátku operace bez ohledu na to, zda byla změněna nebo ne.

## Interlocked::CompareExchange(int32_t\&, int32_t, int32_t, bool\&) metoda

Porovná a vymění hodnotu proměnné: kontroluje, zda je proměnná rovna specifické hodnotě, a uloží novou hodnotu pouze pokud se uložená hodnota shoduje s očekávanou.

```cpp
static int32_t System::Threading::Interlocked::CompareExchange(int32_t &location1, int32_t value, int32_t comparand, bool &succeeded)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| location1 | **int32_t**\& | Reference na proměnnou k změně. |
| value | **int32_t** | Hodnota k uložení. |
| comparand | **int32_t** | Hodnota, se kterou se před výměnou porovnává hodnota proměnné. |
| succeeded | **bool**\& | Reference na proměnnou, která je nastavena na true, pokud k výměně došlo, a na false v opačném případě. |

### Návratová hodnota

Hodnota proměnné na začátku operace bez ohledu na to, zda byla změněna nebo ne.

## Viz také

* Třída [Interlocked](../)
* Jmenný prostor [System::Threading](../../)
* Knihovna [Aspose.Slides](../../../)