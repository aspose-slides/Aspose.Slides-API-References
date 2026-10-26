---
title: CancellationTokenRegistration
second_title: Aspose.Slides untuk Referensi API C++
description: Mewakili pendaftaran untuk callback token pembatalan.
type: docs
weight: 27
url: /id/system.threading/cancellationtokenregistration/
---
## CancellationTokenRegistration kelas


Mewakili pendaftaran untuk callback token pembatalan.

```cpp
class CancellationTokenRegistration
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| void [Dispose](./dispose/)() | Membuang pendaftaran dan menghapus callback dari [CancellationTokenSource](../cancellationtokensource/) yang terkait. Setelah memanggil metode ini, callback yang terdaftar tidak akan lagi dipanggil ketika [CancellationTokenSource](../cancellationtokensource/) yang terkait dibatalkan. |
## Catatan


Kelas ini memungkinkan penghapusan pendaftaran callback dari token pembatalan. Saat dibuang, ia menghapus callback dari [CancellationTokenSource](../cancellationtokensource/) yang terkait. 
Kelas ini tidak boleh dibuat secara langsung - ia dikembalikan oleh metode pendaftaran [CancellationToken](../cancellationtoken/). 

## Lihat Juga

* Ruang Nama [System::Threading](../)
* Pustaka [Aspose.Slides](../../)