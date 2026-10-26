---
title: ResultTask()
second_title: Aspose.Slides for C++ API 參考
description: 使用返回值的函式建構一個 ResultTask。
type: docs
weight: 1
url: /zh-hant/system.threading.tasks/resulttask/resulttask/
---
## ResultTask::ResultTask(const Func\<T\>\&) 建構子

使用返回值的函式建構一個 [ResultTask](../)。

```cpp
System::Threading::Tasks::ResultTask<T>::ResultTask(const Func<T> &function)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| function | const [Func](../../../system/func/)\<T\>\& | 以非同步方式執行並返回結果的函式 |

## ResultTask::ResultTask() 建構子

內部實作。非供使用者程式碼使用。

```cpp
System::Threading::Tasks::ResultTask<T>::ResultTask()
```

## 備註

用於建立未初始化結果任務的內部建構子 

## ResultTask::ResultTask(const T\&) 建構子

用於建立具有指定結果的結果任務的內部建構子。

```cpp
System::Threading::Tasks::ResultTask<T>::ResultTask(const T &result)
```

## 參見

* 類別 [Func](../../../system/func/)
* 類別 [ResultTask](../)
* 命名空間 [System::Threading::Tasks](../../)
* 函式庫 [Aspose.Slides](../../../)