---
title: ConfigureAwait()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengonfigurasi cara await pada tugas hasil ini berperilaku terkait penangkapan konteks.
type: docs
weight: 27
url: /id/system.threading.tasks/resulttask/configureawait/
---
## ResultTask::ConfigureAwait(bool) const metode


Mengonfigurasi bagaimana await pada ResultTask ini harus berperilaku terkait penangkapan konteks.

```cpp
Runtime::CompilerServices::ConfiguredResultTaskAwaitable<T> System::Threading::Tasks::ResultTask<T>::ConfigureAwait(bool continueOnCapturedContext) const
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| continueOnCapturedContext | **bool** | Apakah harus melanjutkan pada konteks yang ditangkap |

### Nilai Kembali

Runtime::CompilerServices::ConfiguredResultTaskAwaitable<T> Awaitable yang telah dikonfigurasi untuk hasil
## Keterangan



Ini memungkinkan kontrol yang lebih terperinci atas aliran konteks untuk pola async/await patterns 

## Lihat Juga

* Kelas [ConfiguredResultTaskAwaitable](../../../system.runtime.compilerservices/configuredresulttaskawaitable/)
* Kelas [ResultTask](../)
* Namespace [System::Threading::Tasks](../../)
* Perpustakaan [Aspose.Slides](../../../)