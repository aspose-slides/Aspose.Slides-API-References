---
title: WriteAsync()
second_title: Referensi API Aspose.Slides untuk C++
description: Menulis secara asinkron urutan byte ke stream saat ini, menggeser posisi saat ini dalam stream ini sebesar jumlah byte yang ditulis, dan memantau permintaan pembatalan.
type: docs
weight: 66
url: /id/system.io/stream/writeasync/
---
## Stream::WriteAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const Threading::CancellationToken\&) metode

Menulis secara asinkron urutan byte ke stream saat ini, menggeser posisi saat ini dalam stream ini sebesar jumlah byte yang ditulis, dan memantau permintaan pembatalan.

```cpp
virtual TaskPtr System::IO::Stream::WriteAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count, const Threading::CancellationToken &cancellationToken)
```

### Argumen

| Parameter | Type | Deskripsi |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Array yang berisi byte yang akan ditulis. |
| offset | **int32_t** | Indeks berbasis 0 dari elemen dalam **buffer** tempat subrentang yang akan ditulis dimulai. |
| count | **int32_t** | Jumlah elemen dalam subrentang yang akan ditulis. |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | Token untuk memantau permintaan pembatalan. |

### Nilai Kembalian

Sebuah tugas yang mewakili operasi penulisan secara asinkron.

## Stream::WriteAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metode

Menulis secara asinkron urutan byte ke stream saat ini, menggeser posisi saat ini dalam stream ini sebesar jumlah byte yang ditulis, dan memantau permintaan pembatalan.

```cpp
TaskPtr System::IO::Stream::WriteAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count)
```

### Argumen

| Parameter | Type | Deskripsi |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Array yang berisi byte yang akan ditulis. |
| offset | **int32_t** | Indeks berbasis 0 dari elemen dalam **buffer** tempat subrentang yang akan ditulis dimulai. |
| count | **int32_t** | Jumlah elemen dalam subrentang yang akan ditulis. |

### Nilai Kembalian

Sebuah tugas yang mewakili operasi penulisan secara asinkron.

## Lihat Juga

* Typedef [TaskPtr](../../../system/taskptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Kelas [CancellationToken](../../../system.threading/cancellationtoken/)
* Kelas [Stream](../)
* Ruang Nama [System::IO](../../)
* Library [Aspose.Slides](../../../)