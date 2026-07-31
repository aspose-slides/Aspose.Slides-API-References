---
title: WriteAsync()
second_title: Referensi API Aspose.Slides untuk C++
description: Menulis secara asinkron urutan byte ke aliran saat ini, memajukan posisi saat ini dalam aliran ini sebesar jumlah byte yang ditulis, dan memantau permintaan pembatalan.
type: docs
weight: 261
url: /id/system.io/filestream/writeasync/
---
## FileStream::WriteAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const Threading::CancellationToken\&) metode

Menulis secara asinkron urutan byte ke aliran saat ini, memajukan posisi saat ini dalam aliran ini sebesar jumlah byte yang ditulis, dan memantau permintaan pembatalan.

```cpp
TaskPtr System::IO::FileStream::WriteAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count, const Threading::CancellationToken &cancellationToken) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Array yang berisi byte yang akan ditulis. |
| offset | **int32_t** | Indeks berbasis 0 dari elemen dalam **buffer** tempat subrentang yang akan ditulis dimulai. |
| count | **int32_t** | Jumlah elemen dalam subrentang yang akan ditulis. |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | Token untuk memantau permintaan pembatalan. |

### Nilai Kembalian

Sebuah tugas yang mewakili operasi penulisan secara asinkron.

## Lihat Juga

* Typedef [TaskPtr](../../../system/taskptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Kelas [CancellationToken](../../../system.threading/cancellationtoken/)
* Kelas [FileStream](../)
* Ruang Nama [System::IO](../../)
* Perpustakaan [Aspose.Slides](../../../)