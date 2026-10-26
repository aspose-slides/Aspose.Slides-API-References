---
title: Nullable()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Tworzy instancję, która reprezentuje wartość null.
type: docs
weight: 1
url: /pl/system/nullable/nullable/
---
## Nullable::Nullable() konstruktor

Tworzy instancję, która reprezentuje wartość null.

```cpp
System::Nullable<T>::Nullable()
```
## Nullable::Nullable(std::nullptr_t) konstruktor

Tworzy instancję, która reprezentuje null.

```cpp
System::Nullable<T>::Nullable(std::nullptr_t)
```
## Nullable::Nullable(const T1\&) konstruktor

Tworzy instancję klasy [Nullable](../), która reprezentuje podaną wartość przekształconą (w razie potrzeby) na wartość podstawowego typu T.

```cpp
template<typename T1> System::Nullable<T>::Nullable(const T1 &value)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T1 | Typ podanej wartości |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const T1\& | Stałe odwołanie do wartości, którą ma reprezentować nowo utworzony obiekt [Nullable](../) |

## Nullable::Nullable(const Nullable\<T1\>\&) konstruktor

Tworzy instancję, która reprezentuje wartość reprezentowaną przez podany obiekt [Nullable](../). Podany obiekt nullable może reprezentować wartość innego typu niż podstawowy typ konstrukcji, w takim przypadku reprezentowana wartość jest konwertowana na wartość typu T.

```cpp
template<typename T1> System::Nullable<T>::Nullable(const Nullable<T1> &value)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T1 | Typ wartości reprezentowanej przez podany obiekt [Nullable](../) |

## Zobacz także

* Klasa [Nullable](../)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)