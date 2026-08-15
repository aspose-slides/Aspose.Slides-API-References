---
title: get_Result()
second_title: Aspose.Slides for C++ API 參考
description: 取得已完成工作項的結果。
type: docs
weight: 66
url: /zh-hant/system.threading.tasks/resultvaluetask/get_result/
---
## ResultValueTask::get_Result() 方法

取得已完成工作項的結果。

```cpp
T System::Threading::Tasks::ResultValueTask<T>::get_Result()
```

### 返回值

T 結果值。

## 備註

如果任務由 ResultTask<T> 支援，此方法將等待結果並將其快取。隨後的呼叫將直接傳回快取的值，而不必等待。

## 參見

* 類別 [ResultValueTask](../)
* 命名空間 [System::Threading::Tasks](../../)
* 函式庫 [Aspose.Slides](../../../)