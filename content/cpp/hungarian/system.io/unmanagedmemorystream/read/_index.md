---
title: Read()
second_title: Aspose.Slides for C++ API hivatkozás
description: A megadott számú bájtot a streame-ből olvassa, és a megadott bájttömbbe írja.
type: docs
weight: 144
url: /hu/system.io/unmanagedmemorystream/read/
---
## UnmanagedMemoryStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method

A streameből a megadott számú bájtot olvassa, és a megadott bájttömbbe írja.

```cpp
virtual int32_t System::IO::UnmanagedMemoryStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Paraméterek

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | A bájttömb, ahová a beolvasott bájtokat írja |
| offset | **int32_t** | 0-alapú pozíció a **buffer**-ben, ahol a írás kezdődik |
| count | **int32_t** | A beolvasandó bájtok száma |

### Visszatérési érték

A beolvasott bájtok száma

## UnmanagedMemoryStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) method

A streameből a megadott számú bájtot olvassa, és a megadott bájttömb-nézetbe írja.

```cpp
virtual int32_t System::IO::UnmanagedMemoryStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Paraméterek

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | A bájttömb-nézet, ahová a beolvasott bájtokat írja |
| offset | **int32_t** | 0-alapú pozíció a **buffer**-ben, ahol a írás kezdődik |
| count | **int32_t** | A beolvasandó bájtok száma |

### Visszatérési érték

A beolvasott bájtok száma

## Lásd még

* Típusdefiníció [ArrayPtr](../../../system/arrayptr/)
* Osztály [UnmanagedMemoryStream](../)
* Névtér [System::IO](../../)
* Könyvtár [Aspose.Slides](../../../)