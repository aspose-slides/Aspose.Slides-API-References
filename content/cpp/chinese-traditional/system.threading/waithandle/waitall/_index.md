---
title: WaitAll()
second_title: Aspose.Slides for C++ API 參考手冊
description: 等待所有句柄觸發。
type: docs
weight: 1
url: /zh-hant/system.threading/waithandle/waitall/
---
## WaitHandle::WaitAll(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&, int) 方法

等待所有句柄觸發。

```cpp
static bool System::Threading::WaitHandle::WaitAll(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles, int millisecondsTimeout)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\>\& | 要等待的句柄。 |
| millisecondsTimeout | int | [Timeout](../../timeout/)等待的時間（毫秒）；-1 表示無限等待，0 表示檢查後返回，正值表示超時。 |

### 回傳值

如果所有句柄已觸發則返回 true，若超時則返回 false。

## WaitHandle::WaitAll(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&, TimeSpan) 方法

等待所有句柄觸發。

```cpp
static bool System::Threading::WaitHandle::WaitAll(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles, TimeSpan timeout)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\>\& | 要等待的句柄。 |
| timeout | [TimeSpan](../../../system/timespan/) | 一個 [System::TimeSpan](../../../system/timespan/)，表示要等待的毫秒數，或一個 [System::TimeSpan](../../../system/timespan/)，表示 -1 毫秒以表示無限等待。 |

### 回傳值

如果所有句柄已觸發則返回 true，若超時則返回 false。

## WaitHandle::WaitAll(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&) 方法

等待所有句柄觸發。

```cpp
static bool System::Threading::WaitHandle::WaitAll(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\>\& | 要等待的句柄。 |

### 回傳值

當 waitHandles 中的每個元素皆收到訊號時返回 true；否則此方法將永不返回。

## 另見

* 型別定義 [ArrayPtr](../../../system/arrayptr/)
* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [WaitHandle](../)
* 類別 [TimeSpan](../../../system/timespan/)
* 命名空間 [System::Threading](../../)
* 函式庫 [Aspose.Slides](../../../)