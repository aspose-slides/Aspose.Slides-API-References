---
title: TryEnter()
second_title: Aspose.Slides for C++ API 參考
description: 嘗試對指定的物件取得排他鎖。未實作。
type: docs
weight: 27
url: /zh-hant/system.threading/monitor/tryenter/
---
## Monitor::TryEnter(const SharedPtr\<Object\>\&) 方法

嘗試對指定的物件取得排他鎖。未實作。

```cpp
static bool System::Threading::Monitor::TryEnter(const SharedPtr<Object> &obj)
```

## Monitor::TryEnter(const System::SharedPtr\<Object\>\&, bool\&) 方法

嘗試對指定的物件取得排他鎖，並原子性地設定一個指示是否已取得鎖定的值。

```cpp
static void System::Threading::Monitor::TryEnter(const System::SharedPtr<Object> &obj, bool &lockTaken)
```

## Monitor::TryEnter(const SharedPtr\<Object\>\&, int32_t) 方法

在指定的毫秒數內嘗試對指定的物件取得排他鎖。未實作。

```cpp
static bool System::Threading::Monitor::TryEnter(const SharedPtr<Object> &obj, int32_t millisecondsTimeout)
```

## Monitor::TryEnter(const SharedPtr\<Object\>\&, TimeSpan) 方法

在指定的時間內嘗試對指定的物件取得排他鎖。未實作。

```cpp
static bool System::Threading::Monitor::TryEnter(const SharedPtr<Object> &obj, TimeSpan timeout)
```

## Monitor::TryEnter(const System::SharedPtr\<Object\>\&, int32_t, bool\&) 方法

在指定的時間內嘗試對指定的物件取得排他鎖，並原子性地設定一個指示是否已取得鎖定的值。

```cpp
static void System::Threading::Monitor::TryEnter(const System::SharedPtr<Object> &obj, int32_t millisecondsTimeout, bool &lockTaken)
```

## Monitor::TryEnter(const System::SharedPtr\<Object\>\&, TimeSpan, bool\&) 方法

在指定的時間內嘗試對指定的物件取得排他鎖，並原子性地設定一個指示是否已取得鎖定的值。

```cpp
static void System::Threading::Monitor::TryEnter(const System::SharedPtr<Object> &obj, TimeSpan timeout, bool &lockTaken)
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [Object](../../../system/object/)
* 類別 [Monitor](../)
* 類別 [TimeSpan](../../../system/timespan/)
* 命名空間 [System::Threading](../../)
* Library [Aspose.Slides](../../../)