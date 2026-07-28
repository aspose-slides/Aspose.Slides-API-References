---
title: ReportProgress()
second_title: Aspose.Slides dla C++ – odniesienie API
description: "Wywołuje zdarzenie System::ComponentModel::BackgroundWorker::ProgressChanged."
type: docs
weight: 40
url: /pl/system.componentmodel/backgroundworker/reportprogress/
---
## BackgroundWorker::ReportProgress(int) metoda

Wywołuje zdarzenie **System::ComponentModel::BackgroundWorker::ProgressChanged**.

```cpp
void System::ComponentModel::BackgroundWorker::ReportProgress(int percentProgress)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| percentProgress | int | Procent, od 0 do 100, operacji w tle, który został ukończony. |

## BackgroundWorker::ReportProgress(int, const System::SharedPtr\<System::Object\>\&) metoda

Wywołuje zdarzenie **System::ComponentModel::BackgroundWorker::ProgressChanged** z obiektem userState.

```cpp
void System::ComponentModel::BackgroundWorker::ReportProgress(int percentProgress, const System::SharedPtr<System::Object> &userState)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| percentProgress | int | Procent, od 0 do 100, operacji w tle, który został ukończony. |
| userState | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | Obiekt stanu przekazany do System::ComponentModel::BackgroundWorker::RunWorkerAsync(System::Object). |

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [BackgroundWorker](../)
* Klasa [Object](../../../system/object/)
* Przestrzeń nazw [System::ComponentModel](../../)
* Biblioteka [Aspose.Slides](../../../)