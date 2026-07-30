---
title: Exchange()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: "Vyměňuje hodnotu v proměnné: ukládá novou hodnotu a vrací hodnotu, kterou proměnná měla těsně před uložením."
type: docs
weight: 66
url: /cs/system.threading/interlocked/exchange/
---
## Interlocked::Exchange(T\&, T) metoda


Vyměňuje hodnotu v proměnné: uloží novou hodnotu a vrátí hodnotu, kterou proměnná měla těsně před uložením.

```cpp
template<typename T> static std::enable_if<IsSupportedInt<T>, T>::type System::Threading::Interlocked::Exchange(T &location1, T value)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ proměnné. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| location1 | T\& | Odkaz na proměnnou, která se má změnit. |
| value | T | Hodnota k uložení. |

### Návratová hodnota

Hodnota proměnné těsně před jejím změněním.

## Interlocked::Exchange(T\&, T) metoda


Vyměňuje hodnotu v proměnné: uloží novou hodnotu a vrátí hodnotu, kterou proměnná měla těsně před uložením. Not implemented.

```cpp
template<typename T> static std::enable_if<!IsSupportedInt<T>, T>::type System::Threading::Interlocked::Exchange(T &location1, T value)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ proměnné. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| location1 | T\& | Odkaz na proměnnou, která se má změnit. |
| value | T | Hodnota k uložení. |

### Návratová hodnota

Hodnota proměnné těsně před jejím změněním.

## Viz také

* Třída [Interlocked](../)
* Jmenný prostor [System::Threading](../../)
* Knihovna [Aspose.Slides](../../../)