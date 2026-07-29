---
title: ReportProgress()
second_title: Aspose.Slides för C++ API-referens
description: "Utlöser System::ComponentModel::BackgroundWorker::ProgressChanged-händelsen."
type: docs
weight: 40
url: /sv/system.componentmodel/backgroundworker/reportprogress/
---
## BackgroundWorker::ReportProgress(int) metod


Utlöser **System::ComponentModel::BackgroundWorker::ProgressChanged**-händelsen.

```cpp
void System::ComponentModel::BackgroundWorker::ReportProgress(int percentProgress)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| percentProgress | int | Procentandelen, från 0 till 100, av bakgrundsoperationen som är slutförd. |

## BackgroundWorker::ReportProgress(int, const System::SharedPtr\<System::Object\>\&) metod


Utlöser **System::ComponentModel::BackgroundWorker::ProgressChanged**-händelsen med userState-objektet.

```cpp
void System::ComponentModel::BackgroundWorker::ReportProgress(int percentProgress, const System::SharedPtr<System::Object> &userState)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| percentProgress | int | Procentandelen, från 0 till 100, av bakgrundsoperationen som är slutförd. |
| userState | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | Tillståndsobjektet som skickas till System::ComponentModel::BackgroundWorker::RunWorkerAsync(System::Object). |

## Se även

* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Klass [BackgroundWorker](../)
* Klass [Object](../../../system/object/)
* Namnrymd [System::ComponentModel](../../)
* Bibliotek [Aspose.Slides](../../../)