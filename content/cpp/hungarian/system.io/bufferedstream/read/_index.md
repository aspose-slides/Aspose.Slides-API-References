---
title: Read()
second_title: Aspose.Slides for C++ API referencia
description: Beolvassa a megadott számú bájtot a mögöttes adatfolyamból, és a megadott bájttömbbe írja.
type: docs
weight: 53
url: /hu/system.io/bufferedstream/read/
---
## BufferedStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metódus


Beolvassa a megadott számú bájtot a mögöttes adatfolyamból, és a megadott bájttömbbe írja.

```cpp
virtual int32_t System::IO::BufferedStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Arguments

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | A bájttömb, ahová a beolvasott bájtokat írja |
| offset | **int32_t** | E egy 0-alapú pozíció a **buffer**-ben, ahol a írás kezdődik |
| count | **int32_t** | A beolvasandó bájtok száma |

### Visszatérési érték

A beolvasott bájtok száma

## BufferedStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) metódus


Beolvassa a megadott számú bájtot a mögöttes adatfolyamból, és a megadott bájttömbbe írja.

```cpp
virtual int32_t System::IO::BufferedStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Arguments

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | A bájttömb, ahová a beolvasott bájtokat írja |
| offset | **int32_t** | E egy 0-alapú pozíció a **buffer**-ben, ahol a írás kezdődik |
| count | **int32_t** | A beolvasandó bájtok száma |

### Visszatérési érték

A beolvasott bájtok száma

## Lásd még

* Típusdefiníció [ArrayPtr](../../../system/arrayptr/)
* Osztály [BufferedStream](../)
* Névtér [System::IO](../../)
* Könyvtár [Aspose.Slides](../../../)