---
title: ReportProgress()
second_title: Aspose.Slides for C++ API Referansı
description: "System::ComponentModel::BackgroundWorker::ProgressChanged olayını tetikler."
type: docs
weight: 40
url: /tr/system.componentmodel/backgroundworker/reportprogress/
---
## BackgroundWorker::ReportProgress(int) yöntemi

**System::ComponentModel::BackgroundWorker::ProgressChanged** olayını tetikler.

```cpp
void System::ComponentModel::BackgroundWorker::ReportProgress(int percentProgress)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| percentProgress | int | Arka plan işleminin tamamlanma yüzdesi, 0 ile 100 arasında. |

## BackgroundWorker::ReportProgress(int, const System::SharedPtr\<System::Object\>\&) yöntemi

**System::ComponentModel::BackgroundWorker::ProgressChanged** olayını kullanıcı durumu nesnesiyle tetikler.

```cpp
void System::ComponentModel::BackgroundWorker::ReportProgress(int percentProgress, const System::SharedPtr<System::Object> &userState)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| percentProgress | int | Arka plan işleminin tamamlanma yüzdesi, 0 ile 100 arasında. |
| userState | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | System::ComponentModel::BackgroundWorker::RunWorkerAsync(System::Object) yöntemine geçirilen durum nesnesi. |

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [BackgroundWorker](../)
* Sınıf [Object](../../../system/object/)
* Ad alanı [System::ComponentModel](../../)
* Kütüphane [Aspose.Slides](../../../)