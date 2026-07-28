---
title: SetByte()
second_title: Aspose.Slides C++ API-referencia
description: A megadott típusú tömböt nyers bájt tömbként értelmezi, és a megadott bájt értéket a megadott bájt eltolásnál állítja be.
type: docs
weight: 40
url: /hu/system/buffer/setbyte/
---
## Buffer::SetByte(const SharedPtr\<Array\<T\>\>\&, int, uint8_t) metódus

A megadott típusú tömböt nyers bájt tömbként értelmezi, és a megadott bájt értéket a megadott bájt offsetnél állítja be.

```cpp
template<typename T> static void System::Buffer::SetByte(const SharedPtr<Array<T>> &array, int index, uint8_t value)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | A tömb elemeinek típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| array | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<T\>\>\& | A cél tömb |
| index | int | A beállítandó bájt nulla-alapú eltolása |
| value | **uint8_t** | A beállítandó bájt érték |

## Buffer::SetByte(const System::Details::ArrayView\<T\>\&, int, uint8_t) metódus

A megadott típusú tömböt nyers bájt tömbként értelmezi, és a megadott bájt értéket a megadott bájt offsetnél állítja be.

```cpp
template<typename T> static void System::Buffer::SetByte(const System::Details::ArrayView<T> &array, int index, uint8_t value)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | A tömb elemeinek típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| array | const System::Details::ArrayView\<T\>\& | A cél tömb nézet |
| index | int | A beállítandó bájt nulla-alapú eltolása |
| value | **uint8_t** | A beállítandó bájt érték |

## Buffer::SetByte(const System::Details::StackArray\<T, N\>\&, int, uint8_t) metódus

A megadott típusú tömböt nyers bájt tömbként értelmezi, és a megadott bájt értéket a megadott bájt offsetnél állítja be.

```cpp
template<typename T,std::size_t> static void System::Buffer::SetByte(const System::Details::StackArray<T, N> &array, int index, uint8_t value)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | A tömb elemeinek típusa |
| N | A stack tömb mérete |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| array | const System::Details::StackArray\<T, N\>\& | A cél stack tömb |
| index | int | A beállítandó bájt nulla-alapú eltolása |
| value | **uint8_t** | A beállítandó bájt érték |

## Lásd még

* Típusdefiníció [SharedPtr](../../sharedptr/)
* Osztály [Array](../../array/)
* Osztály [Buffer](../)
* Névterület [System](../../)
* Könyvtár [Aspose.Slides](../../../)