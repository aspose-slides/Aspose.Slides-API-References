---
title: ReportProgress()
second_title: Riferimento API di Aspose.Slides per C++
description: "Genera l'evento System::ComponentModel::BackgroundWorker::ProgressChanged."
type: docs
weight: 40
url: /it/system.componentmodel/backgroundworker/reportprogress/
---
## BackgroundWorker::ReportProgress(int) metodo


Genera l'evento **System::ComponentModel::BackgroundWorker::ProgressChanged**.

```cpp
void System::ComponentModel::BackgroundWorker::ReportProgress(int percentProgress)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| percentProgress | int | La percentuale, da 0 a 100, dell'operazione in background completata. |

## BackgroundWorker::ReportProgress(int, const System::SharedPtr\<System::Object\>\&) metodo


Genera l'evento **System::ComponentModel::BackgroundWorker::ProgressChanged** con l'oggetto userState.

```cpp
void System::ComponentModel::BackgroundWorker::ReportProgress(int percentProgress, const System::SharedPtr<System::Object> &userState)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| percentProgress | int | La percentuale, da 0 a 100, dell'operazione in background completata. |
| userState | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | L'oggetto di stato passato a System::ComponentModel::BackgroundWorker::RunWorkerAsync(System::Object). |

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [BackgroundWorker](../)
* Class [Object](../../../system/object/)
* Namespace [System::ComponentModel](../../)
* Library [Aspose.Slides](../../../)