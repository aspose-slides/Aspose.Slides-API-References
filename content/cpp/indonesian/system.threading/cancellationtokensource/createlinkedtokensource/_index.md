---
title: CreateLinkedTokenSource()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat sumber token terhubung yang dibatalkan ketika salah satu token yang diberikan dibatalkan.
type: docs
weight: 66
url: /id/system.threading/cancellationtokensource/createlinkedtokensource/
---
## CancellationTokenSource::CreateLinkedTokenSource(const CancellationToken\&, const CancellationToken\&) metode

Membuat sumber token terhubung yang dibatalkan ketika salah satu token yang diberikan dibatalkan.

```cpp
static SharedPtr<CancellationTokenSource> System::Threading::CancellationTokenSource::CreateLinkedTokenSource(const CancellationToken &token1, const CancellationToken &token2)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| token1 | const [CancellationToken](../../cancellationtoken/)\& | Token pembatalan pertama yang dipantau. |
| token2 | const [CancellationToken](../../cancellationtoken/)\& | Token pembatalan kedua yang dipantau. |

### Nilai Kembali

Sumber token baru yang akan dibatalkan ketika salah satu token masukan dibatalkan.

## Keterangan

Sumber yang dikembalikan akan langsung dibatalkan jika salah satu token masukan sudah dibatalkan. 

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [CancellationTokenSource](../)
* Kelas [CancellationToken](../../cancellationtoken/)
* Ruang Nama [System::Threading](../../)
* Pustaka [Aspose.Slides](../../../)