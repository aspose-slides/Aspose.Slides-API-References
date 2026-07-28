---
title: Exchange()
second_title: Aspose.Slides C++ API referencia
description: "Kicseréli a változó értékét: tárolja az új értéket, és visszaadja a változó tárolás előtt meglévő értékét."
type: docs
weight: 66
url: /hu/system.threading/interlocked/exchange/
---
## Interlocked::Exchange(T&, T) metódus

Kicseréli a változó értékét: tárolja az új értéket, és visszaadja a változó tárolás előtt meglévő értékét.

```cpp
template<typename T> static std::enable_if<IsSupportedInt<T>, T>::type System::Threading::Interlocked::Exchange(T &location1, T value)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | Változó típusa. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| location1 | T\& | Változóra mutató referencia a módosításhoz. |
| value | T | Tárolandó érték. |

### Visszatérési érték

A változó értéke közvetlenül a módosítás előtt.

## Interlocked::Exchange(T&, T) metódus

Kicseréli a változó értékét: tárolja az új értéket, és visszaadja a változó tárolás előtt meglévő értékét. Nincs megvalósítva.

```cpp
template<typename T> static std::enable_if<!IsSupportedInt<T>, T>::type System::Threading::Interlocked::Exchange(T &location1, T value)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | Változó típusa. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| location1 | T\& | Változóra mutató referencia a módosításhoz. |
| value | T | Tárolandó érték. |

### Visszatérési érték

A változó értéke közvetlenül a módosítás előtt.

## Lásd még

* Osztály [Interlocked](../)
* Névtér [System::Threading](../../)
* Könyvtár [Aspose.Slides](../../../)