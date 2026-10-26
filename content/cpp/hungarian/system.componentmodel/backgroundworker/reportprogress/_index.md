---
title: ReportProgress()
second_title: Aspose.Slides for C++ API referenciája
description: "Elindítja a System::ComponentModel::BackgroundWorker::ProgressChanged eseményt."
type: docs
weight: 40
url: /hu/system.componentmodel/backgroundworker/reportprogress/
---
## BackgroundWorker::ReportProgress(int) metódus

Elindítja a **System::ComponentModel::BackgroundWorker::ProgressChanged** eseményt.

```cpp
void System::ComponentModel::BackgroundWorker::ReportProgress(int percentProgress)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| percentProgress | int | A háttér művelet befejezett százalékos aránya 0 és 100 között. |

## BackgroundWorker::ReportProgress(int, const System::SharedPtr\<System::Object\>\&) metódus

Elindítja a **System::ComponentModel::BackgroundWorker::ProgressChanged** eseményt a userState objektummal.

```cpp
void System::ComponentModel::BackgroundWorker::ReportProgress(int percentProgress, const System::SharedPtr<System::Object> &userState)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| percentProgress | int | A háttér művelet befejezett százalékos aránya 0 és 100 között. |
| userState | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | Az a állapotobjektum, amelyet a System::ComponentModel::BackgroundWorker::RunWorkerAsync(System::Object) kap. |

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [BackgroundWorker](../)
* Osztály [Object](../../../system/object/)
* Névtér [System::ComponentModel](../../)
* Könyvtár [Aspose.Slides](../../../)