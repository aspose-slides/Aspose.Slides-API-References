---
title: Wait()
second_title: Aspose.Slides for C++ API 參考
description: 釋放對物件的鎖並阻塞目前執行緒，直到重新取得鎖。若指定的逾時間隔已過，執行緒會進入就緒佇列。可選地在等待之前退出同步上下文的同步域，之後再重新取得該域。未實作。
type: docs
weight: 53
url: /zh-hant/system.threading/monitor/wait/
---
## Monitor::Wait(const SharedPtr\<Object\>\&, int32_t, bool) 方法

釋放對物件的鎖並阻塞目前執行緒，直到重新取得鎖。  
如果指定的逾時間隔已過，執行緒將進入就緒佇列。  
可選地在等待之前退出同步上下文的同步域，之後再重新取得該域。  
未實作。

```cpp
static bool System::Threading::Monitor::Wait(const SharedPtr<Object> &obj, int32_t millisecondsTimeout, bool exitContext)
```
## Monitor::Wait(const SharedPtr\<Object\>\&, TimeSpan, bool) 方法

釋放對物件的鎖並阻塞目前執行緒，直到重新取得鎖。  
如果指定的逾時間隔已過，執行緒將進入就緒佇列。  
可選地在等待之前退出同步上下文的同步域，之後再重新取得該域。  
未實作。

```cpp
static bool System::Threading::Monitor::Wait(const SharedPtr<Object> &obj, TimeSpan timeout, bool exitContext)
```
## Monitor::Wait(const SharedPtr\<Object\>\&, int32_t) 方法

釋放對物件的鎖並阻塞目前執行緒，直到重新取得鎖。  
如果指定的逾時間隔已過，執行緒將進入就緒佇列。  
未實作。

```cpp
static bool System::Threading::Monitor::Wait(const SharedPtr<Object> &obj, int32_t millisecondsTimeout)
```
## Monitor::Wait(const SharedPtr\<Object\>\&, TimeSpan) 方法

釋放對物件的鎖並阻塞目前執行緒，直到重新取得鎖。  
如果指定的逾時間隔已過，執行緒將進入就緒佇列。  
未實作。

```cpp
static bool System::Threading::Monitor::Wait(const SharedPtr<Object> &obj, TimeSpan timeout)
```
## Monitor::Wait(const SharedPtr\<Object\>\&) 方法

釋放對物件的鎖並阻塞目前執行緒，直到重新取得鎖。  
未實作。

```cpp
static bool System::Threading::Monitor::Wait(const SharedPtr<Object> &obj)
```
## 另見

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [Object](../../../system/object/)
* 類別 [Monitor](../)
* 類別 [TimeSpan](../../../system/timespan/)
* 命名空間 [System::Threading](../../)
* 函式庫 [Aspose.Slides](../../../)