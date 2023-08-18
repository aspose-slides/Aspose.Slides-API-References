---
title: ReportProgress()
second_title: Aspose.Slides for C++ API Reference
description: "Raises the System::ComponentModel::BackgroundWorker::ProgressChanged event."
type: docs
weight: 40
url: /system.componentmodel/backgroundworker/reportprogress/
---
## BackgroundWorker::ReportProgress(int) method


Raises the **System::ComponentModel::BackgroundWorker::ProgressChanged** event.

```cpp
void System::ComponentModel::BackgroundWorker::ReportProgress(int percentProgress)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| percentProgress | int | The percentage, from 0 to 100, of the background operation that is complete. |

## BackgroundWorker::ReportProgress(int, const System::SharedPtr\<System::Object\>\&) method


Raises the **System::ComponentModel::BackgroundWorker::ProgressChanged** event with userState object.

```cpp
void System::ComponentModel::BackgroundWorker::ReportProgress(int percentProgress, const System::SharedPtr<System::Object> &userState)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| percentProgress | int | The percentage, from 0 to 100, of the background operation that is complete. |
| userState | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | The state object passed to System::ComponentModel::BackgroundWorker::RunWorkerAsync(System::Object). |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [BackgroundWorker](../)
* Class [Object](../../../system/object/)
* Namespace [System::ComponentModel](../../)
* Library [Aspose.Slides](../../../)