---
title: ReportProgress()
second_title: Referensi API Aspose.Slides untuk C++
description: "Memicu peristiwa System::ComponentModel::BackgroundWorker::ProgressChanged."
type: docs
weight: 40
url: /id/system.componentmodel/backgroundworker/reportprogress/
---
## BackgroundWorker::ReportProgress(int) metode

Memicu peristiwa **System::ComponentModel::BackgroundWorker::ProgressChanged**.

```cpp
void System::ComponentModel::BackgroundWorker::ReportProgress(int percentProgress)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| percentProgress | int | Persentase, dari 0 hingga 100, dari operasi latar belakang yang telah selesai. |

## BackgroundWorker::ReportProgress(int, const System::SharedPtr\<System::Object\>\&) metode

Memicu peristiwa **System::ComponentModel::BackgroundWorker::ProgressChanged** dengan objek userState.

```cpp
void System::ComponentModel::BackgroundWorker::ReportProgress(int percentProgress, const System::SharedPtr<System::Object> &userState)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| percentProgress | int | Persentase, dari 0 hingga 100, dari operasi latar belakang yang telah selesai. |
| userState | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | Objek status yang diteruskan ke System::ComponentModel::BackgroundWorker::RunWorkerAsync(System::Object). |

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [BackgroundWorker](../)
* Kelas [Object](../../../system/object/)
* Namespace [System::ComponentModel](../../)
* Library [Aspose.Slides](../../../)