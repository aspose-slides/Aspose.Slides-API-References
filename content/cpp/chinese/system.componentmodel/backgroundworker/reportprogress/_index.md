---
title: ReportProgress()
second_title: Aspose.Slides C++ API 参考
description: "引发 System::ComponentModel::BackgroundWorker::ProgressChanged 事件。"
type: docs
weight: 40
url: /zh/system.componentmodel/backgroundworker/reportprogress/
---
## BackgroundWorker::ReportProgress(int) 方法

引发 **System::ComponentModel::BackgroundWorker::ProgressChanged** 事件。

```cpp
void System::ComponentModel::BackgroundWorker::ReportProgress(int percentProgress)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| percentProgress | int | 后台操作已完成的百分比，范围为 0 到 100。 |

## BackgroundWorker::ReportProgress(int, const System::SharedPtr\<System::Object\>\&) 方法

引发 **System::ComponentModel::BackgroundWorker::ProgressChanged** 事件并附带 userState 对象。

```cpp
void System::ComponentModel::BackgroundWorker::ReportProgress(int percentProgress, const System::SharedPtr<System::Object> &userState)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| percentProgress | int | 后台操作已完成的百分比，范围为 0 到 100。 |
| userState | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | 传递给 System::ComponentModel::BackgroundWorker::RunWorkerAsync(System::Object) 的状态对象。 |

## 另请参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [BackgroundWorker](../)
* 类 [Object](../../../system/object/)
* 命名空间 [System::ComponentModel](../../)
* 库 [Aspose.Slides](../../../)