---
title: ReportProgress()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: "يُطلق حدث System::ComponentModel::BackgroundWorker::ProgressChanged."
type: docs
weight: 40
url: /ar/system.componentmodel/backgroundworker/reportprogress/
---
## طريقة BackgroundWorker::ReportProgress(int) method

يُطلق حدث **System::ComponentModel::BackgroundWorker::ProgressChanged**.

```cpp
void System::ComponentModel::BackgroundWorker::ReportProgress(int percentProgress)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| percentProgress | int | النسبة المئوية، من 0 إلى 100، للعملية الخلفية المكتملة. |

## طريقة BackgroundWorker::ReportProgress(int, const System::SharedPtr\<System::Object\>\&) method

يُطلق حدث **System::ComponentModel::BackgroundWorker::ProgressChanged** مع كائن userState.

```cpp
void System::ComponentModel::BackgroundWorker::ReportProgress(int percentProgress, const System::SharedPtr<System::Object> &userState)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| percentProgress | int | النسبة المئوية، من 0 إلى 100، للعملية الخلفية المكتملة. |
| userState | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | كائن الحالة الممرّر إلى System::ComponentModel::BackgroundWorker::RunWorkerAsync(System::Object). |

## انظر أيضا

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [BackgroundWorker](../)
* Class [Object](../../../system/object/)
* Namespace [System::ComponentModel](../../)
* Library [Aspose.Slides](../../../)