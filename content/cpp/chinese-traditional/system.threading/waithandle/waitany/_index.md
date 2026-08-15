---
title: WaitAny()
second_title: Aspose.Slides for C++ API 參考
description: 等待任意一個處理程序觸發。
type: docs
weight: 14
url: /zh-hant/system.threading/waithandle/waitany/
---
## WaitHandle::WaitAny(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&, int) 方法

等待任意一個處理程序觸發。

```cpp
static int System::Threading::WaitHandle::WaitAny(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles, int millisecondsTimeout)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\>\& | 要等待的處理程序。 |
| millisecondsTimeout | int | [Timeout](../../timeout/) 等待時間（毫秒）；-1 表示無限等待，0 表示檢查後返回，正值表示超時。 |

### 返回值

如果有任何處理程序觸發，則返回 True；如果超時，則返回 false。

## WaitHandle::WaitAny(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&, TimeSpan) 方法

等待任意一個處理程序觸發。

```cpp
static int System::Threading::WaitHandle::WaitAny(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles, TimeSpan timeout)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\>\& | 要等待的處理程序。 |
| timeout | [TimeSpan](../../../system/timespan/) | 一個 [System::TimeSpan](../../../system/timespan/)，其表示要等待的毫秒數；或是一個 [System::TimeSpan](../../../system/timespan/)，其表示 -1 毫秒以無限期等待。 |

### 返回值

如果有任何處理程序觸發，則返回 True；如果超時，則返回 false。

## WaitHandle::WaitAny(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&) 方法

等待任意一個處理程序觸發。

```cpp
static int System::Threading::WaitHandle::WaitAny(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\>\& | 要等待的處理程序。 |

### 返回值

如果 waitHandles 中的每個元素皆已收到訊號則返回 True；否則該方法永不返回。

## 另請參閱

* 類型定義 [ArrayPtr](../../../system/arrayptr/)
* 類型定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [WaitHandle](../)
* 類別 [TimeSpan](../../../system/timespan/)
* 命名空間 [System::Threading](../../)
* 函式庫 [Aspose.Slides](../../../)