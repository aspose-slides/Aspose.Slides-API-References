---
title: Read()
second_title: Aspose.Slides C++ API referenciája
description: Ha a csomagolási mód bináris, a megadott számú bájtot olvassa a streame-ből, egyébként a megadott számú karaktert, és uint8_t típusra konvertálja. Az olvasás eredményét a megadott bájt tömbbe írja.
type: docs
weight: 66
url: /hu/system.io/basicstdiostreamwrapper/read/
---
## BasicSTDIOStreamWrapper::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metódus

Ha a csomagolási mód bináris, a megadott számú bájtot olvassa a streame-ből, egyébként a megadott számú karaktert, és **uint8_t** típusra konvertálja. Az olvasás eredményét a megadott bájt tömbbe írja.

```cpp
virtual int32_t System::IO::BasicSTDIOStreamWrapper<T, typename>::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Paraméterek

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | The byte array to write the read bytes to |
| offset | **int32_t** | A 0-based position in **buffer** to start writing at |
| count | **int32_t** | The number of bytes to read |

### Visszatérési érték

Olvasott bájtok vagy karakterek száma

## BasicSTDIOStreamWrapper::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) metódus

A megadott számú bájtot olvassa a streame-ből, és a megadott bájt tömbbe írja.

```cpp
virtual int32_t System::IO::BasicSTDIOStreamWrapper<T, typename>::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Paraméterek

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | The byte array view to write the read bytes to |
| offset | **int32_t** | A 0-based position in **buffer** to start writing at |
| count | **int32_t** | The number of bytes to read |

### Visszatérési érték

Olvasott bájtok száma

## Lásd még

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [BasicSTDIOStreamWrapper](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)