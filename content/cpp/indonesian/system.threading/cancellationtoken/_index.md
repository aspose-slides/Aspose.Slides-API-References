---
title: CancellationToken
second_title: Referensi API Aspose.Slides untuk C++
description: Menyebarkan notifikasi bahwa operasi harus dibatalkan. Kelas ini menyediakan mekanisme untuk pembatalan kooperatif antara thread, memungkinkan satu thread memberi tahu yang lain bahwa sebuah operasi harus dibatalkan.
type: docs
weight: 14
url: /id/system.threading/cancellationtoken/
---
## CancellationToken kelas

Menyebarkan notifikasi bahwa operasi harus dibatalkan. Kelas ini menyediakan mekanisme untuk pembatalan kooperatif antara thread, memungkinkan satu thread memberi tahu yang lain bahwa sebuah operasi harus dibatalkan.

```cpp
class CancellationToken : public System::Details::BoxableObjectBase
```

## Metode

| Metode | Deskripsi |
| --- | --- |
|  [CancellationToken](./cancellationtoken/)() | Konstruktor default. |
| **bool** [get_CanBeCanceled](./get_canbecanceled/)() const | Mendapatkan apakah token ini dapat berada dalam keadaan dibatalkan. |
| **bool** [get_IsCancellationRequested](./get_iscancellationrequested/)() const | Mendapatkan apakah pembatalan telah diminta untuk token ini. |
| static [CancellationToken](./) [get_None](./get_none/)() | Mengembalikan nilai [System::Threading::CancellationToken](./) kosong. |
| [CancellationTokenRegistration](../cancellationtokenregistration/) [Register](./register/)(const [Action](../../system/action/)<>\&) const | Mendaftarkan callback yang akan dipanggil ketika pembatalan diminta. |
| void [ThrowIfCancellationRequested](./throwifcancellationrequested/)() const | Melempar OperationCanceledException jika pembatalan telah diminta. |
## Catatan

Sebuah [CancellationToken](./) hanya dapat dibatalkan melalui [CancellationTokenSource](../cancellationtokensource/) yang terkait.

## Lihat Juga

* Ruang nama [System::Threading](../)
* Pustaka [Aspose.Slides](../../)