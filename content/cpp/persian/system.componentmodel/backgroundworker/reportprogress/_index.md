---
title: ReportProgress()
second_title: مرجع API Aspose.Slides برای C++
description: "رویداد System::ComponentModel::BackgroundWorker::ProgressChanged را فراخوانی می‌کند."
type: docs
weight: 40
url: /fa/system.componentmodel/backgroundworker/reportprogress/
---
## BackgroundWorker::ReportProgress(int) متد

رویداد **System::ComponentModel::BackgroundWorker::ProgressChanged** را فراخوانی می‌کند.

```cpp
void System::ComponentModel::BackgroundWorker::ReportProgress(int percentProgress)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| percentProgress | int | درصد پیشرفت، از 0 تا 100، عملیات پس‌زمینه که تکمیل شده است. |

## BackgroundWorker::ReportProgress(int, const System::SharedPtr\<System::Object\>\&) متد

رویداد **System::ComponentModel::BackgroundWorker::ProgressChanged** را با شیء userState فراخوانی می‌کند.

```cpp
void System::ComponentModel::BackgroundWorker::ReportProgress(int percentProgress, const System::SharedPtr<System::Object> &userState)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| percentProgress | int | درصد پیشرفت، از 0 تا 100، عملیات پس‌زمینه که تکمیل شده است. |
| userState | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | شیء حالت که به System::ComponentModel::BackgroundWorker::RunWorkerAsync(System::Object) پاس داده می‌شود. |

## موارد مرتبط

* تایپ‌دف [SharedPtr](../../../system/sharedptr/)
* کلاس [BackgroundWorker](../)
* کلاس [Object](../../../system/object/)
* فضای‌نام [System::ComponentModel](../../)
* کتابخانه [Aspose.Slides](../../../)