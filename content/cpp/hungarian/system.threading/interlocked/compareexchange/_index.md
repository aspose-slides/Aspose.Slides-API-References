---
title: CompareExchange()
second_title: Aspose.Slides C++ API Referenciája
description: "Összehasonlít és cserél értéket a változón: ellenőrzi, hogy a változó egy adott értékkel egyenlő-e, és csak akkor tárolja az új értéket, ha a tárolt érték megegyezik a várt értékkel."
type: docs
weight: 79
url: /hu/system.threading/interlocked/compareexchange/
---
## Interlocked::CompareExchange(T&, T, T) metódus


Összehasonlít és cserél értéket a változón: ellenőrzi, hogy a változó egy adott értékkel egyenlő-e, és csak akkor tárolja az új értéket, ha a tárolt érték megegyezik a várt értékkel.

```cpp
template<typename T> static std::enable_if<IsSupportedInt<T>, T>::type System::Threading::Interlocked::CompareExchange(T &location1, T value, T comparand)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | Változó típusa. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| location1 | T\& | Változóreferencia a módosításhoz. |
| value | T | Tárolandó érték. |
| comparand | T | Az a érték, amellyel a változó értékét cserélés előtt összehasonlítják. |

### Visszatérési érték

A változó értéke a művelet kezdete előtt, függetlenül attól, hogy megváltozott-e vagy sem.

## Interlocked::CompareExchange(T&, T, T) metódus


Összehasonlít és cserél értéket a változón: ellenőrzi, hogy a változó egy adott értékkel egyenlő-e, és csak akkor tárolja az új értéket, ha a tárolt érték megegyezik a várt értékkel. Nem implementált.

```cpp
template<typename T> static std::enable_if<!IsSupportedInt<T>, T>::type System::Threading::Interlocked::CompareExchange(T &location1, T value, T comparand)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | Változó típusa. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| location1 | T\& | Változóreferencia a módosításhoz. |
| value | T | Tárolandó érték. |
| comparand | T | Az a érték, amellyel a változó értékét cserélés előtt összehasonlítják. |

### Visszatérési érték

A változó értéke a művelet kezdete előtt, függetlenül attól, hogy megváltozott-e vagy sem.

## Interlocked::CompareExchange(int32_t&, int32_t, int32_t, bool&) metódus


Összehasonlít és cserél értéket a változón: ellenőrzi, hogy a változó egy adott értékkel egyenlő-e, és csak akkor tárolja az új értéket, ha a tárolt érték megegyezik a várt értékkel.

```cpp
static int32_t System::Threading::Interlocked::CompareExchange(int32_t &location1, int32_t value, int32_t comparand, bool &succeeded)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| location1 | **int32_t**\& | Változóreferencia a módosításhoz. |
| value | **int32_t** | Tárolandó érték. |
| comparand | **int32_t** | Az a érték, amellyel a változó értékét cserélés előtt összehasonlítják. |
| succeeded | **bool**\& | Változóra mutató referencia, amely igazra (true) lesz állítva, ha a csere megtörtént, egyébként hamisra (false). |

### Visszatérési érték

A változó értéke a művelet kezdete előtt, függetlenül attól, hogy megváltozott-e vagy sem.

## Lásd még

* Osztály [Interlocked](../)
* Névtér [System::Threading](../../)
* Könyvtár [Aspose.Slides](../../../)