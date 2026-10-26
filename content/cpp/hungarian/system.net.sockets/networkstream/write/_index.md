---
title: Write()
second_title: Aspose.Slides C++ API Referencia
description: A megadott bájt tömbből a meghatározott bájttartományt írja a streambe.
type: docs
weight: 209
url: /hu/system.net.sockets/networkstream/write/
---
## NetworkStream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metódus


A megadott bájt tömbből a meghatározott bájttartományt írja a streambe.

```cpp
void System::Net::Sockets::NetworkStream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t size) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | A bájtokat tartalmazó tömb, amelyet írni kell. |
| offset | **int32_t** | Az adott tömbben lévő eltolás bájtokban. |
| size | **int32_t** | Az írandó al tartomány elemeinek száma. |

## NetworkStream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) metódus


A megadott bájt tömbből a meghatározott bájttartományt írja a streambe.

```cpp
void System::Net::Sockets::NetworkStream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t size) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | A bájtokat tartalmazó tömbnézet, amelyet írni kell |
| offset | **int32_t** | A 0-alapú index a **buffer** tömbben, ahol az írandó al tartomány elkezdődik |
| size | **int32_t** | Az írandó al tartomány elemeinek száma |

## Lásd még

* Typedef [ArrayPtr](../../../system/arrayptr/)
* osztály [NetworkStream](../)
* névtér [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)