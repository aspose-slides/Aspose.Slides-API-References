---
title: ResultValueTask()
second_title: Aspose.Slides for C++ API 參考
description: 建構一個空的、未初始化的 ResultValueTask。
type: docs
weight: 1
url: /zh-hant/system.threading.tasks/resultvaluetask/resultvaluetask/
---
## ResultValueTask::ResultValueTask() 建構函式


建構一個空的、未初始化的 [ResultValueTask](../)。

```cpp
System::Threading::Tasks::ResultValueTask<T>::ResultValueTask()
```

## 備註



此工作未完成且不包含結果。嘗試取得結果會拋出例外。 

## ResultValueTask::ResultValueTask(const T\&) 建構函式


建構一個已完成的 [ResultValueTask](../)，其結果為指定的值。

```cpp
System::Threading::Tasks::ResultValueTask<T>::ResultValueTask(const T &result)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| result | const T\& | 要封裝於已完成工作中的結果值。 |
## 備註



這會建立一個成功完成的工作，立即回傳該值。 

## ResultValueTask::ResultValueTask(const RTaskPtr\<T\>\&) 建構函式


從指向 ResultTask<T> 的共享指標建構一個 [ResultValueTask](../)。

```cpp
System::Threading::Tasks::ResultValueTask<T>::ResultValueTask(const RTaskPtr<T> &task)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| task | const [RTaskPtr](../../../system/rtaskptr/)\<T\>\& | 要封裝的工作。對於空工作，可為 null。 |
## 備註



[ResultValueTask](../) 會表示提供之工作任務的狀態與結果。 

## 另見

* 類型別名 [RTaskPtr](../../../system/rtaskptr/)
* 類別 [ResultValueTask](../)
* 命名空間 [System::Threading::Tasks](../../)
* 函式庫 [Aspose.Slides](../../../)