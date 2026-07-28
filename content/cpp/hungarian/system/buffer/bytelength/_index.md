---
title: ByteLength()
second_title: Aspose.Slides C++ API Referencia
description: Megállapítja a megadott tömb összes elemét által elfoglalt bájtok számát.
type: docs
weight: 14
url: /hu/system/buffer/bytelength/
---
## Buffer::ByteLength(const SharedPtr\<Array\<T\>\>\&) metódus


Meghatározza a megadott tömb összes elemét által elfoglalt bájtok számát.

```cpp
template<class T> static int System::Buffer::ByteLength(const SharedPtr<Array<T>> &array)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | A tömb elemeinek típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| array | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<T\>\>\& | Egy tömb |

### Visszatérési érték

A megadott tömb összes elemét által elfoglalt bájtok száma

## Buffer::ByteLength(const System::Details::ArrayView\<T\>\&) metódus


Meghatározza a megadott tömb nézet összes elemét által elfoglalt bájtok számát.

```cpp
template<class T> static int System::Buffer::ByteLength(const System::Details::ArrayView<T> &array)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | A tömb nézet elemeinek típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| array | const System::Details::ArrayView\<T\>\& | Egy tömb nézet |

### Visszatérési érték

A megadott tömb nézet összes elemét által elfoglalt bájtok száma

## Buffer::ByteLength(const System::Details::StackArray\<T, N\>\&) metódus


Meghatározza a megadott stack tömb összes elemét által elfoglalt bájtok számát.

```cpp
template<class T,std::size_t> static int System::Buffer::ByteLength(const System::Details::StackArray<T, N> &array)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | A stack tömb elemeinek típusa |
| N | A stack tömb mérete |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| array | const System::Details::StackArray\<T, N\>\& | Egy stack tömb |

### Visszatérési érték

A megadott stack tömb összes elemét által elfoglalt bájtok száma

## Lásd még

* Típusdefiníció [SharedPtr](../../sharedptr/)
* Osztály [Array](../../array/)
* Osztály [Buffer](../)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)