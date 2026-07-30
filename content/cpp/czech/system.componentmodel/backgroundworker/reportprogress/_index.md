---
title: ReportProgress()
second_title: Aspose.Slides pro C++ referenční příručka API
description: "Vyvolá událost System::ComponentModel::BackgroundWorker::ProgressChanged."
type: docs
weight: 40
url: /cs/system.componentmodel/backgroundworker/reportprogress/
---
## BackgroundWorker::ReportProgress(int) metoda

Vyvolá událost **System::ComponentModel::BackgroundWorker::ProgressChanged**.

```cpp
void System::ComponentModel::BackgroundWorker::ReportProgress(int percentProgress)
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| percentProgress | int | Procentuální podíl od 0 do 100 dokončené operace na pozadí. |

## BackgroundWorker::ReportProgress(int, const System::SharedPtr\<System::Object\>\&) metoda

Vyvolá událost **System::ComponentModel::BackgroundWorker::ProgressChanged** s objektem userState.

```cpp
void System::ComponentModel::BackgroundWorker::ReportProgress(int percentProgress, const System::SharedPtr<System::Object> &userState)
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| percentProgress | int | Procentuální podíl od 0 do 100 dokončené operace na pozadí. |
| userState | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | Objekt stavu předaný metodě System::ComponentModel::BackgroundWorker::RunWorkerAsync(System::Object). |

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [BackgroundWorker](../)
* Třída [Object](../../../system/object/)
* Jmenný prostor [System::ComponentModel](../../)
* Library [Aspose.Slides](../../../)