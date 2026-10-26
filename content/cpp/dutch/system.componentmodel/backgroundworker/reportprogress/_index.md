---
title: ReportProgress()
second_title: Aspose.Slides voor C++ API-referentie
description: "Activeert de System::ComponentModel::BackgroundWorker::ProgressChanged gebeurtenis."
type: docs
weight: 40
url: /nl/system.componentmodel/backgroundworker/reportprogress/
---
## BackgroundWorker::ReportProgress(int) methode


Activeert de **System::ComponentModel::BackgroundWorker::ProgressChanged** gebeurtenis.

```cpp
void System::ComponentModel::BackgroundWorker::ReportProgress(int percentProgress)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| percentProgress | int | Het percentage, van 0 tot 100, van de achtergrondbewerking die voltooid is. |

## BackgroundWorker::ReportProgress(int, const System::SharedPtr\<System::Object\>\&) methode


Activeert de **System::ComponentModel::BackgroundWorker::ProgressChanged** gebeurtenis met userState-object.

```cpp
void System::ComponentModel::BackgroundWorker::ReportProgress(int percentProgress, const System::SharedPtr<System::Object> &userState)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| percentProgress | int | Het percentage, van 0 tot 100, van de achtergrondbewerking die voltooid is. |
| userState | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | Het statusobject dat wordt doorgegeven aan System::ComponentModel::BackgroundWorker::RunWorkerAsync(System::Object). |

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [BackgroundWorker](../)
* Klasse [Object](../../../system/object/)
* Naamruimte [System::ComponentModel](../../)
* Library [Aspose.Slides](../../../)