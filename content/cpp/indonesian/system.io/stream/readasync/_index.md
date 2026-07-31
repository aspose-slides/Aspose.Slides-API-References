---
title: ReadAsync()
second_title: Referensi API Aspose.Slides untuk C++
description: Membaca secara asinkron urutan byte dari aliran saat ini, memajukan posisi dalam aliran sebesar jumlah byte yang dibaca, dan memantau permintaan pembatalan.
type: docs
weight: 40
url: /id/system.io/stream/readasync/
---
## Stream::ReadAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const Threading::CancellationToken\&) metode

Membaca secara asinkron urutan byte dari aliran saat ini, memajukan posisi dalam aliran sebesar jumlah byte yang dibaca, dan memantau permintaan pembatalan.

```cpp
virtual RTaskPtr<int32_t> System::IO::Stream::ReadAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count, const Threading::CancellationToken &cancellationToken)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Array byte untuk menulis byte yang dibaca. |
| offset | **int32_t** | Posisi berbasis 0 dalam **buffer** untuk memulai penulisan. |
| count | **int32_t** | Jumlah byte yang akan dibaca. |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | Token untuk memantau permintaan pembatalan. |

### Nilai Kembali

Tugas yang mewakili operasi baca secara asinkron. Nilai parameter TResult berisi total jumlah byte yang dibaca ke dalam buffer. Nilai hasil dapat lebih kecil dari jumlah byte yang diminta jika jumlah byte yang tersedia saat ini lebih kecil daripada jumlah yang diminta, atau dapat menjadi 0 (nol) jika akhir aliran telah tercapai.

## Stream::ReadAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metode

Membaca secara asinkron urutan byte dari aliran saat ini, memajukan posisi dalam aliran sebesar jumlah byte yang dibaca, dan memantau permintaan pembatalan.

```cpp
RTaskPtr<int32_t> System::IO::Stream::ReadAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Array byte untuk menulis byte yang dibaca. |
| offset | **int32_t** | Posisi berbasis 0 dalam **buffer** untuk memulai penulisan. |
| count | **int32_t** | Jumlah byte yang akan dibaca. |

### Nilai Kembali

Tugas yang mewakili operasi baca secara asinkron. Nilai parameter TResult berisi total jumlah byte yang dibaca ke dalam buffer. Nilai hasil dapat lebih kecil dari jumlah byte yang diminta jika jumlah byte yang tersedia saat ini lebih kecil daripada jumlah yang diminta, atau dapat menjadi 0 (nol) jika akhir aliran telah tercapai.

## Lihat Juga

* Typedef [RTaskPtr](../../../system/rtaskptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Kelas [CancellationToken](../../../system.threading/cancellationtoken/)
* Kelas [Stream](../)
* Ruang Nama [System::IO](../../)
* Pustaka [Aspose.Slides](../../../)