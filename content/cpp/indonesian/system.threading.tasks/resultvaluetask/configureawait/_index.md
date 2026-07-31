---
title: ConfigureAwait()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengonfigurasi awaiter untuk tugas ini.
type: docs
weight: 92
url: /id/system.threading.tasks/resultvaluetask/configureawait/
---
## ResultValueTask::ConfigureAwait(bool) const metode

Mengonfigurasi awaiter untuk tugas ini.

```cpp
Runtime::CompilerServices::ConfiguredResultValueTaskAwaitable<T> System::Threading::Tasks::ResultValueTask<T>::ConfigureAwait(bool continueOnCapturedContext) const
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| continueOnCapturedContext | **bool** | true untuk mencoba memindahkan lanjutan kembali ke konteks asli yang ditangkap; jika tidak, false. |

### Nilai Kembali

ConfiguredResultValueTaskAwaitable<T> Sebuah objek yang mengonfigurasi bagaimana awaiter berperilaku untuk tugas ini.

## Lihat Juga

* Kelas [ConfiguredResultValueTaskAwaitable](../../../system.runtime.compilerservices/configuredresultvaluetaskawaitable/)
* Kelas [ResultValueTask](../)
* Ruang Nama [System::Threading::Tasks](../../)
* Pustaka [Aspose.Slides](../../../)