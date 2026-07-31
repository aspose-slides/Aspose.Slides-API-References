---
title: FlushAsync()
second_title: Referensi API Aspose.Slides untuk C++
description: Secara asinkron membersihkan semua buffer untuk stream ini, menyebabkan data yang di-buffer ditulis ke perangkat dasar, dan memantau permintaan pembatalan.
type: docs
weight: 118
url: /id/system.io/stream/flushasync/
---
## Stream::FlushAsync(const Threading::CancellationToken\&) metode


Secara asinkron membersihkan semua buffer untuk stream ini, menyebabkan data yang di-buffer ditulis ke perangkat dasar, dan memantau permintaan pembatalan.

```cpp
virtual TaskPtr System::IO::Stream::FlushAsync(const Threading::CancellationToken &cancellationToken)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | Token untuk memantau permintaan pembatalan. |

### Nilai Kembali

Tugas yang mewakili operasi flush secara asinkron.

## Stream::FlushAsync() metode


Secara asinkron membersihkan semua buffer untuk stream ini, menyebabkan data yang di-buffer ditulis ke perangkat dasar, dan memantau permintaan pembatalan.

```cpp
TaskPtr System::IO::Stream::FlushAsync()
```


### Nilai Kembali

Tugas yang mewakili operasi flush secara asinkron.

## Lihat Juga

* Typedef [TaskPtr](../../../system/taskptr/)
* Kelas [CancellationToken](../../../system.threading/cancellationtoken/)
* Kelas [Stream](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)