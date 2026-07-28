---
title: GetByte()
second_title: Aspose.Slides C++ API referenciája
description: Az adott típusú tömböt nyers bájt tömbként értelmezi, és visszaadja a megadott bájteltolásnál lévő bájt értékét.
type: docs
weight: 27
url: /hu/system/buffer/getbyte/
---
## Buffer::GetByte(const SharedPtr\<Array\<T\>\>\&, int) metódus


Az adott típusú tömböt nyers bájt tömbként értelmezi, és visszaadja a megadott bájteltolásnál lévő bájt értékét.

```cpp
template<typename T> static uint8_t System::Buffer::GetByte(const SharedPtr<Array<T>> &array, int index)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | A tömb elemeinek típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| array | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<T\>\>\& | A cél tömb |
| index | int | A lekért bájt nulla-alapú eltolása |

### Visszatérési érték

A bájt értéke a megadott indexnél

## Buffer::GetByte(const System::Details::ArrayView\<T\>\&, int) metódus


Az adott típusú tömböt nyers bájt tömbként értelmezi, és visszaadja a megadott bájteltolásnál lévő bájt értékét.

```cpp
template<typename T> static uint8_t System::Buffer::GetByte(const System::Details::ArrayView<T> &array, int index)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | A tömb nézet elemeinek típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| array | const System::Details::ArrayView\<T\>\& | A cél tömb nézet |
| index | int | A lekért bájt nulla-alapú eltolása |

### Visszatérési érték

A bájt értéke a megadott indexnél

## Buffer::GetByte(const System::Details::StackArray\<T, N\>\&, int) metódus


Az adott típusú tömböt nyers bájt tömbként értelmezi, és visszaadja a megadott bájteltolásnál lévő bájt értékét.

```cpp
template<typename T,std::size_t> static uint8_t System::Buffer::GetByte(const System::Details::StackArray<T, N> &array, int index)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | A verem tömb elemeinek típusa |
| N | A verem tömb mérete |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| array | const System::Details::StackArray\<T, N\>\& | A cél verem tömb |
| index | int | A lekért bájt nulla-alapú eltolása |

### Visszatérési érték

A bájt értéke a megadott indexnél

## Lásd még

* Typedef [SharedPtr](../../sharedptr/)
* Osztály [Array](../../array/)
* Osztály [Buffer](../)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)