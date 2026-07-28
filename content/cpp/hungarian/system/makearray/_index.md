---
title: MakeArray()
second_title: Aspose.Slides C++ API-referencia
description: Egy gyári függvény, amely új Array objektumot hoz létre, kitölti a megadott inicializáló listából származó elemekkel, és visszaad egy okos mutatót, amely az Array objektumra mutat.
type: docs
weight: 2029
url: /hu/system/makearray/
---
## System::MakeArray(std::initializer_list\<T\>) függvény


Egy gyári függvény, amely új [Array](../array/) objektumot hoz létre, feltölti a megadott inicializáló listából származó elemekkel, és visszaad egy okos mutatót, amely a [Array](../array/) objektumra mutat.

```cpp
template<typename T> ArrayPtr<T> System::MakeArray(std::initializer_list<T> init)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | A [Array](../array/) objektum elemeinek típusa, amelyet a függvény hoz létre |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| init | std::initializer_list\<T\> | Az inicializáló lista, amely a tömb feltöltéséhez szükséges elemeket tartalmazza |

### Visszatérési érték

Egy okos mutató, amely a létrehozott [Array](../array/) objektumra mutat

## System::MakeArray(Args\&&...) függvény


Egy gyári függvény, amely új [Array](../array/) objektumot hoz létre, a megadott argumentumokat átadva annak konstruktorának.

```cpp
template<class T,class...> ArrayPtr<T> System::MakeArray(Args &&... args)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | A [Array](../array/) objektum elemeinek típusa, amelyet a függvény hoz létre |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| args | Args\&&... | Az argumentumok, amelyeket a létrehozandó [Array](../array/) objektum konstruktorának adnak át |

### Visszatérési érték

Egy okos mutató, amely a létrehozott [Array](../array/) objektumra mutat

## System::MakeArray(Integral, Args\&&...) függvény


Egy gyári függvény, amely új [Array](../array/) objektumot hoz létre, a megadott argumentumokat átadva annak konstruktorának.

```cpp
template<class T,class Integral,class...> std::enable_if<std::is_integral<Integral>::value, ArrayPtr<T>>::type System::MakeArray(Integral size, Args &&... args)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | A [Array](../array/) objektum elemeinek típusa, amelyet a függvény hoz létre |
| Integral | A tömb méretének típusa. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| size | Integral | A létrehozandó tömb mérete. |
| args | Args\&&... | Az argumentumok, amelyeket a létrehozandó [Array](../array/) objektum konstruktorának adnak át |

### Visszatérési érték

Egy okos mutató, amely a létrehozott [Array](../array/) objektumra mutat

## Lásd még

* Typedef [ArrayPtr](../arrayptr/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)