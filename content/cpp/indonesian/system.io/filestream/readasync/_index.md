---
title: ReadAsync()
second_title: Referensi API Aspose.Slides untuk C++
description: Membaca secara asinkron urutan byte dari aliran saat ini, memajukan posisi di dalam aliran sebesar jumlah byte yang dibaca, dan memantau permintaan pembatalan.
type: docs
weight: 196
url: /id/system.io/filestream/readasync/
---
## FileStream::ReadAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const Threading::CancellationToken\&) method

Membaca secara asinkron urutan byte dari aliran saat ini, memajukan posisi di dalam aliran sebesar jumlah byte yang dibaca, dan memantau permintaan pembatalan.

```cpp
RTaskPtr<int32_t> System::IO::FileStream::ReadAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count, const Threading::CancellationToken &cancellationToken) override
```

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Array byte untuk menulis byte yang dibaca. |
| offset | **int32_t** | Posisi berbasis 0 dalam **buffer** tempat mulai menulis. |
| count | **int32_t** | Jumlah byte yang akan dibaca. |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | Token untuk memantau permintaan pembatalan. |

### Nilai Pengembalian

Sebuah task yang mewakili operasi baca asinkron. Nilai parameter TResult berisi total jumlah byte yang dibaca ke dalam buffer. Nilai hasil dapat lebih kecil daripada jumlah byte yang diminta jika jumlah byte yang tersedia saat ini kurang dari jumlah yang diminta, atau dapat menjadi 0 (nol) jika akhir aliran telah tercapai.

## Lihat Juga

* Typedef [RTaskPtr](../../../system/rtaskptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Kelas [CancellationToken](../../../system.threading/cancellationtoken/)
* Kelas [FileStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)