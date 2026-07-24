---
title: ReportProgress()
second_title: Aspose.Slides für C++ API Referenz
description: "Löst das System::ComponentModel::BackgroundWorker::ProgressChanged Ereignis aus."
type: docs
weight: 40
url: /de/system.componentmodel/backgroundworker/reportprogress/
---
## BackgroundWorker::ReportProgress(int) Methode

Löst das **System::ComponentModel::BackgroundWorker::ProgressChanged** Ereignis aus.

```cpp
void System::ComponentModel::BackgroundWorker::ReportProgress(int percentProgress)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| percentProgress | int | Der Prozentsatz von 0 bis 100 der abgeschlossenen Hintergrundoperation. |

## BackgroundWorker::ReportProgress(int, const System::SharedPtr\<System::Object\>\&) Methode

Löst das **System::ComponentModel::BackgroundWorker::ProgressChanged** Ereignis mit dem userState-Objekt aus.

```cpp
void System::ComponentModel::BackgroundWorker::ReportProgress(int percentProgress, const System::SharedPtr<System::Object> &userState)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| percentProgress | int | Der Prozentsatz von 0 bis 100 der abgeschlossenen Hintergrundoperation. |
| userState | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | Das Zustandsobjekt, das an System::ComponentModel::BackgroundWorker::RunWorkerAsync(System::Object) übergeben wird. |

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [BackgroundWorker](../)
* Klasse [Object](../../../system/object/)
* Namensraum [System::ComponentModel](../../)
* Bibliothek [Aspose.Slides](../../../)