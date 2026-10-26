---
title: ReportProgress()
second_title: Aspose.Slides 用於 C++ 的 API 參考
description: "引發 System::ComponentModel::BackgroundWorker::ProgressChanged 事件。"
type: docs
weight: 40
url: /zh-hant/system.componentmodel/backgroundworker/reportprogress/
---
## BackgroundWorker::ReportProgress(int) 方法

引發 **System::ComponentModel::BackgroundWorker::ProgressChanged** 事件。

```cpp
void System::ComponentModel::BackgroundWorker::ReportProgress(int percentProgress)
```

### 引數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| percentProgress | int | 背景作業完成的百分比，範圍為 0 到 100。 |

## BackgroundWorker::ReportProgress(int, const System::SharedPtr\<System::Object\>\&) 方法

引發 **System::ComponentModel::BackgroundWorker::ProgressChanged** 事件，並帶有 userState 物件。

```cpp
void System::ComponentModel::BackgroundWorker::ReportProgress(int percentProgress, const System::SharedPtr<System::Object> &userState)
```

### 引數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| percentProgress | int | 背景作業完成的百分比，範圍為 0 到 100。 |
| userState | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | 傳遞給 System::ComponentModel::BackgroundWorker::RunWorkerAsync(System::Object) 的狀態物件。 |

## 另請參閱

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [BackgroundWorker](../)
* 類別 [Object](../../../system/object/)
* 命名空間 [System::ComponentModel](../../)
* 函式庫 [Aspose.Slides](../../../)