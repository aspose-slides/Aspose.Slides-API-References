---
title: Register()
second_title: Referensi API Aspose.Slides untuk C++
description: Mendaftarkan sebuah callback yang akan dipanggil ketika pembatalan diminta.
type: docs
weight: 40
url: /id/system.threading/cancellationtoken/register/
---
## CancellationToken::Register(const Action<>\&) const method

Mendaftarkan sebuah callback yang akan dipanggil ketika pembatalan diminta.

```cpp
CancellationTokenRegistration System::Threading::CancellationToken::Register(const Action<> &callback) const
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| callback | const [Action](../../../system/action/)<>\& | Action<> yang akan dijalankan ketika pembatalan diminta. |

### Nilai Kembalian

Sebuah objek [CancellationTokenRegistration](../../cancellationtokenregistration/) yang dapat digunakan untuk membatalkan pendaftaran callback.

## Catatan

Jika pembatalan sudah diminta, callback akan dipanggil segera.

Callback sebaiknya singkat dan tidak memblokir karena akan dijalankan pada thread yang memanggil Cancel() pada [CancellationTokenSource](../../cancellationtokensource/).

## Lihat Juga

* Typedef [Action](../../../system/action/)
* Kelas [CancellationTokenRegistration](../../cancellationtokenregistration/)
* Kelas [CancellationToken](../)
* Namespace [System::Threading](../../)
* Perpustakaan [Aspose.Slides](../../../)