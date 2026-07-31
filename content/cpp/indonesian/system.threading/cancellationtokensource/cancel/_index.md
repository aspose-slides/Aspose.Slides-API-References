---
title: Cancel()
second_title: Aspose.Slides for C++ Referensi API
description: Menyampaikan permintaan pembatalan.
type: docs
weight: 40
url: /id/system.threading/cancellationtokensource/cancel/
---
## CancellationTokenSource::Cancel() metode


Menyampaikan permintaan pembatalan.

```cpp
void System::Threading::CancellationTokenSource::Cancel()
```

## Catatan


Semua callback yang terdaftar akan dipanggil. 

Pemanggilan berikutnya ke [get_IsCancellationRequested()](../get_iscancellationrequested/) akan mengembalikan true. 

Callback dieksekusi secara sinkron selama pemanggilan ini. 

## Lihat Juga

* Kelas [CancellationTokenSource](../)
* Ruang Nama [System::Threading](../../)
* Perpustakaan [Aspose.Slides](../../../)