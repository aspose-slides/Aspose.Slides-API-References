---
title: Read()
second_title: Aspose.Slides C++ API Referencia
description: A megadott számú bájtot olvassa be a folyamatról, és a megadott bájttömbbe írja.
type: docs
weight: 196
url: /hu/system.net.sockets/networkstream/read/
---
## NetworkStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metódus

A megadott számú bájtot olvassa be a folyamatról, és a megadott bájttömbbe írja.

```cpp
int32_t System::Net::Sockets::NetworkStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t size) override
```


### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | A bájttömb, ahová az olvasott bájtok lesznek írva. |
| offset | **int32_t** | A megadott tömbben lévő eltolás bájtokban. |
| size | **int32_t** | Az olvasandó bájtok száma. |

### Visszatérési érték

Az olvasott bájtok száma.

## NetworkStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) metódus

A megadott számú bájtot olvassa be a folyamatról, és a megadott bájttömbbe írja.

```cpp
int32_t System::Net::Sockets::NetworkStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t size) override
```


### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | A bájttömb nézet, ahová az olvasott bájtok íródnak. |
| offset | **int32_t** | A **buffer**-ben lévő 0-alapú pozíció, ahol a írás elkezdődik. |
| size | **int32_t** | Az olvasandó bájtok száma. |

### Visszatérési érték

Az olvasott bájtok száma

## Lásd még

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [NetworkStream](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)