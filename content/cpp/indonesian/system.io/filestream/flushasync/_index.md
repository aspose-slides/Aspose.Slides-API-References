---
title: FlushAsync()
second_title: Referensi API Aspose.Slides untuk C++
description: Secara asinkron membersihkan semua buffer untuk stream ini, menyebabkan data yang dibuffer ditulis ke perangkat dasar, dan memantau permintaan pembatalan.
type: docs
weight: 157
url: /id/system.io/filestream/flushasync/
---
## FileStream::FlushAsync(const Threading::CancellationToken\&) metode


Secara asinkron membersihkan semua buffer untuk stream ini, menyebabkan data yang dibuffer ditulis ke perangkat dasar, dan memantau permintaan pembatalan.

```cpp
TaskPtr System::IO::FileStream::FlushAsync(const Threading::CancellationToken &cancellationToken) override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | Token yang dipantau untuk permintaan pembatalan. |

### Nilai Kembalian

Sebuah task yang mewakili operasi flush secara asynchronous.

## Lihat Juga

* Typedef [TaskPtr](../../../system/taskptr/)
* Class [CancellationToken](../../../system.threading/cancellationtoken/)
* Class [FileStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)