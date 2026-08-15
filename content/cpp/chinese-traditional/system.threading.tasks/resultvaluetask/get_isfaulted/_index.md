---
title: get_IsFaulted()
second_title: Aspose.Slides for C++ API 參考文件
description: 取得一個值，用以指示任務是否因未處理的例外而完成。
type: docs
weight: 14
url: /zh-hant/system.threading.tasks/resultvaluetask/get_isfaulted/
---
## ResultValueTask::get_IsFaulted() const 方法

取得一個值，用於指示任務是否因未處理的例外而完成。

```cpp
bool System::Threading::Tasks::ResultValueTask<T>::get_IsFaulted() const
```

### 返回值

bool 若任務發生錯誤則為 True；否則為 false.

## 備註

如果任務包含直接結果值，則返回 false。

## 參見

* 類別 [ResultValueTask](../)
* 命名空間 [System::Threading::Tasks](../../)
* 函式庫 [Aspose.Slides](../../../)