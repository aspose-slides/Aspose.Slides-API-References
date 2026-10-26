---
title: Read()
second_title: Aspose.Slides C++ API referencia
description: A megadott számú bájtot olvassa a streamből, és a megadott bájttömbbe írja.
type: docs
weight: 79
url: /hu/system.io/memorystream/read/
---
## MemoryStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metódus


A megadott számú bájtot olvassa el a streame-ből, és a megadott bájttömbbe írja.

```cpp
int32_t System::IO::MemoryStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | A bájttömb, ahová az olvasott bájtok írásra kerülnek |
| offset | **int32_t** | 0-bázisú pozíció a **buffer**-ben, ahol a írás kezdődik |
| count | **int32_t** | A beolvasandó bájtok száma |

### Visszatérési érték

A beolvasott bájtok száma

## MemoryStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) metódus


A megadott számú bájtot olvassa el a streame-ből, és a megadott bájttömbre írja.

```cpp
int32_t System::IO::MemoryStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | A bájttömb nézet, ahová az olvasott bájtok írásra kerülnek |
| offset | **int32_t** | 0-bázisú pozíció a **buffer**-ben, ahol a írás kezdődik |
| count | **int32_t** | A beolvasandó bájtok száma |

### Visszatérési érték

A beolvasott bájtok száma

## Lásd még

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Osztály [MemoryStream](../)
* Névtér [System::IO](../../)
* Könyvtár [Aspose.Slides](../../../)