---
title: Read()
second_title: Aspose.Slides for C++ API Referencia
description: A megadott számú bájtot olvassa be a streameből, és a megadott bájt tömbbe írja őket.
type: docs
weight: 183
url: /hu/system.io/filestream/read/
---
## FileStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metódus


A megadott számú bájtot olvassa be a streameből, és a megadott bájt tömbbe írja őket.

```cpp
int32_t System::IO::FileStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | A bájt tömb, ahová az olvasott bájtokat írja. |
| offset | **int32_t** | A **buffer**-ben a 0-alapú pozíció, ahol a írás kezdődik. |
| count | **int32_t** | A beolvasandó bájtok száma. |

### Visszatérési érték

A beolvasott bájtok száma.

## FileStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) metódus


A megadott számú bájtot olvassa be a streameből, és a megadott bájt tömb nézetbe írja őket.

```cpp
int32_t System::IO::FileStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | A bájt tömb nézet, ahová az olvasott bájtokat írja. |
| offset | **int32_t** | A **buffer**-ben a 0-alapú pozíció, ahol a írás kezdődik. |
| count | **int32_t** | A beolvasandó bájtok száma. |

### Visszatérési érték

A beolvasott bájtok száma.

## Lásd még

* Típusdefiníció [ArrayPtr](../../../system/arrayptr/)
* Osztály [FileStream](../)
* Névtér [System::IO](../../)
* Könyvtár [Aspose.Slides](../../../)